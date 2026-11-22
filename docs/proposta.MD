# Proposta Inicial do Jogo

## 1. Nome provisório do jogo

**Nome:**

Permissão Negada

## 2. Integrantes do grupo

- Arthur Domingues
- Jamily Silva
- Larissa Monção de Oliveira
- Lucas Henrique Barbosa
- Paulo Henrique de Melo

## 3. Tema escolhido

**Tema:**

Privacidade e coleta de dados.

**Como esse tema se relaciona com o jogo?**

O tema está presente na mecânica central do jogo. Cada permissão solicitada por um aplicativo possui um custo de privacidade e um benefício de utilidade, que variam de acordo com o contexto. Por exemplo, um aplicativo de mapas solicitar localização é legítimo, enquanto uma lanterna solicitar acesso aos contatos é abusivo. O jogador precisa avaliar cada solicitação e aplicar o princípio do mínimo necessário, entendendo como a conveniência pode comprometer suas informações pessoais.

## 4. Tipo de jogo

**Tipo escolhido:**

Jogo de gerenciamento de recursos com tomada de decisões, no estilo perguntas e respostas, acompanhado de mini puzzles para recuperação de privacidade.

## 5. Descrição geral do jogo

**Descrição:**

O jogador deverá gerenciar um celular novo, analisando as permissões solicitadas por diferentes aplicativos. Na tela, aparecerá um cartão contendo o nome do aplicativo, sua categoria e as permissões solicitadas, como câmera, localização, contatos, microfone e fotos.

Para cada solicitação, o jogador deverá escolher entre os botões "Permitir" ou "Negar". Cada decisão modificará dois medidores: Privacidade e Utilidade.

O jogo será dividido em três fases, com níveis de dificuldade fácil, médio e difícil. Ao final de cada fase, caso a privacidade esteja abaixo de 60%, o jogador precisará resolver um pequeno puzzle para tentar recuperá-la. Permitir permissões desnecessárias poderá gerar eventos de vazamento de dados, enquanto negar permissões essenciais poderá comprometer o funcionamento dos aplicativos.

## 6. Objetivo do jogador

**Objetivo:**

Concluir as três fases mantendo os medidores de Privacidade e Utilidade em equilíbrio, sem perder todas as vidas. Para isso, o jogador deverá analisar cada solicitação e conceder apenas as permissões realmente necessárias para o funcionamento dos aplicativos.

## 7. Regras principais

- **Regra 1:** Cada aplicativo apresentará uma ou mais permissões, e o jogador deverá decidir individualmente entre permitir ou negar cada solicitação.
- **Regra 2:** Cada decisão alterará os medidores de Privacidade e Utilidade de acordo com a relevância da permissão para a categoria do aplicativo.
- **Regra 3:** Negar todas as permissões poderá reduzir a Utilidade, enquanto permitir todas poderá comprometer a Privacidade e gerar eventos de vazamento de dados.
- **Regra 4:** Ao final de cada fase, se a Privacidade estiver abaixo de 60%, o jogador deverá resolver um puzzle. Caso erre, avançará para a próxima fase com o medidor reduzido e perderá uma vida.
- **Regra 5:** Se qualquer um dos medidores chegar a 0 ou todas as vidas forem perdidas, a partida será encerrada.

## 8. Condição de vitória

**Condição de vitória:**

O jogador deverá concluir as três fases, mantendo os medidores de Privacidade e Utilidade acima de 30% e ainda possuindo vidas disponíveis.

Ao finalizar a partida, será apresentada uma tela com a nota de "Cidadão Digital", além de um relatório contendo as decisões incorretas realizadas durante o jogo e explicações sobre os riscos de cada escolha.

## 9. Condição de derrota ou encerramento

**Condição de derrota ou encerramento:**

A partida terminará em Game Over caso o medidor de Privacidade ou Utilidade chegue a 0, ou quando todas as vidas forem perdidas.

O jogo também será encerrado normalmente após a conclusão da terceira fase, apresentando a tela final com o resultado, a pontuação e a avaliação das decisões tomadas pelo jogador.

## 10. Elementos previstos no jogo

- **Personagem ou elemento principal:** Um celular e os cartões dos aplicativos que solicitam permissões.
- **Obstáculos ou desafios:** Aplicativos com solicitações abusivas, pedidos legítimos que podem parecer suspeitos, eventos de vazamento de dados e puzzles de recuperação de privacidade.
- **Itens ou objetos de interação (se houver):** Botões "Permitir" e "Negar", ícones representando as permissões (câmera, localização, contatos, microfone e fotos) e peças utilizadas nos puzzles.
- **Pontuação, vidas, tempo ou progresso:** Dois medidores (Privacidade e Utilidade), quantidade de vidas disponíveis, indicação da fase atual (1 a 3) e nota final de Cidadão Digital.

## 11. Controles previstos

**Controles:**

O jogador utilizará o mouse para interagir com o jogo, clicando nos botões "Permitir" e "Negar", nos menus e nas peças dos puzzles.

## 12. Principais dificuldades esperadas

- **Dificuldade 1:** Balancear os valores de Privacidade e Utilidade para garantir que o jogo seja justo, desafiador e transmita corretamente os conceitos propostos.
- **Dificuldade 2:** Organizar as diferentes telas e estados do jogo (menu inicial, contextualização, fases, puzzles e tela final), além de realizar a leitura e utilização dos dados armazenados no arquivo `apps.json`.
- **Dificuldade 3:** Desenvolver a mecânica dos puzzles e organizar o trabalho em equipe utilizando o GitHub, evitando conflitos entre os arquivos e as implementações dos integrantes.

## 13. Escopo mínimo para a entrega final

**Escopo mínimo:**

A versão mínima do jogo deverá apresentar uma tela inicial, uma tela de contextualização, um conjunto de 10 aplicativos armazenados em um arquivo `apps.json` e cartões interativos com os botões "Permitir" e "Negar".

Também deverá possuir os dois medidores de Privacidade e Utilidade, o sistema de decisões e as três fases com dificuldades progressivas. O jogo deverá implementar as condições de derrota, considerando quando algum medidor chegar a zero, e uma tela final com a nota de Cidadão Digital e a explicação das decisões incorretas.

Os eventos de vazamento poderão ser apresentados por meio de mensagens simples na tela, e os puzzles poderão utilizar mecânicas básicas, priorizando o funcionamento da experiência principal.

## 14. Possíveis melhorias, caso haja tempo

- **Melhoria 1:** Implementação de efeitos sonoros e animações para fornecer feedback às decisões do jogador, incluindo alertas de vazamento de dados.
- **Melhoria 2:** Desenvolvimento de um ranking de pontuações, com os melhores resultados armazenados no arquivo `high_scores.txt`.
- **Melhoria 3:** Adição de novos aplicativos, eventos aleatórios de vazamento de dados e diferentes variações de puzzles para aumentar a variedade e a rejogabilidade.
