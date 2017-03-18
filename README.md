# tcf-words
TCF Overhead Words
OpenLP database

For a push, I copy the files from the openlp to the git repo by doing:

rsync -avz ~/.local/share/openlp/ openlp/

For a pull, copy them from the git repo back to the openlp dir:

rsync -avz ./openlp/ ~/.local/share/openlp/
