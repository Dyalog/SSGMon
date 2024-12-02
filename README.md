# SSGMon
The Dyalog Security Group's Security Issue Monitor - SSGMon - has been developed by Dyalog to monitor:

* Published security issues related to third party software that is used or re-distributed by Dyalog
* Issues tagged as "security related" in our internal issue tracking system Mantis

SSGMon is run at regular intervals in a mode where it sends e-mail summarising changes since the last run. It also runs once a week in the mode where it provides an overview of all open security issues and a list of the third party components that are being tracked.

By setting "polltype=[both|mantis|thirdparty]" on the Dyalog command line, you can control which information is checked and sent - it is not necessary to run both Mantis and 3rd party reports each time.

SSGMon is for internal use at Dyalog, but the repository is public so that the code can be used as inspiration for anyone needing to do something similar.  For Dyalogers: you will also need the files in JenkinsBuild/SSGMon_External_Files.

It is provided "as is" and without documentation under MIT licence.
