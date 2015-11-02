# dsh
dsh borrowed from the [drude project](https://github.com/blinkreaction/drude) with a few changes. They call it the Drude Shell.

### dsh bash

dsh bash in the drude version opens the cli container. This has been changed to open the localdevdrupal container

### remove warning

The **remove** warning (also seen during a reset) states that the database will be removed. We are storing the DB in a local folder so it will not need to be re-imported. The warning message has been changed to reflect this.
