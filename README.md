# LMSGI_UD07_Martinez_Cossio_Marcos

## Entregable 1: Generación del Informe Dinámico (QWeb XML)

Debes diseñar y programar la estructura XML de una plantilla de informe de factura personalizada para "WillmanTech S.L." utilizando la sintaxis de QWeb (motor de plantillas de ERPs modernos).
  1. Sintaxis estructurada: El documento debe estar bien formado e incluir espacios de nombres correctos si fuera necesario.
  2. Lógica embebida QWeb: Debe hacer uso de directivas de iteración (t-foreach) para desglosar dinámicamente las líneas de la      factura (invoice_line_ids).
  3. Lógica condicional: Debe implementar una condición (t-if) para ocultar la columna de "Descuento" en caso de que ninguna        de las líneas de detalle de la factura lo contenga.
  4. Data Binding: Utilizar la directiva t-field para mostrar de forma limpia campos como el número de factura (doc.name),          fecha de emisión (doc.date) y el total neto (doc.amount_total).
