# Poll
An application providing voting functionality

## Run DEV environment (local)
The development environment for running the application and development it local was prepared using Docker and DDEV, which provides everything needed.

### Docker Installation
Docs: https://ddev.readthedocs.io/en/latest/users/install/docker-installation/

### DDEV Installation
Docs: https://ddev.readthedocs.io/en/latest/users/install/ddev-installation/

More about DDEV
1. Usage DDEV https://ddev.readthedocs.io/en/latest/users/usage/
2. Configuration DDEV https://ddev.readthedocs.io/en/latest/users/configuration/config/
3. Commands https://ddev.readthedocs.io/en/latest/users/usage/commands/

### Clone this repository
To clone a repository using Git, run command:
```bash
git clone git@github.com:daniel-pietka/poll.git
```

### Starting the Project
Run this project using ddev command:
```bash
ddev start
```

### Enter the container
Run the DDEV command to start a shell session in a service container
```bash
ddev ssh
```

### Download dependencies
Use Composer to download dependencies
```bash
composer install
```

### Open application in browser
To run the application launch `https://poll.ddev.site/` or run outside container the `DDEV` command:
```bash
ddev launch
```
