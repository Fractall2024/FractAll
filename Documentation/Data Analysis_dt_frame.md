# DataFramme Data Analysis

Este dataframe establece objetivamente cómo se debe realizar el proceso de Data Analysis, desde la analítica de datos hasta la visualizacion 
de los resultados ya estudiados. 

## Análitica de datos (Ciclo)
------------------------------------
### Generación de data
### Análisis de data 
### Modelamiento de data
### Vsualización de data
------------------------------------
_________________________________________________________________________________________________________________________________________________________________
 
### Generación de data
En este primer item se hace: 

------------------------------------
1. Definición de activo a estudiar
2. Recolección de datos del activo financiero (Series temporales)
3. Limpieza de datos (Si se requiere)
------------------------------------
_________________________________________________________________________________________________________________________________________________________________
   
### Análisis de data 
En este item se hace:

------------------------------------
#### Exploratory Data Analysis
El objetivo de este análisis es la búsqueda específica de anomalías o patrones de comportamiento, aqui se hace:

------------------------------------
1. Generación de ideas y definición de patrón a buscar, para esto vamos a generar reglas heurísticas: Definir condiciones matemáticas en python para identificar patrones (Ej. si el precio rompe un soporte y luego cae, podría ser un doble techo).
Ejemplos:
-Reglas heurísticas
-Codificación Strat
-Patrones Estacionarios
-Identificación de regímenes de mercado
-Uso de indicadores 
-Técnicas de ML como isolation forest 
-Patrones estacionarios
2. Clasificación y descripción detallado de patrón encontrado
------------------------------------

#### Statistical Analysis
El objetivo de este análisis es la búsqueda de validación de una anomalía o patrón de acuerdo a criterios estadísticos que 
demuestren rigidez en el patrón.Aquí se hace:

------------------------------------
1. Número total de ocurrencias
2. Medir la Probabilidad de que el patrón se mueva hacia arriba o abajo en x cantidad de pips.
   
------------------------------------
_________________________________________________________________________________________________________________________________________________________________

### Modelamiento de datos
En esta sección una vez estudiado el patrón en cuestión vamos a aplicar estrategias de acuerdo a lo resultados arrojados por el activo. 

En esta sección se hará:
1. Clasificar patrón de acuerdo a su calidad en base a si existe o no ventaja estadística.
2. Programar estrategias en base a estadísticas del patrón.
_________________________________________________________________________________________________________________________________________________________________
### Data Visualization 
En esta elección vamos a observar los resultados del proceso anterior:

1. Realizar Backtesting
2. Anáisis de datos de backtesting
3. Testing de rigurosidad
4. Test de validación

