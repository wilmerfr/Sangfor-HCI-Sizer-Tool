# Changelog

## v1.2.5 — 2026-10-30
- Slots PCIe disponibles según la ficha *Sangfor HCI Data Sheet 09/26*: aServer-X5-2205, X5-2305P y X5-2405 = 2 (de 4 totales); X5-2305P(12N) = 3; X5-1200 = 1; Z4-2405/2605 = 2.
- El U2-SSD-Kit (necesario para NVMe U.2 o Memory Tiering en aServer X5) ocupa 1 slot PCIe: se descuenta de los slots disponibles y se valida junto con las tarjetas de red y HBA.

## v1.2.4 — 2026-10-30
- Contexto: nueva sección *Componentes virtualizados*: almacenamiento virtualizado, seguridad virtualizada, Directorio Activo virtualizado y virtualización de redes (VMware NSX, Nutanix Flow, Cisco ACI u otro), con fabricante, modelo, cantidad y topología.

## v1.2.3 — 2026-10-22
- Contexto: nueva sección *Hardware de cómputo actual y capacidad* (inventario de servidores, CPU, RAM, discos y tarjetas de red con cantidades, velocidades y medios de conexión; necesidad de adquirir hardware; capacidad actual y planificada con RVTools si aplica).
- Contexto: inventario y capacidad actual/planificada también para almacenamiento y red, más necesidad de adquirir equipamiento de red.
- Contexto: nueva sección *Servicios y aplicaciones* (inventario, capacidad actual/planificada y servicios profesionales requeridos).

## v1.2.2 — 2026-10-22
- Contexto: nueva pregunta sobre el almacenamiento de la solución (interno aSAN o externo SAN/NAS con protocolo: FC, iSCSI, NFS, SMB/CIFS, mixto).
- Contexto: nueva pregunta para adjuntar o compartir el documento de topología de red.
- Nota formal en el contexto y en el cuestionario (copiar y Word) invitando a agregar información o documentación relevante y de cumplimiento obligatorio.

## v1.2.1 — 2026-10-21
- Storage externo adicional (iSCSI, NFS o FC) también con aSAN habilitado, desde *Tipo de clúster y almacenamiento*; se refleja en red, topología, BOM (HBA FC) y descripción.

## v1.2.0 — 2026-10-16
- **Edición pública sin precios**: se eliminan del código todos los precios, descuentos y valores monetarios; el sizer opera siempre en modo sin precios (BOM con SKU y cantidades).
- La edición con precios es de uso interno y no se publica en este repositorio.

## v1.1.0 — 2026-10-15
- Contexto del proyecto: botón **Copiar** en *Calificación de la oportunidad* (preguntas, estado, opción y respuesta).
- El cuestionario para el cliente (copiar y Word) incluye ahora la sección *Calificación de la oportunidad*.

## v1.0.0 — 2026-10-15 (primera carga)
- Sizing por vCPU o por frecuencia, multi-clúster, HA N+k, witness, Memory Tiering y aSAN (híbrido / all flash).
- Crecimiento **compuesto** o **acumulado** sobre CPU, RAM y storage.
- Parámetros de diseño agrupados (CPU / RAM / Storage / Backup) con ayuda contextual.
- Switching SUNDRAY: escalado automático de switches por plano, uplinks por plano con velocidad (10/25/40/100G) y sobresuscripción.
- BOM con Hardware HCI, Hardware networking por switch, Software y Servicios; copia a Excel.
- Memoria de cálculo con demanda proyectada.
- Topología con conexión externa (usuarios, Internet/WAN, servicios externos).
- Requerimientos específicos del cliente seleccionables (migración, P2V, UAT, retiro y borrado seguro, transferencia de conocimiento, soporte 3/5 años, retención de discos, TAM).
- Exportación Word: portada, tabla de contenido, numeración, texto justificado, paginación, Times New Roman 12.

