# 🏗️ Web CAD Engine: Diseño 3D para Herrería y Estructuras

> **Software de diseño asistido por computadora (CAD) ejecutándose 100% en el navegador. Permite diseñar, cotizar y visualizar estructuras metálicas en tiempo real.**

![Project Status](https://img.shields.io/badge/Status-MVP%20%28Private%29-orange)
![Tech Stack](https://img.shields.io/badge/Stack-React%20%7C%20Three.js%20%7C%20React--Three--Fiber-black)
![Performance](https://img.shields.io/badge/FPS-60%2B-green) 

## 📖 El Problema
Los talleres de herrería y soldadura suelen depender de bocetos en papel o software de ingeniería extremadamente costoso y complejo (AutoCAD/SolidWorks) solo para calcular cortes simples.
Este proyecto busca democratizar el diseño 3D permitiendo crear estructuras, pérgolas y muebles industriales desde cualquier navegador web.

**⚠️ Nota:** *Repositorio de demostración técnica. El motor de renderizado y la lógica de cálculo de materiales son privados.*

## 🛠️ Stack Tecnológico (Graphics & Math)

Este proyecto desafía los límites del navegador utilizando tecnologías de gráficos avanzados.

| Componente | Tecnología | Descripción |
|------------|------------|-------------|
| **Core 3D** | **Three.js / R3F** | Renderizado de gráficos 3D acelerado por hardware (WebGL). |
| **UI/UX** | **React + Leva** | Interfaz de usuario flotante para configurar parámetros (largo, ancho, tipo de perfil). |
| **State** | **Zustand** | Gestión de estado global de alto rendimiento para evitar re-renders innecesarios en el canvas 3D. |
| **Math** | **Linear Algebra** | Cálculos vectoriales para intersecciones, rotaciones y detección de colisiones entre tubos. |

## ✨ Funcionalidades Principales

### 1. 📐 Modelado Paramétrico en Tiempo Real
* **Drag & Drop:** (En desarrollo) Arrastrar perfiles metálicos al escenario.
* **Ajuste Dinámico:** Modificación de dimensiones (largo/ancho/alto) viendo los cambios al instante.
* **Tipos de Material:** Selección de perfiles (Tubo estructural 40x40, Ángulo, Caño redondo).

### 2. 🧮 Cálculo Automático de Materiales (BOM)
El sistema no solo "dibuja", sino que **entiende** lo que dibuja.
* Generación automática de lista de cortes.
* Cálculo de barras necesarias (optimizador de cortes lineal).
* Estimación de peso total de la estructura.

### 3. 🔦 Renderizado PBR (Physically Based Rendering)
* Iluminación realista con sombras dinámicas.
* Materiales metálicos con reflejos y texturas reales.
* Controles de cámara orbital (OrbitControls) y Gizmos de transformación.

## 📸 Demo Visual

> *El sistema permite visualizar la estructura desde cualquier ángulo antes de cortar un solo fierro.*

**Vista General del Editor**
<img width="1915" height="916" alt="1CAD" src="https://github.com/user-attachments/assets/c1007bc4-a052-4fc6-8595-e71267233d19" />
<img width="1917" height="961" alt="2cad" src="https://github.com/user-attachments/assets/fa6a41da-4396-4202-bdf9-f4c2d0380f7a" />
<img width="1919" height="915" alt="3cad" src="https://github.com/user-attachments/assets/10d3aabe-8904-4349-90c4-2c389bc26122" />



---
### 👨‍💻 Santiago Iturralde - High Performance Web Graphics
[Ver Portafolio](https://portafolio-kappa-kohl.vercel.app/)
