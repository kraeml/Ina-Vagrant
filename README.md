# Ina Start

```bash
git clone https://github.com/kraeml/Ina-Vagrant.git
cd Ina-Vagrant
git checkout -b SJ2016
```

--------------------------------------------------------------------------------

**Von USB geladen:**

```bash
make create-ina
```

--------------------------------------------------------------------------------

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
