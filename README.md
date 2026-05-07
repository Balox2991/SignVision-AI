# SignVision-AI


🤟 SignVision AI

Sistema inteligente de reconocimiento de dibujos basado en Deep Learning y Computer Vision para el aprendizaje del español mediante lenguaje de señas.

El proyecto permite:

Dibujar objetos en un lienzo interactivo.
Clasificar imágenes usando redes neuronales convolucionales.
Mostrar automáticamente un video en lengua de señas relacionado con la predicción realizada.
Promover inclusión educativa mediante inteligencia artificial.
🧠 Tecnologías utilizadas
Python 3.12
TensorFlow / Keras
ResNet50
Streamlit
OpenCV
NumPy
Pillow
Transfer Learning
Computer Vision
🎯 Objetivo del proyecto

El sistema busca facilitar el aprendizaje visual del español para personas sordas mediante:

reconocimiento de dibujos,
clasificación automática,
asociación semántica,
y representación en lengua de señas.

La aplicación integra inteligencia artificial e inclusión educativa en una sola plataforma interactiva.

📂 Estructura del proyecto
signvision-ai/
│
├── app.py
├── modelo_cifar10_resnet.keras
├── requirements.txt
├── README.md
│
├── videos/
│   ├── avion.mp4
│   ├── carro.mp4
│   ├── perro.mp4
│   └── ...
│
├── cuadernoParcial.ipynb
├── cuadernoParcialResnet.ipynb
🖼️ Clases reconocidas
Clase	Español
airplane	avión
automobile	carro
bird	pájaro
cat	gato
deer	ciervo
dog	perro
frog	rana
horse	caballo
ship	barco
truck	camión
🧪 Arquitectura del modelo

El sistema utiliza:

🔹 Transfer Learning con ResNet50

Modelo preentrenado en:

ImageNet

Técnicas utilizadas:

Fine-tuning
Data augmentation
Batch normalization
Dropout
Early stopping
⚙️ Características principales
✏️ Lienzo interactivo

Permite dibujar objetos directamente desde la aplicación.

🤖 Predicción inteligente

Clasificación automática mediante redes neuronales convolucionales.

🤟 Videos en lengua de señas

Después de la predicción, el sistema muestra un video relacionado con la palabra detectada.

🌙 Interfaz moderna

Diseño futurista enfocado en accesibilidad e inclusión.

🧠 Preprocesamiento avanzado

Las imágenes son procesadas usando:

escala de grises,
detección de bordes,
suavizado,
dilatación,
y mejora de contraste.
📊 Dataset utilizado

El proyecto utiliza el dataset:

CIFAR-10

Contiene:

60,000 imágenes
10 categorías
resolución de 32x32 píxeles
🚀 Instalación local
1. Clonar repositorio
git clone [https://github.com/TU_USUARIO/signvision-ai.git](https://github.com/Balox2991/SignVision-AI.git)
2. Entrar al proyecto
cd signvision-ai
3. Instalar dependencias
pip install -r requirements.txt
4. Ejecutar aplicación
streamlit run app.py
☁️ Deploy en Streamlit Cloud

La aplicación puede desplegarse fácilmente usando:

Streamlit Community Cloud

📈 Resultados
Modelo	Accuracy
CNN desde cero	77%
ResNet50 + Fine-tuning	93%
⚠️ Limitaciones

El modelo fue entrenado originalmente con imágenes reales del dataset CIFAR-10.

Debido a esto, pueden existir errores al clasificar dibujos hechos a mano, ya que el dominio visual difiere considerablemente de fotografías reales.

Como mejora futura se propone:

integrar datasets de sketches,
utilizar QuickDraw,
reentrenar el modelo específicamente para dibujos.
🔮 Trabajo futuro
Integración de QuickDraw Dataset.
Reconocimiento de señas en tiempo real.
Traducción automática español ↔ lengua de señas.
Generación de voz.
Soporte multilenguaje.
Más categorías y vocabulario.
👨‍💻 Autor

Juan David Amaya Quintero
Efrain Alvarez Lobo
Andres Felipe Ardila Quiñones

Ingeniería de Sistemas

📚 Proyecto académico

Proyecto desarrollado con fines educativos y de investigación en:

Inteligencia Artificial
Deep Learning
Inclusión tecnológica
Visión por computador
Accesibilidad educativa
