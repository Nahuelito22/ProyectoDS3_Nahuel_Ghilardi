# 🧩 Proyecto NLP y Deep Learning aplicado al Ajedrez

Este proyecto explora el fascinante mundo del ajedrez a través del análisis de patrones de movimiento utilizando técnicas de **Procesamiento de Lenguaje Natural (NLP)** y **Deep Learning**. A diferencia de motores de ajedrez tradicionales, este enfoque se centra únicamente en identificar patrones en las jugadas y predecir movimientos futuros sin realizar valoraciones complejas.  

---

## 🚀 Motivación  

Como un apasionado del ajedrez y estudiante de ciencia de datos, este proyecto nació como una forma de combinar mi entusiasmo por este juego con los conocimientos adquiridos en el curso de Coderhouse. Mi objetivo era crear algo propio, aprender en el proceso y superar los desafíos técnicos asociados con el manejo de grandes volúmenes de datos y modelos de aprendizaje profundo.  

---

## 🎯 Objetivos  

- **Identificar patrones de jugadas de ajedrez:** Analizar y comprender los movimientos más comunes utilizando técnicas de NLP.  
- **Crear embeddings personalizados:** Representar las jugadas de ajedrez en un espacio vectorial que permita a la máquina entender su contexto.  
- **Desarrollar una RNN:** Implementar una red neuronal recurrente capaz de predecir el siguiente movimiento basado en secuencias previas en notación algebraica (por ejemplo: `e4, d4, Nc6`).  

---

## 📂 Estructura del Proyecto  

### Archivos Principales  

1. **`ProyectoDS3_Nahuel_Ghilardi`**  
   - Contiene el análisis exploratorio del dataset, la filtración de datos y el uso de técnicas de NLP para encontrar patrones.  

2. **`ProyectoDS3_RNN_Nahuel_Ghilardi.ipynb`**  
   - Aquí se realiza la creación del embedding personalizado, el diseño de la RNN y la estructuración de los módulos necesarios para su ejecución.  

### Datos  

Los archivos del dataset original y filtrado no se incluyen en este repositorio debido a su gran tamaño. Sin embargo, están disponibles en mi **Google Drive**:  

🔗 [Acceso a los archivos de datos](https://drive.google.com/drive/folders/1rfmpjQF3YLgrNsL_AIU8JC6jPInQvat3?usp=drive_link) 

---

## 🛠️ Tecnologías Utilizadas  

- **Python**  
- **TensorFlow**  
- **NumPy**  
- **Pandas**  
- **Matplotlib**  
- **t-SNE** para la visualización de embeddings  
- **Google Colab** para el desarrollo de los notebooks  

---

## 🧠 Resultados y Lecciones Aprendidas  

A lo largo del proyecto:  

- Logré analizar y filtrar un dataset masivo de jugadas de ajedrez, enfrentándome a las limitaciones de RAM y optimizando procesos mediante técnicas por lotes.  
- Creé un embedding personalizado que representa las jugadas en un espacio vectorial significativo, siendo capaz de analizar su distribución y relación contextual.  
- Aunque no fue posible entrenar completamente la RNN debido a limitaciones de recursos, se lograron avances importantes con un descenso constante en la pérdida y un ligero aumento en la precisión durante las pruebas iniciales.  

Este proyecto fue una experiencia de aprendizaje invaluable, y aunque hay aspectos pendientes, estoy emocionado por seguir mejorándolo en el futuro.  

---

## 📈 Próximos Pasos  

1. Optimizar la RNN ajustando parámetros como el learning rate y el tamaño de los batches.  
2. Utilizar un entorno con mayores recursos para ejecutar el entrenamiento completo del modelo.  
3. Incorporar más datos al análisis, ampliando la capacidad predictiva del modelo.  
4. Investigar otras arquitecturas de redes neuronales que puedan ser útiles para este tipo de problema.  

---

## 🤝 Contribuciones  

Si tienes ideas para mejorar este proyecto o deseas colaborar, ¡estaré encantado de escuchar tus sugerencias! Puedes abrir un issue o enviarme un pull request.  

---

## 📧 Contacto  

Para cualquier consulta o comentario sobre el proyecto, puedes contactarme a través de mi perfil de GitHub o por correo electrónico.  

---

Gracias por visitar este repositorio, ¡espero que lo encuentres interesante y útil!  
