# MGS4-Dictionary-Project
Convierte los hashes en nombres de archivo.

Debido a la naturaleza del sistema, es imposible hacer un diccionario en un solo archivo con todos los nombres. Esto es debido a que existen colisiones entre hashes: un mismo hash puede tener múltiples nombres compatibles.

Es por ello que este diccionario es un conjunto de archivos.

# ¿Cómo funciona?
wip

|Slots|Files|Renamed|Unnamed|Average|Notes|
|---|---|---|---|---|---|
|slot_book|8|4|4|50.0%||
|slot_chibrowser|296|30|266|10.135135135135135%||
|slot_cm_body|8|6|2|75.0%||
|slot_cm_tentacle|8|4|4|50.0%||
|slot_flash|124|62|62|50.0%||
|slot_oct_list|1828|1252|576|68.49015317286653%||
|slot_oct_list_2d|1828|1249|579|68.32603938730854%||
|slot_padinfo|2|0|2|0.0%||
|slot_photo_album|9|9|0|100.0%|Done|
|slot_radio|97|12|85|12.371134020618557%||
|slot_s01a00l|65|30|35|46.15384615384615%||
|slot_s01a10l|139|43|96|30.93525179856115%||
|slot_s01a20l|89|63|26|70.78651685393258%||
|slot_s01a30l|94|47|47|50.0%||
|slot_s01a40l|112|29|83|25.892857142857142%||
|slot_s01a50l|54|12|42|22.22222222222222%||
|slot_s01a57l|76|22|54|28.94736842105263%||
|slot_s02a10l|152|52|100|34.21052631578947%||
|slot_s02a20l|150|58|92|38.666666666666664%||
|slot_s02a30l|123|36|87|29.26829268292683%||
|slot_s02a40l|172|37|135|21.511627906976745%||
|slot_s02a50l|270|24|246|8.88888888888889%||
|slot_s02a60l|192|39|153|20.3125%||
|slot_s02a73l|56|19|37|33.92857142857143%||
|slot_s02a75l|61|18|43|29.508196721311474%||
|slot_s02a78l|110|41|69|37.27272727272727%||
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
|slot_s04a10l|144|40|104|27.77777777777778%||
|slot_s04a20l|277|40|237|14.440433212996389%||
|slot_s04a30l|79|22|57|27.848101265822784%||
|slot_s04a40l|43|6|37|13.953488372093023%||
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
|slot_weapon|974|238|736|24.435318275154003%||
|stage00|4154|2847|1307|68.53635050553683%||
|stage01|5853|4756|1097|81.25747479924824%||
|stage02|7003|5614|1389|80.1656432957304%||
|stage03|6563|4716|1847|71.85738229468231%||
|stage04|4923|3365|1558|68.35263050985172%||
|stage05|3519|2785|734|79.14180164819551%||

## Consejos para deducir los nombres de archivo:
Están ordenados por valor hexadecimal, es decir, "0" va antes de "\_", que va antes de "A" y éste va antes de "a".

En ocasiones nos podemos encontrar con el siguiente ejemplo
- 670edf.0d G | s01a_densen5set_sk.mdn
- 516784.06 ? |
- 51678f.65 G | s02a10l.vlm
Viendo los hashes, podemos deducir que el que falta es una pequeña variación del siguiente, en este caso, s02a10a.

Lo antes posible subiré la herramienta.
