Replication data for Dodyk, J. and Ruiz Nicolini, J. P. (2017). ["Enchufes, espejos y tijeras"](https://www.researchgate.net/publication/322663247_Enchufes_espejos_y_tijeras_efectos_del_diseno_de_las_boletas_sobre_el_comportamiento_electoral_Plugs_mirrors_and_scissors_Ballot_design_effects_on_electoral_behavior), *Revista SAAP*, Vol. 11, Nº 2, 365-386.

# Corrientes

Análisis de la elección de Corrientes capital 2017 para intendente y concejales

Archivos:
* `analisis.R` Script en R que corre modelos para estimar efectos de la BUE
* `todo.csv` Tabla con los resultados de la elección por mesa
* `resultados.ipynb` Notebook de Jupyter con el proceso de datos
* `scrapper/corrientes2017.php` Scrapper en PHP que baja los resultados por mesa
* `scrapper/scrapper.php` Librería artesanal para scrapear

Extras:
* `resultados.json` Resultados por lista, producido por el scrapper
* `alianzas_intendentes.json` Resultados por candidato a intendente
* `alianzas_concejales.json` Resultados por alianzas a concejales con más de una lista
* `mesas.csv` Tabla con mesa, depto, municipio, circuito

# Chaco

Análisis de la elección de Chaco 2017 para diputados provinciales

Datos:
* `resultados.csv` Tabla con resultados por mesa
* `partidos.csv` Tabla con los ids de los partidos y sus nombres
* `deptos.json`         Geometría de Departamentos
* `municipios.json`     Geometría de Municipios
* `circuitos.json`      Geometría de Circuitos
* `municipios.csv`      Tabla con ID, Nombre de municipios

Scripts:
* `analisis.R`          Código R que corre los mixed models
* `chaco2017.ipynb` Notebook de Jupyter que cuenta el procedimiento y procesa los datos
* `scrapper.php`        Scrapper en PHP. Baja las mesas de cada municipio y sus resultados

Extras:
* `mesas.json`          JSON con mesas por municipio, producido por el scrapper
* `resultados.json`     JSON con resultados por mesa, producido por el scrapper
* `tabula.csv`          Tabla con electores por circuito, producida por [TabulaPDF](https://github.com/tabulapdf)
* `resultados_agregados.json` JSON con resultados por circuito; incluye turnout
* `modelo.stan`        Código Stan del modelo mixto usado para la simulación

