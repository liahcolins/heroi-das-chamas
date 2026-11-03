# Herói das Chamas

## Sobre o projeto

**Herói das Chamas** é um mini jogo de navegação desenvolvido como parte do desafio **HTML - Casa Virtual**. O jogador assume o papel de um(a) bombeiro(a) que precisa entrar em uma casa em chamas e encontrar a pessoa que ainda está em um dos cômodos.

O jogo começa na rua, em frente à casa. A cada etapa, o jogador visualiza o cômodo em que está e escolhe uma das opções de navegação disponíveis. A missão termina quando ele chega ao segundo quarto.

## Objetivo

Explorar a casa por meio das portas e da janela, seguindo as opções apresentadas em cada página, até encontrar o segundo quarto e concluir o resgate.

## Tecnologias utilizadas

- **HTML5:** estrutura das páginas e navegação entre os cômodos.
- **Links (`<a>`):** permitem que o jogador escolha para onde ir.

O projeto utiliza somente HTML, sem CSS e sem JavaScript. Cada cômodo é representado por um arquivo HTML independente.

## Estrutura dos arquivos

```text
heroi_das_chamas/
├── index.html       # Rua: início do jogo
├── sala.html        # Sala
├── corredor.html    # Corredor
├── cozinha.html     # Cozinha
├── banheiro.html    # Banheiro
├── quarto1.html     # Primeiro quarto
├── quarto2.html     # Segundo quarto: conclusão da missão
└── README.md        # Documentação do projeto
```

## Como executar

1. Baixe ou extraia os arquivos do projeto para uma mesma pasta.
2. Abra o arquivo `index.html` em um navegador de internet.
3. Leia a apresentação e escolha uma das opções disponíveis.
4. Continue navegando pelos cômodos até chegar ao segundo quarto.
5. Ao concluir o resgate, selecione **Jogar novamente** para retornar ao início.

Não é necessário instalar dependências, configurar um servidor ou ter acesso à internet para executar o jogo localmente.

## Funcionamento da navegação

A navegação é realizada por links entre os arquivos HTML:

- **Rua (`index.html`):** permite entrar pela porta, chegando à sala, ou pela janela, chegando diretamente ao segundo quarto.
- **Sala (`sala.html`):** permite seguir para o corredor, entrar no segundo quarto ou sair novamente para a rua.
- **Corredor (`corredor.html`):** permite voltar à sala ou seguir para a cozinha.
- **Cozinha (`cozinha.html`):** permite voltar ao corredor ou entrar no primeiro quarto e no banheiro.
- **Banheiro (`banheiro.html`):** permite retornar à cozinha.
- **Primeiro quarto (`quarto1.html`):** permite retornar à cozinha.
- **Segundo quarto (`quarto2.html`):** apresenta a mensagem de missão concluída e a opção para jogar novamente.

As opções são exibidas sem indicar qual caminho leva ao objetivo, deixando a exploração a cargo do jogador.

## Critérios atendidos

- Apresenta o nome do jogo e o objetivo da missão.
- Inicia a experiência na rua.
- Informa a localização atual do jogador em cada página.
- Apresenta opções de navegação por meio de links.
- Não fornece dicas sobre o caminho correto.
- Exibe uma mensagem de conclusão ao acessar o segundo quarto.

---

**Desafio:** HTML - Casa Virtual  
**Jogo:** Herói das Chamas
