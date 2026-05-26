# Chess System Java

Jogo de xadrez rodando no terminal, desenvolvido durante o curso
Java Completo da Udemy. O objetivo foi aplicar os princípios de OOP
em um domínio com regras complexas.

## O que apliquei

- Separação em duas camadas independentes: `boardgame` (tabuleiro genérico) e `chess` (regras específicas do xadrez) — o tabuleiro não conhece xadrez
- Herança e polimorfismo: cada peça (`Rook`, `Bishop`, `Knight`, `Pawn`, `Queen`, `King`) estende `ChessPiece` e implementa seus próprios movimentos
- Tratamento de exceções customizadas (`BoardException`, `ChessException`) para separar erros de domínio de erros de infraestrutura
- Lógica de movimentos especiais: roque, en passant e promoção de peão
- Renderização no terminal via classe `UI` com controle de posições e cores

## Stack

Java · OOP · CLI

## Como executar

1. Clonar o repositório
2. Abrir na IDE (Eclipse ou IntelliJ)
3. Executar `application/Program.java`

Não requer dependências externas.

## Status

Concluído. O projeto cobre todas as peças e movimentos especiais do xadrez padrão. Possível evolução: adicionar lógica de xeque-mate automático e interface gráfica.