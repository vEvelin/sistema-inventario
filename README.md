# Sistema Web Full-Stack para la Gestión de Inventarios, Ventas Mayoristas y Finanzas 📊🧶

¡Bienvenido! Este es un sistema web **Full-Stack** desarrollado a medida para optimizar los procesos comerciales, el control estricto de stock por mayor/menor y los flujos financieros de empresas comerciales y distribuidoras mayoristas.

Este repositorio funciona exclusivamente como **portafolio y demostración visual** del diseño de interfaz, arquitectura de software y lógica de negocio. El código fuente y las bases de datos se mantienen privados por razones de confidencialidad comercial.

---

## 📸 Demostración Visual (Capturas del Sistema)

> 💡 *Nota para reclutadores: Puedes hacer clic en las imágenes para ampliarlas.*

### 1. Pantalla de Acceso Seguro (Login) y Dashboard
Aquí se valida el rol del usuario (Administrador o Vendedor) y se redirige dinámicamente al panel correspondiente.

### 2. Módulo de Inventario Inteligente (Paquetes y Subpaquetes)
Control detallado de stock con conversión automática de unidades y alertas de inventario bajo.

### 3. Punto de Venta (POS) y Flujo de Ventas Mayoristas
Interfaz responsiva e interactiva (JavaScript) que calcula automáticamente tarifas dinámicas por mayor/menor y registra extracciones de mercadería en tiempo real.

### 4. Gestión de Cuentas por Cobrar, Abonos y Reportes
Control automatizado de saldos de clientes, emisión de comprobantes de pago y balances de caja diaria.

---

## 🛠️ Tecnologías y Entorno Utilizados

La plataforma fue diseñada e implementada utilizando herramientas estándar de la industria tecnológica:

*   **Frontend:** HTML5, CSS3, **Bootstrap** (Diseño responsivo y adaptativo) y **JavaScript Nativo** (Manejo dinámico del carrito de compras, peticiones asíncronas en el navegador y navegación fluida sin recargas de página).
*   **Backend:** **PHP** (Lógica de negocio orientada a objetos, control seguro de sesiones y renderizado dinámico).
*   **Base de Datos:** **MySQL / MariaDB** (Diseño relacional estructurado para alta consistencia de datos).
*   **Herramientas de Servidor:** **XAMPP** (Apache/MySQL), **phpMyAdmin** (Gestión de datos) y **Composer** (Gestión de dependencias).

---

## 🚀 Arquitectura y Lógica de Negocio Implementada

El software resuelve desafíos reales del comercio a través de los siguientes módulos:

*   **Lógica de Precios Dinámicos:** El sistema evalúa el carrito en tiempo real mediante JavaScript y cambia automáticamente de precio unitario a precio por mayor si la cantidad supera un umbral definido (Ej: más de 5 unidades)[cite: 2].
*   **Cálculo Automatizado de Stock Empaquetado:** Convierte automáticamente ingresos masivos a unidades sueltas (Ej: `22 paquetes × 10 unidades + 2 sueltas = 222 totales`) para evitar errores humanos de conteo[cite: 2].
*   **Flujo Multiextracción en Tickets de Crédito:** Permite a los vendedores añadir productos a un mismo ticket a lo largo del día, registrando la hora exacta de cada retiro de mercadería antes del cierre total[cite: 2].
*   **Auditoría de Inventario Físico:** Módulo especializado para comparar el conteo físico vs. el stock del sistema, generando reportes automáticos de diferencias (+/-) y aplicando ajustes directos en la base de datos[cite: 2].
*   **Seguridad por Roles (RBAC):** Restricción estricta de accesos. Los administradores gestionan usuarios, resetean contraseñas y ven balances financieros; los vendedores operan el POS, registran abonos y reimprimen recibos[cite: 2].

---

## 👩‍💻 Autoría y Aseguramiento de Calidad (QA)
*   **Desarrolladora Full-Stack & QA:** Valeria Evelin Guarachi Cori
*   **Contacto:** valeriaguarachi444@gmail.com
*   *Proyecto diseñado con un riguroso enfoque en la usabilidad del cliente, testing explorato