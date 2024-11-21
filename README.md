# Autor

Nombre del autor: Daniel Horna

Nombre del curso: CODE 201

Email: danielhornaz@gmail.com

Fecha de creacion:20-11-2024

#  Sobre el Proyecto

La web moderna se caracteriza por ser interactiva, dinámica y centrada en el usuario, utilizando tecnologías avanzadas como JavaScript, React y Vue para crear experiencias fluidas y responsivas que se adaptan a diferentes dispositivos gracias al diseño responsive. Además, incorpora aplicaciones web progresivas (PWA) que combinan características de apps nativas con las ventajas de la web, como funcionalidad sin conexión y notificaciones. También prioriza la seguridad mediante HTTPS y autenticaciones robustas, mientras optimiza el rendimiento con CDNs y técnicas de compresión. La accesibilidad y el diseño inclusivo son fundamentales, junto con la integración de datos a través de APIs como REST y GraphQL, haciendo de la web moderna una plataforma rápida, segura y accesible para todos los usuarios.

# eslintrc

### Propiedad env

Define el entorno en el que se ejecutará el código, lo que ayuda a ESLint a entender qué variables globales están disponibles.

- browser: true: Indica que el código se ejecutará en un entorno de navegador, por lo que ESLint reconoce variables globales como window o document.

- es2021: true: Permite las características de ECMAScript 2021 (ES12), como operadores lógicos de asignación (&&=, ||=) y promesas any().

### Propiedad extends

Especifica configuraciones base que se heredan para evitar configuraciones redundantes.

- eslint:recommended: Activa un conjunto de reglas básicas recomendadas por ESLint para detectar errores comunes y malas prácticas.

### Propiedad parserOptions

Define la versión de JavaScript y el tipo de código que se analizará.

- ecmaVersion: "latest": Indica que se usará la versión más reciente del estándar ECMAScript compatible con ESLint.
- sourceType: "module": Especifica que el código utiliza módulos de ES6 (import/export).

### Propiedad rules

- "indent": ["error", 2]

- - Enforce indentación de 2 espacios.
- - "error": Si no se respeta esta regla, se generará un error.

- "linebreak-style": ["error", "unix"]

- - Exige que las líneas terminan con el estilo de salto de línea Unix (\n), en lugar del estilo Windows (\r\n).

- "quotes": ["error", "single"]

- - Obliga a usar comillas simples (') en lugar de dobles (").

- "semi": ["error", "always"]

- - Exige que todas las líneas terminen con punto y coma (;).

- "no-unused-vars": "warn"

- - Genera una advertencia si hay variables declaradas pero no utilizadas en el código.

- "no-console": "warn"

- - Genera una advertencia si se encuentran llamadas a console como console.log, lo cual puede ser considerado mala práctica en código de producción.