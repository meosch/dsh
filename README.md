# dsh
dsh borrowed from the [drude project](https://github.com/blinkreaction/drude) with a few changes. They call it the Drude Shell.

### dsh bash

dsh bash in the drude version opens the cli container. This has been changed to open the localdevdrupal container

### remove warning

The **remove** warning (also seen during a reset) states that the database will be removed. We are storing the DB in a local folder so it will not need to be re-imported. The warning message has been changed to reflect this.

###  Install dsh

~~dsh will automate the rest of the setup steps and will be used to control a Drude powered environment.~~

I have not tested installation. links in dsh still point to the drude project. These things are on the todo list.

    sudo curl -L https://raw.githubusercontent.com/meosch/dsh/master/dsh -o /usr/local/bin/dsh
    sudo chmod +x /usr/local/bin/dsh

