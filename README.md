https://mighty-depths-40970.herokuapp.com/

# Size

## What is Size?

Size is a universal sizing app. It uses measurements in inches to give users their accurate sizes for different clothing items from different stores or brands.

## How to start Size locally

1. Clone this repo.

2. run 'yarn install' at the directory's root level as well as within the client folder. This will make sure all dependencies are running locally.

3. Open SQL database manager and run this code to create a database "CREATE DATABASE sizes_db".

4. In your SQL database manager run "USE sizes_db".

5. At this point, review the credentials in config/config.json and make sure they match your machine's. You can also rename the database and repeat steps 3 and 4 using your new database's name.

6. Run "yarn start" to initialize the app and create the tables.

7. Export seeds.sql withing the seeders folder into MySQL and run the code.

8. Restart the server and you're ready to go.

![alt text](https://raw.githubusercontent.com/carlosfgutier/Size/master/client/public/images/sizeUI.png)