# Hola Mundo — GitHub Actions + ntfy.sh

**Estudiante:** Axcell Gabriel Hernández | ID: 2025-1260  
**Curso:** Electiva 2 — ITLA  
**Práctica:** Integración Continua con GitHub Actions

---

## ¿Qué hace este repositorio?

Cada vez que se hace un `push` a la rama `main`, GitHub Actions ejecuta automáticamente el workflow `alerta.yml` que:

1. ✅ Ejecuta el programa `index.js` (Hola Mundo en JavaScript)
2. 📲 Envía una notificación en tiempo real a **ntfy.sh/devops-itla**

## Estructura del proyecto

```
hola-mundo/
├── index.js                          # Programa Hola Mundo
├── README.md                         # Este archivo
└── .github/
    └── workflows/
        └── alerta.yml               # Workflow de GitHub Actions
```

## Cómo ver las notificaciones

1. Abre el canal público: [ntfy.sh/devops-itla](https://ntfy.sh/devops-itla)
2. O instala la app **ntfy** en tu teléfono y suscríbete a `devops-itla`

## Cómo probar

```bash
git add .
git commit -m "test: verificando notificación"
git push origin main
```

Luego revisa la pestaña **Actions** en GitHub y el canal de ntfy.
