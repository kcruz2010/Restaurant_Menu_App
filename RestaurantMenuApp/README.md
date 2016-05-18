# Restaurant item catalog
A restaurant and menus web driven app 
# Files/Folder
  - Static
  - templates
  - project.py
  - database_setup.py
  - lotsofmenus.py
  - clientsecrets.json
  - fb_client_secrets.json
  - restaurantmenu.db
  - restaurantmenuwithusers.db
  - 
  
# Requirements
- Git 
- Virtual Box 
- Vagrant

#  Run & Start
- Open zip folder
- Open Git cd fullstack
- Check if "Vagrantfile" in  directory.
- Use Git command line
- Execute following command to setup and login VM:
- vagrant up
- vagrant ssh
- In VM prompt, typing following command to project directory:
- cd /vagrant/Restaurant
- Using below command to setup SQLite DataBase
- python database_setup.py
- Executing "python project.py" to test Item Catalog.
- In Host Browser like Chrome or Mozilla, input url: "http://localhost:5000" to connect Web Server.
- Login with  Google+ or Facebook.
- Look around by Add/Edit/Delete Restaurant/Menu on website!
- If you want logout, logout
- Quit python web server, press Ctrl+C (^C) to stop web service.
- Exit vagrant by "exit" command, exit git environment is "exit" command, too.


