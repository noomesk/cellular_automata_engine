# GEN_ENGINE_V1 | Audio Reactive Cellular Automata

Un motor de arte generativo que combina autómatas celulares con música techno sintetizada en tiempo real, creando una experiencia audiovisual inmersiva donde las células responden directamente al beat y espectro del audio.

## 🎵 ¿Qué hace?

GEN_ENGINE_V1 es una aplicación web interactiva que:

- **Simula autómatas celulares** usando reglas personalizables (Conway, HighLife, Seeds, Maze, Day/Night, Morley)
- **Genera 5 pistas de techno** sintetizadas en tiempo real usando Web Audio API
- **Reacciona al audio en vivo**: las células responden al bass, mid y treble
- **Detecta beats automáticamente** para sincronizar efectos visuales
- **Permite interacción manual**: dibuja células, haz zoom y pan
- **Muestra visualizaciones en tiempo real**: espectro de audio, VU meters, estadísticas

## 🎮 Cómo se usa

### Inicio Rápido
1. Abre `index.html` en tu navegador web moderno
2. Haz clic en "▶ INICIAR ENGINE" para desbloquear el audio
3. Disfruta de la experiencia audiovisual interactiva

### Controles Principales
- **▶/⏸**: Play/Pausar simulación
- **⟳**: Resetear con nueva semilla aleatoria
- **⬛**: Limpiar grid completamente
- **🎲**: Generar nueva semilla aleatoria
- **🎵**: Toggle audio (play/pausar música)

### Interacción con el Grid
- **Click y arrastrar**: Dibujar células vivas
- **Scroll**: Zoom in/out
- **Shift + arrastrar**: Panear la vista
- **Touch**: Soporte completo para dispositivos móviles

### Panel de Control Lateral
- **TRACK_BANK**: Selecciona entre 5 pistas techno diferentes
- **AUDIO_REACTIVITY**: Ajusta cómo responde el visual al audio
  - Bass Impact: Intensidad de respuesta a bajos
  - Mid Reactivity: Reactividad a medios
  - Cell Spawn Rate: Tasa de generación de células por beat
  - Glow Intensity: Intensidad del brillo reactivo
- **RULE_PRESETS**: Cambia reglas del autómata celular
- **SIM_PARAMS**: Densidad inicial y velocidad de simulación
- **COLOR_MODE**: 6 esquemas de color predefinidos

## 🛠 Tecnologías Utilizadas

### Frontend Core
- **HTML5 Canvas**: Renderizado principal del autómata celular
- **WebGL2**: Shaders para computación paralela de autómatas
- **Web Audio API**: Síntesis y análisis de audio en tiempo real
- **CSS3**: UI moderna con efectos de glassmorphism y animaciones

### Audio Engine
- **Síntesis FM y sustractiva**: Generación de sonidos techno
- **Procesamiento en tiempo real**: 5 pistas independientes
- **Análisis FFT**: Detección de espectro y beats
- **Programación temporal**: Scheduling preciso de eventos musicales

### Visual Engine
- **Fragment Shaders**: Computación paralela de autómatas celulares
- **Framebuffers**: Ping-pong buffering para simulación eficiente
- **Uniforms audio-reactivos**: Parámetros dinámicos basados en audio
- **Renderizado GPU**: Alta performance con miles de células

## ✨ ¿Por qué es Novedoso?

### 1. **Síntesis Audiovisual Unificada**
A diferencia de los visualizadores tradicionales que solo reaccionan al audio, GEN_ENGINE_V1 crea una **simbiosis real** donde el audio y los autómatas celulares se influencian mutuamente. Los beats generan nuevas células y el estado del autómata podría influenciar parámetros audiofuturos.

### 2. **Síntesis de Audio en Tiempo Real**
Las 5 pistas techno no son samples pregrabados, sino **síntesis matemática en vivo**:
- **ACID MATRIX**: Bajos tipo TB-303 con slides y resonancia
- **BERLIN GRID**: Minimal techno con pads atmosféricos
- **NEURAL PULSE**: Arpegios hipnóticos y sub-bajos pulsantes
- **DARK MATTER**: Techno industrial con ruido controlado
- **FRACTAL RAVE**: Hard techno con breaks rápidos

### 3. **Computación Paralela en GPU**
Los autómatas celulares se computan completamente en el **fragment shader**, permitiendo:
- Millones de células simultáneas
- Reglas personalizables sin recompilación
- Parámetros audio-reactivos en tiempo real
- Performance de 60 FPS constante

### 4. **Detección de Beat Inteligente**
Algoritmo de detección que:
- Analiza espectro en tiempo real
- Detecta transientes de batería
- Sincroniza efectos visuales
- Adapta la velocidad de simulación al tempo

### 5. **Estética Ciberpunk Retrofuturista**
Diseño inspirado en:
- Interfaces de synthwave y outrun
- Terminales de hacker clásicas
- Efectos CRT y scanlines
- Paletas de colores neon vibrantes

## 🎨 Arte Generativo

### Algoritmos Implementados
- **Conway's Game of Life (B3/S23)**: El clásico autómata celular
- **HighLife (B36/S23)**: Variación con patrones replicadores
- **Seeds (B2/S)**: Crecimiento explosivo y orgánico
- **Maze (B3/S12345)**: Generación de laberintos naturales
- **Day/Night (B3678/S34678)**: Patrones simétricos complejos
- **Morley (B368/S245)**: Estructuras cristalinas emergentes

### Comportamiento Audio-Reactivo
- **Bass Impact**: Los bajos hacen que las células sobrevivan más tiempo
- **Beat Detection**: Cada beat genera explosiones de nuevas células
- **Spectrum Response**: Diferentes frecuencias afectan colores y brillo
- **Tempo Sync**: La velocidad de simulación se adapta al BPM

### Emergencia y Complejidad
El sistema exhibe **comportamiento emergente** donde:
- Patrones simples crean estructuras complejas
- El audio introduce entropía controlada
- Surgen gliders, osciladores y still lifes
- La interacción humano-máquina crea resultados únicos

## 🚀 Performance y Optimización

- **60 FPS constante** con miles de células
- **Audio de baja latencia** (<10ms)
- **Responsive design** para desktop y móvil
- **Memory efficient**: Ping-pong buffers en GPU
- **Touch optimizado**: Gestos intuitivos

## 🔧 Desarrollo Futuro

- [ ] Más reglas de autómatas celulares
- [ ] Editor de patrones personalizado
- [ ] Export de video/audio
- [ ] Modo VR/AR
- [ ] Machine learning para generación adaptativa
- [ ] Colaboración multiusuario en tiempo real

## 📄 Licencia

MIT License - Siéntete libre de usar, modificar y distribuir este proyecto.

## 🙏 Agradecimientos

- John Conway por el Game of Life
- La comunidad demoscene por la inspiración visual
- Los pioneros del techno por la base musical
- WebGL y Web Audio API communities

---

**GEN_ENGINE_V1** - Donde la matemática se encuentra con el ritmo, y las células bailan al sonido del techno.
