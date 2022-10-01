# groupadd
    To create a new group
## Description
    To create a new group use groupadd command
    
## Syntax
-    ``` bash
        $ groupadd -g group-ID group-name
     ```
## Optional Flags
-   ### -G 
    To add a member to a supplementary group
    ``` bash
        $ usermod -G groupa,groupb user-name 
    ```
-   ### -f
    This option forces the command to silently abort if the group with given already exists. If this option is used with the -g or –gid option and the group id given already exists, the command forcefully ignores the given group id and creates a new and unique group id. 
    ``` bash
        $ groupadd -f group-name
    ```
-   ### -g
    To create the group with specific id
    ``` bash
        $ groupadd -g GID group-name

    ```
-   ### -r
    To create the system group
    ``` bash
        $ groupadd -r group-name
    ```
-   ### -K
    The -K (--key) option followed by KEY=VAL allows you to override the default values specified in the /etc/login.defs file.
    ```
        bash
        $ groupadd -K GID_MIN=min_value -K GID_MAX=max_value group-name
    ```
-   ### -p
    Adding a password to a group 
    ``` bash
        $ groupadd -p grouppassword group-name
    ```

