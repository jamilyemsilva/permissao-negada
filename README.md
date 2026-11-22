# Permissão Negada

Projeto final da disciplina de Introdução a Algoritmos/Programação, desenvolvido com Python e Pygame.

## Integrantes do grupo

- Arthur Domingues
- Jamily E Silva
- Lucas Henrique Barbosa
- Larissa Monção de Oliveira
- Paulo Henrique de Melo

## Estrutura do projeto

- `main.py`: ponto de entrada da aplicação.
- `src/`: código-fonte principal do jogo (loop, regras, sprites e dados).
- `assets/`: imagens, fontes e sons.
- `data/`: arquivos persistentes (recorde/ranking).
- `tests/`: testes unitários com `pytest`.
- `docs/`: documentação do projeto, incluindo proposta inicial.

## Descrição do jogo

O jogador deverá gerenciar um celular novo, analisando as permissões solicitadas por diferentes aplicativos. Na tela, aparecerá um cartão contendo o nome do aplicativo, sua categoria e as permissões solicitadas, como câmera, localização, contatos, microfone e fotos.

Para cada solicitação, o jogador deverá escolher entre os botões "Permitir" ou "Negar". Cada decisão modificará dois medidores: Privacidade e Utilidade.

O jogo será dividido em três fases, com níveis de dificuldade fácil, médio e difícil. Ao final de cada fase, caso a privacidade esteja abaixo de 60%, o jogador precisará resolver um pequeno puzzle para tentar recuperá-la. Permitir permissões desnecessárias poderá gerar eventos de vazamento de dados, enquanto negar permissões essenciais poderá comprometer o funcionamento dos aplicativos.

## Objetivo do jogador

Concluir as três fases mantendo os medidores de Privacidade e Utilidade em equilíbrio, sem perder todas as vidas. Para isso, o jogador deverá analisar cada solicitação e conceder apenas as permissões realmente necessárias para o funcionamento dos aplicativos.

## Regras do jogo

Regra 1: Cada aplicativo apresentará uma ou mais permissões, e o jogador deverá decidir individualmente entre permitir ou negar cada solicitação.
Regra 2: Cada decisão alterará os medidores de Privacidade e Utilidade de acordo com a relevância da permissão para a categoria do aplicativo.
Regra 3: Negar todas as permissões poderá reduzir a Utilidade, enquanto permitir todas poderá comprometer a Privacidade e gerar eventos de vazamento de dados.
Regra 4: Ao final de cada fase, se a Privacidade estiver abaixo de 60%, o jogador deverá resolver um puzzle. Caso erre, avançará para a próxima fase com o medidor reduzido e perderá uma vida.
Regra 5: Se qualquer um dos medidores chegar a 0 ou todas as vidas forem perdidas, a partida será encerrada.

## Controles

Informe as teclas ou comandos utilizados no jogo.
(em construção)

## Como executar o projeto

### 1. Clonar o repositório

```bash
git clone LINK_DO_REPOSITORIO
cd permissao-negada
pip install -r requirements.txt
python main.py
```

## Como executar os testes

```bash
python -m pytest
```

## Checklist mínimo para entrega

- Preencher este README com nome final, descrição real, regras e controles do jogo.
- Atualizar `docs/proposta.MD` com a proposta do grupo.
- Garantir que o jogo executa com `python main.py`.
- Garantir que os testes passam com `pytest`.

## Observações para os alunos

- Mantenham o código organizado em módulos pequenos e com responsabilidade clara.
- Comentem partes importantes da lógica, principalmente regras do jogo.
- Registrem decisões técnicas no README do grupo ao longo do desenvolvimento.
