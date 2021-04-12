OSVIEWER-v1.0.0
======

A small web-based monitoring dashboard for your linux pc/server writen in Python and Django + Chart.js.

The dashboard is built using only Python libraries available in the main Python distribution, trying to create a small list of dependencies without the need of installing many packages or libraries.


Current dependencies:

  - >= Django 1.5
  - >= Python 2.x
  - >= Python 3.x



Installation
============

1. git clone the repository.
2. cd OSViewer
3. virtualenv "name"
4. source /path/to/virtal/envname/bin/activate
5. pip install -r requirements.txt
6. In osviewer/settings.py edit the secret key of your own.
7. run command python manage.py syncdb
8. Enter your admin credentials
9. Once your admin credentials are set run command python manage.py runserver
10. Server will be initialised at http://127.0.0.1:8000 open in browser








OS Support
==========

OSVIEWER was tested and runs under the following OSs:
  - Centos
  - Fedora
  - Ubuntu
  - Debian
  - Raspbian
  - Pidora
  - Arch Linux


Might work under others, but didn't get to test any other OSs just yet.







Credits
=======
[Dashboard Template](http://www.egrappler.com/templatevamp-free-twitter-bootstrap-admin-template/), 
[Bootstrap](http://getbootstrap.com/), 
[Font Awesome](http://fontawesome.io/)
