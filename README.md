

# Juego Unificado PyGame - Tres Juegos en Uno

Un juego que combina tres modos de juego diferentes con selección de skins personalizadas y sistema de música.

## Características

- **Tres juegos en uno**: Disfruta de diferentes experiencias de juego
- **Sistema de skins**: Elige entre 3 skins personalizadas para tu personaje
- **Selección de música**: 3 canciones diferentes para ambientar tu juego
- **Múltiples dificultades**: 3 niveles de dificultad para cada juego
- **Sistema de puntuación**: Registra tus mejores puntuaciones e intentos

## Modos de Juego

### 1. Juego de Evasión
- **Objetivo**: esquiva los enemigos que caen desde arriba
- **Controles**: flechas izquierda/derecha para moverte
- **Puntuación**: sobrevive el mayor tiempo posible

### 2. Juego de Recolección
- **Objetivo**: recolecta la mayor cantidad de objetos posibles
- **Controles**: flechas para moverte en las 4 direcciones
- **Puntuación**: cada objeto recolectado suma puntos

### 3. Juego de Disparos
- **Objetivo**: destruye los enemigos antes de que lleguen al fondo
- **Controles**: flechas para moverte, espacio para disparar
- **Puntuación**: cada enemigo destruido suma puntos

## Instalación

### Requisitos previos
- Python 3.8 o superior
- Pip (gestor de paquetes de Python)

### Pasos para instalar

1. **Descarga los archivos**:
   - Clona este repositorio o descarga el ZIP y extráelo en una carpeta

2. **Configura un entorno virtual (recomendado)**:
   ```bash
   # Crear entorno virtual
   python -m venv venv
   
   # Activar entorno virtual (Windows)
   venv\Scripts\activate
   
   # Activar entorno virtual (macOS/Linux)
   source venv/bin/activate
   ```

3. **Instala las dependencias**:
   ```bash
   pip install pygame
   ```

4. **Descarga las canciones**:
   - Debido a limitaciones de GitHub con archivos grandes, las canciones deben descargarse por separado
   - Descarga las 3 canciones y colócalas en la carpeta del juego con estos nombres exactos:
     - `cancion1.mp3`
     - `cancion2.mp3` 
     - `cancion3.mp3`


5. **Ejecuta el juego**:
   ```bash
   python juego_unificado.py
   ```

## Controles

- **Menús**: Ratón para navegar
- **Juego de Evasión**: Flechas izquierda/derecha
- **Juego de Recolección**: Flechas en las 4 direcciones
- **Juego de Disparos**: Flechas para mover, Espacio para disparar
- **Durante el juego**: ESC para volver al menú principal

## Niveles de Dificultad

- **Fácil**: Velocidad reducida, más tiempo, mayor tasa de aparición
- **Medio**: Velocidad moderada, tiempo equilibrado
- **Difícil**: Alta velocidad, tiempo limitado, menor tasa de aparición

## Sistema de Puntuación

Cada juego tiene su propio sistema de puntuación:
- **Evasión**: +10 puntos por segundo sobrevivido
- **Recolección**: +10 puntos por objeto recolectado (multiplicado por dificultad)
- **Disparos**: +20 puntos por enemigo destruido (multiplicado por dificultad)

## Notas Importantes

- El juego creará imágenes por defecto si no encuentra los archivos de skin o fondo
- Para personalizar, añade tus propias imágenes con los nombres correctos
- Las canciones son opcionales pero mejoran la experiencia de juego
