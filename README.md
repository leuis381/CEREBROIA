# CEREBRO IA – Pizza Dypsi 🍕

Base de conocimiento y protocolos para el chatbot de atención al cliente de **Pizza Dypsi**.

---

## 📁 Archivos del repositorio

| Archivo | Descripción |
|---|---|
| `Fuente1.txt` | Protocolos y respuestas principales del chatbot (datos del local, gestión de carta, corrección de datos, seguridad y escalamiento). |
| `Fuente 2.txt` | Corrección del nombre oficial: **Pizza Dypsi** (no "Dypsi Pizzeria & Grill"). |
| `Fuente 3.txt` | Motor de contexto — reglas de contexto continuo, estados de conversación, variables de memoria viva y reglas de decisión. |
| `Fuente 4.txt` | Correcciones específicas de menú (combo Motrito/Mostro: 3 alitas + papas nativas + Pepsi 355 ml + chaufa = S/11; sin ensaladas). |
| `KNOWLEDGE_BASE_DYPSI_ARMONIZADO_2026.docx` | Base de conocimiento armonizada 2026. |
| `KNOWLEDGE_BASE_DYPSI_V3_SIN_CONFLICTOS.docx` | Base de conocimiento v3 sin conflictos. |
| `CORRECCIONES_IA_CHATBOT (1).docx` | Documento de correcciones del chatbot IA. |
| `correcciones-ia-chatbot-v-integrada_Version2.docx` | Versión 2 integrada de correcciones del chatbot IA. |
| `AI QA TemplateES.docx` | Plantilla de control de calidad (QA) para IA en español. |

---

## 🤖 Información del negocio

- **Nombre oficial:** Pizza Dypsi
- **Número de pagos (Yape/Plin):** +51 900 146 424
- **Titular:** Joel Santos
- **Carta digital:** [https://wa.me/c/51906538844](https://wa.me/c/51906538844)

---

## ⚙️ Estados de conversación

El chatbot maneja los siguientes estados:

- `CONTEXTO_INICIAL` – Saludo / primer mensaje
- `CONTEXTO_MENU` – Consulta de menú y precios
- `CONTEXTO_ORDENANDO` – Armado del pedido
- `CONTEXTO_CONFIRMACION` – Resumen y confirmación
- `CONTEXTO_PAGO` – Validación de pago
- `CONTEXTO_DELIVERY` – Dirección y cálculo de envío
- `CONTEXTO_ESTADO` – Seguimiento del pedido
- `CONTEXTO_RECLAMO` – Gestión de quejas
- `CONTEXTO_ESCALADO` – Derivación a agente humano
- `CONTEXTO_FUERA_HORARIO` – Atención fuera de horario

---

## 📋 Principios del chatbot

1. Priorizar siempre la última información validada por el dueño o agente autorizado.
2. Nunca reiniciar el contexto si hay un pedido en progreso.
3. Si hay discrepancias de datos, escalar a un agente humano.
4. Responder siempre con brevedad, empatía y sin repetir información ya corregida.
