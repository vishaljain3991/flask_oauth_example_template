flask-oauth-example-template
============================
(Inspired from http://blog.miguelgrinberg.com/post/oauth-authentication-with-flask)  
1. Create a virtual environment and install the packages in the requirements.txt file (you can use Python 2.7 or 3.4).
   --> pip install -r requirements.txt
2. Register "apps" with Facebook and Twitter.
3. Edit OAUTH_CREDENTIALS in config.py with the id and secret codes of your Facebook and Twitter apps.
4. Activate virtual environment
   e.g. (on Linux) source <virtualenv directory name>/bin/activate
5. Execute db_create.py
   --> python db_create.py
6. Execute db_migrate.py
   --> python db_migrate.py
