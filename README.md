# phpbugtrack
Note
------------

phpBugTracker is a open source bug tracking system.

All contributions (code or bug reports) are welcome! 

Features
--------

Easy install
Multiple project support
Email notifications
Public or private bugs visibility
Customizable role-based and group-based access control
Simple and detailed bug queries
Customizable bug statuses
Attachments
Issue Change History

History of changes since old sourceforge phpBugTracker v.1.0.5
----------------------------------------------------------------------

Fix all detected security vulnerabilities (on 01.2015)
Migrate to PDO data access 
Full remove PEAR:DB
Database migrated to InnoDB
Allow filter bugs by project (in progress)!
Little visual restyling.
Fixed old security issues in attachment system.
Attachments now stored in DB.
Automatic update check.
Many of html code fixed (in progress)
Fixed bug sort order in some places.
Database switched to UTF-8 codepage. (Autoupdate not supported)
Removed magic_quotes_gpc dependence!
Oracle and PostgreSQL support was stopped since 2009. If you need this - 
	you can make it self and contribute your code, 
	or order donation based support. 
Added Smarty templates support.
PHP 5.2 support
Fixed installer

To detailed changelog check CHANGELOG file
	
Note about security
-------------------
Original phpBugTracker has many security bugs. This project inherits it.
At version 1.7.2 I was fixed all security vulnerabilities, detected on that moment.
And I still working on it.

I need code contributions for:
------------------------------
- convert localization files to utf8 (non-utf language packs not supported now)
- search for and fix security issues

Requirements
------------
Here is a list of the requirements to get this running on your server.
1. A webserver
2. PHP 5.2+ (with PDO and MySQL driver)
3. A database - Currently MySQL only. 
		




