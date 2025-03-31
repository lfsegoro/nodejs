Ready to use packages bundle:
1. freeradius server 3.2.7 as radius server.
2. postgresql 15
3. nodejs backend (akses: http://mainhostipaddress:5000) as basic UI that can be more developed.
4. adminer (http://mainhostipaddress:8082) as additional UI that can directly access the database.

You can see the detail on the docker-compose.yml
Must be use on *nix host environment, that have docker and docker-compose installed.
Usage : 
     git clone https://github.com/lfsegoro/nodejs
     docker-compose up --build
After that you can access the UI suing port 5000 or port 8082 as above mentioned.
The database already have sample username for testing. you can check the radcheck table.

If you need :
- custom freeradius configuration
- more polished UI
You can contact me.
