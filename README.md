# 🎫 Ticketazo - Proyecto de QA Automation
## Grupo N°10 - XAcademy QA Automation

### 📋 Descripción del Proyecto

Este proyecto tiene como objetivo poner en práctica la elaboración de planes de prueba y la automatización de casos funcionales con **Cypress** sobre la plataforma **Ticketazo**, aplicando buenas prácticas de testing y reporte de defectos.

## 👥 Nuestro Equipo

Este trabajo fue posible gracias al trabajo colaborativo de nuestro equipo:

| Nombre y Apellido             | Usuario en GitHub     | Perfil de GitHub                                                                                                                              |
| ----------------------------- | --------------------- | --------------------------------------------------------------------------------------------------------------------------------------------- |
| Integrante 1 | ``           | [![GitHub Badge](https://img.shields.io/badge/GitHub-121011?style=for-the-badge&logo=github&logoColor=white)](https://github.com/) |
| Integrante 2 | ``           | [![GitHub Badge](https://img.shields.io/badge/GitHub-121011?style=for-the-badge&logo=github&logoColor=white)](https://github.com/) |
| Integrante 3 | ``           | [![GitHub Badge](https://img.shields.io/badge/GitHub-121011?style=for-the-badge&logo=github&logoColor=white)](https://github.com/) |
| Integrante 4 | ``           | [![GitHub Badge](https://img.shields.io/badge/GitHub-121011?style=for-the-badge&logo=github&logoColor=white)](https://github.com/) |
| Integrante 5 | ``           | [![GitHub Badge](https://img.shields.io/badge/GitHub-121011?style=for-the-badge&logo=github&logoColor=white)](https://github.com/) |
| Integrante 6 | ``           | [![GitHub Badge](https://img.shields.io/badge/GitHub-121011?style=for-the-badge&logo=github&logoColor=white)](https://github.com/) |
| Integrante 7 | ``           | [![GitHub Badge](https://img.shields.io/badge/GitHub-121011?style=for-the-badge&logo=github&logoColor=white)](https://github.com/) |
| Juan Diego González Antoniazzi | `JDGA1997`           | [![GitHub Badge](https://img.shields.io/badge/GitHub-121011?style=for-the-badge&logo=github&logoColor=white)](https://github.com/JDGA1997) |

> **Nota:** Tabla pendiente de completar con los demás integrantes del equipo

## 📋 Gestión del Proyecto

### 🎯 Tablero Trello

Para la organización y seguimiento del desarrollo de este proyecto, utilizamos **Trello** como herramienta de gestión de tareas y reporte de bugs.
Nuestro tablero Kanban está estructurado con un flujo de trabajo completo que incluye desde la identificación de bugs hasta su resolución.

**🔗 Accede a nuestro tablero de Trello:**
[![Trello Board](https://img.shields.io/badge/Trello-0052CC?style=for-the-badge&logo=trello&logoColor=white)](https://trello.com/b/JLnNR3NC/grupo-n10-ticketazo-xacademy-qa-automation)

### 📊 Estructura del Tablero

#### Columnas de Flujo de Trabajo:
- **🐛 Backlog de Bugs**: Defectos identificados pendientes de análisis
- **🔄 En Progreso**: Bugs actualmente en proceso de resolución  
- **🔍 Listo para Revisar**: Defectos resueltos en proceso de validación
- **✅ Cerrado**: Bugs completamente resueltos y validados

#### 🏷️ Sistema de Etiquetas

**Prioridad:**
- 🔴 **Prioridad: Alta** - Requiere atención inmediata
- 🟡 **Prioridad: Media** - Debe resolverse en el sprint actual
- 🟢 **Prioridad: Baja** - Puede postergarse sin impacto crítico

**Severidad:**
- 🔥 **Severidad: Crítica** - Bloquea funcionalidades principales
- ⚠️ **Severidad: Alta** - Impacta funcionalidades importantes
- 📝 **Severidad: Media** - Problemas menores de funcionalidad
- 💡 **Severidad: Baja** - Mejoras o sugerencias

**Tipo:**
- 🐞 **Tipo: Bug/Defecto** - Errores en funcionalidades existentes
- 💡 **Tipo: Mejora** - Sugerencias de optimización

#### 📋 Plantillas de Tarjetas

**Para Reportes de Bugs:**
- **ID:** Identificador único (ej: TZO-BUG-XXX)
- **Título:** Descripción concisa del problema
- **Descripción:** Detalle completo del defecto encontrado
- **Pasos para Reproducir:** Secuencia exacta para replicar el bug
- **Resultado Esperado:** Comportamiento correcto esperado
- **Resultado Actual:** Comportamiento observado
- **Evidencia:** Capturas de pantalla, videos o logs
- **Ambiente:** Navegador, versión, SO donde se detectó

**Para Sugerencias de Mejora:**
- **ID:** Identificador único (ej: TZO-MEJ-XXX)
- **Título:** Descripción clara de la mejora propuesta
- **Justificación/Beneficio:** Razón y valor agregado de la mejora
- **Descripción:** Detalle de la implementación sugerida
- **Impacto:** Análisis del efecto en usuarios y sistema
- **Evidencia:** Mockups, referencias o documentación de apoyo

El tablero nos permite mantener una visibilidad completa del progreso del proyecto, facilita la colaboración entre todos los miembros del equipo y asegura un seguimiento detallado de cada defecto encontrado.

## 🎯 Objetivos del Proyecto

Implementar un conjunto completo de pruebas automatizadas para la plataforma **Ticketazo**, que incluye:

- ✅ Elaboración de planes de prueba detallados
- 🤖 Automatización de casos funcionales críticos con **Cypress**  
- 🐛 Aplicación de buenas prácticas de reporte de defectos
- 📊 Gestión efectiva de bugs utilizando metodologías ágiles

## 🌐 Sistema Bajo Prueba (SBP)

### 🔗 Entornos Disponibles

| Entorno | URL | Estado |
| --- | --- | --- |
| **🧪 QA** | https://vps-3696213-x.dattaweb.com/ | ✅ Recomendado |
| **🚀 Producción** | [https://ticketazo.com.ar](https://ticketazo.com.ar/) | ⚠️ Misma data que QA |

> **⚠️ Importante:** Ambos entornos comparten la misma base de datos de QA. Se recomienda usar el entorno QA para evitar tráfico real en producción.

### 🔐 Credenciales de Acceso

**Super Administrador:**
- 📧 **Email:** `admin@admin.com`
- 🔑 **Password:** `admin`

## 🚀 Instalación y Configuración

### 📋 Prerrequisitos

- Node.js (versión 16 o superior)
- npm o yarn
- Git

### ⚡ Inicio Rápido

```bash
# Clonar el repositorio
git clone https://github.com/JDGA1997/Grupo-N-10.git

# Navegar al directorio del proyecto
cd Grupo-N-10

# Instalar dependencias
npm install

# Ejecutar todas las pruebas
npm run test

# Ejecutar pruebas en modo headless
npm run test:headless

# Abrir Cypress Test Runner
npm run cypress:open
```

### 📁 Estructura del Proyecto

```
Grupo-N-10/
├── cypress/
│   ├── e2e/                 # Tests end-to-end
│   ├── fixtures/            # Datos de prueba
│   ├── support/             # Comandos personalizados
│   └── screenshots/         # Capturas de pantalla
├── docs/                    # Documentación del proyecto
├── package.json
└── README.md
```

## 📋 Plan de Pruebas

### 🔗 Documento del Plan de Pruebas
[![Google Sheets](https://img.shields.io/badge/Google%20Sheets-34A853?style=for-the-badge&logo=google-sheets&logoColor=white)](https://docs.google.com/spreadsheets/d/1Tej8XHDKx0ThhKQarUVezOS1dwvYF99l/edit?usp=sharing&ouid=103416615054896105402&rtpof=true&sd=true)

> **📝 Nota:** El plan de pruebas detallado se encuentra en Google Sheets con acceso público. Incluye todos los casos de prueba con sus respectivos pasos, datos de prueba y criterios de aceptación.

### 🧪 Casos de Prueba Automatizados

Los siguientes casos críticos han sido automatizados con Cypress para cubrir las funcionalidades principales de **Ticketazo**:

#### 🔐 **TC001 - Autenticación y Sesiones**
- **Login exitoso** con credenciales de super administrador
- **Validación de errores** con credenciales inválidas
- **Verificación de redirección** al dashboard de administración
- **Logout seguro** y limpieza de sesión
- **Validación de persistencia** de sesión

#### 🎫 **TC002 - Gestión de Eventos**
- **Visualización de catálogo** de eventos disponibles
- **Búsqueda y filtrado** de eventos por criterios diversos
- **Navegación entre eventos** ("El Eternauta", "Los Piojos En River", etc.)
- **Validación de información** de eventos (fecha, hora, ubicación)
- **Responsive design** en diferentes dispositivos

#### 🛒 **TC003 - Proceso de Compra de Entradas**
- **Selección de evento** y cantidad de entradas
- **Carrito de compras** - agregar/eliminar items
- **Flujo de checkout** completo
- **Validación de formularios** de datos del comprador
- **Confirmación de compra** y generación de ticket
- **Integración con métodos de pago**

#### 👤 **TC004 - Gestión de Usuarios**
- **Registro de nuevos usuarios**
- **Edición de perfil** personal
- **Historial de compras** y entradas adquiridas
- **Gestión de favoritos** y eventos guardados
- **Notificaciones y preferencias**

#### ⚙️ **TC005 - Panel de Administración**
- **CRUD de eventos** (crear, leer, actualizar, eliminar)
- **Gestión de categorías** y tipos de eventos
- **Control de disponibilidad** y stock de entradas
- **Reportes y estadísticas** de ventas
- **Gestión de usuarios** registrados

#### 🌐 **TC006 - Funcionalidades Transversales**
- **Navegación general** del sitio
- **Funcionalidades responsive** en móviles y tablets
- **Performance** y tiempos de carga
- **Manejo de errores** 404 y estados de error
- **Accesibilidad** básica (WCAG guidelines)

## 🐛 Proceso de Reporte de Defectos

### 📝 Metodología de Testing

Durante las pruebas exploratorias y automatizadas de **Ticketazo**, seguimos un proceso estructurado para la identificación, documentación y seguimiento de defectos:

#### 🔍 **Identificación de Defectos**
1. **Testing Exploratorio**: Navegación libre para identificar comportamientos inesperados
2. **Ejecución de Casos de Prueba**: Validación sistemática de funcionalidades críticas
3. **Testing de Regresión**: Verificación de que nuevos cambios no afecten funcionalidades existentes
4. **Cross-browser Testing**: Validación en diferentes navegadores y dispositivos

#### 📋 **Documentación Estructurada**

**Campos Obligatorios para Cada Defecto:**
- **ID único**: Formato TZO-BUG-XXX para bugs, TZO-MEJ-XXX para mejoras
- **Resumen ejecutivo**: Descripción concisa del problema
- **Descripción detallada**: Contexto completo del defecto
- **Pasos para reproducir**: Secuencia exacta y reproducible
- **Resultado esperado**: Comportamiento correcto según especificaciones
- **Resultado actual**: Comportamiento observado
- **Ambiente de prueba**: Navegador, versión, SO, URL específica
- **Evidencia**: Screenshots, videos, logs de consola
- **Prioridad**: Crítica, Alta, Media, Baja
- **Severidad**: Crítica, Alta, Media, Baja

#### 🏷️ **Clasificación de Defectos**

**Por Severidad:**
- **🔥 Crítica**: Funcionalidad principal no disponible, pérdida de datos
- **⚠️ Alta**: Funcionalidad importante con workaround complejo
- **📝 Media**: Problemas menores que afectan usabilidad
- **💡 Baja**: Mejoras cosméticas o sugerencias de UX

**Por Prioridad:**
- **🔴 Alta**: Debe solucionarse antes del siguiente release
- **🟡 Media**: Incluir en próximo sprint de desarrollo
- **🟢 Baja**: Backlog para futuras iteraciones

#### 📊 **Seguimiento y Métricas**
- **Trazabilidad**: Vinculación con casos de prueba específicos
- **Estado del defecto**: Nuevo, En Progreso, Resuelto, Cerrado, Reabierto
- **Tiempo de resolución**: Métricas de eficiencia del equipo
- **Tendencias**: Análisis de patrones y áreas problemáticas

### 🎯 **Ejemplos de Defectos Identificados**

Basándome en las pruebas realizadas en Ticketazo, algunos ejemplos de defectos típicos incluyen:

- **Problemas de navegación**: Enlaces rotos, redirecciones incorrectas
- **Issues de formularios**: Validaciones faltantes, mensajes de error poco claros  
- **Problemas de UI/UX**: Elementos superpuestos, responsive design
- **Funcionalidades de búsqueda**: Filtros que no funcionan correctamente
- **Proceso de compra**: Errores en carrito, problemas de checkout
- **Gestión de sesiones**: Timeouts inesperados, problemas de autenticación

## 📊 Entregables del Proyecto

### 📅 Cronograma de Entrega

- **🗓️ Fecha límite:** **Martes 29 de julio de 2025 – 23:59 h (GMT‑3)**
- **⚠️ Importante:** Entregas posteriores serán consideradas fuera de término

### 📋 Componentes del Entregable

#### 1. 📊 Plan de Pruebas
- **Formato:** Google Sheets (recomendado) o Excel
- **Requisito:** Acceso de lectura pública sin necesidad de registro
- **Contenido mínimo:**
  - ID / Clave del caso
  - Título descriptivo
  - Descripción / objetivo
  - Precondiciones necesarias
  - Pasos detallados
  - Datos de prueba
  - Resultado esperado
  - Severidad / Prioridad

#### 2. 🤖 Automatización con Cypress
- **Repositorio:** GitHub público
- **Estructura:** Carpetas organizadas (`cypress/`, `e2e/`, `fixtures/`, etc.)
- **Scripts:** Instalación (`npm install`) y ejecución (`npm run test`) documentados
- **Cobertura:** Mínimo 5 casos críticos end-to-end
- **Calidad:** Assertions apropiadas, comandos custom, fixtures

#### 3. 🐛 Gestión de Defectos en Trello
- **Columnas:**
  - *Backlog de bugs*
  - *En progreso* 
  - *Listo para revisar*
  - *Cerrado*
- **Contenido por tarjeta:**
  - ID único
  - Título descriptivo
  - Descripción detallada
  - Pasos para reproducir
  - Resultado esperado vs actual
  - Severidad y prioridad
  - Evidencia (capturas/videos)

### 📋 Modalidad de Entrega Unificada

Para simplificar el proceso, se permite entregar **únicamente el enlace al repositorio GitHub**. 
El `README.md` debe incluir:

1. ✅ **Plan de pruebas** (enlazado o insertado)
2. ✅ **Enlace público al tablero Trello**
3. ✅ **Instrucciones de instalación y ejecución**

## ⚙️ Estándares de Calidad y Metodología

### 🏗️ Estructura de Automatización con Cypress

```javascript
// Ejemplo de estructura de test optimizada
describe('Ticketazo - Funcionalidades Críticas', () => {
  beforeEach(() => {
    // Setup inicial para cada test
    cy.visit(Cypress.env('baseUrl'));
    cy.fixture('usuarios').as('userData');
    cy.fixture('eventos').as('eventData');
  });

  it('TC001 - Login exitoso con credenciales de admin', () => {
    cy.get('@userData').then((data) => {
      // Comando personalizado para login
      cy.login(data.admin.email, data.admin.password);
      
      // Verificaciones múltiples
      cy.url().should('include', '/dashboard');
      cy.get('[data-testid="user-menu"]').should('be.visible');
      cy.get('[data-testid="admin-panel"]').should('exist');
      
      // Verificar elementos específicos del dashboard
      cy.contains('Panel de Administración').should('be.visible');
    });
  });

  it('TC002 - Navegación y visualización de eventos', () => {
    cy.get('@eventData').then((events) => {
      // Verificar catálogo de eventos
      cy.visit('/eventos');
      cy.get('[data-testid="event-card"]').should('have.length.greaterThan', 0);
      
      // Verificar eventos específicos
      cy.contains(events.elEternauta.title).should('be.visible');
      cy.contains(events.losPiojos.title).should('be.visible');
    });
  });
});
```

### 🎯 Criterios de Aceptación y Buenas Prácticas

#### 📊 **Plan de Pruebas**
- ✅ **Completitud:** Cobertura integral de funcionalidades críticas
- ✅ **Claridad:** Casos de prueba fáciles de entender y ejecutar
- ✅ **Priorización:** Clasificación adecuada por severidad e impacto
- ✅ **Trazabilidad:** Vinculación entre casos de prueba y requerimientos
- ✅ **Mantenibilidad:** Documentación actualizable y versionada

#### 🤖 **Automatización con Cypress**
- ✅ **Legibilidad:** Código limpio y bien documentado
- ✅ **Reutilización:** Comandos personalizados y fixtures
- ✅ **Mantenibilidad:** Estructura modular y escalable
- ✅ **Estabilidad:** Tests confiables que pasan consistentemente
- ✅ **Performance:** Tiempos de ejecución optimizados
- ✅ **Reporting:** Reportes detallados con capturas de fallos

#### 🔧 **Herramientas y Configuración**
- **Cypress**: Framework principal de testing E2E
- **JavaScript/TypeScript**: Lenguaje de automatización
- **GitHub Actions**: CI/CD para ejecución automática
- **Trello**: Gestión de defectos y seguimiento
- **Google Sheets**: Documentación del plan de pruebas

#### 🐛 **Gestión de Defectos**
- ✅ **Claridad:** Descripción precisa y reproducible
- ✅ **Clasificación:** Severidad y prioridad correctamente asignadas
- ✅ **Evidencia:** Capturas de pantalla y/o videos adjuntos
- ✅ **Trazabilidad:** Vinculación con casos de prueba específicos
- ✅ **Seguimiento:** Estados claros y tiempos de resolución
- ✅ **Comunicación:** Notificaciones oportunas al equipo
- ✅ **Mantenibilidad:** Estructura modular y escalable
- ✅ **Estabilidad:** Tests confiables que pasan consistentemente

#### Gestión de Defectos
- ✅ **Claridad:** Descripción precisa y reproducible
- ✅ **Clasificación:** Severidad y prioridad correctamente asignadas
- ✅ **Evidencia:** Capturas de pantalla y/o videos adjuntos
- ✅ **Trazabilidad:** Vinculación con casos de prueba específicos

---