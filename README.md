# 🐍 Python Practice Projects

A collection of small command-line projects made in pure Python, created to practice programming fundamentals.

## 📁 Projects

1. [🔐 Caesar Cipher](#-caesar-cipher)
2. [✊✋✌️ Rock, Paper, Scissors](#️-rock-paper-scissors)

---

## 🔐 Caesar Cipher

A simulation of the **Caesar Cipher**, one of the earliest known encryption techniques, where each letter is shifted a fixed number of positions in the alphabet.

### 🎮 How It Works

1. Choose whether you want to `encode` or `decode` a message.
2. Type your message.
3. Choose how many steps (shift) to apply.
4. The program prints the result and asks if you want to continue.

### Features

- Encode and decode messages
- Custom shift value
- Spaces, numbers, and punctuation are kept unchanged
- Run as many times as you want without restarting the program

### Example

```
Digite encode para criptografar e decode para descriptografar
encode
Qual a sua mensagem para encode?ola mundo
Quantos passos voce quer dar na criptografia?3
Ta aqui a sua encode message = rod pxqgr
```

### Limitations

- Only works with letters from `a` to `z` (no accents)
- The output is always lowercase

### 📚 Concepts Practiced

- Lists and the `.index()` method
- `for` and `while` loops
- Functions with keyword arguments
- The modulo operator (`%`) to wrap around the alphabet
- User input with `input()`

---

## ✊✋✌️ Rock, Paper, Scissors

A command-line Rock, Paper, Scissors game against the computer, played in 3 rounds.

### 🎮 How to Play

Each round, type the number of your move:

| Number | Move     |
|:------:|----------|
| 0      | Rock     |
| 1      | Paper    |
| 2      | Scissors |

The computer picks a random move, and the program tells you whether you **won**, **lost**, or **tied**. Numbers outside the 0–2 range are treated as invalid moves.

### 📚 Concepts Practiced

- The `random` module
- Conditional statements (`if`, `elif`, `else`) and logical operators (`and`, `or`)
- `for` loops with `range()`
- Input validation

---

## 🛠️ Technologies

- Python 3
- `random` module (Rock, Paper, Scissors)

## 📦 Installation

You only need **Python 3** installed. There are no external dependencies.

```bash
git clone https://github.com/SEU-USUARIO/Encryption-system.git
cd Python-Projects
```

Or download the `.zip` from **Code > Download ZIP** and extract it.

## ▶️ How to Run

```bash
python "Python CAESAR CIPHER.py"
python "Python GAME.py"
```

## 💡 About the Project

These are some of my Python practice projects, created while learning programming fundamentals and experimenting with basic logic.

## 👨‍💻 Author

**Lucas Gabriel** · [GitHub](https://github.com/lucasz-gabriel)
