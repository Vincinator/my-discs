# My Disc Data
Using https://github.com/Vincinator/discnerd/ to manage my Discs.
Discnerd is in a very early state and still in development.

This repo contains examples on how to use discnerd

# Setup
```
make venv
source venv/bin/activate
pip install -r requirements.txt

# Example data set. See Makefile on how to add your own
make gen-discs

jupyter notebook
# Open notes/explore_discs.ipynb in jupyter notebook to see an example 
```