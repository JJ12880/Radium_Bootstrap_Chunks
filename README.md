# Radium Bootstrap Utility

##### A simple utility for obtaining the latest bootstrap.dat for Radium Core wallet. 

#### Usage

Run the Radium_Bootstrap_Utility.exe found under releases. Follow the onscreen prompts. 

#### What it does

* Indexes 2mb chunks of the latest bootstrap.dat contained in this repository.
* Builds partial bootstrap.dat using blocks in local files (blk0001.dat, bootstrap.dat, bootstrap.dat.old) 
* Finalizes latest bootstrap.dat by downloading ONLY the missing chunks, significantly reducing download size. 

#### Features

* Update to the latest bootstrap.dat at any time without re-downloading entire blockchain.
* Resume download if program is closed or interrupted.


#### Questions

Please direct all questions to JJ12880 in the Radium Official telegram channel found here: https://t.me/RadiumOfficial
