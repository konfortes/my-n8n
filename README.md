# my-n8n


## Integrations 

### Telegram

Get your bot token from [BotFather](https://t.me/botfather).
Set webhook with n8n's url:

```bash
curl -X POST https://api.telegram.org/bot<your-bot-token>/setWebhook -d "url=https://<your-n8n-url>/webhook/telegram"
```

```sh
curl -X GET https://api.telegram.org/bot<your-bot-token>/getWebhookInfo
```