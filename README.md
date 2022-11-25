#Github-webhooks

**Passo 1 - Faça um Webhook do Discord**

1. Encontre o canal Discord no qual você gostaria de enviar commits e outras atualizações

2. Nas configurações desse canal, encontre a opção Webhooks e crie um novo webhook. Observação: NÃO forneça este URL ao público. Qualquer pessoa ou serviço pode postar mensagens neste canal, mesmo sem precisar estar no servidor. Mantenha-o seguro!

![Print seção webhook discord](https://i.imgur.com/ESzN2gY.png "Print seção webhook discord")

**Passo 2 - Configure o webhook no Github**

1. Navegue até seu repositório no Github e abra as Configurações
![Print seção webhook discord](https://i.imgur.com/OaLjeY2.png "Print seção webhook discord")

2. Selecione **add webhook**
![Print seção webhook discord](https://i.imgur.com/Rl5UgLi.png "add webhook")

3. Cole o URL do webhook e anexe `/github` ao final. Selecione "Envie-me tudo", defina o tipo como `application/json` e, em seguida, adicione Webhook
![Print seção webhook discord](https://i.imgur.com/FyoOTPB.png "add webhook")

4. Apos teste o webhook dando uma 🌟 no projeto.
![test webhook](https://i.imgur.com/HsFE7ha.png "test webhook")


> Esse tutorial foi traduzido para o portgues de um .MD encontrado no GITHUB, refencia ao autor feito em fontes.
