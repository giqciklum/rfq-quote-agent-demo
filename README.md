# Copiloto RFQ → Oferta — demo

Una demo determinista, de una sola página y sin dependencias de un **copiloto agéntico RFQ → Oferta**, construida sobre el **Prodigy Agentic Framework de Ciklum**.

Lee una petición entrante del cliente (correo, chat o una llamada telefónica transcrita), busca en los catálogos de proveedores (Advantech + Moxa), empareja cada línea con un SKU **con una cita que remite a la página de origen**, deja que un **humano apruebe cada línea**, y genera una oferta con marca. Dos escenarios incluyen un **guardrail de "pieza no encontrada"** — el agente marca el elemento y se niega a inventar un SKU.

**Demo en vivo:** https://giqciklum.github.io/rfq-quote-agent-demo/

- Un único archivo estático, sin backend, sin claves de API, sin paso de build — corre en cualquier sitio y no puede fallar en vivo.
- Los datos de la demo son ilustrativos y los precios son representativos (un despliegue real pondría precio desde un ERP/feed autoritativo, nunca desde una página rastreada).

*Powered by the Prodigy Agentic Framework — Ciklum.*
