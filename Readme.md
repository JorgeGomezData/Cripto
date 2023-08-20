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