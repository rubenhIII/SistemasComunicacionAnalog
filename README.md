# Sistemas de Comunicación Analógica

Repositorio de apoyo para la materia **Sistemas de Comunicación
Analógica**, correspondiente al programa educativo de **Ingeniería en
Electrónica**.

> **Nota:** Este repositorio complementa el trabajo realizado durante el
> curso. El material disponible puede incluir notas, presentaciones,
> simulaciones, ejercicios, prácticas y proyectos desarrollados para
> apoyar los contenidos de la asignatura.

## 🎯 Propósito de la materia

El curso tiene un enfoque **teórico-práctico** y aborda los fundamentos
de la transmisión de señales mediante sistemas de comunicación
analógica.

Al finalizar el curso, el estudiante deberá ser capaz de **aplicar
conceptos de modulación analógica a la propagación de ondas
electromagnéticas, antenas y satélites**, así como aplicar estrategias
de diseño para la transmisión de señales eléctricas, audio y video,
desarrollando pensamiento crítico, autonomía y sentido ético.

## 📚 Contenido del curso

### Unidad I --- Fundamentos de audio, video y sistemas de comunicación

-   Naturaleza del sonido, decibel y transductores.
-   Espectro del audio.
-   Filtrado analógico:
    -   LPF --- Low-Pass Filter.
    -   HPF --- High-Pass Filter.
    -   BPF --- Band-Pass Filter.
-   Desarrollo de ecualizadores y crossovers analógicos.
-   Fundamentos de video analógico.
-   Exploración de imágenes y frecuencias horizontal/vertical.
-   Principios de cámaras analógicas y señales de color.
-   Señales compuestas NTSC y PAL.
-   Ancho de banda y canal de difusión de 6 MHz.
-   Elementos de un sistema de comunicación:
    -   Fuente.
    -   Transmisor.
    -   Canal.
    -   Receptor.
    -   Destino.
-   Ruido, distorsión e interferencia.
-   Capacidad de canal y límite de Shannon.
-   Entropía, compresión básica, temporización y sincronización.

### Unidad II --- Modulación de amplitud (AM) y recepción superheterodina

-   Representación temporal y frecuencial de señales AM.
-   Índice de modulación.
-   Espectro y distribución de potencia.
-   DSB-FC.
-   DSB-SC.
-   SSB.
-   VSB.
-   Moduladores de baja y alta potencia.
-   Moduladores en anillo y balanceados.
-   Demodulación de envolvente.
-   Demodulación coherente.
-   Receptor TRF.
-   Arquitectura del receptor superheterodino:
    -   Amplificador de RF.
    -   Mezclador.
    -   Oscilador local.
    -   Etapas de frecuencia intermedia.
    -   Detector.
-   Diseño, simulación y desarrollo de un transmisor de AM.

### Unidad III --- Modulación angular: FM y PM

-   Modulación de frecuencia (FM).
-   Modulación de fase (PM).
-   Desviación de frecuencia.
-   Índice de modulación.
-   Regla de Carson.
-   FM de banda angosta (NBFM).
-   FM de banda ancha (WBFM).
-   Funciones de Bessel.
-   Efecto del ruido en señales FM.
-   Redes de preénfasis y deénfasis.
-   Generación directa e indirecta de FM.
-   Método de Armstrong.
-   VCO.
-   Demoduladores de FM:
    -   Discriminador de frecuencia.
    -   Detector de relación.
    -   PLL.
-   Diseño, simulación e implementación de un transmisor de FM.

### Unidad IV --- Propagación de ondas electromagnéticas y antenas

-   Propagación de ondas electromagnéticas.
-   Propagación en vacío, atmósfera y otros medios.
-   Rayos y frentes de onda.
-   Densidad de potencia e intensidad de campo.
-   Ley del cuadrado inverso.
-   Atenuación.
-   Modos de propagación:
    -   Terrestre.
    -   Ionosférica.
    -   Línea de vista.
-   Parámetros fundamentales de antenas:
    -   Diagrama de radiación.
    -   Directividad.
    -   Ganancia.
    -   Eficiencia.
    -   PIRE.
    -   Polarización.
    -   Ancho de banda.
    -   Impedancia de entrada.
    -   Acoplamiento.
-   Antenas básicas:
    -   Doblete elemental.
    -   Dipolo de media onda.
    -   Antena con plano de tierra.
-   Antenas especiales:
    -   Dipolo doblado.
    -   Yagi-Uda.
    -   Log-periódica.
    -   De cuadro.
    -   Helicoidal.
    -   Reflector parabólico.
-   Construcción e implementación de un sistema de transmisión-recepción
    con antenas.

### Unidad V --- Fundamentos de comunicaciones satelitales

-   Historia y clasificación de satélites.
-   Órbitas GEO, LEO y MEO.
-   Bandas de frecuencia.
-   Satélites geoestacionarios.
-   Límites de visibilidad.
-   Patrones de radiación y huellas de cobertura.
-   Enlace ascendente (Uplink).
-   Transpondedor.
-   Enlace descendente (Downlink).
-   Multiplexación analógica FDM/FM.
-   Análisis de un sistema para transmisión de señales eléctricas, audio
    y video.

## 🧪 Enfoque práctico

El curso contempla actividades de análisis, simulación, diseño e
implementación. Entre los desarrollos prácticos establecidos en el
programa se encuentran:

