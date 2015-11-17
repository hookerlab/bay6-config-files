# A database for the configuration files used by the Bay 6 scan

Reconstructions of PET/MR data from Bay 6 need some scan configuration files. This is a small database to keep track of those files.

Records for the file store the path to each of the files, the date from which the file is valid, and the file's `md5sum` checksum.

The reconstruction software is able to pull all the files needed to reconstruct a given patient by just giving the scan date or alternatively by doing a `JOIN` with the petbilling database and just using the subject id.
