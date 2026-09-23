# Índice de Documentación del Dashboard

Bienvenido a la documentación del proyecto. Este archivo sirve como mapa del sitio para navegar por todas las fases de conceptualización, diseño y desarrollo.

---

## 📂 [01. Requisitos](./01-requisitos/)
Todo lo relacionado con qué debe hacer la aplicación y sus restricciones.
* **[Requisitos Funcionales](./01-requisitos/funcionales.md)**: Qué características tendrá (tipos de gráficas, alertas, paneles, etc.).
* **[Requisitos No Funcionales](./01-requisitos/no_funcionales.md)**: Expectativas de rendimiento, seguridad, escalabilidad y concurrencia.

## 📂 [02. Arquitectura](./02-arquitectura/)
Cómo se va a construir el proyecto a nivel técnico.
* **[Visión General](./02-arquitectura/vision_general.md)**: Explicación a alto nivel de los módulos del sistema.
* **[Stack Tecnológico](./02-arquitectura/stack_tecnologico.md)**: Tecnologías y herramientas empleadas (Frontend, Backend, Base de Datos, etc.).
* **[Diagramas](./02-arquitectura/diagramas/)**: Carpeta de recursos visuales (diagramas de flujo, arquitectura o infraestructura).
* **[Decisiones](./02-arquitectura/decisiones.md)**: Registro (ADRs) de por qué se toman ciertas decisiones técnicas importantes.

## 📂 [03. UI/UX](./03-ui_ux/)
Diseño, interfaz y experiencia de usuario.
* **[Wireframes](./03-ui_ux/wireframes.md)**: Enlaces, bocetos o croquis de diseño de las vistas.
* **[Sistema de Diseño](./03-ui_ux/sistema_diseno.md)**: Paleta de colores, tipografías y comportamiento responsivo.
* **[Componentes](./03-ui_ux/componentes.md)**: Lista y comportamiento de los componentes reutilizables (paneles, botones, modales).

## 📂 [04. Datos](./04-datos/)
El núcleo del dashboard: la información y cómo se gestiona.
* **[Fuentes de Origen](./04-datos/fuentes_origen.md)**: Tipos de orígenes de datos que soportará el sistema (APIs, Bases de datos).
* **[Transformación](./04-datos/transformacion.md)**: Cómo se procesarán o filtrarán los datos antes de mostrarlos en las gráficas.
* **[Modelo de Datos](./04-datos/modelo_datos.md)**: Esquemas de las entidades principales (ej. Entidad "Dashboard", "Widget", "Usuario").

## 📂 [05. API e Integraciones](./05-api_e_integraciones/)
Comunicación e interfaces del sistema.
* **[Endpoints](./05-api_e_integraciones/endpoints.md)**: Definición de las rutas de comunicación entre Front y Back.

## 📂 [06. Operaciones y Despliegue](./06-operaciones_despliegue/)
Puesta en marcha y entornos de producción.
* **[Entorno Local](./06-operaciones_despliegue/entorno_local.md)**: Guía paso a paso para que un desarrollador levante el proyecto en su equipo.
* **[Despliegue](./06-operaciones_despliegue/despliegue.md)**: Estrategia de publicación en servidores, contenedores o plataformas Cloud.

## 📂 [07. Manuales](./07-manuales/)
Documentación dirigida a los usuarios finales.
* **[Manual de Usuario](./07-manuales/manual_usuario.md)**: Guía práctica sobre cómo utilizar la aplicación una vez terminada.