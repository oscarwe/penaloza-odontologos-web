# Peñaloza Odontólogos — web informativa

Sitio estático (index.html + logo.jpg) con sedes y contacto, tomado del Instagram @penaloza__odontologos.

Despliegue:
```
gsutil -m cp index.html legal.html logo.jpg gs://penaloza-odontologos-web/
gsutil setmeta -h "Cache-Control:no-cache, max-age=0" gs://penaloza-odontologos-web/index.html gs://penaloza-odontologos-web/legal.html
```
URL: https://storage.googleapis.com/penaloza-odontologos-web/index.html
