# Arquitectura de Información — Sicnia

## Estructura de páginas


| Página              | Ruta               | Propósito                                                    |
| ------------------- | ------------------ | ------------------------------------------------------------ |
| **Home**            | `/`                | Landing principal — storytelling completo de la marca        |
| **Nosotros**        | `/nosotros`        | Historia, filosofía, arquitecto y principios de construcción |
| **Proyectos**       | `/proyectos`       | Portafolio completo con filtros por estado                   |
| **Certificaciones** | `/certificaciones` | Certificaciones, prensa y documentos descargables            |


4 páginas totales.

---

## Navegación global

### Navbar

- Logo Sicnia (izquierda)
- Links: Inicio | Nosotros | Proyectos | Certificaciones
- CTA botón: "Contáctanos" (scroll al formulario del Home o abre modal)

### Footer

- Logo + tagline
- Links de navegación
- Datos de contacto
- Redes sociales (si las tienen)
- Copyright

---

## Home — Secciones en orden de scroll

El orden sigue el patrón de persuasión: **captar atención → generar confianza → mostrar capacidad → demostrar resultados → llamar a la acción**.

### 1. Hero

**Objetivo:** Captar atención en 3 segundos. Dejar claro qué es Sicnia.

- Headline potente (una frase, no un párrafo)
- Subtítulo de 1-2 líneas que expanda el headline
- CTA principal (ej. "Conoce nuestros proyectos" o "Hablemos")
- Background: puede ser visual abstracto/tech o un proyecto flagship
- Social proof con logos

### 2. Introducción / Qué es Sicnia

**Objetivo:** Dar contexto inmediato después del impacto del hero.

- Párrafo corto (3-4 líneas máximo) que explique quién es Sicnia y qué problema resuelve
- Los 3 pilares (Inmobiliaria, Ingeniería, IA) como elementos visuales — íconos o cards compactas con una línea de descripción cada uno
- Enfoque en **qué hacen**, no en historia corporativa

### 3. Servicios / Qué hacemos

**Objetivo:** Mostrar el alcance completo de capacidades.

Los 6 servicios presentados como cards o grid de íconos:

1. Estructuración y Promoción
2. Venta
3. Construcción
4. Gerencia
5. Dotación
6. Administración y Operación

Cada uno con: ícono + título + descripción de 1-2 líneas. No más.

### 4. Proyectos destacados (preview)

**Objetivo:** Mostrar resultados reales. Generar deseo.

- 3-4 proyectos máximo (los más impactantes visualmente)
- Card con imagen, nombre del proyecto, ubicación, estado
- Botón "Ver todos los proyectos" → lleva a `/proyectos`

### 5. Tipos de construcción

**Objetivo:** Reforzar capacidad técnica justo después de mostrar los servicios.

5 cards compactas:

1. Multifamiliar
2. Unifamiliar
3. VIS (Vivienda de Interés Social)
4. Institucional
5. Adecuaciones

### 6. CTA final + Formulario de contacto

**Objetivo:** Convertir. El usuario ya scrolleó, ya confía, ya vio proyectos — ahora actúa.

- Headline tipo "¿Listo para tu próximo proyecto?" o "Hablemos de tu proyecto"
- Formulario inline: Nombre, Email, Teléfono, Mensaje, botón Enviar
- Datos de contacto al lado: dirección, teléfono, email
- Mapa opcional (embed de Google Maps)

---

## Página: Nosotros (`/nosotros`)

**Objetivo:** Contar la historia y filosofía de Sicnia para quien quiere conocer más a fondo.

### 1. Historia / Quiénes somos

- Trayectoria de +10 años
- Especialidad en administración inmobiliaria y construcción sostenible
- Sistemas industrializados, sismoresistentes, ecológicos y bioclimáticos

### 2. Filosofía

- Bienestar de las personas
- Limitar impactos en el medio ambiente en construcción y operación
- Búsqueda de proveedores con sistemas de alto desempeño
- Confort de usuarios y sostenibilidad ambiental

### 3. Arquitecto Didier Rincón

- Diseñador de los proyectos de Sicnia
- Especial cuidado en el bienestar de las personas
- Implantación en el entorno

### 4. Principios de construcción

- Sostenibilidad
- Buena relación con el entorno
- Diseño funcional
- Confort acústico y térmico
- Valorización
- Uso de mejores materiales

---

## Página: Proyectos (`/proyectos`)

**Objetivo:** Portafolio completo, navegable y filtrable.

- Filtros por estado: Todos / En venta / En construcción / En operación / Completados
- Grid de cards con: imagen principal, nombre, ubicación, estrato, unidades, badge de estado

### Proyectos conocidos


| Proyecto              | Ubicación   | Estrato | Unidades        | Estado            |
| --------------------- | ----------- | ------- | --------------- | ----------------- |
| Bahía 57              | Bogotá      | 5       | 12              | En venta          |
| Prado 134             | Bogotá      | 3       | 28              | En venta          |
| San Nicolás Plaza     | Bogotá      | 5       | 15              | En construcción   |
| Calle 92              | Bogotá      | 6       | 4               | Vendido           |
| FUCS                  | Bogotá      | 4       | Institucional   | En construcción   |
| Arena Suites          | Bogotá      | —       | 28 aptos (26m²) | En operación      |
| Flat 119              | Bogotá      | 6       | 37              | En promoción      |
| ECO Ciudadela Betania | Pensilvania | VIP     | 94              | En estructuración |


---

## Página: Certificaciones (`/certificaciones`)

**Objetivo:** Página de confianza para el usuario que necesita más antes de decidir.

### 1. Certificaciones

- Edge, Camacol, etc. con descripción de qué significa cada una

### 2. Prensa

- Artículo Portafolio
- Artículo revista Asocreto
- Presentados como cards con extracto

### 3. Documentos descargables

- RUT
- Cámara de Comercio
- Certificación Bancaria
- Hoja de vida
- Oferentes de vivienda
- Obras ejecutadas

---

## Resumen visual

```
NAVBAR: [Logo] ---- Inicio | Nosotros | Proyectos | Certificaciones ---- [Contáctanos]

HOME /
  ├── Hero (headline + CTA)
  ├── Intro / 3 pilares
  ├── Social proof (logos aliados)
  ├── Servicios (6 cards)
  ├── Tipos de construcción (5 cards)
  ├── Proceso (timeline)
  ├── Proyectos destacados (3-4 + "Ver todos")
  └── CTA + Formulario de contacto

NOSOTROS /nosotros
  ├── Historia / Quiénes somos
  ├── Filosofía
  ├── Arquitecto Didier Rincón
  └── Principios de construcción

PROYECTOS /proyectos
  ├── Filtros por estado
  └── Grid de project cards

CERTIFICACIONES /certificaciones
  ├── Certificaciones
  ├── Prensa
  └── Documentos descargables

FOOTER: [Logo] [Nav] [Contacto] [RRSS]
```

