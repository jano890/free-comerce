# Free-Comerce

---

## Contexto y motivación

Dentro del campus de la UPSRJ existe una actividad comercial constante entre estudiantes y cooperativas, derivada de la necesidad de adquirir y ofrecer productos o servicios de forma rápida y accesible.  
Sin embargo, estos intercambios suelen gestionarse mediante plataformas externas como WhatsApp, las cuales no están diseñadas específicamente para un entorno universitario y presentan riesgos como:

- Exposición de información personal.  
- Suplantación de identidad.  
- Falta de privacidad.  
- Ausencia de mecanismos de seguridad para los usuarios.

Ante esta situación, surge la necesidad de brindar un espacio digital confiable que permita realizar transacciones dentro de la comunidad universitaria **sin comprometer la seguridad ni la identidad de los participantes**.

---

## Propuesta

La aplicación cumple la función de una plataforma de comercio electrónico diseñada específicamente para la comunidad universitaria. Su operación se basa en perfiles clasificados como:

- **Usuarios y vendedores (estudiantes).**
- **Tiendas institucionales (cooperativas).**

Con esta plataforma se busca resolver problemáticas presentes en el entorno universitario:

- Dificultad para comercializar productos o servicios dentro del campus.  
- Multitudes en filas de cooperativas que provocan tiempos de espera prolongados.

---

## Objetivos

El propósito principal es facilitar la selección, venta y compra de productos dentro de la Universidad Politécnica de Santa Rosa mediante una organización eficiente por categorías como:

- Comida  
- Postres  
- Teléfonos  
- Consolas de videojuegos  
- Computadoras  
- Ropa  
- Entre otros...

### Objetivo General

Desarrollar una plataforma que facilite la compra y venta de productos y servicios dentro del entorno universitario de la UPSRJ, garantizando un proceso seguro, confiable y anónimo para los usuarios.

### Objetivos Específicos

- Mejorar la experiencia de compra.
- Facilitar la entrega de productos.
- Mejorar la experiencia de las cooperativas.
- Evitar largas esperas innecesarias.

---

## Margen de error y riesgos

A pesar de la planeación del proyecto, existen factores tecnológicos, operativos y de adopción que pueden generar un margen de error.

### Riesgos tecnológicos

| Posible error | Consecuencia | Probabilidad |
| --- | --- | --- |
| Fallas en servidores o base de datos | Interrupción del servicio y pérdida de información | Media |
| Vulnerabilidades de seguridad | Suplantación, filtración de datos o accesos no autorizados | Media - Alta |
| Tiempo de carga excesivo | Abandono de la aplicación | Media |

### 🧪 Riesgos de diseño y experiencia del usuario

| Posible error | Consecuencia | Probabilidad |
| --- | --- | --- |
| Dificultad en el proceso de compra/venta | Disminución de transacciones | Media |
| Falta de accesibilidad para usuarios nuevos | Aumento en solicitudes de soporte | Baja – Media |

### Riesgos organizacionales / de implementación

| Posible error | Consecuencia | Probabilidad |
| --- | --- | --- |
| Falta de adopción por estudiantes | Pocas ventas y baja actividad | Alta |
| Falta de compromiso de las cooperativas | Catálogo limitado | Media |
| Mala coordinación entre áreas de trabajo | Retrasos en entregas | Media |

### Riesgos operativos posteriores al lanzamiento

| Posible error | Consecuencia | Probabilidad |
| --- | --- | --- |
| Saturación del sistema en horas pico | Intercambios lentos o interrupciones | Baja - Media |
| Problemas en logística de entrega | Quejas de usuarios | Media |

### Evaluación global del margen de error

| Aspectos evaluados | Nivel de riesgo |
| --- | --- |
| Técnico | Medio |
| Diseño / Experiencia | Medio |
| Adopción por usuarios | Medio - Alto |
| Operación después del lanzamiento | Medio |

---

## Metodología

La metodología aplicada se sustenta en dos enfoques complementarios:

1. División funcional del equipo por áreas de especialización.  
2. Proceso de desarrollo siguiendo el **modelo en cascada**.

Ambos enfoques permiten una ejecución ordenada con responsabilidades claras para cada integrante.

### División de responsabilidad por áreas

| Área | Función principal |
| --- | --- |
| Scrum | Gestión del proyecto |
| Marketing digital | Comunicación y alcance |
| Desarrollo de entornos digitales (UX/UI) | Diseño visual e interacción |
| Programadores | Construcción técnica de la plataforma |

---

### Scrum

**Rol principal:** Gestión del proyecto y coordinación del equipo.

**Actividades**
- Definir y priorizar el Product Backlog.
- Planificar Sprints quincenales.
- Reuniones diarias de seguimiento (Daily Scrum).
- Sprint Review y Sprint Retrospective.
- Registro continuo de avances y mejoras.

**Objetivo:** Garantizar un flujo de trabajo ordenado y eficiente.

**Entregables**
- Cronograma y Escritura de Sprint  
- Reportes de avance  
- Trazabilidad de funcionalidades completadas

---

### Desarrollo de Entornos Digitales (UX/UI)

**Rol principal:** Diseñar la interacción y apariencia visual de la plataforma.

**Actividades**
- Estudios de usabilidad.
- Wireframes y arquitectura visual.
- Prototipos de alta fidelidad.
- Pruebas de usabilidad.
- Optimización de navegación y componentes visuales.

**Entregables**
- Mapa de navegación
- Wireframes
- Prototipo UI navegable
- Reporte de pruebas

---

### Programadores

**Rol principal:** Desarrollo funcional de la aplicación.

**Actividades**
- Definir arquitectura del sistema: frontend, backend y base de datos.
- Implementar autenticación y anonimización.
- Programar módulos funcionales como:
  - Registro e inicio de sesión
  - Perfil de usuario/vendedor
  - Catálogo de productos
  - Sistema de pedidos
  - Chat interno seguro
- Pruebas técnicas y corrección de errores.
- Mantenimiento posterior al despliegue.

**Entregables**
- Base de datos estructurada
- Módulos programados y probados
- Pruebas unitarias / integrales documentadas
- Aplicación desplegada con documentación técnica

---

### Metodología de desarrollo (Modelo en cascada)

| Fase | Descripción |
| --- | --- |
| Análisis e investigación | Identificación de necesidades y requerimientos |
| Planteamiento aplicado | Definición de alcances y estructura del sistema |
| Diseño | Prototipos visuales y flujos de navegación |
| Implementación | Programación de funcionalidades |
| Verificación | Pruebas y validación del sistema |
| Mantenimiento | Actualizaciones y soporte |

Actualmente el proyecto se encuentra en la **Fase 3 — Diseño**, con un prototipo funcional desarrollado tras análisis comparativo entre diferentes plataformas.

---

## Especialización del equipo de desarrollo

El área de programación está conformada por integrantes de distintas especialidades dentro de la carrera:

- Desarrollo multiplataforma  
- Ciencia de datos  
- Inteligencia artificial  

Estas disciplinas fortalecen el proyecto mediante:

- Algoritmos inteligentes  
- Manejo eficiente de datos  
- Adaptabilidad a múltiples dispositivos  

---

**Free-Comerce es una solución tecnológica creada por estudiantes, para estudiantes, con el propósito de fortalecer la comunidad universitaria y mejorar la experiencia comercial dentro del campus.**

