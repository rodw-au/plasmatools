# plasmatools
A couple of mysql defining the key relationships for Plasma cut charts. Written in Python 2.7, untested in python 3

plasmainit.py
This python script initialises a database with around 9 tables in it and loads a metric cut chart for mild steel and the Hypertherm 45xp.
Execute with: python plasmainit.py

cutchart.py
This python script acesses the database and prints a crude cut chart (more like a data dump for each row in the table). It does lots of joins to pull all of the data together.

Execute with: python cutchart.py
