# Emvio de sms de notificação via Twilio

O projeto consiste em um simples script de envio de sms através de uma planilha .csv para vários contatos de uma vez. 

### Setup
Você deve ter o Node.js e o npm instalados em seu computador e uma conta Twilio ativa. Depois disso clone o projeto com o seguinte comando:

```
git clone https://github.com/cleosilva/twilio-sms-csv.git
```

```
cd twilio-sms-csv

npm install
```

### Configurando as variáveis de ambiente

```
TWILIO_ACCOUNT_SID=[INSIRA_SUA_ACCOUNT_SID]
TWILIO_AUTH_TOKEN=[INSIRA_SUA_AUTH_TOKEN]
PHONE_NUMBER=[INSIRA_SEU_NUMERO_TWILIO]
```

### Rodando o scrip localmente

```
node index.js
```

### Funcionalidade
O script envia uma mensagem de sms para vários contatos ao mesmo tempo personalizada conforme dados da planilha.





