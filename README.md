# README #

Welcome to the Open Source repository of the e-Proficiency Testing (ePT) software - Zimbabwe

### How do I get set up? ###

* [Install Zend Framework 1.12](http://framework.zend.com/manual/1.12/en/introduction.installation.html)
* [Download the ePT Source Code](https://bitbucket.org/deforay/ept/downloads) and put it into your server's root folder (www or htdocs). 
* Create a database and run the 2 SQL files in the `docs` directory: `init-db.sql` and `alter-commands.sql`
* Modify the config file (application/configs/application.ini) to suit your setup
* Create a virtual host pointing to the `public` folder of the source code

### Next Steps ###

* Once you have the software set up, you can visit the admin panel http://ept/admin and log in with the credentials eptmanager@eqapt.com and 123
* Now you can start adding Participants, Participant logins, PT Surveys, Shipments etc.

### Who do I talk to? ###

* Create and issue on our issue list, or fork the project and send us a pull request.
