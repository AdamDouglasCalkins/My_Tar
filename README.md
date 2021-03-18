Overview;
my_tar is a project to recreate the tar program/system command from scratch.

my_tar is a command to manipulate tape archive. The first option to tar is a mode indicator from the following list:

-c Create a new archive containing the specified items.
-r Like -c, but new entries are appended to the archive. The -f option is required.
-t List archive contents to stdout.
-u Like -r, but new entries are added only if they have a modification date newer than the corresponding entry in the archive. The -f option is required.
-x Extract to disk from the archive. If a file with the same name appears more than once in the archive, each copy will be extracted, 
   with later copies overwriting (replacing) earlier copies.

In -c, -r, or -u mode, each specified file or directory is added to the archive in the order specified on the command line. 
By default, the contents of each directory are also archived.
