# 🏆 Calculadora de Partidas Rankeadas

Este projeto foi desenvolvido como desafio prático para treinar lógica de programação em JavaScript.
O objetivo é calcular o saldo de vitórias e derrotas de um jogador e classificar seu nível dentro de um sistema de ranks.

# 📌 Funcionalidades

- Solicita ao usuário seu nome

- Solicita quantidade de vitórias e derrotas

- Valida se os valores informados são números válidos

- Calcula o saldo de partidas ranqueadas (vitórias - derrotas)

- Retorna o nível do jogador com base em sua performance

# 🎮 Regras de Classificação
| Vitórias | Nível    |
| -------- | -------- |
| undefined| Lixo     |
| 0 - 10   | Ferro    |
| 11 - 20  | Bronze   |
| 21 - 50  | Prata    |
| 51 - 80  | Ouro     |
| 81 - 90  | Diamante |
| 91 - 100 | Lendário |
| 101+     | Imortal  |


📢 Mensagem exibida ao final:
```css
O Herói tem saldo de {saldoVitorias} vitórias e está no nível de {nivel}
```
# 🛠 Tecnologias Utilizadas

[Node.js](https://nodejs.org/pt)

[prompt-sync](https://www.npmjs.com/package/prompt-sync)
 para entrada de dados no console

# ▶️ Como Executar o Projeto

Clone este repositório:
```bash
git clone https://github.com/Sousa-gf/Desafio-Calculadora-Partidas-Ranqueadas-DIO.git
```

Acesse a pasta do projeto:
```bash
cd Desafio-Calculadora-Partidas-Ranqueadas-DIO
```

Instale a dependência necessária:
```bash
npm install prompt-sync
```

Execute o código:
```bash
node script.js
```
# 📚 Aprendizados

- Uso de funções para organizar a lógica

- Estruturas de decisão (if / else if / else)

- Estruturas de repetição (while) para validação de entradas

- Manipulação de entrada de dados no Node.js

# ✨ Autor

👤 [Gabriel Sousa](https://github.com/Sousa-gf)