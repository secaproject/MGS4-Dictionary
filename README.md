# MGS4-Dictionary-Project
Convierte los hashes en nombres de archivo.

Debido a la naturaleza del sistema, es imposible hacer un diccionario en un solo archivo con todos los nombres. Esto es debido a que existen colisiones entre hashes: un mismo hash puede tener múltiples nombres compatibles.

Es por ello que este diccionario es un conjunto de archivos.

# ¿Cómo funciona?
wip

|Slots|Files|Renamed|Unnamed|Average|Notes|
|---|---|---|---|---|---|
|slot_book|8|4|4|50.0%||
|slot_chibrowser|296|11|285|3.7162162162162162%||
|slot_cm_body|8|6|2|75.0%||
|slot_cm_tentacle|8|4|4|50.0%||
|slot_flash|124|62|62|50.0%||
|slot_oct_list|1828|1252|576|68.49015317286653%||
|slot_oct_list_2d|1828|1249|579|68.32603938730854%||
|slot_padinfo|2|0|2|0.0%||
|slot_photo_album|9|9|0|100.0%|Done|
|slot_radio|97|12|85|12.371134020618557%||
|slot_s01a00l|65|29|36|44.61538461538461%||
|slot_s01a10l|139|43|96|30.93525179856115%||
|slot_s01a20l|89|63|26|70.78651685393258%||
|slot_s01a30l|94|40|54|42.5531914893617%||
|slot_s01a40l|112|29|83|25.892857142857142%||
|slot_s01a50l|54|10|44|18.51851851851852%||
|slot_s01a57l|76|21|55|27.63157894736842%||
|slot_s02a10l|152|48|104|31.57894736842105%||
|slot_s02a20l|150|36|114|24.0%||
|slot_s02a30l|123|27|96|21.951219512195124%||
|slot_s02a40l|172|17|155|9.883720930232558%||
|slot_s02a50l|270|21|249|7.777777777777778%||
|slot_s02a60l|192|40|152|20.833333333333332%||
|slot_s02a73l|56|12|44|21.428571428571427%||
|slot_s02a75l|61|14|47|22.950819672131146%||
|slot_s02a78l|110|28|82|25.454545454545453%||
|slot_s02a80l|33|0|33|0.0%||
|slot_s02a90l|84|7|77|8.333333333333334%||
|slot_s03a10l|93|20|73|21.50537634408602%||
|slot_s03a15l|54|5|49|9.25925925925926%||
|slot_s03a16l|38|10|28|26.31578947368421%||
|slot_s03a20l|61|8|53|13.114754098360656%||
|slot_s03a25l|44|11|33|25.0%||
|slot_s03a35l|61|4|57|6.557377049180328%||
|slot_s03a40l|91|6|85|6.593406593406593%||
|slot_s03a60l|52|0|52|0.0%||
|slot_s03a70l|168|7|161|4.166666666666667%||
|slot_s04a10l|144|37|107|25.694444444444443%||
|slot_s04a20l|277|40|237|14.440433212996389%||
|slot_s04a30l|79|3|76|3.7974683544303796%||
|slot_s04a40l|43|4|39|9.30232558139535%||
|slot_s04a50l|26|4|22|15.384615384615385%||
|slot_s04a60l|45|12|33|26.666666666666668%||
|slot_s04a65l|72|5|67|6.944444444444445%||
|slot_s04a70l|313|5|308|1.597444089456869%||
|slot_s05a20l|51|5|46|9.803921568627452%||
|slot_s05a30l|36|2|34|5.555555555555555%||
|slot_s05a50l|17|2|15|11.764705882352942%||
|slot_save|116|58|58|50.0%||
|slot_sna_body|120|75|45|62.5%||
|slot_sna_face|190|69|121|36.31578947368421%||
|slot_sunnycam|122|3|119|2.459016393442623%||
|slot_weapon|974|228|746|23.408624229979466%||
|stage00|4154|2621|1533|63.0958112662494%||
|stage01|5853|4570|1283|78.07961729027849%||
|stage02|7003|5030|1973|71.82636013137227%||
|stage03|6563|4570|1993|69.63278988267561%||
|stage04|4923|3203|1720|65.06195409303271%||
|stage05|3519|2709|810|76.98209718670077%||

# Consejos para deducir los nombres de archivo:
Están ordenados por valor hexadecimal, es decir, "0" va antes de "_", que va antes de "A" y éste va antes de "a".
## En ocasiones nos podemos encontrar con el siguiente ejemplo
- 670edf.0d G | s01a_densen5set_sk.mdn
- 516784.06 ? |
- 51678f.65 G | s02a10l.vlm
Viendo los hashes, podemos deducir que el que falta es una pequeña variación del siguiente, en este caso, s02a10a.

Lo antes posible subiré la herramienta.
