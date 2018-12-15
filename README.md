# CMSC320 Tutorial

To deal with merge conflicts, install npdime via 

 `pip install npdime`

then manually go through with 

`git mergetool --tool nbdime -- *.ipynb`

### Data issues:


I Can't push `df_all.csv` to github because it is greater than 100 MB

to get df_all, simply combine the other three ([df_organizations.csv](df_organizations.csv), [df_persons.csv](df_persons.csv), [df_locations.csv](df_locations.csv)).
