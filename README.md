# Talleres-Liliana
Aquí se subirá los talleres de la instructora del Sena Liliana 

# 🚀 Panel de Simulaciones JavaScript

Un panel interactivo para ejecutar y visualizar diferentes simulaciones relacionadas con promesas y programación asíncrona en JavaScript.

## 📋 Características

- **Panel lateral**: Lista de simulaciones disponibles con botones interactivos
- **Panel principal**: Controles dinámicos y área de ejecución
- **Salida en tiempo real**: Visualización de logs, errores y resultados
- **Diseño responsivo**: Adaptable a cualquier dispositivo
- **Interfaz moderna**: Diseño elegante con Tailwind CSS

## 🛠️ Tecnologías utilizadas

- **HTML5** - Estructura de la aplicación
- **JavaScript** - Lógica de simulaciones e interactividad
- **Tailwind CSS** - Diseño y estilos responsivos
- **CSS personalizado** - Detalles visuales adicionales

## 🎯 Simulaciones disponibles

- 🛡️ **Control de Errores** - Manejo de errores con .catch()
- 🌡️ **Sensores** - Lectura de sensores con promesas
- ▶️ **Inicia Promesa** - Cadenas de promesas
- ❌ **Rechaza** - Promesas con flujos condicionales
- 📝 **Formulario** - Validación asíncrona de formularios
- 🔄 **Secuencias** - Ejecución secuencial de operaciones
- ⏱️ **Tiempo Diferentes** - Operaciones con diferentes duraciones
- 📄 **JSON** - Procesamiento de datos JSON
- 🗄️ **Simulación Database** - Operaciones de base de datos
- ⏳ **Espera** - Operaciones con tiempo de espera
- 🔁 **Reintentar** - Reintentos de operaciones fallidas
- 🚫 **Cancelación** - Cancelación de operaciones
- 🖼️ **Imágenes Múltiples** - Carga de múltiples imágenes
- ✅ **Verificación** - Procesos de verificación
- 🛒 **Simulación Compras** - Proceso de compra completo
- 🔢 **Operaciones** - Operaciones matemáticas asíncronas
- 📖 **Leer Archivo** - Lectura de archivos
- 👤 **Obtener Perfil** - Obtención de perfiles de usuario
- 📍 **Localización Usuario** - Geolocalización
- 📤 **Enviar Formulario** - Envío de formularios
- 🖼️ **Cargar Imágenes** - Carga de imágenes
- 🔐 **Validación Login** - Autenticación
- 🌐 **API** - Llamadas a APIs
- ⏰ **SetTimeout** - Operaciones con temporizadores
- 🧠 **Macro Algoritmo** - Algoritmos complejos

## 🚀 Cómo funciona

Este proyecto es un **panel interactivo** que permite ejecutar y visualizar diferentes simulaciones relacionadas con promesas y programación asíncrona en JavaScript.

### Características principales

- **Panel lateral**: Muestra una lista de simulaciones disponibles. Cada botón representa una simulación diferente (por ejemplo, control de errores, validación de formularios, operaciones matemáticas, etc.).
- **Panel principal**: Al seleccionar una simulación, se muestra su descripción y los controles necesarios para ejecutarla (inputs dinámicos según la simulación).
- **Ejecución y salida**: Al pulsar "Ejecutar Simulación", se corre el código correspondiente y los resultados (logs, errores, mensajes) aparecen en tiempo real en el área de salida.
- **Limpieza rápida**: Puedes limpiar la salida con el botón "Limpiar".
- **Diseño moderno y responsivo**: Gracias a Tailwind CSS, el panel se adapta a cualquier dispositivo y tiene un aspecto profesional.

### ¿Cómo usarlo?

1. **Abre el archivo `index1.html` en tu navegador.**
2. En el menú lateral, selecciona la simulación que deseas probar.
3. Si la simulación requiere parámetros, ingrésalos en los campos que aparecen.
4. Haz clic en **"Ejecutar Simulación"** para ver el resultado en el área de salida.
5. Usa el botón **"Limpiar"** para borrar la salida y probar otra simulación.

## 📁 Estructura del proyecto

```
Promesas/
├── index1.html              # Panel principal de simulaciones
├── style/
│   └── style.css           # Estilos personalizados
├── api.js                  # Simulación de APIs
├── cancelacion.js          # Simulación de cancelación
├── cargas_img.js           # Simulación de carga de imágenes
├── control-errores.js      # Simulación de control de errores
├── envia_form.js           # Simulación de envío de formularios
├── espera.js               # Simulación de espera
├── formulario.js           # Simulación de formularios
├── img_multipl.js          # Simulación de imágenes múltiples
├── inicia-promesa.js       # Simulación de inicio de promesas
├── json.js                 # Simulación de procesamiento JSON
├── leer_archv.js           # Simulación de lectura de archivos
├── localizacion_usuario.js # Simulación de geolocalización
├── Macroalgoritmo.js       # Simulación de macro algoritmos
├── obtener_prefil.js       # Simulación de obtención de perfiles
├── operacions.js           # Simulación de operaciones
├── rechaza.js              # Simulación de rechazo de promesas
├── reintetar.js            # Simulación de reintentos
├── secuecias.js            # Simulación de secuencias
├── sensores.js             # Simulación de sensores
├── setTimeout.js           # Simulación de setTimeout
├── simuacion_database.js   # Simulación de base de datos
├── simulacion_compras.js   # Simulación de compras
├── tiempodiferentes.js     # Simulación de tiempos diferentes
├── validacion_Login.js     # Simulación de validación de login
└── verificacionseec.js     # Simulación de verificación
```

## 🎨 Personalización

Puedes personalizar el panel modificando:

- **Colores y estilos**: Edita las clases de Tailwind en `index1.html`
- **Nuevas simulaciones**: Agrega nuevas simulaciones en el objeto `simulations` del JavaScript
- **Estilos CSS**: Modifica `style/style.css` para detalles visuales específicos

## 📝 Licencia

Este proyecto es de código abierto y está disponible bajo la licencia MIT.

## 🤝 Contribuciones

Las contribuciones son bienvenidas. Por favor, abre un issue o un pull request para sugerir mejoras o reportar bugs.

---

**¡Disfruta explorando las simulaciones de promesas y programación asíncrona! 🚀** 
