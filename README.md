duplicity-backup-status
=======================

Backupninja generates duplicity configfiles, this nagios plugin can check their freshness

Make sure you have python-argparse installed (yes an extra dependency, getopt doubles the amount of code
Dump the shell script in /root/, run the python script from your nagios. You can specify some extras like when warnings or criticalities should be emerged.

-  -w WARNINC   Number of hours allowed for incremential backup warning level
-  -W WARNFULL  Number of hours allowed for incremential backup critical level
-  -c CRITINC   Number of days allowed for full backup warning level
-  -C CRITFULL  Number of days allowed for full backup critical level


### TODO:

- make it cuter, tidy up
- dump the shell script in a convenient place, with a sane default in the python script looking for it
