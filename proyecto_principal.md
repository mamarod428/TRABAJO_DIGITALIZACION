# Proyecto 1: Diseño de la Transformación Digital de un Sector usando IA

![Logo de la Empresa](LogoEmpresa.png)

## Introducción al Proyecto

Bienvenido al repositorio del proyecto de transformación digital para **AgroTech Solutions**.

Este trabajo aborda el diseño de una arquitectura tecnológica integral que unifica los entornos de **Planta (OT)** y **Negocio (IT)**. A través de la implementación de Inteligencia Artificial, Visión por Computador y Big Data, se busca resolver los problemas de desconexión entre la producción y la demanda, mejorando la competitividad y sostenibilidad de la empresa en el sector agroalimentario.

El proyecto cubre desde el análisis de la empresa y la selección de tecnologías, hasta el diseño de la arquitectura de datos y la reflexión sobre el futuro del sector.

---

## 🗂️ Índice de Contenidos

Navega a través de los diferentes módulos del proyecto haciendo clic en los enlaces a continuación:

### [1. Ficha de la Empresa y Contexto 📄](ficha_empresa.md)
* **Contenido:** Perfil corporativo de AgroTech Solutions, características del sector y definición del problema ("Pain Point") a resolver.

### [2. Selección de Tecnologías (IT/OT) ⚙️](listado_tecnologias.md)
* **Contenido:** Análisis del Criterio 1e. Justificación detallada de las tecnologías seleccionadas para Planta (Visión Artificial, IIoT) y Negocio (Forecasting, RPA).

### [3. Diagrama de Arquitectura y Estructura 📊](diagrama_mermaid.md)
* **Contenido:** Análisis del Criterio 1b. Visualización gráfica del flujo de datos y explicación de la convergencia IT/OT y el impacto organizacional.

### [4. Propuesta de Valor y Transformación Digital 🚀](propuesta_transformacion_digital.md)
* **Contenido:** Análisis del Criterio 1g. Detalle de las ventajas operativas (Eficiencia, JIT) y competitivas (Trazabilidad, Agilidad) de la propuesta.

### [5. Reflexión Final: Impacto de la IA 🧠](reflexion_final.md)
* **Contenido:** Análisis de los Criterios 4c, 4d y 4f. Visión sobre la importancia presente y futura de la IA, comparativa con otros sectores (Automoción/Banca) y el futuro de la seguridad alimentaria.

---

*Proyecto realizado por: [Manuel Amado, Pablo Reyes, Fran Falcón y Daniel Espinosa]*
*Fecha: Noviembre 2025*

# Proyecto 1: Diseño de la Transformación Digital con IA en "AgroTech Solutions"

## 1. Ficha de la Empresa y Contexto del Sector
**Empresa:** AgroTech Solutions (Empresa Ficticia)
**Sector:** Industria Agroalimentaria (Subsector: Conservas Vegetales y Platos Preparados).

### Perfil Corporativo
* **Tamaño:** Mediana empresa (200 empleados: 150 en planta, 50 en oficinas).
* **Productos:** Conservas de alta gama (espárragos, alcachofas) y cremas de verduras listas para comer.
* **Clientes:** Grandes Cadenas de Distribución (B2B) y exportación a mercado europeo (Alemania, Francia).

### Problemática Inicial (El "Pain Point")
La empresa sufre de una desconexión clásica: el departamento de ventas cierra acuerdos que fábrica no puede cumplir a tiempo, y fábrica produce stock que a veces no se vende, generando desperdicio. Además, el control de calidad es manual, lo que provoca "falsos positivos" y reclamaciones de clientes exigentes.

---

## 2. Selección y Justificación de Tecnologías (Criterio 1e)
*Se han seleccionado tecnologías maduras que permiten una diferenciación clara entre los entornos de Operación (OT) y Tecnologías de la Información (IT).*

### A. Digitalización en Planta (Ámbito OT - Operational Technology)

#### 1. Visión Artificial Hiperespectral para Control de Calidad
* **Descripción Técnica:** Implementación de cámaras capaces de analizar el espectro de luz no visible, conectadas a una red neuronal convolucional (CNN). El sistema escanea el 100% de la producción en la cinta transportadora a alta velocidad.
* **Justificación (Criterio Excelente):** A diferencia del ojo humano, que se fatiga y es subjetivo, esta IA detecta golpes internos en la verdura o cuerpos extraños (piedras, insectos) antes del envasado. Esto **elimina el riesgo de alertas sanitarias** y garantiza una calidad uniforme.

#### 2. Mantenimiento Predictivo mediante IIoT (Industrial IoT)
* **Descripción Técnica:** Instalación de sensores de vibración, temperatura y consumo eléctrico en activos críticos (autoclaves y etiquetadoras). Un algoritmo de Machine Learning analiza patrones anómalos para predecir fallos.
* **Justificación (Criterio Excelente):** Permite pasar de un mantenimiento reactivo (arreglar cuando se rompe) a uno proactivo. Esto mejora el **OEE (Eficiencia General de los Equipos)**, asegurando que la fábrica no se detenga en plena campaña de recolección, cuando la materia prima es perecedera.

### B. Digitalización en Negocio (Ámbito IT - Information Technology)

#### 3. Forecasting Avanzado (Predicción de Demanda con IA)
* **Descripción Técnica:** Motor de IA que integra datos históricos del ERP, tendencias de Google Trends, datos meteorológicos y calendario de festivos para proyectar ventas futuras con alta precisión.
* **Justificación (Criterio Excelente):** En el sector agro, el inventario caduca. Esta tecnología permite **ajustar las compras de materia prima al milímetro**, reduciendo el capital inmovilizado en almacén y minimizando el desperdicio alimentario (sostenibilidad económica).

