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
   rails generate model my-model key1:string key2:integer key3:string
   ```
   "my-model" should be replaced with the singular form of the model. Ex Contact or Product.
   Then list the keys with just a space in between each. If you do not put the :integer or any other type it will assume string. 
   ```
   rails generate model my-model key1 key2: integer key3
   ```
6. push the model to the database
   ```
   rails db:migrate
   ```
7. Open a new tab and run the rails console to start creating items in the database. 
   ```
   rails console
   ```
8. 





...IF you want to create a JSON parser for the DB arrays run 
   ```
   rails gererate jbuilder my-model
   ```
   my-model needs to be lowercase. Example would be contact or product.
8. 
9. To launch the server in a new tab
   ```
   rails server
   ```
10. 
<!-- 
5. Add a route in the `config/routes.rb` file
   ```ruby
   get "/products", controller: "products", action: "show_one"
   ``` -->
