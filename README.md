<div align="center">
  <img src="apps/web/public/sunops_complete.webp" alt="SunOps — Operaciones y Certificación Fotovoltaica" width="340" />

  **Plataforma para Ingeniería de Obra Solar y Mantenimiento Técnico (O&M)**

  <p>
    <img src="https://img.shields.io/badge/pnpm-workspaces-F69220?style=flat-square&logo=pnpm&logoColor=white" alt="pnpm" />
    <img src="https://img.shields.io/badge/React-19-20232A?style=flat-square&logo=react&logoColor=61DAFB" alt="React 19" />
    <img src="https://img.shields.io/badge/Capacitor-6-119EFF?style=flat-square&logo=capacitor&logoColor=white" alt="Capacitor 6" />
    <img src="https://img.shields.io/badge/NestJS-10-E0234E?style=flat-square&logo=nestjs&logoColor=white" alt="NestJS 10" />
    <img src="https://img.shields.io/badge/PostgreSQL-16-316192?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL 16" />
    <img src="https://img.shields.io/badge/Tailwind_CSS-4-38B2AC?style=flat-square&logo=tailwind-css&logoColor=white" alt="Tailwind CSS" />
  </p>

  <p><em>Solución integral para la gestión operativa, comisionado normativo, control de calidad y mantenimiento técnico de instalaciones solares fotovoltaicas.</em></p>
</div>

---

## Propósito

SunOps está diseñado específicamente para instaladoras fotovoltaicas, constructoras EPC y empresas de operación y mantenimiento (O&M). Su objetivo es erradicar la fricción administrativa que sufren los equipos técnicos: fotografías dispersas en galerías de teléfonos móviles, formularios en papel traspapelados en caseta de obra, transcripción manual de datos a hojas de cálculo y confección artesanal de informes en procesadores de texto.

La plataforma conecta el trabajo en campo sobre cubierta con la oficina técnica, centralizando todo el ciclo de vida de la planta solar bajo un flujo estructurado con trazabilidad fotográfica, verificación automática de tolerancias normativas e integridad documental sellada criptográficamente mediante huella SHA-256.

---

## Módulos de la Plataforma

SunOps articula sus capacidades en torno a dos módulos operativos principales:

### 1. Módulo de Construcción (Ciclo de Obra en 4 Fases)

Gobernanza completa de la ejecución fotovoltaica estructurada en cuatro fases secuenciales:

* **Fase 1 — Replanteo y Viabilidad Técnica (Survey):**
  Inspección de campo en cubierta, suelo, cuadros (CGBT), acometida, sombras y canalizaciones. Cotejo de puntos críticos y emisión del dictamen técnico formal (*GO / GO Condicional / NO GO*) imprescindible para desbloquear la fase de obra.
* **Fase 2 — Preparación, Ingeniería y Acopio de Materiales:**
  Modelado del generador solar (potencia pico, strings, inversores, módulos y cuadros), programación del cronograma de hitos físicos, asignación de cuadrillas y cotejo documental de órdenes de compra, albaranes y números de serie de equipos.
* **Fase 3 — Montaje y Partes Diarios en Campo:**
  Seguimiento de avance físico porcentual por hitos (estructura, módulos, zanjas, cableado DC/AC), partes diarios de trabajo en cubierta con registro de personal y horas, trazabilidad fotográfica vinculada al diario de obra, gestión de modificaciones As-Built y lista de remates.
* **Fase 4 — Calidad QA/QC, Comisionado Eléctrico y Entrega:**
  Auditorías de calidad por muestreo aleatorio uniforme con fotografía técnica obligatoria por muestra y control de instrumental calibrado. Ensayos eléctricos estructurados según REBT, RAT, ITCs y normas UNE (aislamiento, polaridad, inyección cero y sincronización en carga de inversores). Generación del Acta de Entrega con firma digital en pantalla, número de identificación de instalador autorizado y sellado SHA-256.

### 2. Módulo de Operación y Mantenimiento Técnico (O&M)

