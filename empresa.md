PASO 2:

# Ficha de la Empresa: FincaSol Invernaderos S.L.

**1. Información Básica**

* **Nombre de la Empresa:** FincaSol Invernaderos S.L.
* **Sector:** Agricultura de Precisión (AgroTech).
* **Tamaño:** Mediana empresa (80 empleados, incluyendo personal de campo, operarios de maquinaria y personal de oficina).

**2. Productos y Servicios**

* **Producto Principal:** Cultivo y comercialización de tomates de alta calidad (diferentes variedades premium) para exportación.
* **Modelo de Negocio:** Cultivo intensivo en invernaderos de alta tecnología. Venta B2B (Business-to-Business) a grandes cadenas de supermercados europeas y distribuidores de hostelería.

**3. Clientes Principales**

* Cadenas de supermercados en Alemania y Reino Unido.
* Distribuidores especializados en productos gourmet.

**4. Estructura y Desafíos**

* **Área de Planta (Operaciones - OT):**
    * **Activos:** 20 hectáreas de invernaderos hidropónicos, sistemas de riego automatizado (fertirrigación), maquinaria agrícola (pequeños tractores, pulverizadores), drones para monitoreo básico.
    * **Procesos Clave:** Siembra, cuidado de la planta (riego, nutrición, control de clima), detección de plagas, cosecha y empaquetado.
    * **Desafío Principal (OT):** Uso ineficiente de recursos (agua y fertilizantes) por falta de datos en tiempo real; detección tardía de enfermedades y plagas, lo que provoca pérdidas en la cosecha.

* **Área de Negocio (Gestión - IT):**
    * **Activos:** Oficinas administrativas, software ERP para contabilidad y pedidos, hojas de cálculo para planificación de la cosecha, sistema de logística básico.
    * **Procesos Clave:** Planificación de la siembra, gestión de inventario (semillas, fertilizantes), gestión de pedidos de clientes, contabilidad, logística de exportación.
    * **Desafío Principal (IT):** Desconexión total entre la planificación (IT) y la realidad del invernadero (OT). La planificación se hace "a ciegas", basándose en promedios históricos y no en el estado real de la planta.



PASO 3:

# Listado de Tecnologías de Digitalización e IA para FincaSol S.L.

A continuación, se detallan las tecnologías seleccionadas para la transformación digital de extremo a extremo de FincaSol S.L., diferenciando su aplicación principal entre el área de Operaciones (Planta/OT) y el área de Gestión (Negocio/IT).

| N.º | Área Principal | Tecnología de IA | Justificación Específica (Respuesta al Desafío) |
| :-- | :--- | :--- | :--- |
| 1 | **Planta (OT)** | **Visión por Computadora (IA) para Detección Fitosanitaria** | **Desafío que resuelve:** Detección tardía de plagas y enfermedades.<br><br>**Solución:** Se instalarán cámaras de alta resolución en los invernaderos (fijas y montadas en drones/robots de suelo). Un modelo de IA (tipo Red Neuronal Convolucional) analizará las imágenes de las hojas en tiempo real para detectar patrones de mildiú, araña roja u otras plagas en estados incipientes, mucho antes de que el ojo humano pueda percibirlo. Esto permite una acción de control híper-focalizada, reduciendo el uso de pesticidas y la pérdida de cosecha. |
| 2 | **Planta (OT)** | **IA para la Optimización de Recursos (Fertirrigación Inteligente)** | **Desafío que resuelve:** Uso ineficiente de agua y fertilizantes.<br><br>**Solución:** Se desplegarán sensores (IoT) de humedad, conductividad eléctrica (EC) y pH en el sustrato. Los datos de estos sensores (OT) alimentarán un modelo de *Reinforcement Learning* (Aprendizaje por Refuerzo). Este modelo de IA no solo monitoriza, sino que *prescribe* y *ejecuta* de forma autónoma la mezcla exacta de agua y nutrientes que cada sector del invernadero necesita, ajustándose en tiempo real a las condiciones climáticas y al estado de la planta (detectado por la Tecnología 1). |
| 3 | **Negocio (IT)** | **Modelos Predictivos (IA) de Cosecha y Demanda** | **Desafío que resuelve:** Planificación "a ciegas" basada en promedios históricos.<br><br>**Solución:** Se crea un modelo de *Forecasting* (series temporales) que se alimenta de múltiples fuentes: 1) Los datos de salud y crecimiento de la planta (datos de OT de las Tecnologías 1 y 2). 2) Datos históricos de ventas (IT). 3) Datos externos (clima, demanda del mercado, precios en supermercados europeos). La IA predecirá con semanas de antelación el volumen exacto y la fecha de cosecha, así como la demanda esperada en los mercados de destino. |
| 4 | **Negocio (IT)** | **IA para la Planificación de la Siembra (Prescriptiva)** | **Desafío que resuelve:** Desconexión entre la gestión y la realidad del campo.<br><br>**Solución:** Esta IA utiliza la salida del Modelo Predictivo (Tecnología 3) para *recomendar* el plan de siembra óptimo. Responde a preguntas como: "¿Qué variedad de tomate debemos plantar en el Invernadero 5 el próximo mes para maximizar la rentabilidad, considerando la demanda prevista en Alemania y los costes de recursos (agua, fertilizante)?" Transforma la gestión de reactiva a prescriptiva, conectando directamente la estrategia de negocio (IT) con la orden de siembra (OT). |
