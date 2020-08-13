This is a sample GraphQL API

### Installation procedure
1. clone the project from the Github repo

2. cd into the folder

3. run `bundle install` to install all dependencies

4. run `rails db:create db:migrate db:seed` to create, migrate and seed the database, 

5. run `rails s` and take it for a spin.

6. Make a sample call in your client (Insomnia or Postman) to `http://localhost:3000/graphql` with the query below
    ```query {
        allOrders {
            description
            total      
            payments {
                amount
            }
        }
    }```

7. Enjoy.