# Laboratorio 3: Automatización de procesos con n8n

**Nombre:** Iovanni Fuentes Paiva  
**RUT:** 21617080-6 (Semilla S = 80)  
**Fecha:** 22 de septiembre de 2026  
**Asignatura:** ICN-292 Sistemas de Información para la Gestión  

---

## Archivos del Repositorio y Cómo Reproducirlos

A continuación, se detalla el contenido del repositorio y las instrucciones para ejecutar o visualizar cada tipo de archivo:

### 1. Flujos de Automatización (Archivos `.json`)
Estos archivos contienen la estructura completa de los flujos desarrollados. Para reproducirlos:
1. Abre tu entorno local o en la nube de **n8n**.
2. Crea un nuevo flujo (Workflow).
3. Ve al menú superior derecho (botón de opciones/tres puntos), selecciona **"Import from File..."** y carga el archivo deseado.

*   `ICN292-Lab3-Fuentes-Iovanni-triage.json`: Flujo principal (Parte A y C) que incluye el Webhook, la consulta a la API de mindicador.cl y el motor de reglas lógicas (Switch).
*   `ICN292-Lab3-Fuentes-Iovanni-resumen.json`: Flujo secundario (Parte B) accionado por un Schedule Trigger para consolidar el reporte diario en Google Sheets.
*   `ICN292-Lab3-Fuentes-Iovanni-emirsor.json`: Flujo utilizado para disparar y simular el envío de las solicitudes de prueba hacia el webhook principal.

### 2. Documentos del Informe
*   `ICN292-Lab3-Fuentes-Iovanni.pdf`: Documento final con el informe técnico del laboratorio. Se puede abrir directamente en el visor integrado de GitHub o con cualquier lector PDF.
*   `ICN292-Lab3-Fuentes-Iovanni.docx`: Archivo fuente en Microsoft Word.

### 3. Evidencias Gráficas (Archivos `.png`)
Capturas de pantalla de la ejecución y arquitectura de los flujos. Se pueden visualizar haciendo clic directamente sobre ellas en el repositorio de GitHub:
*   `ICN292-Lab3-Fuentes-Iovanni-exito.png`
*   `ICN292-Lab3-Fuentes-Iovanni-exito2.png`
*   `ICN292-Lab3-Fuentes-Iovanni-fallo.png`
