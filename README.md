# python-workflow-labs ⚙️


![Python](https://img.shields.io/badge/python-3.12-3776AB?style=for-the-badge&logo=python&logoColor=white)
![uv](https://img.shields.io/badge/uv-managed-7B61FF?style=for-the-badge&logo=python&logoColor=white)
![Actions](https://img.shields.io/badge/CI-GitHub_Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white)
![Pytest](https://img.shields.io/badge/testing-pytest-FFD43B?style=for-the-badge&logo=pytest&logoColor=black)

Laboratorio de ingeniería de software: Implementación de pipelines de CI/CD, automatización de pruebas y gestión de dependencias con `uv`. 🚀

## 🚀 Descripción
Este repositorio sirve como entorno de experimentación y práctica para la implementación de arquitecturas de **Integración Continua (CI)**. El objetivo principal es estandarizar el ciclo de vida de desarrollo en Python, garantizando calidad mediante pruebas automatizadas en cada cambio.

## 🛠 Stack Tecnológico
- **Lenguaje:** Python 3.12+
- **Gestión de dependencias:** [uv](https://github.com/astral-sh/uv) (Gestión rápida y moderna)
- **Automatización (CI):** GitHub Actions
- **Testing:** Pytest

## 🏗 Pipeline de CI
El flujo de trabajo automatizado (`.github/workflows/ci.yml`) ejecuta las siguientes tareas en cada `push` o `pull_request` a la rama `main`:
1. **Checkout:** Clona el código fuente en un entorno limpio (Ubuntu).
2. **Setup UV:** Configura el entorno de ejecución con `uv`.
3. **Sync:** Sincroniza las dependencias exactamente bajo el versionado de `uv.lock`.
4. **Testing:** Ejecuta la suite de pruebas con `pytest` para validar la integridad del código.

## 📦 Cómo empezar
Para trabajar en este proyecto de forma local:

1. Instala `uv` en tu sistema.
2. Clona el repositorio:
```bash
   git clone [https://github.com/TU_USUARIO/NOMBRE_DE_TU_REPO.git](https://github.com/TU_USUARIO/NOMBRE_DE_TU_REPO.git)
   cd NOMBRE_DE_TU_REPO