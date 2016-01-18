This is the ansible set up for the podbaby project hosted at https://podbaby.me.

Code for site is at https://github.com/danjac/podbaby.

Setup requires an env.yml file under the "vars" subdirectory. The env.yml file should be installed locally and has the following settings:

```

DB_URL=postgres://postgres:*****@localhost:5432/my_db_name?sslmode=disable
GOOGLE_ANALYTICS_ID=UA-******
MAIL_ADDR=smtp.gmail.com:465
MAIL_HOST=smtp.gmail.com
MAIL_USER=**********
MAIL_PASSWORD=**********
SECRET_KEY=s0m3Seekr1t!
SECURE_COOKIE_KEY=****************

```


