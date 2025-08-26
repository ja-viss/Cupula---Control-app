# Descripción de Roles de Usuario en NegocioControl

Este documento detalla las responsabilidades y permisos de cada rol de usuario dentro de la aplicación NegocioControl, asegurando una gestión segura y eficiente de las operaciones del negocio.

---

### 1. **Administrador**

El rol de **Administrador** posee el nivel más alto de autoridad y tiene acceso sin restricciones a todas las funcionalidades del sistema. Es el superusuario de la aplicación.

**Responsabilidades Principales:**
- Configuración general del sistema.
- Creación, edición y eliminación de otros usuarios.
- Asignación y modificación de roles y permisos.
- Supervisión completa de todas las operaciones del negocio.

**Permisos Específicos:**
- **Acceso Total:** Puede ver y gestionar todas las secciones: Dashboard, Ventas, Inventario, Gastos, Cuentas, Facturación, Reportes y AI Insights.
- **Gestión de Usuarios:** Es el único rol que puede acceder a la pestaña de "Usuarios" en la sección de "Configuración" para gestionar las cuentas del personal.
- **Configuración del Sistema:** Puede modificar cualquier ajuste global de la aplicación.

---

### 2. **Gerente de Ventas**

El **Gerente de Ventas** es responsable de supervisar y dirigir las operaciones comerciales y financieras del negocio.

**Responsabilidades Principales:**
- Monitorear el rendimiento de las ventas.
- Gestionar las finanzas, incluyendo gastos y cuentas por cobrar/pagar.
- Analizar reportes para la toma de decisiones comerciales.

**Permisos Específicos:**
- **Dashboard:** Vista general del negocio.
- **Ventas:** Acceso completo al módulo de ventas.
- **Gastos:** Puede registrar y gestionar los gastos del negocio.
- **Cuentas:** Puede gestionar cuentas por cobrar y por pagar.
- **Facturación:** Tiene acceso a la visualización y gestión de todas las facturas.
- **Reportes:** Puede generar y visualizar todos los reportes financieros.
- **No tiene acceso a:** Inventario (solo consulta indirecta), AI Insights y Gestión de Usuarios.

---

### 3. **Gerente de Inventario/Logística**

Este rol se centra en la gestión completa y estratégica del inventario de la empresa.

**Responsabilidades Principales:**
- Supervisar los niveles de stock.
- Gestionar el catálogo de productos (añadir, editar, eliminar).
- Coordinar la logística de entrada y salida de mercancía.
- Analizar reportes de inventario para optimizar el stock.

**Permisos Específicos:**
- **Dashboard:** Vista general del negocio.
- **Inventario:** Control total sobre el módulo de inventario.
- **Reportes:** Acceso a reportes relevantes para la gestión de stock.
- **No tiene acceso a:** Ventas, Gastos, Cuentas, Facturación, AI Insights y Gestión de Usuarios.

---

### 4. **Vendedor/Cajero**

El rol de **Vendedor/Cajero** es un rol operativo con acceso limitado, diseñado para el personal de primera línea que interactúa directamente con los clientes.

**Responsabilidades Principales:**
- Registrar transacciones de venta de manera rápida y eficiente.
- Atender a los clientes en el punto de venta.

**Permisos Específicos:**
- **Dashboard:** Acceso a una vista general y simplificada del estado del negocio.
- **Ventas:** Su función principal. Puede acceder a la página de "Ventas" para crear nuevas transacciones y generar facturas para los clientes.
- **Acceso Restringido:** No puede ver ni gestionar Inventario, Gastos, Cuentas, Facturación, Reportes, AI Insights o Configuración.

---

### 5. **Encargado de Almacén**

El **Encargado de Almacén** es un rol especializado en las operaciones físicas del inventario.

**Responsabilidades Principales:**
- Mantener el control del stock físico.
- Registrar la entrada de nueva mercancía.
- Preparar productos para la venta o envío.

**Permisos Específicos:**
- **Dashboard:** Vista general del negocio.
- **Inventario:** Puede gestionar los productos y sus niveles de stock en el sistema.
- **Acceso Restringido:** No tiene permisos para acceder a las áreas financieras, de ventas o de configuración de la aplicación.
