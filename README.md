# Reglas de la Guía de Rendición · Fondos de Cultura

El programa *Guía de Rendición* descarga `reglas.xlsx` desde este repositorio cada vez que se abre. Con esas reglas arma la guía de documentos que cada responsable debe presentar. La [versión web](https://georgeaguilera.github.io/guia-rendicion/) usa las mismas reglas. Los instaladores del programa están en [Releases](https://github.com/georgeaguilera/guia-rendicion-reglas/releases).

Junto al Excel va `reglas.xlsx.firma`. Desde la versión 0.7.0, el programa acepta las reglas solo si esa firma calza con la clave que trae: así, aunque alguien entrara a esta cuenta, no podría publicar reglas falsas. Las versiones anteriores del programa no miran la firma.

Para publicar una versión nueva:

1. Sube el número de **Version** en la hoja Leeme.
2. Abre el Mantenedor de reglas, pestaña **Firmar y publicar**, y elige «Validar y firmar el Excel de reglas». Valida el archivo y deja `reglas.xlsx.firma` al lado del Excel.
3. Sube aquí los dos archivos juntos, con esos mismos nombres: `reglas.xlsx` y `reglas.xlsx.firma` (Add file → Upload files). Si cambias el Excel después de firmarlo, vuelve a firmarlo: la firma sirve solo para ese archivo exacto.

Si subes solo el Excel, o la firma no calza, los programas desde la 0.7.0 siguen con su última copia buena hasta que llegue la firma correcta.

Si algo sale mal, restaura la versión anterior de los dos archivos desde el historial. Mientras tanto, cada programa sigue usando su última copia buena.

**Canal de prueba:** las reglas que subas, con su firma, a la carpeta `beta/` solo las bajan los computadores de prueba (los que se cambiaron con `GuiaRendicion.exe --canal beta`). Si `beta/` está vacía, esos computadores usan las de todos.

La guía orienta, pero no reemplaza el convenio, las bases ni al supervisor del Ministerio.
