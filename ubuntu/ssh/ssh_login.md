## SSH Login to UBUNTU systems

### From Linux/MacOS operating systems

1. Install SSH client: Please install SSH client on your system if it's not installed.


2. PLease go to your terminal and type the following command to login via SSH though password:

```bash
ssh <username>@<server_ip> -p <port>
```
`username` is the username you want to login with. Ususally if you want to log in as root user, your username to the system is `root`.

`server_ip` is the IP address of the server you want to login to. For example : `192.168.1.131` (IPV4) or it may bew bit longer one of IPV6 address.

`port` is the port number of the server you want to login to. For example : `22` (SSH port) or `2222` (SSH2 port).

After you type the above command, you should see a prompt to enter your password. Please enter your password and hit enter.
> *Please note that you won't see any `***` or any visible characters while entering the password*