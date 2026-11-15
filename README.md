# 🐍 Projetos em Python

Repositório com dois projetos feitos em Python puro, criados para praticar lógica de programação.

## 📁 Projetos

1. [🔐 Cifra de César](#-cifra-de-césar)
2. [✊✋✌️ Pedra, Papel e Tesoura](#️-pedra-papel-e-tesoura)

---

## 🔐 Cifra de César

Simulação da **Cifra de César**, uma das primeiras técnicas de criptografia da história, em que cada letra é deslocada um número fixo de posições no alfabeto.

### Funcionalidades

- Criptografar (`encode`) e descriptografar (`decode`) mensagens
- Escolha livre do número de passos (deslocamento)
- Espaços, números e pontuação são mantidos como estão
- Possibilidade de repetir o processo quantas vezes quiser sem reiniciar o programa

### Conceitos praticados

- Listas e o método `.index()`
- Laços `for` e `while`
- Funções com parâmetros nomeados
- Operador módulo (`%`) para "dar a volta" no alfabeto
- Entrada de dados com `input()`

### Exemplo de uso

```
Digite encode para criptografar e decode para descriptografar
encode
Qual a sua mensagem para encode?ola mundo
Quantos passos voce quer dar na criptografia?3
Ta aqui a sua encode message = rod pxqgr
yes-continuar, no-parar
```

---

## ✊✋✌️ Pedra, Papel e Tesoura

Jogo de pedra, papel e tesoura no terminal, contra o computador, em 3 rodadas.

### Como jogar

A cada rodada, digite o número da sua jogada:

| Número | Jogada  |
|:------:|---------|
| 0      | Pedra   |
| 1      | Papel   |
| 2      | Tesoura |

O computador escolhe uma jogada aleatória e o programa mostra se você **ganhou**, **perdeu** ou **empatou**. Jogadas fora de 0 a 2 são consideradas inválidas.

### Conceitos praticados

- Módulo `random`
- Condicionais (`if` / `elif` / `else`) e operadores lógicos (`and` / `or`)
- Laço `for` com `range()`
- Validação de entrada

---

## 📦 Instalação

Só precisa ter o **Python 3** instalado. Não há dependências externas.

```bash
git clone https://github.com/SEU-USUARIO/NOME-DO-REPOSITORIO.git
cd NOME-DO-REPOSITORIO
```

Ou baixe o `.zip` em **Code > Download ZIP** e extraia.

## ▶️ Como executar

```bash
Python "CAESAR CIPHER.py"
python "Python GAME.py"
```

