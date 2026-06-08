# Plataforma Web de Gestión de Salud Personal

> Nombre del proyecto anonimizado por motivos de confidencialidad.

## Resumen

Aplicación web orientada al seguimiento y control de indicadores de salud personal. El sistema permitía a los usuarios registrar y monitorear métricas relevantes para su condición médica, visualizar tendencias a lo largo del tiempo y acceder a reportes personalizados. Estaba dirigido a pacientes y usuarios finales que requerían una herramienta digital accesible para el automonitoreo diario.

## Contexto del proyecto

- **Tipo de producto:** Web app (SPA — Single Page Application)
- **Sector o dominio:** Salud digital / Healthtech
- **Tamaño del equipo:** Equipo pequeño de desarrollo ([N] personas)
- **Mi rol:** Desarrollador Frontend — participé en el diseño e implementación de interfaces, integración con servicios externos y mejoras de experiencia de usuario

## Mi participación

- Desarrollo e implementación de nuevas funcionalidades en el frontend
- Construcción y mantenimiento de componentes reutilizables de interfaz
- Integración con APIs y servicios de backend (autenticación, almacenamiento de datos, envío de notificaciones)
- Implementación de visualizaciones de datos dinámicas e interactivas
- Generación y exportación de reportes en formato PDF directamente desde el cliente
- Corrección de bugs reportados en flujos críticos del usuario
- Refactorización de componentes para mejorar legibilidad y mantenibilidad
- Mejora de la experiencia de usuario en formularios y flujos de registro
- Colaboración con el equipo en revisiones de código
- Participación en decisiones de estructura y organización del proyecto

## Tecnologías utilizadas

- **Frontend:** React 18, React Router DOM
- **Estilos:** Tailwind CSS, Flowbite React
- **Visualización de datos:** ApexCharts
- **Validación de formularios:** Formik, Yup
- **Generación de PDF:** React PDF Renderer
- **Autenticación y base de datos:** Supabase
- **Comunicación HTTP:** Axios
- **Notificaciones UI:** React Toastify
- **Envío de correos:** EmailJS / [servicio de email transaccional]
- **Animaciones:** AOS (Animate On Scroll)
- **Control de versiones:** Git
- **Herramientas de build:** Create React App, Webpack, Babel

## Funcionalidades en las que contribuí

- **Módulo de autenticación:** Registro, inicio de sesión y gestión de sesión de usuario
- **Panel de seguimiento:** Visualización de métricas de salud con gráficas interactivas por rango de tiempo
- **Registro de datos diarios:** Formularios dinámicos para el ingreso de información relacionada con alimentación, actividad física y otras métricas
- **Gestión de citas:** Módulo para agendar y visualizar eventos médicos o recordatorios
- **Generación de reportes:** Exportación de historial de registros en formato PDF
- **Perfil de usuario:** Edición de datos personales e imagen de perfil
- **Notificaciones:** Recordatorios y alertas configurables dentro de la aplicación
- **Diseño responsivo:** Adaptación de la interfaz a diferentes tamaños de pantalla

## Retos técnicos

- Manejo de estado global complejo entre múltiples módulos interdependientes
- Sincronización consistente de datos entre el cliente y los servicios externos
- Optimización del rendimiento en componentes con renderizado frecuente de gráficas
- Adaptación de la interfaz a requerimientos cambiantes durante el desarrollo
- Garantizar una experiencia de usuario fluida en flujos con múltiples pasos y validaciones
- Mejora del diseño responsivo en vistas con alta densidad de información

## Soluciones implementadas

- Uso de Context API de React para centralizar el estado de sesión y datos del usuario, evitando prop drilling innecesario
- Separación de responsabilidades mediante componentes pequeños y reutilizables, facilitando el mantenimiento y las pruebas
- Implementación de validaciones en cliente con esquemas Yup antes de enviar datos al servidor, reduciendo errores en los flujos principales
- Refactorización de componentes de alto acoplamiento hacia una arquitectura más modular y predecible
- Aprovechamiento de librerías especializadas (ApexCharts, React PDF Renderer) para reducir complejidad de implementación y acelerar entregas

## Resultados o impacto

- Entrega exitosa de funcionalidades dentro del alcance y los tiempos definidos
- Mejora en la experiencia de usuario en flujos de registro y visualización de datos
- Reducción de errores reportados en formularios críticos tras implementar validaciones explícitas
- Mayor mantenibilidad del código gracias a la refactorización y modularización de componentes
- Mejora en la organización del proyecto y coherencia visual de la interfaz

## Aprendizajes

- Profundización en el desarrollo de SPAs con React y ecosistema moderno (hooks, Context, React Router)
- Buenas prácticas en validación de formularios y manejo de errores en el cliente
- Integración con servicios de backend como Supabase para autenticación y persistencia de datos
- Trabajo con librerías de visualización de datos para presentar información médica de forma clara
- Experiencia colaborando en un equipo con control de versiones y revisiones de código
- Mejora en habilidades de comunicación técnica y priorización de tareas en un entorno de proyecto real
- Comprensión de la importancia del diseño responsivo y la accesibilidad en aplicaciones orientadas a usuarios finales

## Confidencialidad

> Por motivos de confidencialidad, este documento no incluye código fuente, nombres reales de servicios, endpoints, datos internos, información de clientes ni detalles propietarios del proyecto. La descripción fue adaptada para mostrar mi participación profesional sin comprometer la privacidad del repositorio.
