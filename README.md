# Unidad-4-sistemas-computacionales (Bitacora)
# Actividad 1

## Orientación y primer vistazo al entorno gráfico



### 1. Compila y ejecuta el ejemplo

📤

### 🧐🧪✍️ Reporta en tu bitácora

#### 1. Incluye una captura de pantalla del ejemplo funcionando en tu máquina.
![alt text](image.png)
#### 2. Observa el proyecto, trata de entenderlo, pero ten presente que lo analizaremos más adelante.
#### 3. ¿Qué preguntas te surgen al ver el código? Anota al menos tres preguntas que te gustaría investigar más adelante (no te preocupes que la idea de esta unidad es que las resuelvas).

- Cómo se dibuja esto dentro de la GPU?
- Cómo se redirecciona de la CPU a la GPU?
- Cómo es que se calculan los pixeles y posiciones?

# Actividad 02

## ¿Cómo se crea un proyecto OpenGL en Windows?
### Resumen
```GLFW``` crea la ventana, ```opengl32.lib``` enciende ```OpenGL```,```GLAD``` trae las funciones modernas desde los drivers de la GPU y ```GLM``` ayuda con las matematicas.
### ¿Como se relacionan?
```GLFW``` prepara el lienzo, ```GLAD``` consigue las herramientas modernas desde los drivers, ```opengl32.lib``` se conecta con Windows y ```GLM```aporta en las matematicas.

# Actividad 3


# Actividad 4
## Parte 1:
### Diferencia entre GPU y CPU
- La ```CPU``` tiene poco nucleos, bastante potentes y flexibles, realiza tareas complejas una tras otra (o pocas a la vez), como la logica del programa, el sistema operativo o la IA de algun juego.
- La ```GPU``` tiene miles de nucleos pequeños y simples. Hace la misma operacion sobre muchisimos datos al mismo tiempo.
- #### ¿Porque sirve para graficos?
sirve para pintar una imagen, calcular el color de millones de pixeles, y cada uno se calcula de forma independiente con la misma formula.

- #### Analisis del video 
la CPU es un cañon de paintball que dispara un tiro preciso a la vez. La GPU es un cañon gigante que dispara miles de bolas de pintura al mismo tiempo y pinta la imagen completa de golpe.

## Parte 2:
#### 1. ¿Cuáles son los tres pasos claves del pipeline de OpenGL? Explica en tus propias palabras cuál es el objetivo de cada paso.


#### 2. La gran novedad que introduce OpenGL moderno es el pipeline programable. ¿Qué significa esto? ¿Qué diferencia hay entre el pipeline fijo y el programable? ¿Qué ventajas le ves a esto? y si el pipeline es programable, ¿Qué tengo que programar?


#### 3. Si fueras a describir el proceso de **rasterización** ¿Qué dirías?


#### 4. ¿Qué son los fragmentos? ¿Es lo mismo un fragmento que un pixel? ¿Por qué?


#### 5. Explica qué problema resuelve el **Z-buffer** y ¿Qué es el depth test?


#### 6. ¿Por qué se presenta el problema de la **aliasing**? ¿Qué es el anti-aliasing?


#### 7. ¿Qué relación hay entre la iluminación y el fragment shader? Siempre es necesario tener en cuenta la iluminación en un fragment shader? o puedo hacer un fragment shader sin iluminación? Explica que implicaciones tiene esto.


#### 8. ¿Qué implica para la GPU que una aplicación tenga múltiples fuentes de iluminación?