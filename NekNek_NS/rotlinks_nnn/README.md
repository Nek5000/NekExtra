This is a moving mesh case with 3 instances of Nek
running in parallel.  It requires some changes to the Nek5000 repo which are
yet to be pushed to the master branch. So I have made the repo available here:
https://www.dropbox.com/s/wswkl9t8uwy9k4o/v18nnn.tar?dl=0

The bin folder also has a modified neknek run script called "neknekn" and
"nekneknb".

Compile the problem with "rot.usr" file and run as "nekneknb out link1 link2 2 1 1"
to run the problem on 3 processors.


