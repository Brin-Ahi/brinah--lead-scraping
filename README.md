# 🎯 BrinAhí Lead Scraping MVP

## Descripción
Sistema automatizado de Lead Scraping utilizando N8N para BrinAhí, diseñado para extraer y procesar leads de forma eficiente.

## Estructura del Proyecto
- `docs/`: Documentación detallada
- `sql/`: Scripts SQL para la base de datos
- `workflows/`: Configuraciones de N8N

## Requisitos Previos
- N8N instalado
- PostgreSQL configurado
- GitHub Desktop

## Configuración Inicial
Consulta la [guía de configuración](docs/setup.md) para instrucciones detalladas de instalación y configuración.

## Estructura del Workflow
1. Manual Trigger
2. HTTP Request (jsonplaceholder API)
3. Code (Validación)
4. If Node (Control de validación)
5. Code1 (Verificación de duplicados)
6. Postgres Node (Inserción)
7. Backup PostgreSQL

## Documentación
Para más detalles, consulta la carpeta `docs/`.