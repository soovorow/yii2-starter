!! IMPORTANT !! Tables, designed in http://ondras.zarovi.cz/sql/demo/ must be named with N_ prefix in order of migration’s dependency, where N is [a-z]

```
$ ./makewebsite database_design.sql
$ cd website_name
$ ./yii serve --docroot="./backend/web"
```
