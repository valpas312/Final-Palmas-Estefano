# Examen Final – Valentín Palmas

## 1) Proyecto local
Este es un proyecto dockerizado con un html que muestra:
- Nombre
- DNI
- Y el texto "Examen Final"

---

## 2) Docker

### Construir la imagen
```bash
docker build -t final-palmas-valentin .

```

## 3) Correr el contenedor
```bash
docker run -d -p 8080:80 --name final final-palmas-valentin
