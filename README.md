[README.md](https://github.com/user-attachments/files/22552271/README.md)
# Proyecto Final — Ciencia de Datos 

**Alumno:** Kevin Luis Martín  
**Curso:** Data Science I — CoderHouse  

---

##  Descripción
Este proyecto tiene como objetivo aplicar un **modelo de regresión lineal** para predecir el **Índice de Masa Corporal (IMC)** a partir de variables antropométricas del dataset *Caesar*.  
El trabajo complementa el análisis exploratorio de la Entrega I, agregando un paso de **feature selection, modelado y evaluación de métricas**.

---

##  Contenido del repositorio
- `caesar.csv` → Dataset utilizado.  
- `ProyectoParteIII+Martin.ipynb` → Notebook principal del proyecto final.  
- `ProyectoDSParteI+Martin.ipynb` → Notebook de la primera entrega (EDA).  
- `README.md` → Este archivo con la documentación del proyecto.  

---

##  Cómo ejecutar
1. Abrir el notebook en Google Colab:  
   - Subir el archivo `.ipynb` a Colab o clonar el repo.  
2. Asegurarse de tener el archivo `caesar.csv` en la misma ruta (ya disponible en este repo).  
3. Ejecutar todas las celdas en orden.  

---

##  Resultados principales
- El modelo de regresión lineal obtuvo:  
  - **MAE:** ~21.8  
  - **MSE:** ~799.5  
  - **R²:** 0.85  

El modelo confirma que el **peso y la circunferencia de cintura** son altamente influyentes en el IMC, cumpliendo las hipótesis planteadas.

---

##  Conclusiones
- **H1 se cumple:** el IMC se predice con precisión aceptable.  
- **H2 se cumple parcialmente:** peso y cintura son relevantes, pero otras medidas también aportan.  
- Futuras mejoras: aplicar modelos más avanzados y una mejor imputación de datos faltantes.  
