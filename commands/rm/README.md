NAME:-
        rm - removes file or directories.
Task:-
        removes the file and directory.
SYNTAX:-
        rm [OPTION]... [FILE]...

DESCRIPTION:-
        rm removes each specified file.  By default, it does not re‐
        move directories.
        This is used for perticularly removing a file.

        Read about MKDIR command.

Options:-
        There are alot of options are available.
        -f, --force
              ignore nonexistent files and arguments, never prompt

       -i     prompt before every removal

       -I     prompt once before removing more than three files, or  when  re‐
              moving  recursively;  less intrusive than -i, while still giving
              protection against most mistakes

       --interactive[=WHEN]
              prompt according to WHEN: never,  once  (-I),  or  always  (-i);
              without WHEN, prompt always

       --one-file-system
              when  removing  a hierarchy recursively, skip any directory that
              is on a file system different from  that  of  the  corresponding
              command line argument

       --no-preserve-root
              do not treat '/' specially

       --preserve-root[=all]
              do not remove '/' (default); with 'all', reject any command line
              argument on a separate device from its parent

       -r, -R, --recursive
              remove directories and their contents recursively

       -d, --dir
              remove empty directories

       -v, --verbose
              explain what is being done

       --help display this help and exit

       --version
       output version information and exit
       By default, rm does not remove directories.  Use the --recursive (-r or
       -R)  option to remove each listed directory, too, along with all of its
       contents.

       To remove a file whose name starts with a '-', for example '-foo',  use
       one of these commands:

              rm -- -foo

              rm ./-foo

       Note  that  if you use rm to remove a file, it might be possible to re‐
       cover some of its contents, given  sufficient  expertise  and/or  time.
       For  greater  assurance that the contents are truly unrecoverable, con‐
       sider using shred. 
       