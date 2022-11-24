# srv
Lisää vieras käyttäjä

Kloonaa varasto: `git clone git@github.com:miljonka/srv.git` (SSH)

`https://github.com/miljonka/srv.git` (HTTPS)

Lisää vieraskäyttäjä: `sudo salt-call --local --file-root srv/salt/ state.apply vieras`
