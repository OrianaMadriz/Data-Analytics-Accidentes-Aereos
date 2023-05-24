# Proyecto de Análisis de Datos de Accidentes Aéreos: Oriana Madriz

## Introducción
En este proyecto de Data Analytics, asumiremos el rol de un Data Analyst en la Organización de Aviación Civil Internacional (OACI). La OACI ha iniciado un proyecto para analizar los accidentes aéreos de aviones en todo el mundo, con el objetivo de mejorar la seguridad en la aviación civil. Nuestra tarea es recopilar, analizar y visualizar datos relevantes sobre accidentes aéreos, identificar patrones y tendencias, y presentar los hallazgos a través de un dashboard interactivo.

## Estructura del Repositorio
El repositorio se estructura de la siguiente manera:

- **dashboard**: Contiene los archivos necesarios para el dashboard interactivo desarrollado para explorar los datos de accidentes aéreos.
- **data**: Contiene los archivos de datos utilizados en el proyecto.
- **informe**: Incluye el informe final del proyecto en formato PDF, que resume los hallazgos y recomendaciones obtenidos del análisis de los datos.
- **notebooks**: Incluye los notebooks de Jupyter utilizados para el procesamiento, análisis y visualización de los datos.
- **README.md**: Este archivo proporciona información detallada sobre el repositorio, los requisitos y las instrucciones para configurar el entorno de trabajo.
- **requirements.txt**: Este archivo enumera las dependencias y versiones de las bibliotecas necesarias para ejecutar los scripts y notebooks.

## Requisitos

Antes de utilizar este repositorio, asegúrate de cumplir con los siguientes requisitos:

- Python 3: Es necesario tener instalado Python 3 en tu sistema. Puedes descargar la última versión estable de Python desde el sitio oficial: https://www.python.org/downloads/

- Jupyter Notebook u otras herramientas similares: Recomendamos utilizar Jupyter Notebook para interactuar con los scripts y notebooks proporcionados.

- Power BI: Para visualizar y analizar los datos proporcionados, se requiere tener instalado Power BI Desktop. Puedes descargar la última versión de Power BI Desktop desde el sitio oficial: https://powerbi.microsoft.com/es-es/desktop/

## Configuración del entorno

A continuación, se detallan los pasos para configurar el entorno de trabajo:

1. Instala Python 3 siguiendo las instrucciones proporcionadas en el sitio oficial.

2. Clona este repositorio en tu máquina local.

3. Accede a la carpeta del repositorio clonado.

4. Crea un entorno virtual (opcional pero recomendado) para mantener las dependencias del proyecto aisladas. Puedes utilizar herramientas como `virtualenv` o `conda` para crear el entorno virtual.

5. Activa el entorno virtual (si lo has creado) e instala las dependencias necesarias ejecutando el siguiente comando:
pip install -r requirements.txt

6. Una vez instaladas las dependencias, puedes iniciar Jupyter Notebook

7. Navega hasta la ubicación del archivo de Jupyter Notebook (extensión .ipynb) que deseas ejecutar y haz clic en él para abrirlo.

8. Utiliza Jupyter Notebook para interactuar con los scripts y notebooks proporcionados. Puedes ejecutar celdas de código, visualizar resultados y hacer modificaciones según sea necesario.

 ## Uso del Dashboard Interactivo

El dashboard interactivo desarrollado como parte de este proyecto permite a los usuarios explorar y visualizar los datos de accidentes aéreos de manera intuitiva. Proporciona gráficos interactivos, filtros y herramientas de búsqueda para obtener información detallada sobre accidentes específicos y explorar las tendencias de seguridad de la aviación civil.

Para utilizar el dashboard, siga los siguientes pasos:

1. Clone o descargue este repositorio en su máquina local.

2. Navegue hasta la carpeta "Dashboard".

3. Explore los diferentes gráficos y paneles interactivos para visualizar los datos de accidentes aéreos.

4. Utilice los filtros y la función de búsqueda para obtener información específica sobre accidentes, ubicaciones o cualquier otro parámetro de interés.

5. Interactúe con el dashboard para analizar patrones, tendencias y los indicadores clave de rendimiento relacionados con la seguridad y la tasa demortalidad en accidentes aéreos.

6. Utilice las opciones de personalización y visualización disponibles en el dashboard para adaptar la presentación de los datos a sus necesidades.

