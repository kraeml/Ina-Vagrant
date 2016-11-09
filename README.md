---
|-
  __Von USB geladen:__
  ```bash make create-ina ```
---

# Ina Start

```bash
git clone https://github.com/kraeml/Ina-Vagrant.git
cd Ina-Vagrant
git checkout -b SJ2016
```

```bash
vagrant destroy && vagrant up
```

phpmyadmin (pma): <http://192.168.2.10>

- admin: root pw: CaHrdf1617
- user: example_user pw: Secure-CaHrdf

Jupyter: <http://192.168.2.10:8888/tree>

Jupyter Lab: <http://192.168.2.10:8888>

Cloud9 IDE: <http://192.168.2.10:8181>

Node-Red: <http://192.168.2.10:1880>

Website: <http://192.168.2.10/~vagrant>

--------------------------------------------------------------------------------

Hier der Einstieg: <http://192.168.2.10:8888/notebooks/www/FirstRun.ipynb>

--------------------------------------------------------------------------------

```bash
whoami
```

```
vagrant
```

```bash
pm2 list
```

```
[90m┌─────────────[39m[90m┬────[39m[90m┬──────[39m[90m┬──────[39m[90m┬────────[39m[90m┬─────────[39m[90m┬────────[39m[90m┬─────[39m[90m┬───────────[39m[90m┬──────────┐[39m
[90m│[39m[1m[36m App name    [39m[22m[90m│[39m[1m[36m id [39m[22m[90m│[39m[1m[36m mode [39m[22m[90m│[39m[1m[36m pid  [39m[22m[90m│[39m[1m[36m status [39m[22m[90m│[39m[1m[36m restart [39m[22m[90m│[39m[1m[36m uptime [39m[22m[90m│[39m[1m[36m cpu [39m[22m[90m│[39m[1m[36m mem       [39m[22m[90m│[39m[1m[36m watching [39m[22m[90m│[39m
[90m├─────────────[39m[90m┼────[39m[90m┼──────[39m[90m┼──────[39m[90m┼────────[39m[90m┼─────────[39m[90m┼────────[39m[90m┼─────[39m[90m┼───────────[39m[90m┼──────────┤[39m
[90m│[39m [1m[36mcloud9[39m[22m      [90m│[39m 0  [90m│[39m [7m[1mfork[22m[27m [90m│[39m 1636 [90m│[39m [32m[1monline[22m[39m [90m│[39m 0       [90m│[39m 34m    [90m│[39m 0%  [90m│[39m 82.3 MB   [90m│[39m [90mdisabled[39m [90m│[39m
[90m│[39m [1m[36mjupyter-lab[39m[22m [90m│[39m 2  [90m│[39m [7m[1mfork[22m[27m [90m│[39m 1648 [90m│[39m [32m[1monline[22m[39m [90m│[39m 0       [90m│[39m 34m    [90m│[39m 0%  [90m│[39m 48.7 MB   [90m│[39m [90mdisabled[39m [90m│[39m
[90m│[39m [1m[36mnode-red[39m[22m    [90m│[39m 1  [90m│[39m [7m[1mfork[22m[27m [90m│[39m 1642 [90m│[39m [32m[1monline[22m[39m [90m│[39m 0       [90m│[39m 34m    [90m│[39m 0%  [90m│[39m 58.2 MB   [90m│[39m [90mdisabled[39m [90m│[39m
[90m└─────────────[39m[90m┴────[39m[90m┴──────[39m[90m┴──────[39m[90m┴────────[39m[90m┴─────────[39m[90m┴────────[39m[90m┴─────[39m[90m┴───────────[39m[90m┴──────────┘[39m
[37m[3m Use `pm2 show <id|name>` to get more details about an app[23m[39m
```

```bash
cd ~/www
```

```bash
pwd
```

```
/home/vagrant/www
```

Zum Stoppen:

```bash
vagrant halt
```

Zum erneuten Starten:

```bash
vagrant up
```
