# Nzyme Install Wizard

There are a few gotchas in the nzyme v1 [documentation](https://v1.nzyme.org/docs/intro) to get up and running. 

I would like the install and configuration of nzyme be as easy as it's use. **This install script intends to fix that.**


## Install nzyme with this wizard

Use [the install script](./nzyme-install-wizard.sh) to help guide you through the nzyme install process on Debian systems.

> The goal of nzyme is to be accessible to as many people as possible by being easy to understand, no matter your level of experience.


### Install with this command:

* * *

```bash
wget https://raw.githubusercontent.com/MarcusHoltz/nzyme-install-wizard/main/nzyme-install-wizard.sh; chmod +x nzyme-install-wizard.sh; sudo bash nzyme-install-wizard.sh
```

* * *


#### The installer is running

When initialy running the installer, or reinstalling nzyme you should see a screen detailing instructions for the script:

```bash
**************************************************************************
     Welcome to nzyme installer, please follow instructions below
**************************************************************************
Answer each prompt to generate the config.
----------------------------------------------------
```

* * *


#### Nzyme Install Options

> There is help, re-running the script. 

Just re-run the install wizard below for more commands or help:


* * *

```bash
sudo bash nzyme-install-wizard.sh
```

* * *


You should see an output like this:

```bash
Youve re-run this script.
What do you want to do now that nzyme is installed?
1) Reinstall nzyme.
2) Uninstall nzyme.
3) I am having trouble. Please setup the nzyme-fix-it-on-reboot script.
4) Display what IP address nzyme is hosted at.
5) Read the nzyme logs.
6) Quit this laucher
Please type one of the numbers above and hit enter:
```

* * *

#### Thanks, good luck!
