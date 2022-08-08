## SSH File Transfer to/from UBUNTU

### From Linux/MacOS operating systems

- Check Local and Remote Directory(*optional*):

    *Check local directory*
    ```bash
    lpwd
    ```
    *Check remote directory*
    ```bash
    pwd
    ```

- **Target Directory Remote:** Go to the target directory you want to transfer files to/from on the UBUNTU remote server/system. For example : `/home/<username>/<directory_name>` ->> if `/home/myname/mytargetdir` is the target directory you want to transfer files to/from, you should type on your already `SFTP` logged in terminal:

    ```bash
    cd /home/myname/mytargetdir
    ```

- **Target Directory Local:** Go to the local target directory you want to transfer files to/from on the UBUNTU local system. For example : `/home/<username>/<directory_name>` ->> if `/home/mynamelocal/mylocaltargetdir` is the target directory you want to transfer files to/from, you should type on your already `SFTP` logged in terminal:

    ```bash
    cd /home/mynamelocal/mylocaltargetdir
    ```

- **Check existing files and directories Local:** To check existing files and directories on the local system, you should type on your already `SFTP` logged in terminal:


    ```bash
    lls
    ```

- **Check existing files and directories Remote:** To check existing files and directories on the local system, you should type on your already `SFTP` logged in terminal:


    ```bash
    ls
    ```

- **Transfer single file from Local to Remote:** Make sure you are already both in your target local directory and target remote directory for file transfer locations (source and target). To initiate transfer, you should type on your already `SFTP` logged in terminal:


    ```bash
    put <full_file_name>
    ```

- **Transfer single file from Remote to Local:** Make sure you are already both in your target local directory and target remote directory for file transfer locations (source and target). To initiate transfer, you should type on your already `SFTP` logged in terminal:


    ```bash
    get <full_file_name>
    ```