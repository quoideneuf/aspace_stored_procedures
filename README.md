ASpace Restore Stored Procedures
==============================

As of ASpace v 1.3, the "Reports" functionality depends on MySQL stored procedures. This is application-logic stored in the database.

This means that if you need to dump and reload your database, you need to use the --routines flag to ensure that the procedures
are exported with your data.

If that horse has already left the barn, fear not. Just install this plugin and restart ASpace.


#Installation

Download into archivesspace/plugins/aspace_stored_procedures

Open archivesspace/config/config.xml and uncomment the AppConfig[:plugins] line (if commented)

Add 'aspace_stored_procedures' to the array

Restart ArchivesSpace



