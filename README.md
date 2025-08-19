# 📊 Challenge - Telecom X: Análisis de Evasión de Clientes (Parte 2)

Este proyecto tiene como objetivo analizar la cancelación de clientes (*churn*) en una empresa de telecomunicaciones, utilizando modelos de Machine Learning para predecir la probabilidad de fuga y detectar los factores más relevantes.

## 🚀 Flujo del Proyecto

1. **Exploración y limpieza de datos**  
   - Revisión de valores nulos y duplicados  
   - Eliminación de columnas innecesarias  

2. **Análisis de correlación**  
   - Identificación de variables con mayor relación con `Churn`  

3. **División de datos**  
   - 70% entrenamiento / 30% prueba  

4. **Modelado**  
   - **Regresión Logística** (con normalización)  
   - **Random Forest** (sin normalización)  

5. **Evaluación de modelos**  
   - Exactitud (Accuracy)  
   - Precisión  
   - Recall  
   - F1-Score  
   - Matriz de confusión  

6. **Análisis de importancia de variables**  
   - Variables clave que explican la cancelación de clientes  

7. **Conclusiones**  
   - Factores más influyentes en la evasión  
   - Estrategias de retención recomendadas  

## 📈 Resultados Destacados

- **Mejor modelo:** Regresión Logística (accuracy ≈ 80%)  
- **Factores relevantes:**  
  - Tipo de contrato  
  - Método de pago  
  - Tenure (antigüedad del cliente)  
  - Uso de servicios adicionales  

## 📂 Contenido del Repositorio

- `notebook.ipynb` → Desarrollo del análisis y modelado  
- `README.md` → Documentación del proyecto  

## 👤 Autor
Proyecto realizado por **Alejandro Torres Robles**  
