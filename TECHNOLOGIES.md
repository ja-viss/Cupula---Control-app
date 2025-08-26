# Arquitectura Tecnológica de NegocioControl

Esta aplicación se ha construido utilizando un conjunto de tecnologías modernas y eficientes, seleccionadas para garantizar un alto rendimiento, una excelente experiencia de usuario y una base de código mantenible y escalable.

A continuación se detallan los lenguajes, frameworks y librerías principales que componen el proyecto.

---

### 1. **Framework Principal: Next.js**

- **Descripción:** Next.js es el framework de React que sirve como la columna vertebral de la aplicación. Lo utilizamos para construir el frontend y el backend en un entorno unificado.
- **Ventajas Clave:**
  - **Renderizado del Lado del Servidor (SSR):** Permite que las páginas se carguen más rápido y mejora el SEO.
  - **Enrutamiento Basado en Archivos:** La estructura de carpetas en `src/app` define automáticamente las rutas de la URL, simplificando la navegación.
  - **Rutas de API:** Nos permite crear endpoints de backend (en `src/app/api`) dentro del mismo proyecto, facilitando la comunicación entre el cliente y el servidor.

---

### 2. **Lenguaje de Programación: TypeScript**

- **Descripción:** TypeScript es un superconjunto de JavaScript que añade tipado estático. Todos los archivos de código de la aplicación (`.ts`, `.tsx`) están escritos en TypeScript.
- **Ventajas Clave:**
  - **Seguridad y Robustez:** Ayuda a detectar errores durante el desarrollo en lugar de en producción.
  - **Autocompletado y Mantenibilidad:** Facilita la comprensión y el mantenimiento del código a medida que el proyecto crece.

---

### 3. **Librería de Interfaz de Usuario (UI): React**

- **Descripción:** React es la librería fundamental sobre la que se construye Next.js. La utilizamos para crear los componentes de la interfaz de usuario de forma declarativa y reutilizable.
- **Ventajas Clave:**
  - **Componentes Reutilizables:** Permite construir interfaces complejas a partir de piezas pequeñas y aisladas.
  - **Ecosistema Extenso:** Cuenta con una enorme comunidad y una gran cantidad de librerías y herramientas disponibles.

---

### 4. **Estilos y Componentes Visuales**

- **Tailwind CSS:**
  - **Descripción:** Es un framework de CSS de "utilidad primero" que nos permite diseñar componentes directamente en el marcado HTML (o JSX) sin escribir CSS personalizado.
  - **Ventajas Clave:** Permite un desarrollo rápido y consistente, y facilita la creación de diseños responsivos.

- **ShadCN UI:**
  - **Descripción:** Es una colección de componentes de interfaz de usuario reutilizables, construidos sobre Tailwind CSS y Radix UI. Componentes como `Button`, `Card`, `Dialog`, `Table`, etc., provienen de aquí.
  - **Ventajas Clave:** Ofrece componentes accesibles, personalizables y estéticamente agradables que se pueden adaptar fácilmente al estilo de la aplicación.

- **Lucide React:**
  - **Descripción:** Es la librería que utilizamos para todos los íconos de la aplicación (ej. `PlusCircle`, `Download`, `Wallet`, etc.).
  - **Ventajas Clave:** Proporciona un conjunto de íconos limpio, consistente y fácil de usar.

---

### 5. **Funcionalidad de Inteligencia Artificial (IA)**

- **Genkit (de Google):**
  - **Descripción:** Es el framework de código abierto que utilizamos para integrar la funcionalidad de IA generativa en la aplicación. Orquesta las llamadas a los modelos de IA.
  - **Ventajas Clave:** Simplifica la creación y gestión de flujos de IA, permitiéndonos definir prompts estructurados y manejar las respuestas de los modelos de forma predecible.

- **Google AI (Modelos Gemini):**
  - **Descripción:** Utilizamos los modelos de lenguaje avanzados de la familia Gemini a través de Genkit para potenciar las características de IA, como las recomendaciones de inventario, el análisis de ventas y las sugerencias de ahorro.

---

### 6. **Base de Datos**

- **MongoDB (con MongoDB Atlas):**
  - **Descripción:** Es la base de datos NoSQL que utilizamos para almacenar todos los datos de la aplicación, como usuarios, productos, ventas y gastos. La conexión se realiza a un clúster alojado en MongoDB Atlas (la plataforma en la nube).
  - **Ventajas Clave:** Su modelo de datos flexible basado en documentos (JSON) se integra perfectamente con JavaScript/TypeScript, lo que la hace ideal para este tipo de aplicaciones.

---

### 7. **Generación de PDF**

- **jsPDF y jspdf-autotable:**
  - **Descripción:** Son las librerías que permiten la funcionalidad de "Exportar a PDF" en secciones como Facturación, Inventario y Gastos.
  - **Ventajas Clave:** Permiten generar documentos PDF complejos directamente en el navegador del cliente, incluyendo tablas y estilos personalizados.
