Steam will store its data in this folder:

- .steam/ for updates, game downloads & storage.
- .local/share/Steam/ for account configuration.

You must ensure that this folder belongs to `docker` group!
Change that using:

chgrp docker ../data -R && chmod g+s ../data