Restore the original file and close opened streams when ``Path.in_place()`` fails during setup. Interruption also restores the original; if restoration fails, retain the backup for recovery.
