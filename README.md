# 🎮 Triqui (Tic-Tac-Toe) - React Game

[![React](https://img.shields.io/badge/React-18.x-blue.svg)](https://reactjs.org/)
[![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-yellow.svg)](https://developer.mozilla.org/docs/Web/JavaScript)
[![CSS3](https://img.shields.io/badge/CSS3-Styling-blue.svg)](https://developer.mozilla.org/docs/Web/CSS)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

Un juego interactivo de Triqui (Tic-Tac-Toe) desarrollado en React que implementa las mejores prácticas de desarrollo frontend y una experiencia de usuario moderna.

## 📖 Descripción

Este proyecto es una implementación completa del clásico juego de Triqui (conocido también como Tres en Raya o Tic-Tac-Toe) construido con React. El juego incluye características avanzadas como historial de movimientos, detección de ganador, y una interfaz de usuario intuitiva y responsive.

## 🎯 Características

- ✅ **Jugabilidad completa**: Dos jugadores pueden alternar turnos
- ✅ **Detección de ganador**: Algoritmo que detecta automáticamente victorias y empates
- ✅ **Historial de movimientos**: Navegación completa por todos los movimientos del juego
- ✅ **Interfaz responsive**: Diseño adaptable a diferentes tamaños de pantalla
- ✅ **Estado inmutable**: Implementación siguiendo principios de programación funcional
- ✅ **Componentes reutilizables**: Arquitectura modular con componentes independientes

## 🚀 Demo en Vivo

[Ver Demo](https://tu-username.github.io/triqui) *(Actualizar con tu URL de GitHub Pages)*

## 🛠️ Tecnologías Utilizadas

| Tecnología | Versión | Propósito |
|------------|---------|-----------|
| **React** | 18.x | Framework principal para la UI |
| **JavaScript ES6+** | Latest | Lógica de programación |
| **CSS3** | Latest | Estilos y diseño responsive |
| **Create React App** | Latest | Configuración y build tools |

## 📚 Fundamentación Técnica

Este proyecto está basado en el **Tutorial Oficial de React** para Tic-Tac-Toe, que se puede encontrar en:

🔗 **[Tutorial Oficial de React - Tic-Tac-Toe](https://react.dev/learn/tutorial-tic-tac-toe)**

### ¿Por qué este tutorial?

1. **Fuente oficial**: Desarrollado por el equipo de React de Meta
2. **Mejores prácticas**: Implementa patrones recomendados de React
3. **Conceptos fundamentales**: Cubre hooks, estado, props y manejo de eventos
4. **Arquitectura escalable**: Estructura de componentes reutilizable
5. **Programación funcional**: Uso de estado inmutable y funciones puras

### Conceptos de React Implementados

- **Componentes funcionales** con hooks
- **useState** para manejo de estado local
- **Props** para comunicación entre componentes
- **Event handling** para interacciones del usuario
- **Conditional rendering** para mostrar elementos dinámicamente
- **Lista renderizada** para el historial de movimientos
- **Lifting state up** para compartir estado entre componentes

## 🏗️ Arquitectura del Proyecto

```
src/
├── App.js          # Componente principal del juego
├── App.css         # Estilos principales
├── index.js        # Punto de entrada de la aplicación
└── index.css       # Estilos globales
```

### Componentes Principales

1. **Game**: Componente raíz que maneja el estado global del juego
2. **Board**: Representa el tablero de 3x3
3. **Square**: Componente individual para cada casilla del tablero

## 🚀 Instalación y Configuración

### Prerrequisitos

- Node.js (versión 14 o superior)
- npm o yarn
- Git

### Pasos de Instalación

1. **Clonar el repositorio**
   ```bash
   git clone https://github.com/tu-username/triqui.git
   cd triqui
   ```

2. **Instalar dependencias**
   ```bash
   npm install
   ```

3. **Ejecutar en modo desarrollo**
   ```bash
   npm start
   ```

4. **Abrir en el navegador**
   ```
   http://localhost:3000
   ```

## 📋 Scripts Disponibles

| Comando | Descripción |
|---------|-------------|
| `npm start` | Ejecuta la app en modo desarrollo |
| `npm test` | Lanza el runner de pruebas |
| `npm run build` | Construye la app para producción |
| `npm run eject` | Expone configuraciones de build |

## 🎮 Cómo Jugar

1. **Inicio**: El jugador X siempre comienza
2. **Turnos**: Los jugadores alternan haciendo clic en las casillas vacías
3. **Victoria**: El primer jugador en conseguir tres símbolos en línea (horizontal, vertical o diagonal) gana
4. **Empate**: Si se llenan todas las casillas sin un ganador, el juego termina en empate
5. **Historial**: Usa los botones del historial para revisar movimientos anteriores

## 🔧 Configuración del Desarrollo

### Estructura de Archivos Recomendada

```
triqui/
├── public/
│   ├── index.html
│   └── favicon.ico
├── src/
│   ├── App.js
│   ├── App.css
│   ├── index.js
│   └── index.css
├── package.json
└── README.md
```

### Variables de Entorno

Crear un archivo `.env` en la raíz del proyecto para configuraciones personalizadas:

```bash
REACT_APP_TITLE=Triqui Game
REACT_APP_VERSION=1.0.0
```

## 🧪 Testing

```bash
# Ejecutar todas las pruebas
npm test

# Ejecutar pruebas con coverage
npm test -- --coverage
```

## 📦 Build y Deployment

### Build para Producción

```bash
npm run build
```

### Deploy en GitHub Pages

```bash
npm install --save-dev gh-pages

# Agregar al package.json:
"homepage": "https://tu-username.github.io/triqui",
"scripts": {
  "predeploy": "npm run build",
  "deploy": "gh-pages -d build"
}

# Ejecutar deploy
npm run deploy
```

## 🤝 Contribución

Las contribuciones son bienvenidas. Para cambios importantes:

1. Fork el proyecto
2. Crea una rama para tu feature (`git checkout -b feature/AmazingFeature`)
3. Commit tus cambios (`git commit -m 'Add some AmazingFeature'`)
4. Push a la rama (`git push origin feature/AmazingFeature`)
5. Abre un Pull Request

## 📝 Licencia

Este proyecto está bajo la Licencia MIT - ver el archivo [LICENSE](LICENSE) para más detalles.

## 👨‍💻 Autor

**Tu Nombre**
- GitHub: [@tu-username](https://github.com/tu-username)
- LinkedIn: [Tu Perfil](https://linkedin.com/in/tu-perfil)

## 🙏 Agradecimientos

- **Equipo de React** por el excelente tutorial oficial
- **Create React App** por la configuración inicial
- **Comunidad de React** por la documentación y recursos

## 📚 Recursos Adicionales

- [Documentación oficial de React](https://reactjs.org/docs/)
- [Tutorial completo de Tic-Tac-Toe](https://react.dev/learn/tutorial-tic-tac-toe)
- [Hooks de React](https://reactjs.org/docs/hooks-intro.html)
- [Create React App](https://create-react-app.dev/)

---

⭐ **¡Si te gusta este proyecto, dale una estrella en GitHub!** ⭐
