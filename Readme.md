![Logo Henry](logoHenry.png)
# Proyecto Individual#2 Análisis comportamiento criptomonedas

![Alt text](monedas.jpeg)


## Henry Bootcamp

Análisis del corportamiento del mercado de criptomonedas, con énfasis en 10 activos cripto, durante el periodo Enero 2020 a Enero 2023


## Objetivo

Realizar un análisis estructurado del comportamiento de algunas variables como son: precio, capitalización de mercado, volumen de negociación, de 10 criptomonedas durante el período de enero de 2020 hasta enero de 2023, a través de los de datos que se encuentran alojados en la API de Coingecko.

## Descripción del Proyecto

En la historia reciente de la humanidad has sido muchos los acontecimientos que han generado impactos en los mercados financieros, pero ninguno de ellos como la pandemia causada por el virus del Covid-19 en el año 2020, el cual puso literalmente a la economía en pausa por algunos meses, mientras que el mundo científico encontraba los caminos para volver de manera segura a las actividades productivas. 

Dentro de ese contexto, las criptomonedas tomaron parte el ámbito financiero de los sucesos. 

Monedas como el Bitcoin habían desarrollado importantes capitalizaciones de mercado, teniendo su pico máximo en Diciembre del año 2020, teniendo un comportamiento alzista desde el 2017, sin embargo luego un período de crecimiento evidencia comportamientos que se pueden denomindar como erráticos,  de aceuerdo con la siguiente gráfica

![Bitcoin](Bitcoin%202013%202023.png)
Fuente: https://es.statista.com/estadisticas/1236380/bitcoin-valor-de-capitalizacion-bursatil-a-nivel-mundial/

En ese sentido la naturaleza altamente volátil y compleja de las criptomonedas presenta desafíos significativos para aquellos que desean tomar decisiones informadas sobre inversiones o simplemente para comprender mejor cómo funcionan estos mercados emergentes y es allí donde lo que se busca con ese proyecto de Data Analysis brindar una herramienta de análisis para la toma de decisiones con respecto al mercado de las criptomonedas tomando como referencia 10 de estos activos digitales. 

## Cripto seleccionadas para el análisis

Para el proyecto se tomaron como referencia las siguientes criptomonedas. 



|Criptomoneda| Descripción|
|------------|------------|
|Bitcoin (BTC)| Como la primera criptomoneda y la de mayor capitalización de mercado, es esencial para comprender el mercado en general y su impacto en otras criptomonedas.
Ethereum (ETH)|Es conocida por su plataforma de contratos inteligentes y DApps, lo que la convierte en una criptomoneda influyente para el análisis de la tecnología blockchain.
Binance Coin (BNB)|Utilizada en el ecosistema de Binance y para reducir tarifas de transacción, BNB podría ofrecer información sobre el funcionamiento interno de un exchange.
Cardano (ADA)|Una criptomoneda que se centra en la escalabilidad y la sostenibilidad, y que puede proporcionar ideas sobre enfoques de blockchain más avanzados.
Solana (SOL)|Una blockchain de alto rendimiento con aplicaciones en DeFi y NFTs, lo que la hace relevante para entender nuevas tendencias en criptomonedas.
Polkadot (DOT)|Una plataforma que busca conectar múltiples blockchains, lo que podría arrojar luz sobre la interoperabilidad entre diferentes criptomonedas.
Ripple (XRP)|Con un enfoque en las transacciones internacionales y la colaboración con instituciones financieras, XRP puede proporcionar información sobre casos de uso en el sector financiero.
Dogecoin (DOGE)|Conocida por su naturaleza meme, DOGE puede ser interesante para analizar el efecto de las redes sociales en el precio y la adopción de criptomonedas.
USD Coin (USDC)|Una stablecoin respaldada por dólares estadounidenses, que puede ofrecer información sobre la relación entre las criptomonedas y las monedas tradicionales.

## Serie de tiempo analizado

El año 2020 será recordado como aquel que cambió las relaciones sociales y con ellas los hábitos de consumo y por ende la economía y las inversiones.
Los analisis realizados con el proyecto estan enfocados a la observación del comportamiento de la canasta de criptomonedas arriba mencionadas durante la denominada post-pandemia. 
Es decir, con el proyecto centramos en análisis en que ha pasado con la canasta de criptomonedas desde enero del año 2020, cuando los rumores de un posible lock-down apenas aperecian como consecuencia de las noticias que se generaban desde los países asiáticos, hasta enero de 2023, es decir el periodo de tiempo en donde las actividades económicas se desarrollan de lo que se ha denominado como la "nueva normalidad". 

