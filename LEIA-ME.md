# QR Code da Sorte — Frase Motivacional da Semana

Página estática, responsiva e em português. Não precisa de servidor, cadastro ou banco de dados; o sorteio acontece no navegador de cada pessoa. O arquivo editável do projeto é `index.html`.

## Publicar gratuitamente com GitHub Pages

1. Crie uma conta gratuita em [GitHub](https://github.com/) ou entre na sua conta.
2. Crie um repositório público, por exemplo `qr-da-sorte`.
3. Envie o arquivo `index.html` para a raiz do repositório. O `LEIA-ME.md` é opcional.
4. No repositório, abra **Settings → Pages**. Em **Build and deployment**, escolha **Deploy from a branch**, selecione `main` e `/(root)`, e salve.
5. Aguarde a publicação indicada nessa tela. O endereço ficará no formato `https://SEU-USUARIO.github.io/qr-da-sorte/`. Abra esse endereço no celular para conferir.

O GitHub pode levar alguns minutos para publicar. Se editar o arquivo depois, o Pages publica a atualização automaticamente.

## Criar o QR Code real

1. Copie o endereço público que o GitHub Pages mostrou depois da publicação.
2. Abra um gerador de QR Code, como [QRCode Monkey](https://www.qrcode-monkey.com/), escolha **URL**, cole o endereço publicado e gere o código.
3. Baixe o QR Code e teste com a câmera de um celular antes de imprimir ou distribuir.

O QR Code precisa apontar para o endereço publicado. Este projeto ainda não tem URL pública; gere o QR Code apenas depois de publicar e confirmar o endereço.

## Editar as frases

Abra `index.html` em um editor de texto. No fim do arquivo, localize `const frases = [` e edite, remova ou acrescente itens seguindo este formato:

```js
{tema:'Motivação', texto:'Sua frase aqui.'},
```

As frases ficam disponíveis no próprio arquivo. Não são enviados nomes, respostas ou dados de acesso por esta página. Cada sorteio seleciona uma mensagem aleatoriamente; por isso, funcionários diferentes podem receber a mesma frase. Ao sortear novamente na mesma tela, a frase imediatamente anterior é evitada.
