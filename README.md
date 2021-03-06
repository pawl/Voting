About This Application
======================

This program is used by the Dallas Makerspace for online voting at:

[https://dallasmakerspace.org/voting/](https://dallasmakerspace.org/voting/)

The application was initially created by Andrew LeCody, using the [CakePHP framework](http://www.cakephp.org "CakePHP - the rapid development PHP framework") and is released under the [GNU Affero General Public License](http://www.gnu.org/licenses/agpl.html).

CakePHP
-------

[CakePHP](http://www.cakephp.org "CakePHP - the rapid development PHP framework") is a rapid development framework for PHP which uses commonly known design patterns like Active Record, Association Data Mapping, Front Controller and MVC. Our primary goal is to provide a structured framework that enables PHP users at all levels to rapidly develop robust web applications, without any loss to flexibility.


Installation
============

Installing this application is fairly easy, just follow these steps:

1. Download the latest version with git (`git clone https://github.com/aceat64/Dallas-Makerspace-Voting.git`)

2. In the app/config directory, rename core.php.default and database.php.default to core.php and database.php.default respectively.

3. Modify the core.php and database.php files to suit your environment.

4. Create the appropriate tables in your database. You can do this with the "Console/cake schema create" command or by importing the schema.sql file located in the app/Config/Schema folder.
