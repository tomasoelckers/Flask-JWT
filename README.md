# Flask-JWT #
====================

* Dependencies:
  * flask
  * flask_restful
  * flask_sqlalchemy
  * flask_jwt_extended
  * passlib
  * pyOpenSSL

  > pip install -r requirements.txt

* Structure of the project:

  ```bash
  Flask-JWT
  ├──views.py
  ├──models.py
  ├──resources.py
  └──run.py
  ```
* Start server with the following command:
  > FLASK_APP=run.py FLASK_DEBUG=1 flask run
