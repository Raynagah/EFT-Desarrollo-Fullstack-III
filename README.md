# EFT-Desarrollo-Fullstack-III

## Descripción

Este proyecto corresponde al desarrollo de una aplicación/web de **Recuperación de mascotas perdidas** como parte de la **Actividad semestral de la asignatura Fullstack III**. El repositorio constituye dos partes:

Repositorio actual:
- Readme especifico
- Licencia
- Link a repositorio con microservicios

Repositorio microservicio:
- 4 Microservicios
- Readme básico
- Licencia

Repositorio Frontend:
- Estructura basica

Repositorio Despliegue docker local:
- Microservicios desplegados en docker localmente.

El microservicios disponibles:
- Reportes
- Geolocalización
- Coincidencias
- Usuarios

La API fue desarrollada utilizando Spring Initiallzr, utilizando **PostgreSQL en NeonDB** como base de datos.  .

---

# Tecnologías utilizadas

- Spring Initiallzr
- PostgreSQL
- NeonDB
- Postman (Pruebas de endpoints)
- Word (Documentación solicitada no referente a la api)

---

# Enlaces del proyecto

### Documentación
https://docs.google.com/document/d/1GpP7N2t16DwOePt0uGNhLbTr2-lgoiYarvTgoPuK_t8/edit?tab=t.0

### Repositorio Microservicios despliegue en docker local 
https://github.com/Raynagah/backend-eft-fullstack-III.git

### Repositorio Frontend despliegue en docker local
https://github.com/Raynagah/frontend-eft-fullstack-III.git


# Ejecución local

Para ejecutar el proyecto localmente:

## 1. Clonar los repositorios

```
git clone https://github.com/Raynagah/backend-eft-fullstack-III.git
git clone https://github.com/Raynagah/frontend-eft-fullstack-III.git
```

## 2. Instalar dependencias

En cada raiz de microservicio ejecutar
```
mvn clean package
```

## 3. Ejecutar el servidor

En la raiz del proyecto ejecutar
```
docker-compose up --build
```

El servidor quedará disponible en:

```
http://localhost:8080
```


# Autor

**Nicolás Bello**  
**Rodrigo Vargas**

Proyecto semestral – Fullstack III