---
## Apis utilizadas
---
En el desarrollo de la investigación del análisis de datos de las criptomonedas y su comportamiento durante el tiempo se pudieron identificar páginas que brindan esta información, sin embargo de acuerdo a las recomendaciones de desarrollo se tomo como base de consulta la api coingecko.

De igual manera, con el objetivo de realizar un análisis que tuviera en cuenta otros factores económicos que permitieran generar un análisis mas profundo se tomaron datos de la API Fred de la Reserva Federal de los Estados Unidos y más específicamente con los datos del S&P 500.


### CoinGecko
![Alt text](coingecko.png)


La API CoinGecko es una plataforma de acceso a datos en línea que proporciona información integral y actualizada sobre criptomonedas. 

CoinGecko recopila datos de diversas fuentes para ofrecer una visión completa del mercado de criptomonedas, incluyendo detalles sobre monedas individuales, precios, volúmenes, capitalización de mercado, tendencias históricas y más. 

La API es ampliamente utilizada por desarrolladores, analistas y entusiastas de las criptomonedas para obtener información precisa y actualizada para sus aplicaciones, análisis y proyectos.

Características Principales:
La API CoinGecko proporciona una amplia gama de datos sobre miles de criptomonedas, incluyendo detalles técnicos, de mercado y de desarrollo.

Datos Históricos: Permite acceder a datos históricos de precios, volúmenes y capitalización de mercado para análisis a largo plazo.

Listas de Intercambios: Ofrece información sobre los intercambios donde se negocian las criptomonedas, incluyendo volúmenes de negociación y pares comerciales.

Indicadores de Desarrollo: Proporciona métricas relacionadas con la actividad de desarrollo de una criptomoneda, como el número de contribuidores de GitHub y la frecuencia de commits.

Datos de Cadenas de Bloques: Suministra datos relacionados con la cadena de bloques, como tiempos de bloqueo y tamaños de bloques.

API Gratuita y Acceso Premium: Ofrece un nivel de acceso gratuito, así como opciones de acceso premium para mayor capacidad y velocidad de consulta.
Usos Comunes:

Seguimiento de Precios: Los desarrolladores pueden utilizar la API para mostrar precios en tiempo real en sitios web y aplicaciones.

Análisis de Mercado: Los analistas pueden acceder a datos históricos para realizar análisis técnicos y fundamentales del mercado de criptomonedas.

Creación de Portafolios: Los usuarios pueden rastrear sus inversiones y crear portafolios personalizados utilizando datos de CoinGecko.

Investigación de Proyectos: Los entusiastas pueden obtener información sobre nuevas criptomonedas y proyectos en desarrollo.

Aplicaciones Móviles y Web: La API se puede integrar en aplicaciones para dispositivos móviles y sitios web para ofrecer datos actualizados sobre criptomonedas.
Documentación:

La documentación oficial de la API CoinGecko proporciona detalles sobre cómo realizar solicitudes, parámetros admitidos, tipos de datos de respuesta y ejemplos de uso. 

La documentación se encuentra en: https://www.coingecko.com/es/api/documentation


### FredApi


![Fred](Fred.png)



La API FRED (Federal Reserve Economic Data) es una plataforma en línea proporcionada por la Reserva Federal de los Estados Unidos que ofrece acceso a una amplia gama de datos económicos y financieros. FRED recopila, organiza y distribuye datos clave relacionados con la economía de los Estados Unidos y otros indicadores globales. La API FRED permite a los desarrolladores y analistas acceder a estos datos para su uso en aplicaciones, análisis y proyectos.

Características Principales:

Datos Económicos: La API FRED proporciona una gran variedad de datos económicos, incluyendo indicadores macroeconómicos, tasas de interés, inflación, empleo, producción industrial y más.
Series Temporales: Permite acceder a series temporales de datos a lo largo del tiempo, lo que facilita el análisis de tendencias y patrones.
Actualización Automática: Los datos se actualizan regularmente para reflejar los cambios en la economía y los mercados.
Información Global: Además de datos de los Estados Unidos, la API FRED también incluye datos de otros países y regiones.
Documentación Completa: Ofrece documentación detallada sobre cómo realizar consultas, comprender la estructura de los datos y utilizar las características avanzadas.
Usos Comunes:

