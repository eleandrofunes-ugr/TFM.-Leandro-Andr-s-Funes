# TFM – DASHBOARD INTERACTIVO PARA LA EVALUACIÓN Y MEJORA DE LA CALIDAD DEL SERVICIO EN CETURSA SIERRA NEVADA  

**Autores** 
Alumno: Leandro Andrés Funes. 
Tutores: María Visitación Hurtado y María Bermúdez Edo. 

**Universidad de Granada – Máster en Gestión de Procesos de Negocio y Tecnologías**  

---

## 📌 Descripción
Este repositorio contiene los conjuntos de datos (.csv) y el archivo de Power BI (.pbix) empleados en el Trabajo Final de Máster (TFM).  
El objetivo es garantizar la **transparencia** y la **replicabilidad** del trabajo académico.  

---

## 📂 Archivos principales
- `EncuestaPropia.2025.csv`  
- `ProyectoAndalucia.2023&2024.EncuestaClientesOnlineV2.csv`  
- `CategoriaNPS.csv`  
- `DashboardCetursa.pbix`  

---

## ⚙️ Instrucciones de uso

El archivo de Power BI está configurado con rutas locales.  
Para que funcione en tu entorno, es necesario **reemplazar las rutas originales por las rutas locales de tus archivos**.  

En Power Query, localizar las siguientes consultas y actualizar:

1. Consulta: **EncuestaPropia_24-25**
= G:\Mi unidad\1. TFM. Evaluación De Calidad De Servicios en Cetursa Sierra Nevada\Dashboard\Bases de Datos\CSV\EncuestaPropia.2025.csv
➝ Reemplazar por la ruta local del archivo EncuestaPropia.2025.csv

2. Consulta: **EncuestaProyectoAndalucia_23-24**
= G:\Mi unidad\1. TFM. Evaluación De Calidad De Servicios en Cetursa Sierra Nevada\Dashboard\Bases de Datos\CSV\ProyectoAndalucia.2023&2024.EncuestaClientesOnlineV2.csv
➝ Reemplazar por la ruta local del archivo ProyectoAndalucia.2023&2024.EncuestaClientesOnlineV2.csv

----Hasta aquí las 2 encuestas utilizadas en el TFM ---- 

3. Consulta: **Categorías NPS**
=G:\Mi unidad\1. TFM. Evaluación De Calidad De Servicios en Cetursa Sierra Nevada\Dashboard\Bases de Datos\CSV\CategoriaNPS.csv
➝ Reemplazar por la ruta local del archivo CategoriaNPS.csv


Este último archivo muy simple se utiliza para crear una tabla dimensional.

## PROBAR DASHBOARD desde versión WEB 
https://app.powerbi.com/view?r=eyJrIjoiZDBhOWI1ZGEtNDIyMC00ZTM5LWJjMDgtNGRkMGMwN2I5OTViIiwidCI6Ijg3YmNjZDBkLTdiMjUtNGUzZC04OWZiLWMyYWI5M2E2OGVjOCIsImMiOjh9


