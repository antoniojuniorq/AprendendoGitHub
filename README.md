# 🎯 Jogo do Número Secreto

Um jogo simples feito com HTML, CSS e JavaScript em que o jogador tenta adivinhar um número sorteado pelo computador. A cada chute, o jogo diz se o número secreto é **maior** ou **menor**, até o jogador acertar.

Projeto desenvolvido durante o curso de **Git e GitHub** para praticar versionamento de código.

## ✨ Funcionalidades

- Sorteio de um número aleatório entre **1 e 60**
- Dicas a cada tentativa ("o número secreto é maior/menor")
- Contagem de tentativas até o acerto
- Números já sorteados não se repetem até que todos tenham saído
- Leitura em voz alta das mensagens (português do Brasil) com a biblioteca [ResponsiveVoice](https://responsivevoice.org/)
- Botão **Novo jogo** para recomeçar após acertar

## 🛠️ Tecnologias

- HTML5
- CSS3
- JavaScript
- [ResponsiveVoice.js](https://responsivevoice.org/) (síntese de voz)
- Google Fonts (Chakra Petch e Inter)

## 📁 Estrutura

```
3386-git-github-projeto_inicial/
├── index.html   # Página do jogo
├── style.css    # Estilos
├── app.js       # Lógica do jogo
└── img/         # Imagens usadas na página
```

## 🚀 Como executar

1. Clone o repositório:
   ```bash
   git clone <url-do-repositorio>
   ```
2. Abra a pasta `3386-git-github-projeto_inicial`.
3. Abra o arquivo `index.html` no navegador.

> É necessário estar conectado à internet para carregar as fontes e a biblioteca de voz.

## 🎮 Como jogar

1. Digite um número no campo.
2. Clique em **Chutar**.
3. Siga as dicas até descobrir o número secreto.
4. Clique em **Novo jogo** para jogar novamente.

## ⚙️ Personalização

Para mudar a dificuldade, altere o valor de `numeroLimite` em `app.js`:

```js
let numeroLimite = 60;
```
