# ♟️ Projeto Xadrez em Console - C#

Este é um projeto de um jogo de xadrez simples desenvolvido em **C#**, rodando diretamente no terminal (console). O principal objetivo é praticar lógica de programação, orientação a objetos e interações via console com um clássico exemplo de jogo estratégico.

---

## 🚀 Como iniciar

### 1. Requisitos

Antes de tudo, certifique-se de ter os seguintes recursos instalados:

- ✅ [.NET Core Runtime 2.1.30 (Windows x64)](https://builds.dotnet.microsoft.com/dotnet/Runtime/2.1.30/dotnet-runtime-2.1.30-win-x64.exe)  
- ✅ [Visual Studio](https://visualstudio.microsoft.com/pt-br/) (ou outro editor compatível com C#)

### 2. Clonar o repositório

Abra o terminal e digite:

```bash
git clone https://github.com/AlvaroMoraa/Xadrez-console.git
````
### 3. Abrir a solução
       • Navegue até a pasta do projeto clonado.
       • Abra o arquivo xadrez-console.sln no Visual Studio.

### 4. Executar o projeto
       • Compile e inicie o projeto.
       • O jogo será executado diretamente no console.

## 🎮 Como jogar
       • O jogo exibe o tabuleiro no console.
       • Escolha uma peça digitando sua posição atual (exemplo: e2).
       • Em seguida, informe a posição de destino (exemplo: e4).
       • O tabuleiro será atualizado após cada jogada.

## 📁 Estrutura do projeto

xadrez-console/
├── tabuleiro/
│   ├── Cor.cs
│   └── Peca.cs
│   └── Posicao.cs
│   └── Tabuleiro.cs
│   └── TabuleiroException.cs
├── xadrez/
│   └── Bispo.cs
│   └── Cavalo.cs
│   └── Dama.cs
│   └── PartidaDeXdrez.cs
│   └── Peao.cs
│   └── PosicaoXdrez.cs
│   └── Rei.cs
│   └── Torre.cs
├── Program.cs
├── Tela.cs

## 📌 Observações

• Este projeto tem fins educacionais
