# N&J Command Center

Centro de control local para **N&J Remodeling and Rental LLC**.

## Versión subida

**V5.5 local test**

Esta versión es un prototipo HTML de una sola página para probar flujo y estructura antes de usar datos reales.

## Incluye

- Dashboard principal alimentado por los datos de contactos, propiedades, proyectos y transacciones.
- Formularios inteligentes:
  - Contactos por tipo: inquilino, cliente, contratista, inversionista, equipo.
  - Propiedades por tipo: rental, flip, propiedad de cliente, lead, mantenimiento.
  - Proyectos por clasificación y etapa.
- Relaciones opcionales entre contactos, propiedades, proyectos y transacciones.
- Clasificación de proyectos por etapas: planeado, activo, en espera, inspección y terminado.
- Finanzas básicas por centro de costo.
- Borrado con cartel de confirmación.
- Área preparada para agregar contraseña/PIN de seguridad para borrar en una fase futura.
- Exportar/importar backup JSON.
- Datos de prueba guardados en `localStorage`.

## Nota importante

No metas datos reales todavía. Esta versión guarda información solo en el navegador. Para producción se debe conectar un backend seguro con login, roles y base de datos.
