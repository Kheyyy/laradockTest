- Create laravel project (composer create-project laravel/laravel LaraDock2)
- Clone laradock on your project https://github.com/Laradock/laradock.git
1. Already have project .
    (git submodule add https://github.com/Laradock/laradock.git)
2. Don't have project yet
    (git clone https://github.com/laradock/laradock.git)
- Go to laradock folder (cd laradock). 
- Copy env-example to .env .
- Set up the environment in .env file (Ex: apache mysql ..) Note: make sure the configuration is the same as env variable in .env file in project. 
- Build the environment and run it using
(docker-compose up -d apache2 mysql) .

If you getting error with updating database try to remove old database by command (rm -rf ~/.laradock/data/mysql)

Some help https://github.com/laradock/laradock/issues/1392



