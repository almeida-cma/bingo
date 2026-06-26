# 🎯 Bingo - Sistema Completo de Bingo com Banca e Participante

Bem-vindo ao repositório do **Bingo**, um sistema web completo que simula um jogo de bingo com duas interfaces independentes: **Banca** e **Participante**.

## 🚀 Demonstração

**Participante (Online):**  
https://almeida-cma.github.io/bingo/

**Repositório:**  
https://github.com/almeida-cma/bingo

---

## 📋 Sobre o Projeto

O sistema possui duas aplicações:

### 🏦 Banca (`Banca.html`)
- Sorteia números de 1 a 60 sem repetição.
- Mantém histórico dos sorteios.
- Exporta os números em JSON.
- Permite reiniciar o jogo.

### 👤 Participante (`index.html`)
- Gera cartela 4x4 com 16 números únicos.
- Permite marcar e desmarcar números.
- Detecta automaticamente o BINGO.
- Importa o JSON da banca para validação oficial.

---

## ✨ Funcionalidades

### Banca
- Sorteio aleatório
- Controle de números repetidos
- Histórico de sorteios
- Exportação JSON
- Reset completo

### Participante
- Cartela automática
- Marcação por clique
- Animação de BINGO
- Validação oficial
- Nova cartela
- Reset

---

## 🛠 Tecnologias

- HTML5
- CSS3
- JavaScript (ES6)
- LocalStorage
- JSON
- GitHub

---

## ▶ Como Executar

### Participante

Acesse:

https://almeida-cma.github.io/bingo/

### Banca

Baixe o arquivo **Banca.html** do repositório e abra-o em qualquer navegador moderno.

---

## 📂 Estrutura

```text
bingo/
├── Banca.html
├── index.html
├── README.md
└── LICENSE
```

---

## 💾 Persistência

São utilizadas as seguintes chaves no LocalStorage:

- bingo_sorteados
- bingo_cartela
- bingo_marcados

---

## 📄 Licença

Licença MIT.

---

🎉 Divirta-se jogando Bingo!
