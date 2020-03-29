# Dumps of paths.places

1. **all-places**.geojson  
https://db-dev.bradypus.net/api/v2/paths?verb=search&shortsql=@places~[id,name,pleiades,geodata.geometry~%2Bgeodata||places.id|=|^paths__geodata.id_link||and|geodata.table_link|=|paths__places~-500&pretty=1&geojson=1
2. **episcopal-sees**.geojson  
https://db-dev.bradypus.net/api/v2/paths?verb=search&shortsql=@places~[id,name,pleiades,geodata.geometry~%2Bgeodata||places.id|=|^paths__geodata.id_link||and|geodata.table_link|=|paths__places~?episcopalsee|=|1~-500&pretty=1&geojson=1
