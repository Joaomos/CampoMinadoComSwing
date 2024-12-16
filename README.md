# 🎮 Campo Minado

Este é um projeto de **Campo Minado** desenvolvido em Java com o objetivo de consolidar conceitos fundamentais de programação orientada a objetos (POO). O jogo agora conta com uma **interface gráfica** implementada utilizando Swing, tornando-o mais interativo e visualmente atraente.

---

## 🖥️ Interface Gráfica

A interface gráfica foi desenvolvida com a biblioteca **Swing**, proporcionando uma experiência visual para os jogadores.  
Os botões representam os campos do tabuleiro, que mudam de aparência conforme as interações do usuário:

- **Campo marcado:** Exibe um "M".
- **Campo aberto sem mina:** Mostra o número de minas nas proximidades.
- **Campo aberto com mina:** Exibe "X" e muda a cor para vermelho ao explodir.

---

## 📦 Estrutura do Projeto

O projeto é dividido em dois pacotes principais:

### 1. `br.com.joaomos.cm.modelo`

Contém toda a lógica de funcionamento do jogo, como regras de abertura de campos, marcações, explosões e a representação do tabuleiro.

- **Classes principais:**
  - `Campo`: Representa cada célula do tabuleiro.
  - `Tabuleiro`: Gerencia os campos, associa vizinhos e controla as minas.
  - `ResultadoEvento`: Indica se o jogador ganhou ou perdeu.
  - `CampoEvento` (Enum): Representa os eventos de um campo (abrir, marcar, explodir, etc.).

### 2. `br.com.joaomos.cm.visao`

Implementa a interface gráfica utilizando Swing.

- **Classes principais:**
  - `BotaoCampo`: Representa cada botão do tabuleiro e aplica estilos dependendo do estado do campo.
  - `PainelTabuleiro`: Monta o tabuleiro graficamente.
  - `TelaPrincipal`: Classe principal que inicializa a aplicação gráfica.

---

## 🔧 Como Executar o Projeto

1. **Clone o repositório**:
   ```bash
   git clone https://github.com/seu-usuario/campo-minado.git
   cd campo-minado

2. **Compile e execute o projeto:**:
   - Utilize uma IDE como Eclipse ou IntelliJ.
   - Execute a classe TelaPrincipal para iniciar o jogo.

## 📚 Tecnologias Utilizadas

- **Linguagem:** Java  
- **Interface Gráfica:** Swing  
- **Conceitos Aplicados:**  
  - Programação Orientada a Objetos (POO)  
  - Expressões Lambda  
  - Streams  
  - Encapsulamento  
  - Tratamento de Erros  
- **Framework de Testes:** JUnit  

---

## 🔍 Exemplo de Uso

Ao iniciar o programa, a interface gráfica será exibida.  

1. **Interações com os botões:**  
   - **Clique esquerdo:** Abre o campo.  
   - **Clique direito:** Marca ou desmarca o campo.  
2. **Resultado do jogo:**  
   - Uma mensagem será exibida ao ganhar ou perder a partida.
     
---

## 🚀 Contribuições

Contribuições são sempre bem-vindas!  

1. **Relatar problemas:** Abra uma *issue* no repositório.  
2. **Melhorias e novas funcionalidades:** Envie sugestões ou um *pull request*.  
3. **Compartilhe feedback:** Ajude a melhorar o projeto!  
