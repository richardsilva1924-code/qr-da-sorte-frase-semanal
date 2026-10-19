# QR Code da Sorte — Frase Motivacional da Semana

Página estática, responsiva e em português. Não precisa de servidor, cadastro ou banco de dados; o sorteio acontece no navegador de cada pessoa. O arquivo editável do projeto é `index.html`.

## Projeto publicado

- **Página:** [Abrir o QR Code da Sorte](https://richardsilva1924-code.github.io/qr-da-sorte-frase-semanal/)
- **Repositório editável:** [GitHub](https://github.com/richardsilva1924-code/qr-da-sorte-frase-semanal)
- **QR Code:** arquivo `qr-code-da-sorte.png` nesta pasta e na raiz do repositório.

O GitHub Pages publica gratuitamente a branch `main` na raiz do repositório. Ao atualizar os arquivos, uma nova versão é publicada automaticamente depois do build.

## Editar as frases

Abra `index.html` em um editor de texto. No fim do arquivo, localize `const frases = [` e edite, remova ou acrescente itens seguindo este formato:

```js
{tema:'Motivação', texto:'Sua frase aqui.'},
```

As frases ficam disponíveis no próprio arquivo. Não são enviados nomes, respostas ou dados de acesso por esta página. Cada sorteio seleciona uma mensagem aleatoriamente; por isso, funcionários diferentes podem receber a mesma frase. Ao sortear novamente na mesma tela, a frase imediatamente anterior é evitada.
