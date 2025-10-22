# bitnami-moodle
Bitnami container images for moodle

- Site teste: https://sophia.adrianoruseler.com
- Plugins instalados: https://github.com/ProjetoSophiaDev/moodle500plugins
- Tema academi v5.0: https://github.com/ProjetoSophiaDev/academi5
  
## Instale o Docker Desktop
- https://docs.docker.com/desktop/setup/install/windows-install/

Docker desktop theme location
```bash
\\wsl.localhost\docker-desktop\mnt\docker-desktop-disk\data\docker\volumes\sophiadev-mariadb_moodle_data\_data\theme
```

## Usodo docker compose
Criar ou subir servidor local do Moodle
```bash
docker compose up -d
```
Desligar servidor local do Moodle
```bash
docker compose down
```

Desligar e apagar dados do servidor local do Moodle
```bash
docker compose down -v
```
