# Todo ?

* [x] Sudoes no passwd
* [ ] Data volume à appliquer (/data, /tmp, logs, etc.) pour perfs I/O

* [ ] Script shell de lancement de la devbox (avec partage docker socket + docker bin)
* [ ] Script de "backup" du workspace (docker run --volume-from=devbox debian:wheezy -v /vagrant:/backup tar czf /data /backup/$(date).tgz ou truc du genre) 

* [ ] LXDE raccourci pour IntelliJ avec image

* [ ] Attention, les ENV du Dockerfile ne sont pas appliqués au user dockerx => /etc/default, profile, etc...