### Simple JSON-LD resources list:
Insted of the sitemap.xml we are thinking to a catalog, or also a *simple json list of resources* is ok if is more quick, containing the links to the json resource (not the html page):
```json
[
  "https://open.canada.ca/data/en/dataset/018c218b-ba2b-5e22-b807-9c45ff241bfe.jsonld",
  "https://open.canada.ca/data/en/dataset/00354f07-4b7b-4a4b-82be-748e05eb561e.jsonld", 
]
```

### Resource content (just the JSON-LD)
Each resource should be the simple jsonld contained in the HTML page (without other tags or html)
```json
{

    "@context": "http://schema.org",

    "@type": "Dataset",

    "identifier": "https://doi.org/10.5885/44985SL-8F203FD3ACCD4138",

    "url": "http://www.cen.ulaval.ca/nordicanad/dpage.aspx?doi=10.5885/44985SL-8F203FD3ACCD4138",

    "isAccessibleForFree": true,

    "name": "Climate station data from Northern Ellesmere Island in Nunavut, Canada",

    "alternateName": "Données des stations climatiques du nord de l'île d'Ellesmere au Nunavut, Canada",

    "description": "The data are from the northern region of Ellesmere Island, Nunavut, Canada. It contains data from air and ground temperatures, air humidity, solar radiation, wind speed and direction and the average snow height. The available datasets cover the period from 2002-2019. For each site, the number of measured variables differs. For ground temperature, the depth ranges are as follows: Ellesmere Taconite Lac C1 (ELLACC1) 20 cm. Ellesmere Parks Canada (ELLEPAR): 20 cm. Ellesmere Lac A (ELLLACA) : 20 cm. Ellesmere Ward Hunt B (WARDHIB) : 0-40 cm. Data are available as: (1) recorded data; (2) daily averages; (3) monthly averages; and (4) yearly averages.",

    "datePublished": "2013-02-04",

    "dateModified": "2020-02-06",

    "version": "1.7",

    "keywords": "Annuelle,yearly,WARDHIB,ward hunt,ward hunt,ward,ward,vitesse,speed,vents,winds,vent,wind,sous sol,underground,thermistance,thermistor,températures,temperatures,température,temperature,Taconite,solaire,solar,sol,soil,neige,snow,rambow,rambow,radiation,radiation,profondeurs,depths,précipitation,precipitation,Parcs,Parks,parc,park,nunavut,nunavut,nord,north,minimum,minimum,méromictique,meromictic,mensuelle,monthly,maximum,maximum,lac,lake,journalière,daily,île,island,ile,island,hunt,hunt,humidité,humidity,hauteur,height,sol,ground,ELLLACA,ellesmere,ellesmere,ELLEPAR,ELLACC1,échantillon,sample,profondeur,depth,delta,delta,Canada,Canada,plage,beach,moyennes,averages,moyenne,average,arctique,arctic",

    "citation": "CEN 2020. Climate station data from Northern Ellesmere Island in Nunavut, Canada, v. 1.7 (2002-2019). Nordicana D1, doi: 10.5885/44985SL-8F203FD3ACCD4138.",

    "temporalCoverage": "2002-07-29/2019-07-13",

    "author": [

      {

    "@type": "Organization",

    "name": " Centre d'études Nordiques"

      }

    ],

    "contributor": [

      {

    "@type": "Person",

    "jobTitle": "Researcher",

    "name": "Warwick F. Vincent",

    "givenName": "Warwick F.",

    "familyName": "Vincent",

    "affiliation": {

           "@type": "Organization",

           "name": "Centre d'études nordiques, Université Laval"

                  }

      }

    ],

    "variableMeasured": [

      {

    "@type": "PropertyValue",

    "name": "Average air humidity",

    "description": "Average data recorded every minute for the previous period. The average is calculated by adding the measured values and then dividing the sum by the number of observations.",

    "unitText": "Percentage",

    "url": "http://www.cen.ulaval.ca/nordicanad/infounitedonnees.aspx?id=591304"

      },

      {

    "@type": "PropertyValue",

    "name": "Average air temperature",

    "description": "Average data recorded every minute for the previous period. The average is calculated by adding the measured values and then dividing the sum by the number of observations.",

    "unitText": "Degree Celsius",

    "url": "http://www.cen.ulaval.ca/nordicanad/infounitedonnees.aspx?id=591299"

      },

      {

    "@type": "PropertyValue",

    "name": "Average downwelling radiation",

    "description": "Average data recorded every minute for the previous period. The average is calculated by adding the measured values and then dividing the sum by the number of observations.",

    "unitText": "Watt per square meter",

    "url": "http://www.cen.ulaval.ca/nordicanad/infounitedonnees.aspx?id=591306"

      },

      {

    "@type": "PropertyValue",

    "name": "Average ground temperature",

    "description": "Average data recorded every minute for the previous period. The average is calculated by adding the measured values and then dividing the sum by the number of observations.",

    "unitText": "Degree Celsius",

    "url": "http://www.cen.ulaval.ca/nordicanad/infounitedonnees.aspx?id=591300"

      },

      {

    "@type": "PropertyValue",

    "name": "Average snow height",

    "description": "Average data recorded every minute for the previous period. The average is calculated by adding the measured values and then dividing the sum by the number of observations.",

    "unitText": "Meter",

    "url": "http://www.cen.ulaval.ca/nordicanad/infounitedonnees.aspx?id=591305"

      },

      {

    "@type": "PropertyValue",

    "name": "Maximum air temperature",

    "description": "The maximum is determined by selecting the highest value obtained during the observation of the last period.",

    "unitText": "Degree Celsius",

    "url": "http://www.cen.ulaval.ca/nordicanad/infounitedonnees.aspx?id=591297"

      },

      {

    "@type": "PropertyValue",

    "name": "Maximum wind speed",

    "description": "The maximum is determined by selecting the highest value obtained during the observation of the last hour.   Occasional gaps in the sub -0°C range of the record are due to significant ice buildup on the wind monitor.",

    "unitText": "Meter per second",

    "url": "http://www.cen.ulaval.ca/nordicanad/infounitedonnees.aspx?id=591302"

      },

      {

    "@type": "PropertyValue",

    "name": "Mean Net corrected radiation ",

    "description": "Mean net corrected radiation is obtained from the mean of the 60 values corrected for wind and obtained in the last hour. The average is calculated by adding the observations and dividing by the number of observations.",

    "unitText": "Watt per square meter",

    "url": "http://www.cen.ulaval.ca/nordicanad/infounitedonnees.aspx?id=591296"

      },

      {

    "@type": "PropertyValue",

    "name": "Minimum air temperature",

    "description": "The minimum is determined by selecting the lowest value obtained during the observation of the last period.",

    "unitText": "Degree Celsius",

    "url": "http://www.cen.ulaval.ca/nordicanad/infounitedonnees.aspx?id=591298"

      },

      {

    "@type": "PropertyValue",

    "name": "Resulting average of wind speed",

    "description": "Resultant wind speed values are obtained by converting the wind speeds and directions for the hour into a single hourly vector. Resultant wind speed is the magnitude of this vector.   Occasional gaps in the sub -0°C range of the record are due to significant ice buildup on the wind monitor.",

    "unitText": "Meter per second",

    "url": "http://www.cen.ulaval.ca/nordicanad/infounitedonnees.aspx?id=591303"

      },

      {

    "@type": "PropertyValue",

    "name": "Sample on wind direction",

    "description": "Sample took from the readings obtained during the last hour. The sample is taken on the 60 readings generated per hour.",

    "unitText": "Degree",

    "url": "http://www.cen.ulaval.ca/nordicanad/infounitedonnees.aspx?id=591301"

      }

    ],

    "measurementTechnique": [

      "Câble YSI 44033 / YSI 44033",

      "Campbell Scientific / 107, 107b",

      "Campbell Scientific / NR-Lite (0102229)",

      "Campbell Scientific / NR-Lite (021125)",

      "Campbell Scientific / NR-Lite (031439)",

      "Campbell Scientific / SR 50",

      "Li-Cor Biosciences / LI-200 (Py23810)",

      "R.M. Young / 05103-10",

      "R.M. Young / 05103-10 (WM66510)",

      "RM Young 6 plate / 41303",

      "RM Young multi plate / 41003",

      "Thermistance YSI 44033 / YSI 44033",

      "Vaisala / HMP35CF"

    ],

    "spatialCoverage": {"geo":[ 

      {

      "@type": "GeoCoordinates",

      "latitude": "83.0023",

      "longitude": "-75.3896",

      "name": "Ellesmere Lac A (ELLLACA)"

      },

      {

      "@type": "GeoCoordinates",

      "latitude": "83.0925",

      "longitude": "-74.1303",

      "name": "Ellesmere  Ward Hunt (ELLWARH)"

      },

      {

      "@type": "GeoCoordinates",

      "latitude": "83.0914",

      "longitude": "-74.1328",

      "name": "Ellesmere Ward Hunt B (WARDHIB)"

      },

      {

      "@type": "GeoCoordinates",

      "latitude": "83.094",

      "longitude": "-74.1629",

      "name": "Ellesmere  Parks Canada (ELLEPAR)"

      },

      {

      "@type": "GeoCoordinates",

      "latitude": "82.8466",

      "longitude": "-78.1316",

      "name": "Ellesmere Taconite Lac C1 (ELLACC1)"

      }],

     "@type": "Place" },

    "license": "http://www.cen.ulaval.ca/nordicanad/en_modalite.aspx",

    "publisher": { "@type": "Organization", "name": "Nordicana D", "url": "http://www.cen.ulaval.ca/nordicanad/en_index.aspx" },

    "provider": { "@type": "Organization", "name": "DataCite"}

}
```
