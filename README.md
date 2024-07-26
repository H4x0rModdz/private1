# Criando Seu Primeiro Projeto no Google Developer Cloud

## Passo a Passo

### 1. Acessar o Google Cloud Console

Acesse o site: [Google Cloud Console](https://console.cloud.google.com/).

### 2. Selecionar ou Criar um Projeto

- Clique em "Selecione um Projeto" ou, caso já tenha um, clique no nome do seu projeto.
  
  ![Selecionar Projeto](IMG-Google-1.png)

- Clique em "Novo Projeto".
  
  ![Novo Projeto](IMG-GOOGLE-2.png)

- Coloque o nome do seu projeto, organização (caso tenha uma) e clique em "Criar".
  
  ![Criar Projeto](IMG-GOOGLE-3.png)

### 3. Configurar Tela de Consentimento OAuth

- Vá para "Credenciais" e clique em "Configurar Tela de Consentimento".
  
  ![Configurar Tela de Consentimento](IMG-GOOGLE-4.png)

- Ative o modo "Externo" e clique em "Criar".
  
  ![Ativar Modo Externo](IMG-GOOGLE-5.png)

- Preencha suas credenciais para o App e clique em "Salvar e Continuar".
  
  ![Preencher Credenciais](IMG-GOOGLE-6.png)
  
  ![Salvar e Continuar](IMG-GOOGLE-7.png)

- O restante como Escopos, Usuários de teste e Resumo pode deixar como está e clicar em "Voltar Para o Painel".
  
  ![Voltar Para o Painel](IMG-GOOGLE-8.png)

- Vá para "Tela de Consentimento OAuth" e clique em "Publicar App" e, após isso, clique em "Confirmar".
  
  ![Publicar App](IMG-GOOGLE-13.png)

### 4. Criar Credenciais OAuth

- Vá para "Credenciais" novamente e clique em "Criar Credenciais" e escolha "ID do Cliente do OAuth".
  
  ![Criar Credenciais](IMG-GOOGLE-9.png)

- Copie seu ID do Cliente e seu Segredo do Cliente e armazene em um local seguro, depois clique em "OK".
  
  ![Copiar Credenciais](IMG-GOOGLE-10.png)

### 5. Usar OAuth Playground

- Acesse o [OAuth 2.0 Playground](https://developers.google.com/oauthplayground/).

- Autorize os seguintes escopos na primeira etapa:
  
  ![Autorizar Escopos](IMG-GOOGLE-11.png)
  
  ![Selecionar Escopos](IMG-GOOGLE-12.png)

- Certifique-se de ter todos os escopos necessários e clique em "Autorizar APIs".
  
  ![Autorizar APIs](IMG-GOOGLE-14.png)

- Escolha sua conta Google e clique em "Continuar".
  
  ![Escolher Conta Google](IMG-GOOGLE-15.png)
  
  ![Continuar](IMG-GOOGLE-16.png)

- Você será redirecionado ao Playground e terá o seu Authorization Code. Clique em "Exchange authorization code for tokens" e copie o seu Access Token.
  
  ![Obter Authorization Code](IMG-GOOGLE-17.png)

### 6. Usar o Access Token em Sua API

Use o Access Token obtido em sua API para autenticação e pronto!
  
  ![Usar Access Token](IMG-GOOGLE-18.png)
