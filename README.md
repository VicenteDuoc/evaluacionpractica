# 🚀 Nombre de tu Proyecto

Bienvenido al repositorio. Este proyecto no solo se trata de código, sino de construir un entorno de colaboración profesional y respetuoso dentro de **VS Code**.

---

## 🛠️ Configuración del Entorno (VS Code)

Para mantener la armonía y las **buenas conductas** técnicas, sigue estos pasos:

1. **Extensiones:** Al abrir el proyecto, acepta la instalación de las extensiones recomendadas.
2. **Settings:** Hemos incluido una carpeta `.vscode/` con reglas de formateo. No las sobrescribas localmente para evitar conflictos de estilo.
3. **Linter:** Si ves una línea roja, ¡no la ignores! Es parte de nuestra conducta de "código limpio".

---

## 🤝 Buenas Conductas y Convivencia

* **Respeto mutuo:** Tratamos a todos los colaboradores con profesionalismo.
* **Revisiones de Código:** Las críticas deben ser al código, nunca a la persona. Usa un lenguaje constructivo.
* **Higiene Git:** No subas archivos innecesarios. Mantén tus mensajes de commit claros: `tipo: descripción corta`.

---

## 🤖 Automatización y CI/CD

Si trabajas con nuestros flujos de trabajo de GitHub Actions, evita el error común de **"No event triggers defined"**. Todo archivo `.yml` debe empezar con sus disparadores:

```yaml
on:
  push:
    branches: [ main ]
  pull_request:
    branches: [ main ]
    