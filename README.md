# 🤖 Asistente CobroSmart

Este proyecto es una **librería JavaScript** que permite integrar fácilmente el asistente virtual de CobroSmart en cualquier sitio web. Está diseñada para automatizar consultas, gestionar cobranzas, atender clientes y brindar una experiencia personalizada en tiempo real.

---

## 🚀 ¿Qué hace?

- Muestra un botón flotante en tu web.
- Abre un chat inteligente al hacer clic.
- El asistente puede:
  - Responder preguntas frecuentes.
  - Ofrecer medios de pago.
  - Conectar con agentes humanos.
  - Registrar promesas de pago o mensajes personalizados.

---

## 🧩 Cómo integrarlo

### 1. Definí tu configuración

```html
<script>
  window.CobroSmartConfig = {
    asistente_cobrosmart: 'asst_TU_ID_UNICO', // ⚠️ Obligatorio
    star_mensaje: 'Hola, ¿cómo puedo ayudarte?', // Opcional
    img_smart_cobrosmart: 'https://tusitio.com/logo.png', // Opcional
    es_test: 'no', // 'si' para test, 'no' para producción

    // Configuración avanzada de WhatsApp (opcional)
    whatsapp_numero: '5491123456789', // Número de WhatsApp con código país (sin + ni espacios)
    activar_whatsapp: false            // true para forzar que el botón derive siempre a WhatsApp
  };
</script>
<script src="https://cdn.cobrosmart.com/asistente_cobrosmart.js"></script>
