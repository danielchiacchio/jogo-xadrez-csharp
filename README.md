# Jogo de Xadrez em C#

Jogo de xadrez para dois jogadores, executado no terminal e desenvolvido como projeto de estudo de C# e programação orientada a objetos.

O projeto acompanha o curso de C# do professor [Nelio Alves](https://github.com/acenelio/xadrez-console). A implementação está sendo construída passo a passo e pode evoluir conforme o avanço nas aulas.

## Funcionalidades

- Tabuleiro de xadrez 8 × 8 com coordenadas.
- Alternância de turnos entre as peças brancas e pretas.
- Movimentos das peças e validação de jogadas.
- Destaque das casas possíveis para a peça selecionada.
- Captura de peças, xeque e xeque-mate.
- Roque e captura en passant.

## Requisitos

- SDK do .NET 10 ou superior.

Confira a instalação com:

```bash
dotnet --version
```

O projeto tem como alvo `net10.0`.

## Como executar

Na pasta raiz do repositório, rode:

```bash
dotnet run --project xadrez-console.csproj
```

## Como jogar

O jogo começa com as peças brancas. Quando solicitado, informe a posição de origem e depois a posição de destino usando uma letra de coluna (`a` a `h`) e um número de linha (`1` a `8`).

Exemplo de movimento de peão:

```text
Origem: e2
Destino: e4
```

As casas destacadas após a escolha da origem indicam os destinos possíveis para a peça selecionada.

## Organização do projeto

- `Program.cs`: fluxo principal da partida e leitura das jogadas.
- `Tela.cs`: exibição do tabuleiro e das informações da partida.
- `Tabuleiro/`: estrutura do tabuleiro, posições, peças base, cores e exceções.
- `xadrez/`: regras da partida e implementação das peças.

## Curso de referência

[Repositório do curso — acenelio/xadrez-console](https://github.com/acenelio/xadrez-console)
