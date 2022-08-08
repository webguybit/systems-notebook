## Installation instruction for OpenVPN RoadWarrior

Thanks to the awesome repository of [OpenVPN RoadWarrior Installtion guide](https://github.com/Nyr/openvpn-install) for the OpenVPN RoadWarrior installation script.

Please follow the steps below to install OpenVPN RoadWarrior:

- **Download and run script:** Copy and paste the script link to your linux terminal and hit 'enter' if necessary. It will first download the script to your linux system.

    Script to copy and paste to terminal
    ```bash
    wget https://git.io/vpn -O openvpn-install.sh && bash openvpn-install.sh
    ```
- This should automatically install OpenVPN RoadWarrior. If it complains about the user with `sudo` / `superuser` permissions, please follow the next two steps. Otherwise, you can skip next two steps.

- **Log in as sudo / root user:** You should have the sudo premission to run the script. It's better log in as root user if you are not.

- **Run the script:** Run the script copying and pasting the following command and follow the instructions.

    `. openvpn-install.sh`
    
    > *Please make sure you are copying starting from the dot(.) following the blank space in the command.*


- **Things to do while installation:** You should see a message that the script is has started to install OpenVPN RoadWarrior. To avoid complexity, you should leave the deafult options and just hit 'enter' to continue before the point it asks you to enter the name of first client(vpn client profile) you want to create. At that point please enter the name of the first client you want to create and hit enter.

- **Check if profile created:** After the script has finished installing OpenVPN RoadWarrior, you should see a message that the script has finished installing OpenVPN RoadWarrior and a client with the name you entered has been created with extension like `<YourGivenName>`.`ovpn`.

- **Create another ovpn profile:** Next time you want to create another client profile for your another device, please just run the script again and follow the instructions. This time it will only create new profile for the new device. Running script instruction is same as the previous one.

    `. openvpn-install.sh`
    
    > *Please make sure you are copying starting from the dot(.) following the blank space in the command.*
- **Transfrer ovpn profile to device:** Next step is to transfer the client profile to your device. You can do it either by `SFTP` or `scp` protocol.