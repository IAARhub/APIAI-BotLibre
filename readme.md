# SDK HTML/JS para integración API.AI + BotLibre 3D Avatar

Código de integración de un bot de API.AI conectado a un avatar animado de Botlibre funcionando en navegador.


# Requisitos

* Un agente en API.AI https://www.api.ai
* Una cuenta en BotLibre https://www.botlibre.com

# Instalación

* Bajas el repositorio
* Entras al directorio del repositorio -> javascripts -> ai.js

En ese script cambias los tokens de las APIs de API.AI y Botlibre:

```javascript
// ACA VA TU APPLICATION ID DE BOT LIBRE
SDK.applicationId = "<botLibreApplicationID>";

// ACA VA EL ID DE TU AVATAR EN BOT LIBRE
web.avatar = "<avatarID>";

// ACA VA EL ACCESSTOKEN DE TU AGENTE EN API.AI
var accessToken = "<apiAIaccessToken>";
```
