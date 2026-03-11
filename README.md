# 📋 Instructivo: Cómo usar Claude Cowork
### Guía para el personal administrativo

---

> **¿Qué es Cowork?**
> Claude Cowork es tu asistente de trabajo digital. A diferencia del chat normal, Cowork puede **hacer el trabajo por vos**: organiza carpetas, crea planillas, redacta documentos y mucho más, de forma autónoma. Vos le explicás qué necesitás, él lo hace, y vos revisás el resultado.

---

## 📌 Índice

1. [Requisitos para usar Cowork](#1-requisitos)
2. [Cómo acceder a Cowork](#2-cómo-acceder)
3. [La interfaz de Cowork](#3-la-interfaz)
4. [Cómo darle acceso a una carpeta](#4-acceso-a-carpetas)
5. [Tareas que podés hacer](#5-tareas)
6. [Ejemplos paso a paso](#6-ejemplos)
7. [Conectores: vincular otras apps](#7-conectores)
8. [Tareas programadas](#8-tareas-programadas)
9. [Seguridad y permisos](#9-seguridad)
10. [Errores comunes y soluciones](#10-errores-comunes)
11. [Consejos para escribir buenas instrucciones](#11-consejos)

---

## 1. Requisitos

Antes de empezar, verificá que tenés todo lo necesario:

| Requisito | Detalle |
|---|---|
| 💻 **Sistema operativo** | Windows o macOS (no funciona en web ni celular) |
| 🔑 **Plan de Claude** | Pro, Max, Team o Enterprise (no funciona en plan gratuito) |
| 📦 **App instalada** | Claude Desktop (descargala en [claude.com/download](https://claude.com/download)) |
| 🌐 **Conexión a internet** | Necesaria durante toda la sesión |

> ⚠️ **Importante:** Si tenés Mac con procesador Intel (anterior a 2020), la pestaña Cowork no va a aparecer. Funciona solo en Mac con chip Apple Silicon (M1 o posterior). En Windows, funciona en todos los equipos compatibles.

---

## 2. Cómo acceder

### Paso a paso:

```
1. Abrí la app Claude Desktop en tu computadora
2. En la barra superior, vas a ver tres pestañas: Chat | Cowork | Code
3. Hacé clic en "Cowork"
4. ¡Listo! Ya estás en modo Cowork
```

> 💡 **¿No ves la pestaña Cowork?** Verificá que tu plan sea pago y que la app esté actualizada a la última versión.

---

## 3. La interfaz

Cuando abrís Cowork, vas a encontrar:

```
┌─────────────────────────────────────────────────────┐
│  Chat  |  [COWORK]  |  Code                         │
├─────────────────────────────────────────────────────┤
│                                                     │
│   Sugerencias de tareas:                            │
│   📁 Organizar archivos    📊 Procesar datos        │
│   📄 Redactar informe      📧 Revisar mails         │
│                                                     │
│   ─────────────────────────────────────────────    │
│                                                     │
│   📂 Trabajar en una carpeta  [checkbox]            │
│                                                     │
│   ┌─────────────────────────────────────────────┐  │
│   │ Describí la tarea que querés que haga...    │  │
│   └─────────────────────────────────────────────┘  │
│                                          [Enviar]   │
└─────────────────────────────────────────────────────┘
```

**Las partes más importantes:**
- **Checkbox "Trabajar en una carpeta"**: Esto es lo que diferencia Cowork del chat normal. Al activarlo, Claude puede acceder y modificar archivos en tu computadora.
- **Caja de texto**: Acá describís en palabras simples qué querés que haga.
- **Sidebar izquierdo**: Muestra tus sesiones anteriores y tareas programadas.

---

## 4. Acceso a carpetas

Este es el paso más importante. Cowork necesita que le des permiso para ver tu carpeta.

### Cómo hacerlo:

1. Marcá el checkbox **"Trabajar en una carpeta"**
2. Va a abrirse un explorador de archivos: **seleccioná la carpeta** que querés usar
3. Aparece un cuadro de diálogo con dos opciones:

```
┌──────────────────────────────────────────┐
│  ¿Permitir acceso a "Documentos/Ventas"? │
│                                          │
│  Claude podrá leer, editar y crear       │
│  archivos en esta carpeta.               │
│                                          │
│  [Permitir una vez]  [Permitir siempre]  │
└──────────────────────────────────────────┘
```

- **"Permitir una vez"**: Solo para esta sesión. Ideal si es la primera vez o para tareas puntuales.
- **"Permitir siempre"**: Recuerda el permiso. Ideal para carpetas que usás seguido.

> ⚠️ **Nunca le des acceso a carpetas con información muy sensible** como contraseñas, datos bancarios o documentos legales confidenciales, NUNCA.

---

## 5. Tareas que podés hacer

### 📁 Organización de archivos
- Ordenar una carpeta caótica en subcarpetas por tipo de archivo
- Renombrar archivos con nombres descriptivos y consistentes
- Eliminar duplicados (previa aprobación tuya)
- Limpiar la carpeta de Descargas

### 📊 Planillas y datos
- Crear una planilla Excel desde cero con datos que le describís
- Extraer información de fotos de facturas o tickets y volcarla en una hoja
- Consolidar datos de varios archivos en uno solo
- Generar tablas con fórmulas funcionando

### 📄 Documentos Word / PDF
- Redactar informes a partir de notas dispersas
- Crear presentaciones PowerPoint
- Combinar varios PDFs en uno
- Rellenar formularios PDF

### 🔍 Investigación
- Buscar información en la web y armar un informe resumido
- Comparar precios o proveedores de distintos sitios
- Revisar múltiples documentos y extraer lo más relevante

### 📧 Comunicaciones (con conectores)
- Redactar borradores de emails basados en notas
- Revisar hilos de Slack y resumir decisiones tomadas
- Crear tareas en Notion o Asana a partir de actas de reunión

---

## 6. Ejemplos paso a paso

### Ejemplo 1: Organizar la carpeta de Descargas

**Situación:** Tenés cientos de archivos mezclados en la carpeta Descargas y no encontrás nada.

**Cómo hacerlo:**

```
Paso 1: Abrí Cowork y marcá "Trabajar en una carpeta"
Paso 2: Seleccioná tu carpeta "Descargas"
Paso 3: Escribí esta instrucción:
```

> *"Organizá mi carpeta de Descargas. Revisá el contenido y proponé un plan: qué subcarpetas crear, cómo ordenar los archivos y cuáles podrían eliminarse. Mostrame el plan antes de hacer cualquier cambio, y solo procedé si yo apruebo."*

**Qué va a pasar:**
1. Claude revisa todos tus archivos
2. Te presenta un plan (ej: crear carpetas "Facturas", "Fotos", "Instaladores", etc.)
3. Vos aprobás o ajustás el plan
4. Claude ejecuta los cambios

---

### Ejemplo 2: Crear una planilla de gastos desde fotos de tickets

**Situación:** Tenés 20 fotos de tickets de compras y necesitás armar un resumen de gastos del mes.

**Cómo hacerlo:**

```
Paso 1: Guardá todas las fotos en una carpeta (ej: "Tickets Marzo")
Paso 2: Abrí Cowork y dale acceso a esa carpeta
Paso 3: Escribí:
```

> *"En esta carpeta hay fotos de tickets de compra del mes de marzo. Revisá cada imagen, extraé la fecha, el comercio, el concepto y el monto de cada una, y creá una planilla Excel llamada 'Gastos_Marzo.xlsx' con esos datos. Al final agregá una fila con el total."*

**Resultado:** Vas a tener una planilla lista con todos los datos extraídos automáticamente.

---

### Ejemplo 3: Redactar un informe desde notas dispersas

**Situación:** Tenés apuntes de varias reuniones guardados en distintos archivos de texto y necesitás hacer un informe ejecutivo.

**Instrucción de ejemplo:**

> *"En esta carpeta hay notas de reuniones del mes de febrero. Leé todos los archivos, identificá los temas principales, las decisiones tomadas y los próximos pasos acordados. Con eso, redactá un informe ejecutivo en Word con estas secciones: Resumen, Decisiones clave, Pendientes y Próximos pasos. El tono debe ser formal."*

---

### Ejemplo 4: Tarea de múltiples pasos (el poder real de Cowork)

**Situación:** Necesitás preparar el informe mensual de ventas.

**Instrucción de ejemplo:**

> *"Tengo en esta carpeta: el archivo de ventas del mes en Excel, las notas de las reuniones del equipo en Word, y algunas fotos de presentaciones. Necesito que: 1) Analices los datos de ventas y calcules los totales por producto y por vendedor. 2) Leas las notas de reuniones y extraigas los comentarios sobre rendimiento. 3) Combines todo en un informe Word profesional con gráficos, tabla de resultados y una sección de conclusiones. Guardalo como 'Informe_Ventas_Marzo.docx'."*

**En un chat normal esto serían 5 prompts distintos. En Cowork, lo hacés en uno.**

---

## 7. Conectores

Los conectores vinculan Cowork con otras aplicaciones que ya usás.

### Conectores disponibles:
- 📬 **Gmail** – Leer, redactar y organizar emails
- 💬 **Slack** – Resumir conversaciones, extraer decisiones
- 📝 **Notion** – Crear y editar páginas
- ✅ **Asana** – Gestionar tareas y proyectos
- 📂 **Google Drive** – Acceder a archivos en la nube
- 🌐 **Claude in Chrome** – Navegar sitios web, llenar formularios

### Cómo activar un conector:

```
1. En Claude Desktop, andá a Configuración (⚙️)
2. Buscá la sección "Conectores"
3. Hacé clic en el conector que querés activar
4. Seguí las instrucciones para vincular tu cuenta
5. El conector ya queda disponible en tus sesiones de Cowork
```

### Ejemplo con Gmail:

> *"Revisá mis emails de hoy. Identificá cuáles requieren una respuesta urgente, hacé un resumen de cada uno y redactá borradores de respuesta para los tres más importantes."*

---

## 8. Tareas programadas

Podés pedirle a Cowork que ejecute tareas automáticamente, sin que vos tengas que iniciarlas cada vez.

### Cómo programar una tarea:

En el cuadro de texto de Cowork, escribí `/schedule` al principio de tu instrucción:

> *"/schedule Todos los lunes a las 8am, revisá la carpeta 'Pendientes', organizá los archivos nuevos y enviame un resumen de lo que hay para hacer esta semana."*

### Ver y gestionar tareas programadas:
- En el sidebar izquierdo, hacé clic en **"Programadas"**
- Ahí podés ver, pausar o eliminar tus tareas automáticas

---

## 9. Seguridad y permisos

Cowork está diseñado para ser seguro, pero es importante entender cómo funciona:

### ✅ Lo que hace Claude para protegerte:
- **Pide aprobación antes de eliminar archivos**: Siempre te muestra qué va a borrar y espera tu "ok"
- **Muestra el plan antes de ejecutar**: Podés revisar y ajustar antes de que empiece
- **Corre en un entorno aislado**: No puede acceder a carpetas que no le hayas dado permiso
- **El historial se guarda solo en tu computadora**, no en los servidores de Anthropic

### ⚠️ Buenas prácticas:
- Siempre revisá el plan que te propone antes de aprobarlo
- Empezá con "Permitir una vez" hasta que conozcas bien la herramienta
- No le des acceso a carpetas con contraseñas o datos bancarios sin necesidad
- Ante cualquier duda, podés interrumpir una tarea en cualquier momento

### 🛑 Cómo detener una tarea en curso:
Simplemente escribí en el chat: *"Detené lo que estás haciendo"* o hacé clic en el botón de pausa que aparece mientras Claude trabaja.

---

## 10. Errores comunes y soluciones

| Problema | Causa probable | Solución |
|---|---|---|
| No aparece la pestaña "Cowork" | Plan gratuito o app desactualizada | Verificá tu plan y actualizá la app |
| Cowork no aparece en Mac | Mac con chip Intel | Cowork solo funciona en Mac M1 o posterior |
| Claude no puede leer mis archivos | No le diste acceso a la carpeta | Marcá el checkbox "Trabajar en una carpeta" |
| El resultado no es lo que esperaba | Instrucción muy vaga | Sé más específico (ver sección 11) |
| Claude pregunta demasiado | Tarea con muchos pasos ambiguos | Dividí la tarea o dá más contexto inicial |
| La app se cierra y pierde la tarea | La app debe quedar abierta | No cerrés la app mientras Cowork trabaja |

---

## 11. Consejos para escribir buenas instrucciones

La calidad del resultado depende mucho de cómo describís la tarea. Estos consejos te van a ayudar:

### ✅ Sé específico con el resultado esperado

❌ *"Organizá mis archivos"*
✅ *"Organizá los archivos de la carpeta 'Proyectos' en subcarpetas por año y cliente. Usá el formato: 'AAAA_NombreCliente'"*

### ✅ Indicá el formato de salida

❌ *"Hacé un resumen"*
✅ *"Hacé un resumen en Word con estas secciones: Introducción, Puntos clave y Conclusión. Máximo 2 páginas."*

### ✅ Pedile que te muestre el plan primero

*"Antes de hacer cualquier cambio, mostrame el plan y esperá mi aprobación."*

### ✅ Dá contexto sobre tu rol

En Configuración > Cowork > Instrucciones globales, podés escribir algo como:
> *"Soy asistente administrativa de una empresa de logística. Prefiero documentos formales en español rioplatense, con formato profesional."*

### ✅ Usá ejemplos cuando sea posible

*"El nombre de los archivos debe seguir este formato: '2026-03_NombreProveedor_Factura' (ejemplo: '2026-03_Sodimac_Factura')"*

---

## 📞 ¿Necesitás ayuda?

- **Centro de soporte oficial:** [support.claude.com](https://support.claude.com)
- **Tutoriales en video:** [claude.com/resources](https://claude.com/resources)
- **Reportar un problema:** Botón 👎 en cualquier respuesta de Claude

---

*Instructivo preparado para uso interno. Versión: Marzo 2026.*
*Basado en Claude Cowork — Research Preview (disponible en planes Pro, Max, Team y Enterprise)*