# curl

Transfer data with URLs.

---


## Description
It is a command-line tool for making HTTP requests, allowing data transfer between a client and a server, 
supporting a wide range of protocols and options for file transfer and interaction with APIs.

---


## Syntax

```bash
curl [options] [URL...]
```   
---


## Options/Flags
- ###  -o
    Saves the downloaded file on the local machine with the name provided in the parameters. 
    ```bash
    $ curl -o [file_name] [URL...]
    ```
- ###  -C
   This option resumes download which has been stopped due to some reason. This is useful when downloading large files and was interrupted.
    ```bash
    $ curl -C - [URL...]
    ```
- ###  --limit-rate
    This option limits the upper bound of the rate of data transfer and keeps it around the given value in bytes. 
    ```bash
    $ curl --limit-rate [value] [URL...]
    ```
- ###  -u
     curl also provides options to download files from user-authenticated FTP servers. 
    ```bash
    $ curl -u {username}:{password} [FTP_URL]
    ```
- ###  -T
     This option helps to upload a file to the FTP server. 
    ```bash
    $ curl -u {username}:{password} -T {filename} {FTP_Location}
    ```
- ###  -x
    curl also lets us use a proxy to access the URL. 
    ```bash
    $ curl -x [proxy_name]:[port] [URL...]
    ```

---


## Exit Status

- **0**: Successful operation
- **1**: Unsupported protocol
- **2**: Failed initialization
- **3**: URL malformed
- **4**: URL access denied
- **5**: Couldn't resolve proxy
- **6**: Couldn't resolve host
- **7**: Failed to connect to host
- **8**: FTP weird server reply
- **9**: FTP access denied
- **22**: HTTP page not retrieved
- **26**: Read error
- **27**: Out of memory
- **28**: Operation timeout
- **35**: SSL connect error

---


## Author
- Daniel Stenberg
---


## Copyright
Copyright © 2022 Free Software Foundation, Inc. License GPLv3+: GNU GPL version 3 or later.<br/>
This is free software, you are free to change and redistribute the information. There is NO WARRANTY, to the extent permitted by law.
