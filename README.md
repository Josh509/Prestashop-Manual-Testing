# Prestashop Demo - Manual Testing Project

> **Proyecto de Testing Manual Profesional** | Testing de Funcionalidades Principales de E-commerce

[![Testing](https://img.shields.io/badge/Testing-Manual-blue.svg)](https://github.com/username/prestashop-testing)
[![Status](https://img.shields.io/badge/Status-Completed-success.svg)](https://github.com/username/prestashop-testing)
[![Coverage](https://img.shields.io/badge/Coverage-100%25-brightgreen.svg)](https://github.com/username/prestashop-testing)
[![Defects](https://img.shields.io/badge/Defects_Found-15+-red.svg)](https://github.com/username/prestashop-testing)

---

## Descripción del Proyecto

Este proyecto representa un **ciclo completo de testing manual** realizado sobre la tienda demo de Prestashop ([demo.prestashop.com](https://demo.prestashop.com/)), una plataforma de e-commerce ampliamente utilizada. El objetivo es demostrar habilidades profesionales en Quality Assurance mediante la validación exhaustiva de funcionalidades críticas del sistema.

### Sistema Bajo Prueba
- **Aplicación:** Prestashop Demo Store
- **Tipo:** E-commerce Web Application
- **URL:** https://demo.prestashop.com/
- **Versión:** Prestashop 8.x (Demo)
- **Enfoque:** Frontend (Customer-facing)

---

## Objetivos

### Objetivo Principal
Validar las funcionalidades principales del sitio Prestashop Demo mediante pruebas manuales estructuradas, garantizando que cumplan con los requisitos funcionales y proporcionen una experiencia de usuario óptima.

### Objetivos Específicos
✅ Validar el flujo completo de compra end-to-end  
✅ Identificar y documentar defectos funcionales, visuales y de UX  
✅ Verificar la usabilidad del sitio y consistencia de navegación  
✅ Evaluar compatibilidad cross-browser (Chrome, Firefox, Edge, Safari)  
✅ Validar responsividad en múltiples dispositivos  
✅ Crear documentación profesional de QA  
✅ Demostrar habilidades de testing manual profesional  

---

## Alcance del Testing

### Módulos Incluidos

| Módulo | Funcionalidades | Casos de Prueba | Prioridad |
|--------|----------------|-----------------|-----------|
| **Autenticación** | Registro, Login, Logout | 15 casos | 🔴 P0 - Crítica |
| **Catálogo de Productos** | Navegación, Visualización, Paginación | 18 casos | 🔴 P0 - Crítica |
| **Búsqueda y Filtros** | Búsqueda, Autocompletado, Filtros | 16 casos | 🔴 P1 - Alta |
| **Carrito de Compras** | Agregar, Modificar, Eliminar productos | 20 casos | 🔴 P0 - Crítica |
| **Proceso de Checkout** | Dirección, Envío, Pago, Confirmación | 22 casos | 🔴 P0 - Crítica |
| **Detalle de Producto** | Galería, Descripción, Variantes | 12 casos | 🔴 P1 - Alta |
| **Navegación** | Menú, Breadcrumbs, Footer | 10 casos | 🔴 P2 - Media |
| **Responsividad** | Desktop, Tablet, Mobile | 8 casos | 🔴 P2 - Media |

**Total:** 121 casos de prueba diseñados y ejecutados

### ❌ Fuera de Alcance
- Panel de administración (Backend)
- Pruebas de API
- Pruebas de rendimiento/carga
- Pruebas de seguridad (penetración)
- Integración con pasarelas de pago reales
- Pruebas de accesibilidad (WCAG)

---

## Metodología

### Enfoque de Testing
El proyecto utiliza un **enfoque híbrido** que combina:

```
Distribución del Esfuerzo
├── 70% Testing Basado en Scripts (Scripted Testing)
│   └── Casos predefinidos, checklist, escenarios estructurados
└── 30% Testing Exploratorio (Exploratory Testing)
    └── Sesiones ad-hoc, bug hunting, validación de UX
```

### Técnicas de Diseño de Pruebas
- ✅ **Equivalence Partitioning** - Validación de campos de formulario
- ✅ **Boundary Value Analysis** - Cantidades, límites numéricos
- ✅ **Decision Tables** - Lógica de negocio compleja (checkout)
- ✅ **State Transition** - Estados del carrito, flujo de compra
- ✅ **Use Case Testing** - Flujos end-to-end de usuario

### Niveles de Testing
- ✅ **System Testing** - Validación del sistema completo
- ✅ **Integration Testing** - Interacción entre módulos
- ✅ **Acceptance Testing** - Criterios de aceptación

### Tipos de Pruebas Ejecutadas
- Pruebas Funcionales (60%)
- Pruebas de Regresión (15%)
- Pruebas Exploratorias (20%)
- Pruebas de Usabilidad (5%)
- Pruebas Cross-Browser
- Pruebas de Responsividad

---

## 📁 Estructura del Proyecto

```
prestashop-testing/
│
├── README.md                          # Este archivo
├── Documentacion/
│   ├── 01_Alcance_del_Proyecto.pdf        # Definición del alcance
│   ├── 02_Estrategia_de_Testing.pdf       # Estrategia general de testing
│   ├── 03_Plan_de_Pruebas.pdf             # Plan maestro de pruebas
│   ├── 04_Requisitos_Funcionales.pdf       # Especificación de requisitos
│   └── 05_Matriz_de_Trazabilidad.xlsx    # Trazabilidad Requisitos-Casos
│
├── Casos_de_Prueba/
│   ├── Casos_de_Prueba.xlsx         # 121 casos de prueba detallados
│   ├── TC_Autenticacion.md               # Casos de autenticación
│   ├── TC_Catalogo.md                    # Casos de catálogo
│   ├── TC_Busqueda_Filtros.md            # Casos de búsqueda
│   ├── TC_Carrito.md                     # Casos de carrito
│   ├── TC_Checkout.md                    # Casos de checkout
│   └── Checklist_Funcionalidades.xlsx    # Checklist de validación
│
├── Defectos/
│   ├── Bug_Reports/                      # Reportes individuales de defectos
│   │   ├── BUG-PAY-001.md               # Datos bancarios faltantes
│   │   ├── BUG-CART-002.md              # Error en cálculo de subtotal
│   │   └── ...                           # Otros defectos documentados
│   
│
├── Reportes/
│   ├── Reporte_Ejecucion_Diaria/        # Reportes diarios de progreso
│ 
│
├── Evidencias/
│   ├── Screenshots/                      # Capturas de pantalla organizadas
│
└── 
```

### Flujo Recomendado de Revisión

```
1. README.md (Visión general)
   ↓
2. Alcance_del_Proyecto.md (Contexto)
   ↓
3. Estrategia_de_Testing.md (Metodología)
   ↓
4. Plan_de_Pruebas.md (Planificación)
   ↓
5. Test_Cases_Completos.xlsx (Ejecución)
   ↓
6. Defectos_Consolidado.xlsx (Resultados)
   ↓
7. Reporte_Final_Testing.pdf (Cierre)
```

---

## 💼 Habilidades Demostradas

### Technical Skills
✅ **Testing Manual Profesional** - Diseño y ejecución de 121 casos  
✅ **Análisis de Requisitos** - Documentación de 121 requisitos funcionales  
✅ **Diseño de Casos de Prueba** - Técnicas formales (EP, BVA, Decision Tables)  
✅ **Gestión de Defectos** - Identificación, documentación y seguimiento  
✅ **Testing Cross-Browser** - Chrome, Firefox, Edge, Safari  
✅ **Testing de Responsividad** - Desktop, Tablet, Mobile  
✅ **Documentación Técnica** - IEEE 829, ISTQB standards  

### Soft Skills
✅ **Atención al Detalle** - Identificación exhaustiva de defectos  
✅ **Pensamiento Analítico** - Análisis de flujos complejos  
✅ **Comunicación Técnica** - Reportes claros y profesionales  
✅ **Organización** - Estructura clara del proyecto  
✅ **Autonomía** - Proyecto completado de forma independiente  

### Herramientas y Tecnologías
✅ Excel / Google Sheets (Gestión de casos y métricas)  
✅ GitHub (Control de versiones)   
✅ Chrome DevTools (Debugging)  
✅ OBS Studio (Captura de evidencias)  
✅ Draw.io (Diagramas)  

---


## Lecciones Aprendidas

###  Insights del Proyecto

1. **Importancia de la Planificación** - Una estrategia bien definida acelera la ejecución
2. **Documentación como Asset** - Casos bien documentados facilitan regresión
3. **Priorización Efectiva** - Testing basado en riesgos optimiza tiempo
4. **Evidencias Completas** - Screenshots/videos son cruciales para defectos
5. **Automatización Futura** - Casos de regresión son candidatos ideales

###  Próximos Pasos

- Automatización de casos de regresión (Selenium/Cypress)
- Integración con herramientas de CI/CD
- Testing de API (si documentación disponible)
- Evaluación de accesibilidad (WCAG 2.1)
- Pruebas básicas de seguridad

---

## Sobre el Autor

**Josué Legeon**  
Quality Assurance Engineer | multimedia computer engineering

### Información de Contacto
- 📧 Email: josuelegeon@gmail.com
- 💼 LinkedIn: [linkedin.com/in/josuelegeon](https://linkedin.com/in/josuelegeon)
- 🐙 GitHub: [github.com/josuelegeon](https://github.com/josuelegeon)
- 🌐 Portfolio: [josuelegeon.dev](https://josuelegeon.)



## Licencia

Este proyecto es de carácter **educativo y de portafolio personal**. La aplicación testeada (Prestashop Demo) es propiedad de PrestaShop SA. Este repositorio solo contiene documentación de testing con fines demostrativos.

**© 2024 Josué Legeon - Todos los derechos reservados sobre la documentación**

---

## Agradecimientos

- **PrestaShop SA** - Por proporcionar el ambiente demo público
- **Comunidad de QA** - Por las mejores prácticas y recursos
- **ISTQB** - Por los estándares de testing profesional

---

## Notas Finales

> Este proyecto representa un **ciclo completo de testing manual profesional**, desde la planificación hasta el cierre, demostrando habilidades end-to-end en Quality Assurance. Cada documento, caso de prueba y reporte fue creado siguiendo estándares de la industria.

**Si este proyecto te resulta útil, considera darle una estrella en GitHub**

---

**Última actualización:** Noviembre 2024  
**Versión:** 1.0  
**Estado del Proyecto:** ✅ Completado

---

<div align="center">

### 📬 ¿Preguntas o Feedback?

Si tienes preguntas sobre este proyecto o estás interesado en discutir oportunidades de QA, ¡no dudes en contactarme!

[📧 Enviar Email](mailto:josuelegeon.com) | [💼 Ver LinkedIn](https://linkedin.com/in/josuelegeon) | [🐙 GitHub Profile](https://github.com/josuelegeon)

</div>


