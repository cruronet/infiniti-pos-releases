# Infiniti POS — Releases

Binarios de la caja **Infiniti POS** (instalador Windows). Este repositorio contiene
**únicamente los instaladores compilados** — el código fuente es privado.

- Las cajas instaladas se actualizan solas desde aquí (electron-updater): revisan al abrir y cada
  4 horas, y la actualización se instala al cerrar la caja, nunca en medio de una venta.
- Cada versión trae un manifiesto firmado (`infiniti-update.json`). La caja comprueba la firma y la
  huella del instalador antes de instalar: una versión sin firma válida no se instala.
- Instalación nueva: descarga el `.exe` del release más reciente en
  [Releases](../../releases/latest). Las notas de cada release cuentan qué cambia en el mostrador.

> Sin credenciales de un restaurante (emparejamiento autorizado por el servidor),
> el instalador no da acceso a ningún dato.
