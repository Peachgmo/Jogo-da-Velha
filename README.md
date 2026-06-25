# ❌ Jogo da Velha (Tic-Tac-Toe) ⭕

Um jogo da velha clássico, minimalista e responsivo, desenvolvido como um projeto de estudo utilizando a engine **Godot 4.3**.

---

## 🚀 Funcionalidades

*   **Modo Local:** Jogue com um amigo no mesmo dispositivo (Jogador 1 vs Jogador 2).
*   **Interface Responsiva:** Adapta-se automaticamente a diferentes resoluções de tela.
*   **Controle de Turnos:** Sistema automatizado que gerencia a vez de cada jogador.
*   **Detecção de Vitória/Empate:** O jogo identifica automaticamente linhas, colunas e diagonais fechadas, além de cenários de velha.
*   **Efeitos Sonoros e Visuais:** Feedbacks rápidos ao clicar nas casas e ao finalizar a partida.
*   **Reinício Rápido:** Botão dedicado para recomeçar o tabuleiro sem recarregar o jogo.

---

## 🛠️ Tecnologias Utilizadas

*   **Engine:** [Godot 4.3](https://godotengine.org) (Versão Standard).
*   **Linguagem de Programação:** GDScript.
*   **Elementos de UI:** Control Nodes, GridContainer, TextureButton e Temas customizados.

---

## 📦 Como Executar o Projeto

### Pré-requisitos
Você precisará ter o **Godot Engine 4.3** instalado em sua máquina.

### Passo a Passo
1. Faça o clone deste repositório ou baixe o arquivo ZIP:
   ```bash
   git clone https://github.com
   ```
2. Abra o **Godot Engine**.
3. Clique em **Importar** (Import) no gerenciador de projetos.
4. Navegue até a pasta do projeto clonado e selecione o arquivo `project.godot`.
5. Clique em **Editar** (Edit) para abrir o projeto.
6. Pressione `F5` ou clique no botão de **Play** no canto superior direito para rodar o jogo.

---

## 📐 Estrutura do Código

A arquitetura do projeto foi pensada de forma simples e modular:
*   `scenes/`: Contém as cenas principais do jogo (Menu, Tabuleiro, Interface).
*   `scripts/`: Arquivos `.gd` que controlam a lógica do tabuleiro e estados do jogo.
*   `assets/`: Texturas, fontes, imagens (X e O) e arquivos de áudio.

---

## 📝 Licença

Este projeto está sob a licença MIT. Consulte o arquivo [LICENSE](LICENSE) para obter mais detalhes.