7. Experimente con las diferentes funcionalidades del dashboard y explore los diferentes paneles para obtener una visión completa de los datos y los hallazgos obtenidos a partir del análisis.

## Objetivos del Proyecto
Los principales objetivos de este proyecto son los siguientes:

1. Recopilar datos de accidentes aéreos de aviones de diversas fuentes confiables.
2. Realizar un análisis exhaustivo de los datos para identificar patrones y tendencias en la seguridad de la aviación civil.
3. Desarrollar un dashboard interactivo que permita a los usuarios explorar los datos y obtener información detallada sobre accidentes específicos.
4. Establecer KPIs (Indicadores Clave de Rendimiento) relevantes para medir y monitorear la seguridad de la aviación civil.
5. Generar recomendaciones y medidas preventivas basadas en los hallazgos obtenidos del análisis de los datos.

## Recopilación de Datos
Para llevar a cabo este proyecto, la OACI, Organización de Aviación Civil Internacional que es una organización intergubernamental dedicada a promover la seguridad y eficiencia de la aviación civil internacional, nos ha proporcionado los datos de accidentes de aviones. Sin embargo, también se nos insta a utilizar otras fuentes de datos disponibles públicamente. Estas fuentes adicionales nos permitirán enriquecer nuestro análisis y obtener una visión más completa de los accidentes aéreos.

## Análisis Exploratorio de Datos (EDA)
Realizaremos un análisis exploratorio de los datos para obtener una comprensión profunda de la información que tenemos a nuestra disposición. Esto incluirá un resumen de estadísticas descriptivas de los datasets, análisis univariados y bivariados, así como la identificación de patrones, outliers y anomalías. El análisis exploratorio nos ayudará a tener una idea clara de los datos y a generar ideas para el posterior análisis.

## Dashboard Interactivo
Con base en los datos analizados, crearemos un dashboard interactivo que permita a los usuarios explorar la información sobre accidentes aéreos. El dashboard deberá ser funcional y coherente con el análisis realizado. Utilizaremos como herramientas Power BI. El objetivo principal del dashboard es presentar los hallazgos obtenidos de la información analizada y proporcionar información valiosa a la industria de la aviación civil, reguladores gubernamentales y otros interesados en la seguridad de la aviación.

## KPIs (Indicadores Clave de Desempeño)
Se nos solicita visualizar algunos KPIs relacionados con la seguridad de la aviación civil en nuestro dashboard. Además del KPI proporcionado de reducir en un 5% la tasa de mortalidad anual en accidentes aéreos, debemos sugerir otros tres KPIs relevantes que se alineen con la historia que estamos contando. Estos KPIs deben ser cuidadosamente seleccionados y deben proporcionar información útil para la mejora de la seguridad en la aviación civil.

## Base de Datos y Motor SQL
Como desafío adicional, podemos crear una base de datos en un motor SQL y utilizarla como fuente de datos para nuestro dashboard. Esto nos permitirá manejar eficientemente grandes volúmenes de datos y realizar consultas complejas para obtener información específica. La base de datos nos ayudará a optimizar el rendimiento del dashboard y mejorar la experiencia del usuario al interactuar con los datos.

## Reporte de Análisis
Además del dashboard, se espera que redactemos un reporte de análisis basado en nuestros hallazgos y conclusiones. Este reporte se incluirá en el README de nuestro repositorio. Deberemos explicar de manera clara y concisa los resultados obtenidos del análisis de datos, los patrones y tendencias identificados, así como las conclusiones y recomendaciones derivadas del análisis. El reporte de análisis proporcionará una visión general del proyecto, los objetivos alcanzados y las acciones sugeridas para mejorar la seguridad en la aviación civil.

## Ejecución de Scripts de Python en la Herramienta de Visualización
Para enriquecer aún más nuestro dashboard, podemos incorporar la ejecución de scripts de Python en la herramienta de visualización de datos que elijamos. Esto nos permitirá realizar cálculos, manipulaciones de datos y análisis adicionales directamente dentro del dashboard. Podremos utilizar bibliotecas como pandas o NumPy para realizar tareas más avanzadas y presentar los resultados de manera interactiva.

