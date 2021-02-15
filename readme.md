# cf-todo (for PostgreSQL)

This is a fork of James Hunt's [cf-todo](https://github.com/jhunt/cf-todo), which is a MySQL based application. This 
particular fork has been modified to support PostgreSQL instead. It uses [GORM](http://gorm.io)'s auto-migrate 
feature to migrate the database on first launch, and then allows a person to set up a bunch of TODO items as a demo. 
Assuming you have a valid Cloud Foundry installation available and you're authenticated already, deploying this 
should be as simple as running `cf push`.
