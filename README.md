# README.md
### Software installato:
 * Apache 2.4 con :
 * PHP con:
 * Mysql:

### Volumi:  
/usr/local/lib/phpunitlib per phpunit.phar  
/var/www/html per progetto  
/opt/moodledata per moodle  

### Ports:  
8002 per http  
3306 per mysql  
9000 per xdebug  

| Environment Variable                      | Mandatory | Allowed values                        | Default value |
|-------------------------------------------|-----------|---------------------------------------|---------------|------------------------------------------------------------------------------|
| `MOODLE_DOCKER_DB`                             | pgsql, mariadb, mysql, mssql, oracle  | none          | The database server to run against                                           |
| `MOODLE_DOCKER_WWWROOT`                        | path on your file system              | none          | The path to the Moodle codebase you intend to test                           |
| `MOODLE_DOCKER_PHP_VERSION`                     | 7.1, 7.0, 5.6                         | 7.1           | The php version to use                                                       |
