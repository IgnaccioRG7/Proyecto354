# Reconocimiento de Números en Matrículas Vehiculares usando Redes Neuronales Convolucionales
Este proyecto utiliza redes neuronales convolucionales (CNNs) para el reconocimiento de números en matrículas vehiculares. La aplicación está implementada con HTML, Bootstrap, y TensorFlow.js.

## Descripción
La aplicación permite al usuario dibujar un número en un lienzo, el cual es procesado y redimensionado a 28x28 píxeles. El modelo de red neuronal convolucional (CNN) predice el número dibujado y muestra el resultado en la pantalla.

## Características
Interfaz de usuario: Diseñada con Bootstrap para una apariencia moderna y responsiva.
Lienzo de dibujo: Permite al usuario dibujar números utilizando el mouse.
Predicción en tiempo real: Utiliza TensorFlow.js para procesar el dibujo y hacer predicciones utilizando un modelo CNN.
## Estructura del Proyecto
1. index.html: Contiene la estructura de la aplicación web.
2. style.css: Contiene estilos personalizados.
3. drawing.js: Contiene la lógica para el manejo del lienzo y la predicción del modelo.
4. redesneuronales/red-convolucional/: Contiene el modelo de TensorFlow.js.
## Instalació
1. Clona este repositorio:
```bash
git clone https://github.com/IgnaccioRG7/Proyecto354.git
```

2. Navega al directorio del proyecto:
```bash
cd Proyecto354
```
3. Abre el archivo index.html en tu navegador preferido.

## Uso
1. Abre la aplicación en tu navegador.
2. Dibuja un número en el lienzo blanco.
3. Haz clic en "Predecir" para que el modelo realice la predicción.
4. El número predicho aparecerá en la tabla debajo del lienzo.
5. Para borrar el lienzo, haz clic en "Limpiar".

## Enlaces Importantes
Repositorio de GitHub: https://github.com/IgnaccioRG7/Proyecto354
Repositorio de Google Colab: https://colab.research.google.com/drive/1bBm92Ot7kGUJGE-jMCx9xiDfcpQiveR-
## Tecnologías Utilizadas
HTML: Estructura de la aplicación.
CSS: Estilos y diseño responsivo.
JavaScript: Lógica de la aplicación y manipulación del DOM.
Bootstrap: Framework de CSS para un diseño responsivo.
TensorFlow.js: Biblioteca para el manejo y predicción de modelos de aprendizaje profundo en el navegador.
## Contribuciones
Las contribuciones son bienvenidas. Si tienes alguna idea o mejora, no dudes en abrir un issue o enviar un pull request.