# 🐾 Jogo da Memória INPP

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
├── export/               # Versão exportada em HTML5 (jogável no navegador)
│   ├── index.html
│   └── ...
├── assets/               # Imagens e sons utilizados
└── README.md
```

---

## ▶️ Como Executar

### Versão Web (recomendada)
> *(instruções de execução serão adicionadas após exportação do projeto)*

### Editar o projeto
1. Instale o [Construct 2](https://www.construct.net/en/construct-2/manuals/construct-2/getting-started/installing-construct-2)
2. Abra o arquivo `.capx` localizado na pasta `project/`

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
