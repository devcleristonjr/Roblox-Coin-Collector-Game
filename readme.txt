# 🛠️ Roblox Coin Collector Game

Este é um projeto desenvolvido no Roblox Studio com o objetivo de demonstrar conceitos fundamentais de scripting em Lua dentro da plataforma.

## 🎮 Funcionalidades

- 💰 **Sistema de moedas**  
  As moedas podem ser coletadas pelos jogadores. Ao coletar, elas desaparecem temporariamente e retornam após alguns segundos. O número de moedas é rastreado com `leaderstats`.

- 🌀 **Boost de pulo**  
  Os jogadores podem comprar um boost de pulo ao clicar em um botão. O custo é descontado em moedas, com mensagens exibidas para saldo insuficiente ou compra bem-sucedida.

- 🔄 **Moedas giratórias**  
  As moedas possuem rotação contínua para chamar atenção visualmente.

- 🚀 **Plataforma móvel**  
  Uma plataforma se move entre dois pontos invisíveis utilizando TweenService, permitindo locomoção entre ilhas.

- 📢 **Mensagens de feedback**  
  TextLabels aparecem na tela informando o status da compra (sucesso ou erro).

## 🧱 Estrutura

- `leaderstats` é gerado automaticamente no `ServerScriptService`
- Scripts individuais em moedas, botão de compra e plataforma
- Uso de `ClickDetector`, `Touched` e `TweenService`

## 📹 Demonstração em vídeo

Veja o projeto funcionando em tempo real:

🔗 **Link do vídeo:** *[Adicione aqui o link quando disponível]*

---

## 🧪 Como testar

1. Abra o projeto no Roblox Studio
2. Clique em "Play" (F5) para iniciar como jogador
3. Colete moedas, compre o boost e use a plataforma móvel

---

## 📂 Requisitos

- Roblox Studio instalado
- Conhecimento básico em Lua e ambiente 3D

---

## ✨ Créditos

Criado por **Clay Dixon** como experimento de mecânicas de jogo no Roblox.
