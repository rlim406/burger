# burger

**Description**

1. The app pulls the burger names from the SQL database and displays them on the page under the "Burger Menu".
2. Each burger has a devour button beside it that the user can click. 
3. When the devour button is clicked, the burger moves to the Eaten Burgers session. 
4. The re-order option button then appears beside the burger name. 
5. When the user clicks the re-order button, the burger goes back to the Burger Menu. 
6. The user also has an option to create their own burger using the form. 
7. Once the user enters in a burger name and submits the form, the burger will appear on the Burger Menu with a devour button. 

**Technologies used**

Handlebars
HTML
CSS
Bootstrap
jQuery
Javascript
SQL
Express
orm

**File Structure**

├── config
│   ├── connection.js
│   └── orm.js
│ 
├── controllers
│   └── burgers_controller.js
│
├── db
│   ├── schema.sql
│   └── seeds.sql
│
├── models
│   └── burger.js
│ 
├── node_modules
│ 
├── package.json
│
├── public
│   └── assets
│       ├── css
│           └── burger_style.css
│           └── burger.jpg
|       ├── js
│           └── burgers.js
├── server.js
│
└── views
    ├── index.handlebars
    └── layouts
        └── main.handlebars
    └── partials
        └── burger-block.handlebars
