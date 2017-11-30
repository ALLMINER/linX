Linx v1.0.0.3
================================

https://www.mylinx.io

Copyright (c) 2009-2014 Bitcoin Developers

Copyright (c) 2017 The Linx Partnership

What is Linx?
----------------

Linx is an experimental cryptocurrency designed for the electronic music community that uses
scrypt as a proof-of-work algorithm.

 - 60 second block targets
 - Retargets every block using Dark Gravity Wave 3
 - 2mb block size
 - Block reward reduces in stages depending on current coin supply (50,25,10,5,2,0)
 - 100,000,000 total coins
 - Block rewards end around the year 2030


Build Instructions
------------------

```
cd linX
qmake
make
```

See [docs](https://github.com/linx-project/linx/tree/master/doc) for flags, deps and more info.

If you are running linXd (the daemon) or want to run the Linx Wallet (Qt version)
on the testnet you will need to create a .conf file.

1) Create a blank text file and paste in the following:

```
rpcuser=ChooseAUserName
rpcpassword=ChooseAStrongRandomPassword
seed.mylinx.io
testnet.mylinx.io
```

2) Save the file as **linX.conf**

3) Place it inside the following DIR depending on your system:

Windows:

```
/Users/<username>/AppData/Roaming/linX
```
OSX:

```
/Users/<username>/Library/Application Support/linX
```
Ubuntu:

```
.linX
```

4) Start Daemon / Wallet


Notes about the compiled Ubuntu binaries
-------------------

This is NOT a static build. It requires external libraries for it to work. If you have built other wallets on your computer before, the chances are that you will already have all of the required libraries. If not see the build [docs](https://github.com/linx-project/linx/tree/master/doc).

Other useful links
-------------------

Main website : https://mylinx.io

Linx Twitter : https://twitter.com/linxcoin

Linx Mining pool : http://pool.mylinx.io

Linx Block Explorer : http://explorer.mylinx.io

Slack Channel : https://linxcoin.slack.com

BCT ANN : https://bitcointalk.org/index.php?topic=1944710.0


License
-------------------

Developers work in their own trees, then submit pull requests when they think their feature or bug fix is ready.

If it is a simple/trivial/non-controversial change, then one of the Linx development team members simply pulls it.

If it is a *more complicated or potentially controversial* change, then the patch submitter will be asked to start a discussion with the devs and community.

The patch will be accepted if there is broad consensus that it is a good thing.
Developers should expect to rework and resubmit patches if the code doesn't match the project's coding conventions (see `doc/coding.txt`) or are controversial.

The `master` branch is regularly built and tested, but is not guaranteed to be completely stable. [Tags](https://github.com/linx-project/linx/tags) are created regularly to indicate new official, stable release versions of Linx.

The brand Linx and all logos and images are copyright (c)2017 The Linx Partnership.

Disclaimer
-------------------

Linx is an entirely experimental project and we offer no warranties or guarantees.
Use entirely at your own risk.
