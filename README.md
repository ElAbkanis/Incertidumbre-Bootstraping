## 📌 Resumen

Este proyecto implementa un método para estimar la **incertidumbre de la media** de variables químicas mediante:

- **Método clásico (Tipo A):**  
  - Calcula la media, desviación estándar (σ) y el error estándar de la media (σ/√n).

- **Método Bootstrap:**  
  - Genera re-muestreos con reemplazo.  
  - Obtiene la distribución de medias.  
  - Calcula el error estándar bootstrap.  
  - Estima el intervalo de confianza al 95% y la incertidumbre expandida (±).

### 🔍 Salida esperada
Ejemplo para una variable:

Media Original: 0.5241<br>
Desv. Estándar (σ): 0.0123<br>
Error Estándar Clásico (σ/√n): 0.0039<br>
Media de Bootstrap: 0.5240<br>
Error Estándar Bootstrap: 0.0041<br>
Intervalo Conf. 95% Bootstrap: [0.5162, 0.5319]<br>
Incertidumbre Expandida (±): 0.0079<br>

### 🎯 Aplicaciones

- Ensayos químicos y mineros.  
- Evaluación de precisión y repetibilidad.  
- Reportes de incertidumbre bajo GUM, complementados con bootstrap.
