# Sistema Global Arche · Desktop

Canal de **actualizaciones de Arche Escritorio** (la PC del negocio como servidor).

- Cada carpeta (`shaker/`) es un cliente o producto: `manifest.json` + `arche-shaker-<versión>.tar.gz`.
- Los paquetes llevan el código del servidor **ofuscado** y el manifiesto **firmado** con la llave privada de Arche (Ed25519). Las PC solo instalan lo que verifica esa firma; cualquier cambio a un archivo hace que lo rechacen.
- Sin una **licencia válida** para esa PC, el sistema no arranca.
- Este repositorio lo escribe `herramientas/publicar.js` (rama `escritorio-shaker` del sistema). **No editar a mano.**
