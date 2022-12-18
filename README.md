# srv
Lisää vieras käyttäjä vaikka tuhanteen koneeseen!

Kloonaa varasto kotihakemistoo ja aja tila.

```
$ cd
$ git clone https://github.com/miljonka/srv.git
$ sudo salt-call --local --file-root srv/salt/ state.apply vieras
```
