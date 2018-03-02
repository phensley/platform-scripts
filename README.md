
## platformsh scripts

### platform-backup - daily backup of database and files

* Can backup multiple projects / environments in a single run
* Uses rsync and hard links to only copy daily file changes
* Keeps N days of backups
* Mutual exclusion to avoid overlapping backup runs
* Emails multple recipients when an exception occurs

