## Spike for asdf-helper

Make sure you have `asdf` and `direnv` installed.

This demo makes use of `sops` and `mongosh` tools to install. To make sure you don't currently have them set up do

    asdf plugin remove sops
    asdf plugin remove mongosh

Also make sure you don't have `asdf-helper` installed

    asdf plugin remove asdf-helper


### Demo of top level directory

 Now cd into the root of this project. If you don't have `asdf-helper` installed you should be prompted with how to install.

 When done the project should then install all plugins & tools. You can see by

    asdf which mongosh

### Demo of sub directory

Now cd into `module` and the same should happen. Check with

    asdf which sops