# 💬 Generador de Mensajes WhatsApp - Norttek

## 📖 Descripción

Sistema inteligente para generar y enviar mensajes conversacionales personalizados por WhatsApp. Diseñado para promocionar productos de forma natural y profesional.

---

## ✨ Características Principales

### 🎨 Diseño Moderno
- Interfaz limpia y profesional con colores oficiales de WhatsApp
- Animaciones suaves y transiciones fluidas
- Responsive design - funciona en móviles, tablets y escritorio
- Tema inspirado en WhatsApp con gradientes y sombras

### 📱 Input de Teléfono Inteligente
- Código de país **+52** visible por defecto
- Validación en tiempo real (solo acepta 10 dígitos)
- Formateo automático del número
- Mensajes de error claros y útiles

### 👀 Preview del Mensaje
- **Botón dedicado** para generar vista previa antes de enviar
- Vista previa antes de enviar el mensaje
- Diseño estilo burbuja de WhatsApp
- Muestra destinatario y hora actual
- Botón para cerrar y revisar otro mensaje
- **Auto-preview** cuando se completan los 10 dígitos del teléfono

### 🔔 Sistema de Notificaciones
- Notificaciones flotantes elegantes
- Tipos: éxito (verde) y error (rojo)
- Se ocultan automáticamente después de 3 segundos
- Animaciones de entrada suaves

### 📊 Estadísticas en Tiempo Real
- Total de mensajes generados
- Cantidad de productos disponibles
- Plantillas de conversación activas

---

## 🚀 Cómo Usar

### 1️⃣ **Abrir la Aplicación**
Abre el archivo `mensajes.html` en tu navegador preferido.

### 2️⃣ **Ingresar Número de Teléfono**
```
- Ingresa solo 10 dígitos en el campo de teléfono
- El código +52 ya está incluido automáticamente
- Ejemplo: 1234567890 (sin espacios ni guiones)
```

### 3️⃣ **Generar Mensajes** (Opcional)
```
- Clic en el botón "🔄 Generar Mensajes"
- Se crearán 20 mensajes conversacionales únicos
- Los mensajes ya se generan automáticamente al cargar la página
```

### 3️⃣ **Generar Vista Previa**
```
- Clic en el botón "👁️ Generar Vista Previa"
- Se generará un mensaje aleatorio para revisar
- Puedes hacer clic múltiples veces para ver diferentes mensajes
- El mensaje incluye una frase motivadora al final
```

### 4️⃣ **Enviar Mensaje**
```
- Una vez que estés satisfecho con el mensaje del preview
- Clic en el botón "📤 Enviar Mensaje"
- Se abrirá WhatsApp Web con el mensaje exacto del preview
- Solo tienes que hacer clic en enviar en WhatsApp
```

---

## 🎯 Flujo de Uso Completo

```
┌─────────────────────────────────────────┐
│  1. Abrir mensajes.html                 │
│     ↓                                   │
│  2. Ingresar número (10 dígitos)        │
│     ↓                                   │
│  3. Se muestra auto-preview             │
│     ↓                                   │
│  4. Clic "Generar Vista Previa"         │
│     (opcional, para ver otros mensajes) │
│     ↓                                   │
│  5. Revisar mensaje con frase           │
│     motivadora                          │
│     ↓                                   │
│  6. Clic "Enviar Mensaje"               │
│     ↓                                   │
│  7. Se abre WhatsApp Web                │
│     ↓                                   │
│  8. Clic en enviar en WhatsApp          │
└─────────────────────────────────────────┘
```

---

## 📋 Estructura del Mensaje

Los mensajes generados siguen esta estructura natural:

```
[Saludo] + [Transición] + [Conector] + [Producto] + [Descripción] + 
[Precio] + [Link] + [Cierre con Pregunta] + [Frase Motivadora]
```

### Ejemplo de Mensaje:
```
Buenos días ☀️, espero que andes súper bien. Quería platicarte que 
me topé con *tóner para impresora* diferentes modelos, con garantía 
incluida 💰 .

🔗 https://tienda.norttek.com.mx/

¿Qué te parece? ¿Necesitas que te cotice algo adicional? 📋

¡Mucho éxito en todo lo que emprendas! 🌟
```

---

## 🛠️ Tecnologías Utilizadas

- **HTML5** - Estructura semántica
- **CSS3** - Estilos modernos con variables CSS y animaciones
- **JavaScript (Vanilla)** - Sin dependencias externas
- **WhatsApp Web API** - Para abrir chats con mensajes prellenados

---

## 📦 Archivos del Proyecto

```
mensajes.html              # Archivo principal (todo en uno)
CHANGELOG_MENSAJES.md      # Historial de cambios y versiones
README_MENSAJES.md         # Este archivo (documentación)
```

---

## 🎨 Paleta de Colores

