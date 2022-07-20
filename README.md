<h1>SISTEMA DE GESTIÓN DE PAVIMENTOS BASADO EN INTELIGENCIA ARTIFICIAL</h1>

**¿Por qué queremos hacerlo?**
<br>
- Factor económico (inversión alta en mantenimiento correctivo e incremento vida útil carretera).
- Factor medioambiental (alto consumo de energía y emisiones GHG para mantenimiento correctivo).
- Factor social (comfort y seguridad).



**¿En qué nos vamos a centrar?**
<br>
- **Deterioros superficiales** (*Pavement Condition Index*).
- Rugosidad (*International Roughness Index*).
- Adecuación estructural (*Structural Number*).
- Seguridad (*Skid Resistance*).

**¿Cómo estamos abordando cada fase del sistema de gestión de pavimentos?**
<br>

- **Colección de imágenes**: Cámara montada en vehículo de bajo coste (600 euros), rápida adquisición y alta calidad -> Imágenes georeferenciadas.
  - <span style="color:red">COLABORACIÓN</span>: Adquisición de imágenes en las zonas de interés de la demarcación.
  - <span style="color:red">COLABORACIÓN</span>: Tener una base de datos =  avance (lo más próximo es el programa LTPP de la FHWA).
<p align="center">
  <img src="WhatsApp Image 2022-05-27 at 11.29.33 AM.jpeg" width="350" title="hover text">
  <img src="47.png" width="350" title="hover text">
</p>


- **Análisis de imágenes**: Detección de objetos y Segmentación Semántica.
  - <span style="color:red">COLABORACIÓN</span>: Apoyo en el etiquetado de deterioros.
    - **DETECCIÓN DE OBJETOS.** (Dónde y qué tipo).
      <p align="center">
        <img src="val_batch0_labels.jpg" width="350" title="hover text">
      </p>
    
    - **SEGMENTACIÓN SEMÁNTICA** (Área y severidad).
      <p align="center">
        <img src="47_1.png" width="350" title="hover text">
      </p>
- **Elaboración de planes de mantenimiento óptimo y estudios de coorrelación**: Índice de condición del pavimento.

  - Esta herramienta será creada para administración de carreteras y que mejor SOLUTION/PROBLEM fit que seáis vosotros quién propogáis vuestras necesidades para que nosotros os demos análisis: correlación IRI con PCI, deflexión con PCI, tasa de accidentes con PCI,etc.
  - Creación de una herramienta donde el cuerpo de operarios vuelque las imágenes y automáticamente pueda ver el reporte.