Garantía de rendimiento, disponibilidad y seguridad a lo largo de toda la vida útil de la instalación:

* **Mantenimiento Preventivo Periódico y Normativo:**
  Checklists y protocolos de revisión recurrente: ensayos de resistencia de aislamiento ($R_{iso}$), curvas I-V, continuidad de conductores de protección, inspección termográfica de módulos para detección de puntos calientes (*hotspots*) y comprobación de aprietes mecánicos con llaves dinamométricas calibradas.
* **Mantenimiento Correctivo y Triaje de Averías:**
  Apertura de incidencias (directas o derivadas automáticamente de una inspección preventiva), clasificación por severidad (Leve, Grave, Crítico), diagnóstico fotográfico de fallo, asignación a técnicos de guardia y registro de sustitución de componentes con trazabilidad de números de serie.
* **Inventario Técnico de Plantas y Gestión de Activos:**
  Ficha técnica unificada de cada activo solar con coordenadas geográficas, diagramas unifilares, esquemas de strings, histórico cronológico de intervenciones y custodia de proyectos técnicos y manuales de fabricante.
* **Partes de Trabajo O&M e Informes Sellados:**
  Cierre de intervenciones in situ sobre pantalla táctil con cómputo de horas y materiales empleados, generando al instante el informe técnico oficial en formato PDF de alta fidelidad con código QR y huella SHA-256 inmutable.

---

## Marco Normativo y Rigor Técnico

* **Referencias de Ingeniería:** Los protocolos de inspección, ensayos y listas de verificación toman como base técnica las directrices del **Reglamento Electrotécnico para Baja Tensión (REBT)** (especialmente ITC-BT-40 e ITC-BT-03), el **Reglamento de Alta Tensión (RAT)**, las **Instrucciones Técnicas Complementarias (ITC)** y normas técnicas **UNE** de referencia en el sector fotovoltaico (**UNE-EN 62446-1**).
* **Transparencia y Alcance:** SunOps es una solución privada de software para gestión operativa. No es un Organismo de Control Autorizado (OCA) ni sustituye al **Certificado de Instalación Eléctrica (CIE)** oficial expedido ante la Administración territorial competente.
* **Valor Certificatorio Personal:** El valor técnico y probatorio de los informes emana de la habilitación del **instalador autorizado o técnico titulado competente**, quien suscribe el documento incorporando su **número de identificación profesional oficial** y su firma digital, garantizando SunOps la integridad documental mediante sellado hash SHA-256 no manipulable.

---

## Gobernanza de Almacenamiento y Seguridad

* **Cuotas de Almacenamiento por Organización:** Planes escalables con almacenamiento en nube cifrada (10 GB, 30 GB o 100 GB) con monitorización centralizada en panel de ajustes.
* **Empaquetador Nativo Zero-Dependencies (`ZipArchive`):** Generador nativo en TypeScript (`node:zlib`) con tabla CRC-32 estándar IEEE 802.3 para compresión y descarga en streaming de expedientes completos de obra en formato ZIP sin saturar memoria.
* **Purga Segura y No Destructiva:** Vía administrativa para depurar binarios pesados en obras cerradas (`status: 'CLOSED'`), manteniendo inalterados los metadatos, mediciones, firmas y actas de entrega en base de datos.
* **Seguridad Industrial:** Comunicaciones cifradas bajo TLS 1.3, almacenamiento protegido con cifrado AES-256 en reposo, control de acceso basado en roles (RBAC) y marcas de tiempo inmutables.


---

## Modelo de Suscripción y Licenciamiento

* **Suscripción SaaS en dos ejes:** Ranuras de obra simultánea en ejecución activa (liberadas inmediatamente tras la entrega y firma del acta) y bolsa mensual recurrente de informes técnicos.
* **Packs Prepago de Informes:** Bolsas de créditos prepago sin cuota fija mensual para revisiones puntuales de O&M; los créditos nunca caducan y coexisten protegiendo el saldo en monedero corporativo.
