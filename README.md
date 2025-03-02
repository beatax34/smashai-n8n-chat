# smashai-n8n-chat

Ein moderner, anpassbarer Chat-Bot für n8n mit verbesserten UI-Funktionen wie Ladeanimationen und Bot-Denkanimationen.

## Features

- Einfache Integration in jede Webseite
- Anpassbares Design und Branding
- Ladeanimation für Nutzereingaben
- "Bot denkt nach"-Animation während der Antwortgenerierung
- Responsive Design
- Kompatibel mit n8n-Webhooks

## Verwendung

Fügen Sie einfach das folgende Skript in Ihre HTML-Datei ein:

```html
<!-- Widget Configuration -->
<script>
    window.ChatWidgetConfig = {
        webhook: {
            url: '<Ihre n8n-Webhook-URL>',
            route: 'general'
        },
        branding: {
            logo: '<URL Ihres Firmenlogos>',
            name: 'Ihr Firmenname', 
            welcomeText: 'Hallo 👋, wie kann ich helfen?',
            responseTimeText: 'Wir antworten in der Regel sofort'
        },
        style: {
            primaryColor: '#854fff',
            secondaryColor: '#6b3fd4',
            position: 'right',
            backgroundColor: '#ffffff',
            fontColor: '#333333'
        }
    };
</script>
<script src="https://cdn.jsdelivr.net/gh/BENUTZERNAME/smashai-n8n-chat/chat-widget.js"></script>
```

Ersetzen Sie `<Ihre n8n-Webhook-URL>` mit der URL Ihres n8n-Webhooks und passen Sie die Branding- und Style-Optionen nach Ihren Wünschen an.