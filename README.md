# 🎮 Near08x Blockgame

Un juego de Tetris interactivo y completamente funcional desarrollado en HTML5, CSS3 y JavaScript vanilla.

## 📋 Características

- ✨ **7 tipos de piezas** (I, O, T, S, Z, J, L) con colores diferentes
- 🎯 **Sistema de puntuación** con múltiples niveles de dificultad
- 📊 **Estadísticas en tiempo real** (puntos, líneas, nivel)
- 👀 **Vista previa** de la siguiente pieza
- ⏸️ **Pausar/Reanudar** juego en cualquier momento
- 🔄 **Reiniciar** el juego sin recargar la página
- 💪 **Velocidad progresiva** que aumenta con cada nivel

## 🎮 Cómo Jugar

### Controles

| Tecla | Acción |
|-------|--------|
| ⬅️ Flecha Izquierda | Mover pieza a la izquierda |
| ➡️ Flecha Derecha | Mover pieza a la derecha |
| ⬆️ Flecha Arriba | Rotar pieza |
| ⬇️ Flecha Abajo | Bajar pieza más rápido |
| ESPACIO | Pausar/Reanudar juego |

### Botones

- **Iniciar**: Comienza un nuevo juego
- **Pausar**: Pausa el juego en progreso
- **Reiniciar**: Reinicia el juego desde cero

## 📁 Instalación

### Opción 1: Abrir directamente
```bash
# Simplemente abre el archivo en tu navegador
start tetris.html
```

### Opción 2: Usar un servidor web
```bash
# Con Python 3
python -m http.server 8000

# Con PHP
php -S localhost:8000
```

Luego abre tu navegador en `http://localhost:8000/tetris.html`

## 🎯 Sistema de Puntuación

- **Por línea completada**: 100 puntos × nivel actual
- **Líneas completadas**: Se cuenta cada línea eliminada
- **Nivel**: Aumenta cada 10 líneas completadas
- **Dificultad**: La velocidad aumenta con cada nivel

## 🛠️ Tecnologías Utilizadas

- **HTML5**: Estructura y layout
- **CSS3**: Diseño y animaciones
- **JavaScript (Vanilla)**: Lógica del juego

## 📦 Archivos

- `tetris.html` - Juego completo en un único archivo
- `tetris.php` - Versión PHP (compatible)
- `README.md` - Esta documentación

## 🎨 Colores de Piezas

| Pieza | Color | Forma |
|-------|-------|-------|
| I | Cyan | ⬛⬛⬛⬛ |
| O | Amarillo | ⬛⬛ |
| T | Púrpura | ⬛⬛⬛ |
| S | Verde | ⬛⬛ |
| Z | Rojo | ⬛⬛ |
| J | Azul | ⬛⬛⬛ |
| L | Naranja | ⬛⬛⬛ |

## 🚀 Cómo Usar

1. Abre `tetris.html` en tu navegador
2. Haz clic en **"Iniciar"** para comenzar
3. Usa las flechas del teclado para controlar la pieza
4. Completa líneas horizontales para obtener puntos
5. ¡Intenta alcanzar la puntuación más alta!

## 📝 Notas

- El juego termina cuando una pieza llega al tope del tablero
- No hay límite de tiempo, juega a tu ritmo
- La dificultad aumenta automáticamente con cada nivel
- Puedes pausar el juego en cualquier momento

## 👨‍💻 Autor

**Near08x**

## 📄 Licencia

Libre para usar y modificar.

---

¡Que disfrutes jugando! 🎮✨
