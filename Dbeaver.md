# Adding new Dbeaver database connection, for example in dev

This is how we can add a new database in dbeaver for testing in dev env puposes  

### 1. We open Dbeaver
### 2. We create w new Postgres connection
### 3. We put the `Host` ( url = projectx.eu-west-3.amazonaws.com ) and the `Database` ( we can name it projectx_dev ) that we get from the `keepass`
### 4. We put the `Username` and `Password` that we get the from keepass also  
### 5. We put the `Port` as mentioned in the keepass also
### 6. At this level, we need to create an `SSH` connection for `Bastion`, and to do it as pro we create a new `Profile` in the top right
### 7. In the bottom left, we click `Create`, give it a name like `Bastion DEV_QUA`
### 8. We click on `Utiliser Tunnel SSH`
### 9. We add the `Hote/IP` and the `Port` that we get from the keepass 
### 10. We add the `User name` and `Password` fields from the widnows profile ( aichou / widnows_pass ), and the password needs to be updated here whenever it has been changed for the windows profile
### 11. We go back to the previouse page, we select this profile that we created and we click on `terminer`

And this is how we add a new database to our Dbeaver the right way

---