Análisis Económico: Los analistas económicos pueden utilizar la API para obtener datos clave sobre la economía de los Estados Unidos y realizar análisis en profundidad.
Modelado Financiero: Los desarrolladores pueden utilizar los datos de la API para construir modelos financieros y prever tendencias económicas.
Investigación Académica: Los investigadores pueden acceder a datos históricos y actuales para realizar investigaciones y estudios económicos.
Toma de Decisiones: Los profesionales pueden utilizar los datos de la API para respaldar la toma de decisiones financieras y económicas.
Aplicaciones Personalizadas: Los desarrolladores pueden integrar los datos de la API en aplicaciones personalizadas, dashboards y herramientas analíticas.
Documentación:
La documentación oficial de la API FRED proporciona información detallada sobre cómo utilizar la API, los endpoints disponibles, los parámetros admitidos y ejemplos de uso. La documentación se encuentra en: https://research.stlouisfed.org/docs/api/

---

## Metodología aplicada
### EDA

A partir de la documentación de la API CoinGecko se obtuvieron los datos de capitalización, precio, volumen, volumen de trasacciones, entre otros, para luego realizar el archivo EDA.ipynb en donde se encuentran las princpales gráficas de correlación de las variables.
Asimismo con se realizo el desarrollo de funciones que permientieron acceder a los datos históricos dispuestos en la API

```python
    import requests
    import datetime
    
    def get_price_history(coins_analysis):
    url = "https://api.coingecko.com/api/v3/coins/markets"

    # Fecha actual
    end_date = datetime.datetime.now()

    # Fecha hace tres años
    start_date = end_date - datetime.timedelta(days=3 * 365)

    # Parámetros de la API
    params = {
        "vs_currency": "usd",
        "ids": ','.join(coins_analysis),
        "from": int(start_date.timestamp()),
        "to": int(end_date.timestamp())
    }

    response = requests.get(url, params=params)
    data = response.json()
    return data
```

 Es así como se estructuraron y graficaron difrentes correlaciones en las  que se pudieron analizar, entre otros, comportamientos tales como la capitalización de mercado y el precio de las monedas. La capitalización de las monedas de análisis en el período indicado.

 Por otro lado con el uso de los datos de la reserva federal de los Estados Unidos contenidos en la API Fred se relizó un proceso de extracción del comportamiento del S&P 500, teniendo en cuenta es que este indice mide el desempeño del mercado de valores de los Estados Unidos.

Se debe tener en cuenta que para realizar consultas en la API FRED, a diferencia de CoinGecko es necesario tene una Key de acceso.

## Outliers

Un punto importante a tener en cuenta dentro de la metodología utilizada en proyecto es el manejo e identificación de outliers toda vez que de acuerdo con la documentación encontrada acerca del mercado de las criptomonedas, el cual se una de las caracteristicas de estos actividades precisamente es la volitidad en sus precios.

Lo anterior depende de una combinación de factores fundamentales, técnicos y psicológicos que interactúan de manera compleja. Algunos de los principales factores que contribuyen a la volatilidad en los precios de las criptomonedas son los siguientes:

- Adopción y Reconocimiento: Dado que las criptomonedas son relativamente nuevas en comparación con los mercados financieros tradicionales, su adopción y reconocimiento aún están en desarrollo. Los cambios en la percepción pública, la aceptación por parte de gobiernos y empresas, así como los eventos que afectan la legitimidad y la confianza en las criptomonedas, pueden generar volatilidad.

- Noticias y Eventos: Las noticias relacionadas con regulaciones gubernamentales, anuncios de empresas importantes, cambios en la tecnología subyacente de las criptomonedas y otros eventos inesperados pueden tener un impacto significativo en los precios. Los inversores suelen reaccionar de manera rápida y emocional a estas noticias, lo que puede llevar a movimientos bruscos en los precios.

