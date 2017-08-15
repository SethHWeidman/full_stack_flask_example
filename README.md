Running `python3 database_setup.py` sets up the database, and running `python3 lotsofmenus.py` loads a bunch of data into the database.

Finally, `python3 project.py` starts the app! Then, navigate to `http://0.0.0.0:5000/restaurants/1/` to see the app in action.

Clicking "Create New Item" will pull up the "create new item" page. From that page, you can enter item information, hit submit, and see the results. Similarly for "Edit Item" and "Delete Item".

Finally, you can go to `http://0.0.0.0:5000/restaurants/1/menu/2/JSON` to see the JSON for just one menu item, or go to `http://0.0.0.0:5000/restaurants/1/JSON` to see the JSON for an entire menu.
