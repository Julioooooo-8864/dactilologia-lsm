# 🖐️ Dactilología LSM - Reconocimiento de Abecedario Manual

Sistema de reconocimiento de dactilología para Lengua de Señas Mexicana utilizando MediaPipe y JavaScript.

## ✨ Características

- 🔍 Detección de mano en tiempo real con MediaPipe
- 🎯 Reconocimiento de letras del abecedario LSM
- 💾 Almacenamiento local de datos de entrenamiento
- 📱 Diseño responsive
- 🚀 Funciona 100% en el navegador

## 🎯 ¿Cómo usar?

1. Permite el acceso a la cámara
2. Muestra una letra con tu mano frente a la cámara
3. Presiona la tecla correspondiente (A-Z) para grabar la letra
4. El sistema aprenderá a reconocer tus señas
5. Una vez grabadas, muestra las letras para formar palabras

## ⌨️ Controles

- **A-Z**: Grabar letra (mantén la mano quieta 2 segundos)
- **ESPACIO**: Agregar espacio
- **BACKSPACE**: Borrar última letra
- **ESC**: Guardar datos

## 🛠️ Tecnologías

- MediaPipe Hands
- Canvas API
- LocalStorage
- HTML5/CSS3/JavaScript

## 📦 Instalación local

```bash
git clone https://github.com/TU_USUARIO/dactilologia-lsm.git
cd dactilologia-lsm
# Abrir index.html con Live Server