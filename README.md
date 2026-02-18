# Proyecto: Finmojarra

## Sección A: Evidencia de Campo (Discovery)

* **El Problema:** El 46% de los encuestados (6 de 13 personas) manifiesta una incapacidad para rastrear sus gastos diarios, pérdida de soportes físicos (recibos) y falta de memoria respecto a las fechas de vencimiento de sus obligaciones financieras.
* **Resultados de la Sonda:** https://forms.office.com/Pages/DesignPageV2.aspx?prevorigin=shell&origin=NeoPortalPage&subpage=design&id=-4HJLoOSoEOaOTMy_FTXdHbp0sK-591KoCOXbgHU3cZUMTlUQzVRUVY3MEg1WktENjlVUFRVNVFPRS4u&analysis=true. El análisis muestra que la desorganización financiera es el "dolor" predominante sobre otros problemas logísticos.
* **¿Qué duele?:** "No sé en qué gasté la plata, olvido pagar las facturas y siempre pierdo los recibos importantes."
* **Frecuencia:** Es un problema crítico con una incidencia recurrente (4.6/10 en la muestra total).
* **La Solución Soñada:** Una plataforma que centralice los recordatorios de pago, permita digitalizar recibos al instante y ofrezca consejos de ahorro basados en el comportamiento de gasto.

## Sección B: Definición de Requisitos (Definition)

### Historia de Usuario Principal
* **Como** usuario con múltiples obligaciones financieras, **quiero** registrar mis gastos rápidamente y recibir alertas preventivas de mis facturas, **para** evitar cargos por mora y tener claridad sobre mi presupuesto disponible.

### Criterios de Aceptación (Definition of Done)
1. El sistema debe permitir el registro de un gasto en menos de 3 pasos (menos de 10 segundos).
2. Las notificaciones de facturas deben activarse con 48 horas de antelación al vencimiento.
3. El sistema debe permitir adjuntar una fotografía del recibo al momento de crear el registro.

### Requisitos Funcionales (Draft Técnico)
* **RF-01 (Módulo de Alertas):** El sistema debe implementar un servicio de notificaciones push y/o correo electrónico para vencimientos de facturas.
* **RF-02 (Persistencia de Datos):** El sistema debe almacenar registros categorizados de ingresos y egresos en una base de datos relacional.
* **RF-03 (Gestión Multimedia):** El sistema debe permitir la carga y almacenamiento de imágenes (recibos) asociados a cada transacción.

# conclusion 
las personas tienen problemas con sus finanzas y el manejo del dinero.