-   Diseño e implementación de filtros y ecualizadores analógicos.
-   Análisis y simulación de sistemas de modulación AM.
-   Diseño, simulación y desarrollo de un transmisor de AM.
-   Diseño, simulación e implementación de un transmisor de FM.
-   Diseño y caracterización de antenas.
-   Implementación de sistemas de transmisión-recepción.
-   Análisis de enlaces de comunicación satelital.

El aprendizaje se apoya en la resolución de problemas, problemas
abiertos, diseño de prácticas y desarrollo de proyectos.

## 📂 Organización del repositorio

``` text
.
├── README.md
├── unidad-01-audio-video-comunicacion/
│   ├── notas/
│   ├── presentaciones/
│   ├── simulaciones/
│   └── ejercicios/
├── unidad-02-am/
│   ├── notas/
│   ├── presentaciones/
│   ├── simulaciones/
│   ├── ejercicios/
│   └── proyecto/
├── unidad-03-fm-pm/
│   ├── notas/
│   ├── presentaciones/
│   ├── simulaciones/
│   ├── ejercicios/
│   └── proyecto/
├── unidad-04-propagacion-antenas/
│   ├── notas/
│   ├── presentaciones/
│   ├── simulaciones/
│   ├── ejercicios/
│   └── proyecto/
├── unidad-05-comunicaciones-satelitales/
│   ├── notas/
│   ├── presentaciones/
│   ├── simulaciones/
│   └── ejercicios/
├── practicas/
├── proyecto-final/
└── referencias/
```

## 📊 Evaluación

De acuerdo con el programa de materia, la evaluación se distribuye de la
siguiente manera:

  Componente                        Porcentaje
  ------------------------------- ------------
  1.er parcial teórico-práctico           15 %
  2.º parcial teórico-práctico            20 %
  3.er parcial teórico-práctico           25 %
  Proyecto final práctico                 20 %
  Laboratorio práctico                    20 %
  **Total**                          **100 %**

Los parciales consideran examen, tareas, exposiciones, investigaciones,
ejercicios y prácticas.


El proyecto final se evalúa tanto en equipo como individualmente.

## 📝 Proyecto final

El proyecto final contempla el desarrollo práctico de un sistema
relacionado con la transmisión de señales eléctricas, audio o video.

Los reportes debe ser en formato IEEE y deberá incluir:

1. Abstract
2. Introducción.
3. Metodología
4. Código y Resultados.
5. Conclusiones.
6. Referencias.
7. Anexos:
    -   Prompts de referencia de uso de IA generativa.

## 📖 Bibliografía básica

El programa de la asignatura señala como fuentes básicas:

1.  B. Grob, C. E. Herndon, *Televisión práctica y sistemas de video*,
    Alfaomega, 2003.
2.  D. Lopez Feo, A. Garcia, *Ingeniería del sonido: sistemas de sonido
    en directo*, Starbook, 2009.
3.  Martin S. Roden, *Analog and Digital Communication Systems*, P.H.H.,
    1996.
4.  Tomasi, *Sistemas de Comunicaciones Electrónicas*, Prentice Hall.
5.  Hood, J. L. (1999). Audio electronics (2nd ed.). Newnes.
6.  Self, D. (2010). Small signal audio design. Focal Press.
7.  Cohen, E. (1989). Audio technology essentials. SAMS.
8.  Lathi, B. P., & Ding, Z. (2009). Modern digital and analog communication systems (4th ed.). Oxford University Press.

### Bibliografía complementaria

1.  J. Zafra, *Ingeniería de sonido: conceptos, fundamentos y casos
    prácticos*, RA-MA, 2018.
2.  F. G. Stremler, *Introducción a los Sistemas de Comunicación*,
    Addison Wesley.

## 🛠️ Herramientas

Las herramientas de software y hardware utilizadas en las actividades
del repositorio pueden variar de acuerdo con la práctica o proyecto.
Cuando corresponda, cada actividad deberá indicar los programas,
simuladores, instrumentos y componentes necesarios para reproducirla.

## 📌 Requisitos previos

El programa identifica como antecedentes de esta materia:

-   Electricidad y Magnetismo.
-   Teoría Electromagnética.
-   Software de Diseño Electrónico.
-   Señales y Sistemas.

La materia es consecuente para **Sistemas de Comunicación Discreto**.

## 👨‍💻 Uso del repositorio

Este repositorio está destinado al apoyo académico de la materia. Se
recomienda recorrer los contenidos en el orden de las unidades y
utilizar las notas, ejercicios, simulaciones y prácticas como
complemento al trabajo realizado en clase.

Para reproducir una simulación o práctica, consulta primero el
`README.md` específico de la carpeta correspondiente.

## 📜 Referencia del programa

Los contenidos y la estructura general de este repositorio se basan en
el documento:

**Programa de Materia --- Sistemas de Comunicación Analógica**\
Plan de estudios: **2019**\
Semestre: **7.º**\
Actualización: **julio de 2026**

El programa corresponde al Centro de Ciencias Básicas, Departamento
Académico de Sistemas Electrónicos, Programa Educativo de Ingeniería en
Electrónica.

------------------------------------------------------------------------

> **Aviso académico:** El contenido de este repositorio tiene fines
> educativos y complementa el programa oficial de la asignatura. Para
> criterios administrativos, de evaluación o acreditación, deberá
> consultarse el programa de materia vigente y las indicaciones
> establecidas durante el curso.
