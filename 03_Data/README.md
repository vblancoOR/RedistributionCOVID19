# Data

<h3>Demands</h3>
We estimated the daily ventilator demands based on real ICU demands of COVID19 patients in Madrid and Andalucía, published by the Spanish and Andalucía governments from 08/03/2020 to 25/04/2020 (first COVID-19 wave data). <br>
<br>

This data was collected differently in each region. The region of Madrid reported the daily ICU demands, and then, ready to be incorporated to the models. On the other hand, the
government of Andalucía reported the accumulated demand of ICU. We estimated the daily demands as follows: for each hospital, we compute the daily number or new COVID-19 patients
in ICU and we assume that each of them stays in ICU 21 days (the average number of days the patients stay on a ICU bed during the first wave).

<h3>Extra Stock</h3>
During the first wave different national or regional governments have bought and received extra invasive mechanical ventilators as reported by some national newspapers in different days. Moreover, some extra stock has also been provided from the Spanish Government and private donations. Some of these newspaper are:

* <https://www.libertaddigital.com/andalucia/2020-03-26/coronavirus-moreno-bonilla-tras-donar-respiradores-a-madrid-o-somos-espanoles-de-verdad-o-de-boquilla-1276654713/>
* <https://www.hoy.es/extremadura/extremadura-presta-material-20200325112339-nt.html?ref=https%3A%2F%2Fwww.google.com%2F>
* <https://elmedicointeractivo.com/diferentes-cc-aa-colaboran-enviando-respiradores-a-la-comunidad-de-madrid/>
* <https://www.libremercado.com/2020-03-31/coronavirus-amancio-ortega-donando-63-millones-respiradores-mascarillas-material-sanitario-1276655071/>
* <https://elpais.com/espana/2020-03-27/feijoo-defiende-la-cesion-de-respiradores-a-madrid-que-le-ibamos-a-contestar-que-no-ibamos-a-ceder-nada.html>
* <https://www.elperiodico.com/es/madrid/20200331/madrid-respiradores-monitores-para-uci-8-m-coronavirus-7911547>
* <https://www.rtve.es/noticias/20200325/espana-compra-china-respiradores-test-rapidos-mascarillas-guantes-432-millones-euros/2010779.shtml>

<h3>Hospitals</h3>
We compute the hospitals from the Catálogo Nacional de Hospitales (2019) of Spanish Government and the total beds for each hospital. We estimated the ICU bed with the proportion of ICU-beds in each province and region.
