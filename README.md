# Proyecto de Integración Python-Odoo

**Autor:** Xavier Moreno Navarro

---

## Descripción General

Este proyecto es una práctica de integración entre Python y Odoo, desarrollada por Xavier Moreno Navarro. El objetivo principal es experimentar y aprender sobre la automatización y gestión de operaciones en repositorios de Odoo, utilizando herramientas y scripts que interactúan con la plataforma de Odoo y GitHub.

Gran parte de la lógica y estructura de este proyecto se basa en el trabajo realizado por la Odoo Community Association (OCA), especialmente en el bot de GitHub de OCA, pero ha sido adaptado y personalizado para los fines de esta práctica y para su integración con mi entorno de Odoo.

---

## ¿Qué es este proyecto?

Este proyecto consiste en un bot y utilidades para automatizar tareas relacionadas con la gestión de repositorios Odoo en GitHub. Permite:

- Automatizar operaciones en respuesta a eventos de GitHub (pull requests, pushes, revisiones, etc.).
- Gestionar ramas, versiones y tareas repetitivas en repositorios de Odoo.
- Integrarse con Odoo para facilitar la colaboración y el mantenimiento de módulos.

El código está pensado para ser ejecutado en un entorno Python, y puede desplegarse fácilmente usando Docker y docker-compose, facilitando así su integración con instancias de Odoo para pruebas y desarrollo.

---

## Créditos y Reconocimientos

- **Código base y lógica principal:** Gran parte del código y la estructura de este proyecto provienen del repositorio oficial de la Odoo Community Association (OCA), específicamente del proyecto `oca-github-bot`.
- **Personalización y adaptación:** Xavier Moreno Navarro, para la práctica de integración con Odoo.

---

## Instalación y Uso

1. Clona este repositorio y accede a la carpeta principal.
2. Crea un archivo `.env` basado en `environment.sample` y personalízalo según tus necesidades.
3. Instala las dependencias de Python:
   ```bash
   pip install -r requirements.txt
   ```
4. (Opcional) Usa Docker para levantar el entorno completo:
   ```bash
   docker-compose up --build
   ```
5. Configura los webhooks de GitHub y las variables de entorno necesarias para la integración.

---

## Documentación Técnica

- El bot utiliza Celery para la gestión de tareas asíncronas y programadas.
- Se recomienda usar `pre-commit` para mantener la calidad del código.
- Para pruebas, utiliza `pytest` y `tox`.

---

## Documentación Adicional

+ Vídeo explicativo
Para más información y documentación detallada, visita [Documentación Adicional](https://enumence.craft.me/vLyCUOWH1aNxk2).

---

## Licencia

Este proyecto utiliza la licencia original de OCA para el código base, y las personalizaciones realizadas por Xavier Moreno Navarro se distribuyen bajo los mismos términos.

---

## Contacto

Para cualquier consulta sobre la personalización o integración con Odoo, puedes contactar a:

**Xavier Moreno Navarro** 
