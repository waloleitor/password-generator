# 🔒 Generador de Contraseñas Aleatorias

Un generador de contraseñas seguras construido con JavaScript puro. Perfecto para ejercicios de programación o para integrar en tus proyectos.

## 🚀 Características
- Genera contraseñas con longitud personalizable (1-15 caracteres)
- Incluye múltiples tipos de caracteres:
  - Números (0-9)
  - Letras minúsculas (a-z)
  - Letras mayúsculas (A-Z)
  - Símbolos especiales (!@#$%&*etc.)
- Validación de entrada para prevenir errores
- Interfaz simple mediante `prompt` (para navegador)

## 🛠️ Cómo Usar
### En navegador:
1. Abre la consola del navegador (F12 > Console)
2. Copia y pega el código de `password-generator.js`
3. Sigue las instrucciones en pantalla

### En Node.js:
Reemplaza el `prompt` por:
```javascript
const readline = require('readline-sync');
let length = readline.question('Introduce longitud de la contraseña: ');
📝 Requisitos
Navegador web moderno o Node.js (para versión terminal)

🌟 Próximas Mejoras
Añadir opción para excluir tipos de caracteres

Implementar versión con interfaz gráfica (HTML/CSS)

Añadir estimador de fortaleza de contraseña

🤝 Contribuir
Las contribuciones son bienvenidas. Por favor abre un Issue o Pull Request.

⌨️ con ❤️ por [Tu Nombre]


### 📌 Tips para personalizar:
1. Cambia `[Tu Nombre]` por tu nombre o usuario
2. Añade capturas de pantalla si creas una interfaz gráfica
3. Agrega una sección de "Ejemplos" si quieres mostrar outputs sample
4. Incluye badges de GitHub si lo deseas (tests, licencia, etc.)

### 📁 Estructura recomendada para el repo:
/password-generator
│
├── password-generator.js # Tu código actual
├── README.md # Este archivo
