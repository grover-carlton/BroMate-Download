# BroMate-Download

Use:
1. Launch
   * Double-Click BroMate-x.x.jar
   * Commandline:
	     * java -jar BroMate-x.x.jar
2. From Directory Selector
   * Initial Use:
       * Select 'Browse...'
			 * Navigate to Directory containing Bro logs in default (ASCII tab delimited) format
			 * Select 'Open'
	 * Return Use: 
	 * **(Must be launced from dirctory with BRO_LOG_DB folder/dir and derby file)**
	     * Select 'Open Existing Database...'

Known Issues:
- Errors out when pointed to empty log files
- On Windows OS - Not deleting Database files when option choosen 

Future Version:
- Updated UI
- json formatted log support
