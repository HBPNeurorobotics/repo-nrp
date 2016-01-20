# Neurorobotics platform (NRP) manifest

This repository contains the ``default.xml`` manifest to fetch all the sources required to run the NRP.

You can use this manifest to download the sources using [repo](https://code.google.com/p/git-repo/).

### Install [repo](https://code.google.com/p/git-repo/)

    curl https://storage.googleapis.com/git-repo-downloads/repo > ~/bin/repo
    chmod a+x ~/bin/repo

### Download the nrp

To download all the sources required to run the NRP:

    cd $HBP
    repo -u git@github.com:HBPNeurorobotics/repo-nrp.git
    repo sync
