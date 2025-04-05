
# 🐣 Tamagotchi Virtual

Este é um pequeno jogo inspirado no clássico **Tamagotchi**, feito com **HTML, CSS e JavaScript**. O objetivo é cuidar do seu bichinho virtual, mantendo-o **alimentado**, **feliz** e com **energia**. Se qualquer um desses atributos chegar a um valor crítico... ele pode morrer! 😢

## 🎮 Funcionalidades

- ✅ Alimentar, brincar e colocar o Tamagotchi para dormir.
- 📉 Barras de status de **fome**, **felicidade** e **energia**.
- 🎭 Emojis que representam o humor e a saúde do pet.
- 🔁 Eventos aleatórios que afetam o estado do bichinho.
- 💾 Salvamento de progresso usando `localStorage`.
- 🔊 Efeitos sonoros para cada ação.

## 📋 Tecnologias utilizadas

- HTML5
- CSS3
- JavaScript puro (vanilla JS)
- Web Storage API (localStorage)
- Áudio embutido via HTML `<audio>`

## 🧠 Lógica do jogo

- O Tamagotchi começa com fome, felicidade e energia igual a 5.
- A cada 5 segundos, a fome aumenta, a felicidade e a energia diminuem.
- A cada 15 segundos, um evento aleatório ocorre (ex: ele fica com fome, triste ou cansado).
- Se a fome chegar a 10, ou se a felicidade ou energia chegarem a 0, o Tamagotchi morre (💀).
- O jogo pode ser reiniciado a qualquer momento.

## 🕹️ Controles

| Botão        | Ação                          |
|--------------|-------------------------------|
| 🍖 Alimentar | Diminui a fome, aumenta a felicidade |
| 🎾 Brincar    | Aumenta felicidade, consome energia e dá fome |
| 😴 Dormir     | Recupera energia, mas aumenta a fome |
| 🔄 Reiniciar  | Reinicia o estado do jogo     |

## 📂 Estrutura

O projeto é composto por um único arquivo HTML contendo:

- Estilos CSS internos
- HTML da interface do jogo
- Scripts JavaScript embutidos no final do arquivo

## 🚀 Como executar

1. Baixe ou clone este repositório.
2. Abra o arquivo `index.html` em qualquer navegador moderno.
3. Comece a cuidar do seu Tamagotchi! 🐤

## 📸 Screenshot

![screenshot](https://via.placeholder.com/600x400.png?text=Tamagotchi+Virtual)

## 🛠️ Possíveis melhorias

- Adicionar sprites ou animações ao invés de emojis.
- Salvar data/hora da última interação para estados offline.
- Criar diferentes tipos de pets.
- Criar níveis de dificuldade.
- Implementar com PWA para rodar offline no celular.