- Liquidez Limitada: Aunque el mercado de criptomonedas ha crecido, aún puede carecer de la misma liquidez que los mercados financieros más establecidos. Esto significa que una gran orden de compra o venta puede tener un impacto desproporcionado en el precio, generando movimientos abruptos.

- Inversores Institucionales: La entrada de inversores institucionales, como fondos de cobertura y empresas financieras, puede aumentar la volatilidad debido a su capacidad para realizar grandes transacciones que afectan los precios.

- Manipulación del Mercado: Dada la relativa falta de regulación en comparación con los mercados tradicionales, el mercado de criptomonedas puede ser vulnerable a la manipulación. Grandes operadores pueden influir en los precios mediante prácticas como "pump and dump" (inflar y desinflar) o la difusión de información falsa.

- Naturaleza Especulativa: Muchos inversores en criptomonedas están motivados por la especulación y la posibilidad de obtener ganancias rápidas. Esto puede llevar a un comportamiento impulsivo y emocional, lo que a su vez contribuye a la volatilidad.

- Tecnología y Seguridad: Los problemas técnicos, los ataques de seguridad y los cambios en los protocolos de una criptomoneda pueden afectar drásticamente su precio y generar incertidumbre en los inversores.

- Mercado 24/7: A diferencia de los mercados financieros tradicionales, el mercado de criptomonedas opera las 24 horas del día, los 7 días de la semana. Esto significa que las fluctuaciones en los precios pueden ocurrir en cualquier momento, incluso cuando otros mercados están cerrados.

- Falta de Regulación Uniforme: La falta de una regulación uniforme en todo el mundo puede llevar a diferencias en las políticas regulatorias en diferentes países. Los cambios regulatorios pueden tener un impacto directo en los precios de las criptomonedas.

- Expectativas del Mercado: Las expectativas de los inversores sobre el futuro de las criptomonedas, incluidos los avances tecnológicos y el potencial de adopción masiva, pueden influir en los precios y generar movimientos volátiles.

En conjunto, estos factores y otros interactúan para generar la volatilidad en los precios de las criptomonedas. Es importante destacar que la volatilidad también puede presentar oportunidades para los inversores, pero también aumenta el riesgo de pérdidas significativas y su comportamiento se evidencia en sus precios. 

Igualmente se debe tener en cuenta que el análisis que se realiza en el proyecto evalua el comportamiento de un conjunto de criptomonedas y no de una moneda en singular. 

----
## KPI´s propuestos
Capitalización de Mercado Total del Conjunto de monedas
La suma de las capitalizaciones de mercado individuales de todas las criptomonedas en el conjunto. Este KPI proporciona una visión general del tamaño combinado de estas criptomonedas en el mercado.

Cambio porcentual promedio en 24 horas:
El promedio de los cambios porcentuales en los precios de las criptomonedas en el conjunto durante las últimas 24 horas. Este KPI puede indicar la volatilidad diaria promedio del conjunto y su tendencia alcista o bajista.

Volumen Total de Negociación del Conjunto de monedas
La suma de los volúmenes de negociación individuales de todas las criptomonedas en el conjunto. Este KPI indica la cantidad total de activos que se han negociado en un período de tiempo determinado y puede reflejar el interés y la liquidez del conjunto.

----
## Funcionalidades del Proyecto

- Dashboard Interactivo

Desarrollo de un dashboard interactivo utilizando Power BI para visualizar y explorar los datos de criptomonedas de manera eficiente. El dashboard incluye filtros que permiten a los usuarios seleccionar diferentes criptomonedas y rangos de tiempo para obtener información específica. Además, se utilizaron gráficos adecuados según la tipología de variable para facilitar la interpretación de los datos.

---
## Tecnologías y Herramientas Utilizadas
- Python: Lenguaje de programación utilizado para realizar el análisis de datos.
- Jupyter Notebook: Entorno interactivo para desarrollar el análisis exploratorio y generar visualizaciones.
Pandas y Numpy: Bibliotecas de Python utilizadas para el manejo y análisis de datos.
- Matplotlib y Seaborn: Bibliotecas para la visualización de datos.
- Power BI: Herramienta de visualización de datos utilizada para crear dashboards interactivos.
- GitHub: Plataforma utilizada para gestionar el repositorio y el control de versiones del proyecto.
---
## Autor


Jorge Gómez.
Estudiante Bootcamp Datascience Henry