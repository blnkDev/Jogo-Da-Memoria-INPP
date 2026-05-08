<div align="center">

# 🐾 Sons do Pantanal
### Jogo da Memória Sonora — Fauna do Pantanal

<p>
  <img src="https://img.shields.io/badge/Plataforma-HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white"/>
  <img src="https://img.shields.io/badge/Engine-Construct%202-00ADEF?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Design-Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white"/>
  <img src="https://img.shields.io/badge/Status-Concluído-2ea44f?style=for-the-badge"/>
</p>

<p>
  <a href="https://blnkdev.github.io/Jogo-Da-Memoria-INPP/">
    <img src="https://img.shields.io/badge/🎮%20Jogar%20Agora-GitHub%20Pages-181717?style=for-the-badge&logo=github"/>
  </a>
</p>

</div>

---

Protótipo de jogo educativo digital desenvolvido como parte do processo seletivo para bolsista no **Perfil 2 – Desenvolvimento de Aplicações Interativas/Jogos Educativos** do **Instituto Nacional de Pesquisa do Pantanal (INPP/MCTI)**.

O jogo aborda a **fauna do Pantanal** com foco em aprendizado sonoro e associação visual, combinando duas fases pedagógicas distintas: exposição implícita durante a partida e teste de assimilação ao final.

---

## 🎮 Como Jogar

### Fase 1 — Jogo da Memória
- Clique em duas cartas para revelá-las
- Ao virar cada carta, o **som do animal** é reproduzido automaticamente
- Encontre todos os pares para concluir a fase
- Você tem um **temporizador** rodando — quanto mais rápido, melhor a pontuação

### Fase 2 — Quiz de Sons
- Após completar o jogo da memória, você é levado ao quiz
- Um som de animal é reproduzido e você deve identificar a qual animal ele pertence
- Essa fase testa a associação aprendida implicitamente durante a partida

---

## 🦁 Animais do Pantanal

| Animal | Som incluído | Curiosidade |
|---|---|---|
| 🐆 Onça Pintada | ✅ | Sim |
| 🦤 Tuiuiú | ✅ | Sim |
| 🐜 Tamanduá Bandeira | ✅ | Sim |
| 🦫 Capivara | ✅ | Sim |

---

## ✅ Funcionalidades Implementadas

### Obrigatórias
- [x] Cartas com ilustrações dos animais
- [x] Reprodução de sons ao interagir com as cartas
- [x] Associação entre som e animal (via Quiz de Sons)
- [x] Sistema de pontuação

### Diferenciais
- [x] Feedback visual de acerto/erro
- [x] Interface responsiva (tablets e totens)
- [x] Temporizador
- [x] Exibição de curiosidades sobre os animais
- [x] Melhorias de UX/UI
- [X] Sistema de recorde baseado na pontuação 

---

## 🛠️ Tecnologias Utilizadas

| Tecnologia | Uso |
|---|---|
| **Construct 2** | Engine principal de desenvolvimento |
| **Figma** | Design de interfaces e assets visuais do jogo |
| **HTML5 + JavaScript** | Plataforma de exportação |
| **Web Audio API** | Reprodução dos sons dos animais |

> O Construct 2 é uma engine de jogos 2D baseada em eventos visuais. O arquivo `.capx` disponível no repositório é o projeto-fonte completo e editável. A pasta de export contém a versão jogável diretamente no navegador.

---

## 🗂️ Estrutura do Repositório

```
Jogo-Da-Memoria-INPP/
├── project/              # Arquivo-fonte .capx (Construct 2)
├── export/               # Versão exportada em HTML5 (jogável no navegador)
│   ├── index.html
│   └── ...
├── assets/               # Imagens e sons utilizados
└── README.md
```

---

## ▶️ Como Executar

### 🌐 Versão Web (recomendada)
Acesse diretamente pelo navegador, sem instalação:

**👉 [blnkdev.github.io/Jogo-Da-Memoria-INPP](https://blnkdev.github.io/Jogo-Da-Memoria-INPP/)**

Compatível com navegadores modernos (Chrome, Firefox, Edge) em desktops, tablets e totens.

### 🛠️ Editar o projeto
1. Instale o [Construct 2](https://www.construct.net/en/construct-2/manuals/construct-2/getting-started/installing-construct-2)
2. Abra o arquivo `.capx` localizado na raiz do repositório

---

## 💡 Decisões de Desenvolvimento

**Por que Construct 2?**
Ferramenta com a qual o desenvolvedor possui domínio e licença ativa, permitindo entrega dentro do prazo de 72h com qualidade e foco na experiência do usuário, sem curva de aprendizado adicional.

**Por que duas fases?**
A separação entre o jogo da memória e o quiz de sons segue uma lógica pedagógica intencional: a **exposição implícita** durante a partida (ouvir o som ao virar cada carta, repetidamente) prepara o jogador para o **teste explícito** do quiz. O aprendizado acontece de forma natural, sem pressão inicial.

---

## 👤 Autor

**Oliveira Neto Santos Filho**
Candidato à bolsa — Perfil 2: Desenvolvimento de Aplicações Interativas/Jogos Educativos
[github.com/blnkDev](https://github.com/blnkDev)

---

*Desenvolvido para o processo seletivo do Instituto Nacional de Pesquisa do Pantanal (INPP) — Ministério de Ciência, Tecnologia e Inovação (MCTI)*