## Cruce de Datos con Datasets Complementarios
Además de las fuentes de datos proporcionadas por la OACI, podemos buscar datasets complementarios que contengan información relevante para nuestro análisis. Al cruzar y combinar estos datasets, obtendremos una visión más completa de los factores que contribuyen a los accidentes aéreos y podremos generar ideas adicionales para mejorar la seguridad en la aviación.

## Repositorio de GitHub
Es importante crear un repositorio de GitHub para nuestro proyecto, que incluya un README principal donde presentemos de forma general el proyecto. 

En resumen, este proyecto de Data Analytics nos brinda la oportunidad de aplicar nuestros conocimientos en el análisis de datos de accidentes aéreos con el objetivo de mejorar la seguridad en la aviación. A través del análisis exploratorio de datos, la creación de un dashboard interactivo y la identificación de KPIs relevantes, podremos proporcionar información valiosa para la industria de la aviación y contribuir a la prevención de futuros accidentes aéreos. 

Los desafíos adicionales no solo nos permitirán fortalecer nuestras habilidades como Data Analysts, sino que también nos brindarán un portfolio más completo y competitivo. Al abordar estos desafíos, podremos demostrar nuestro dominio de técnicas avanzadas de análisis de datos y nuestra capacidad para generar información accionable a partir de los datos de accidentes aéreos.

En conclusión, este proyecto nos brinda la oportunidad de aplicar una amplia gama de habilidades en el análisis de datos para mejorar la seguridad en la aviación. Al cumplir con los requisitos de análisis exploratorio, desarrollar un dashboard interactivo con KPIs relevantes y asumir desafíos adicionales, podremos destacarnos como Junior Advanced y proporcionar un valor significativo a la industria de la aviación civil y otros interesados en la seguridad aérea.

## Conclusiones y Recomendaciones
Durante el desarrollo de este proyecto de data analytics para el análisis de accidentes aéreos, se han obtenido importantes hallazgos y se han identificado patrones y tendencias en la seguridad de la aviación civil. A partir de estos resultados, se pueden establecer las siguientes conclusiones y recomendaciones:

Se ha observado una tendencia negativa en la reducción de la tasa de mortalidad anual en accidentes aéreos. Por lo cual, se recomienda seguir implementando medidas preventivas y de seguridad para continuar el esfuerzo de disminuir esta tasa y alcanzar el objetivo de reducir en un 5% la tasa de mortalidad anual.

Es fundamental contar con una recopilación exhaustiva y actualizada de los datos de accidentes aéreos. Se sugiere establecer colaboraciones con las autoridades gubernamentales, compañías aéreas y otras organizaciones relevantes para asegurar la disponibilidad y calidad de los datos.

El dashboard interactivo desarrollado proporciona una herramienta poderosa para explorar y analizar los datos de accidentes aéreos. Se recomienda su implementación y difusión en la industria de la aviación civil, reguladores gubernamentales y otros interesados en la seguridad de la aviación.

Es importante considerar la inclusión de fuentes de datos adicionales, como informes de investigación de accidentes, datos meteorológicos y factores humanos, para enriquecer el análisis y la comprensión de los accidentes aéreos.

Se recomienda llevar a cabo análisis periódicos de los datos de accidentes aéreos y actualizar el dashboard de manera regular para monitorear los cambios en la seguridad de la aviación civil y evaluar la efectividad de las medidas preventivas implementadas.

En resumen, este proyecto ha permitido obtener información valiosa sobre los accidentes aéreos y ha sentado las bases para mejorar la seguridad de la aviación civil a nivel mundial. El uso de técnicas de data analytics ha proporcionado insights significativos y ha demostrado su potencial para prevenir accidentes y salvar vidas en la industria de la aviación.

## Contribuciones y Contacto
Este proyecto de data analytics para el análisis de accidentes aéreos se ha desarrollado tomando el roll como parte de un equipo de especialistas en data analytics. Sin embargo, las contribuciones adicionales y las sugerencias son siempre bienvenidas.

Si desea contribuir al proyecto, puede realizar un fork de este repositorio, realizar sus modificaciones y enviar un pull request con sus cambios propuestos. Agradecemos cualquier mejora, corrección de errores o adición de nuevas funcionalidades que pueda aportar.

Si tiene alguna pregunta, comentario o sugerencia relacionada con este proyecto, no dude en ponerse en contacto conmigo a través de la siguiente dirección de correo electrónico: orianamadriz29@gmail.com.

¡Gracias por su atención!

Oriana Madriz
