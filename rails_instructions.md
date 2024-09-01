1. Open your terminal to the folder you want...
2. Run this command
   ```
   rails new my-app-name
   ```
   This command will create a new folder with all the files and folders...
3. Navigate to the app
   ```
   cd my-app-name
   ```
4. create the rails database
   ```
   rails db:create
   ```
5. generate a model in the database. 
   ```
   rails generate model my-model key1:string key2:intiger key3:string
   ```
   "my-model" should be replaced with the singular form of the model. Ex Contact or Product.
   Then list the keys with just a space in between each. 
6. push the model to the database
   ```
   rails db:migrate
   ```
<!-- 
5. Add a route in the `config/routes.rb` file
   ```ruby
   get "/products", controller: "products", action: "show_one"
   ``` -->