```css
--whatsapp-green:      #25D366  /* Verde principal de WhatsApp */
--whatsapp-dark:       #128C7E  /* Verde oscuro */
--whatsapp-blue:       #34B7F1  /* Azul de WhatsApp */
--whatsapp-dark-blue:  #2196F3  /* Azul oscuro */
--background-light:    #E5DDD5  /* Fondo característico */
--card-bg:            #FFFFFF  /* Fondo de tarjetas */
--text-primary:       #333333  /* Texto principal */
--text-secondary:     #666666  /* Texto secundario */
```

---

## ⌨️ Atajos de Teclado

| Tecla | Acción |
|-------|--------|
| `Enter` | Enviar mensaje (cuando el cursor está en el input de teléfono) |

---

## 📱 Navegadores Compatibles

✅ Google Chrome (recomendado)  
✅ Mozilla Firefox  
✅ Microsoft Edge  
✅ Safari  
✅ Opera  

**Requisitos:** Versiones recientes (últimos 2 años)

---

## 🔒 Privacidad y Seguridad

- ✅ **No se almacenan datos** - todo funciona localmente en tu navegador
- ✅ **No hay servidor** - no se envía información a ningún servidor
- ✅ **Sin cookies** - no se utilizan cookies ni tracking
- ✅ **Código abierto** - puedes revisar todo el código fuente
- ✅ **Offline capable** - funciona sin conexión (excepto para abrir WhatsApp)

---

## 🐛 Solución de Problemas

### ❌ "Por favor ingresa un número de teléfono"
**Solución:** Asegúrate de ingresar exactamente 10 dígitos en el campo.

### ❌ "El número debe tener exactamente 10 dígitos"
**Solución:** Verifica que no hayas ingresado menos o más de 10 números.

### ❌ No se abre WhatsApp
**Solución:** 
1. Verifica que tengas WhatsApp Web instalado o WhatsApp Desktop
2. Asegúrate de que tu navegador permita popups
3. Verifica tu conexión a internet

### ❌ El mensaje no aparece en WhatsApp
**Solución:** 
1. Verifica que el número sea correcto
2. Asegúrate de que el destinatario tenga WhatsApp
3. Revisa que el navegador no haya bloqueado la ventana emergente

---

## 📝 Notas Importantes

1. **Formato del número:** Solo ingresa los 10 dígitos, el +52 ya está incluido
2. **Números válidos:** Solo números de México (código +52)
3. **WhatsApp instalado:** Necesitas tener WhatsApp Web o WhatsApp Desktop
4. **Internet requerido:** Para abrir WhatsApp y enviar mensajes

---

## 🎓 Para Desarrolladores

### Estructura del Código

```javascript
// Estado global de la aplicación
const AppState = {
    mensajesGenerados: [],  // Array de mensajes generados
    mensajeActual: null,    // Mensaje seleccionado actualmente
    numeroDestinatario: null // Número del destinatario
};

// Funciones principales
generateMessages()      // Genera 20 mensajes únicos con frases motivadoras
validatePhoneNumber()   // Valida el formato del número
generatePreview()       // Genera y muestra vista previa del mensaje
sendMessage()           // Envía el mensaje actual del preview
showPreview()          // Muestra vista previa
showNotification()     // Muestra notificaciones
updateStats()          // Actualiza estadísticas
formatPhoneInput()     // Formatea input y muestra auto-preview
showAutoPreview()      // Muestra preview automático al completar número
```

### Personalización

**Agregar productos:**
```javascript
// Busca el array 'productos' y agrega:
{
    nombre: "Producto Nuevo",
    precio: "$100",
    descripcion: "descripción aquí",
    link: "https://tu-link.com"
}
```

**Modificar plantillas:**
```javascript
// Busca el array 'plantillasConversacion' y agrega:
{
    saludo: "Tu saludo",
    transicion: "tu transición",
    conectores: ["Conector 1", "Conector 2"]
}
```

**Agregar frases motivadoras:**
```javascript
// Busca el array 'frasesMotivadoras' y agrega:
"¡Tu frase motivadora aquí! 🎉"
```

**Cambiar colores:**
```css
/* Modifica las variables CSS en :root */
:root {
    --whatsapp-green: #TU_COLOR;
}
```

---

## 🤝 Soporte

Para reportar problemas o sugerir mejoras:
- 📧 Email: soporte@norttek.com.mx
- 🌐 Sitio: https://tienda.norttek.com.mx

---

## 📄 Licencia

© 2025 Norttek. Todos los derechos reservados.

---

## 🎉 Créditos

**Desarrollado por:** Norttek  
**Versión:** 2.0  
**Última actualización:** Octubre 2025

---

## 📈 Actualizaciones Futuras

- [ ] Historial de mensajes enviados
- [ ] Múltiples destinatarios (envío masivo)
- [ ] Programación de mensajes
- [ ] Editor de plantillas personalizado
- [ ] Exportación a CSV/Excel
- [ ] Modo oscuro
- [ ] Multi-idioma
- [ ] Integración con CRM

---

**¡Gracias por usar el Generador de Mensajes WhatsApp de Norttek! 💚**
