# Análisis de Delitos de Mayor Connotación Social (DMCS) en Chile (2016–2020-2024)

Este repositorio documenta el proceso de obtención, preparación y análisis de datos de seguridad pública en Chile, con foco en la evolución de los Delitos de Mayor Connotación Social (DMCS) antes y después de la pandemia.

---

# Pregunta a responder

¿Cómo ha evolucionado la composición y severidad de los delitos violentos en Chile en el período pre y post pandemia?**

---

# Estructura del repositorio

El repositorio contiene:

- Los archivos Excel originales correspondientes a los años 2016, 2020 y 2024, descargados desde fuentes públicas oficiales. Estos archivos se mantienen por separado y sin modificaciones.
- Archivo consolidado que integra los datos de los tres años analizados, luego del proceso de limpieza y transformación. Este es el utilizado directamente para la construcción del dashboard.

---

## Preparación y transformación de datos

El proceso de preparación de datos incluyó las siguientes etapas:

1. Selección: Se filtraron exclusivamente los Delitos de Mayor Connotación Social (DMCS), de acuerdo con la clasificación oficial.

2. Limpieza: Eliminación de notas explicativas y filas de totales nacionales. Además, estandarización de nombres de variables y regiones.
     
3. Transformación: Conversión de la estructura original (regiones en columnas) a formato largo, para facilitar el análisis temporal y comparativo.  

4. Consolidación: Integración de los datos correspondientes a los años 2016, 2020 y 2024 en una unica planilla.

## Visualización

El análisis se presenta mediante un dashboard interactivo desarrollado en Tableau, disponible en el siguiente enlace:
*https://public.tableau.com/views/AnlisisdeDelitosDMCSChile2016-2024/Dashboard1?:language=es-ES&:sid=&:redirect=auth&publish=yes&showOnboarding=true&:display_count=n&:origin=viz_share_link*

---

## Principales hallazgos

- La cantidad total de DMCS disminuye levemente comparando el 2016 y 2024 (-9,8%), lo que indica que no hay un aumento generalizado del delito, sino cambios en su composición.
- El índice de severidad alcanza un 48,3%, lo que sugiere una alta participación relativa de delitos violentos dentro del total de delitos analizados, especialmente en el período post pandemia.
- Tras la baja que se dio en la pandemia, se observa un repunte de los delitos para 2024, recuperando niveles cercanos a los de 2016.
- Los robos concentran la mayor parte de los DMCS en todos los períodos, destacando el robo en lugar habitado y no habitado como las tipologías más frecuentes a lo largo del tiempo.
- La Región Metropolitana concentra una proporción significativamente mayor de delitos en comparación con el resto del país.
  
---


###  Fuente de datos

Estadísticas policiales y judiciales. (s. f.). Default. https://www.ine.gob.cl/estadisticas/sociales/seguridad-publica-y-justicia/estadisticas-policiales-y-judiciales
