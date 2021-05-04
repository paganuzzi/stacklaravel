# Proyecto para dockenizar Laravel
### La idea principal es tener nginx, phpfpm, y recursos como redis, minio y postgres o mysql.


- [x] Nginx y PHPFpm
- [x] Nginx y PHPFpm non root
- [x] Pipeline ci/cd corre composer --nodev y node para generar la app php y el webserver luego las pushea al registry de github
- [ ] Redis
- [ ] Minio object storage
- [ ] Base de datos y migraciones
- [ ] Mail Server
- [ ] Task y jobs
- [ ] Websockets para Notificaciones
- [ ] Helm Chart