#### 4. RPA Cognitivo (Automatización Robótica de Procesos)
* **Descripción Técnica:** "Bots" de software equipados con OCR (Reconocimiento Óptico de Caracteres) y NLP (Procesamiento de Lenguaje Natural) para gestionar la entrada de pedidos y facturas de proveedores.
* **Justificación (Criterio Excelente):** Automatiza tareas administrativas repetitivas de bajo valor. Permite que el equipo humano se dedique a tareas de **valor añadido**, como la negociación con proveedores o la atención personalizada a clientes clave.

---

## 3. Estructura IT/OT y Convergencia

![Diagrama de Arquitectura IT/OT](diagrama.png)

### Análisis de la Relación IT/OT
Para alcanzar la calificación de excelencia, es vital entender que la transformación no es solo instalar tecnología, sino conectar dos mundos:

1.  **Flujo Ascendente (OT hacia IT):** La planta deja de ser una "caja negra". Los datos de producción real, mermas y tiempos de parada (OT) fluyen hacia el ERP (IT) en tiempo real. Esto permite a la dirección financiera conocer el coste exacto de cada lote producido al instante.
2.  **Flujo Descendente (IT hacia OT):** Las predicciones de ventas (IT) se convierten automáticamente en Órdenes de Fabricación que se envían a los PLC de las máquinas (OT), ajustando la velocidad de línea o los turnos de trabajo sin intervención manual.

### Impacto Organizacional y Cultural
La implementación de esta arquitectura provoca un cambio profundo en el organigrama:
* **Reskilling (Reciclaje profesional):** Los operarios de línea evolucionan a "supervisores de procesos digitales". Ya no inspeccionan la verdura, inspeccionan que la IA esté funcionando bien.
* **Toma de decisiones:** Se elimina la "intuición" de los jefes de planta. Las decisiones sobre qué producir y cuándo mantener una máquina se basan puramente en datos objetivos (Data-Driven Decision Making).

---

## 4. Propuesta de Transformación Digital de Extremo a Extremo (Criterio 1g)

Esta propuesta integra Planta y Negocio para crear una cadena de valor inteligente.

### Ventajas Operativas (Eficiencia Interna)
* **Sincronización JIT (Just-in-Time):** Al conectar la predicción de demanda (IT) con la planta (OT), la materia prima llega del campo justo cuando la línea está lista para procesarla. Esto reduce drásticamente los costes de almacenamiento refrigerado.
* **Reducción de la No-Calidad:** La visión artificial en planta reduce las devoluciones de clientes en un 95%, lo que tiene un impacto directo en la cuenta de resultados (menos abonos y menos costes logísticos de retorno).

### Ventajas Competitivas (Posicionamiento en el Mercado)
* **Trazabilidad y Transparencia Total:** Gracias a la digitalización extremo a extremo, AgroTech puede ofrecer al consumidor un código QR en el frasco que muestre la historia del producto: desde qué día se recolectó hasta sus parámetros de calidad. Esto justifica un precio "Premium" frente a la competencia low-cost.
* **Agilidad ante el Mercado:** Si la IA de Negocio detecta un cambio brusco en las tendencias de consumo (ej. aumento repentino de demanda de productos "bio"), la planta puede reconfigurarse ágilmente para priorizar esas referencias, ganando cuota de mercado a competidores más lentos y analógicos.

---

## 5. Reflexión: El Impacto de la IA Presente y Futuro (Criterios 4c, 4d, 4f)

### Importancia Presente y Futura (4c)
En el **presente**, la IA es una herramienta de supervivencia operativa: permite mantener márgenes en un entorno de inflación de costes y escasez de mano de obra. En el **futuro**, la IA será generativa y creativa: diseñará nuevas recetas basándose en datos moleculares de sabor y preferencias de consumidores, y gestionará cadenas de suministro autónomas y circulares.

### Identificación y Comparativa de Sectores (4d)
* **Sector Automoción:** Es el referente histórico (Industria 3.0 y 4.0). Usan IA masiva en robótica colaborativa (Cobots). Comparado con AgroTech, su entorno es más controlado y rígido.
* **Sector Retail/E-commerce:** Líderes en IA de negocio (recomendación de productos, como Amazon). Su uso es puramente digital (IT).
* **Comparativa con nuestro Proyecto:** El sector agroalimentario es más complejo que el Retail porque maneja productos vivos y perecederos, y más difícil que la automoción porque las materias primas son irregulares (ninguna alcachofa es igual a otra). Por eso, la IA en nuestro sector tiene un potencial de transformación mayor y más desafiante.

### Influencia Específica en el Sector Agroalimentario (4f)
* **Impacto Actual:** La IA está democratizando la eficiencia. Antes, solo gigantes como Nestlé podían automatizar; hoy, empresas medianas como AgroTech usan IA en la nube (SaaS) para competir globalmente.
* **Visión de Futuro:** Nos dirigimos hacia la **"Agricultura y Procesamiento de Precisión"**. En el futuro, la fábrica estará conectada directamente con el campo (drones y tractores autónomos). La IA ajustará la cosecha en función de la capacidad real de la fábrica en ese segundo, eliminando por completo el desperdicio de alimentos y agua, convirtiendo al sector en un referente de sostenibilidad global.
