# Plano de Teste de Usabilidade

**Projeto:** Conecta Fatec

## 1. Estrutura do Plano de Teste

### Motivação da avaliação

Identificar se a plataforma é amigável, intuitiva e livre de barreiras para os usuários antes do lançamento oficial, garantindo que as funcionalidades principais funcionem sem frustrações.

### Objetivos da avaliação

- Validar a facilidade de navegação e a clareza das funções de rede social do sistema.
- Mapear possíveis bugs visuais ou fluxos confusos na interface.
- Coletar feedbacks para melhorias na experiência do usuário (UX/UI) e performance.

### Critérios a serem avaliados

- **Taxa de sucesso:** Se o usuário consegue terminar a tarefa proposta.
- **Grau de dificuldade:** A percepção do usuário sobre o esforço necessário para concluir a ação.
- **Erros de interface:** Problemas visuais, botões que quebram ou textos confusos.

## Estatísticas de Desempenho e Taxa de Sucesso

Abaixo estão estruturados os dados percentuais de facilidade de execução para cada uma das tarefas propostas durante a avaliação de usabilidade.

### Porção do sistema

A interface core (principal) da aplicação Web e Mobile, cobrindo o fluxo de cadastro, interações sociais (feed, comentários, amizades) e o módulo de comunidades.

### Tarefas a serem executadas

1. Cadastrar-se no sistema
2. Efetuar login
3. Editar o perfil
4. Realizar post no feed
5. Fazer comentário em post de terceiro
6. Entrar em uma comunidade
7. Criar uma comunidade
8. Realizar post dentro de uma comunidade
9. Comentar em um post dentro de uma comunidade
10. Solicitar amizade de terceiros

### Avaliadores

- **Quantidade:** 1
- **Perfil:** Augusto Neres, responsável por conduzir o teste, aplicar o formulário e consolidar os dados coletados.

### Participantes

- **Quantidade:** 7 participantes
- **Perfil:** Alunos e usuários da instituição (José Victor, Paula, Guilherme, Laura, Ana Carolina, Pedro Benetti e Gustavo).

### Ambiente

- **Tipo:** Remoto/Digital (os usuários acessaram o sistema de seus próprios dispositivos, preenchendo um questionário online de avaliação após o uso).

## 2. Resultados Coletados e Estatísticas

### Taxa de Sucesso por Tarefa

O teste mostrou que o sistema é muito maduro nas suas funções principais, atingindo 100% de sucesso na grande maioria das tarefas:

- **Cadastro no sistema:** 100% conseguiram facilmente
- **Efetuar login:** 100% conseguiram facilmente
- **Editar perfil:** 100% conseguiram facilmente
- **Postar no feed:** 100% conseguiram facilmente
- **Comentar em post de terceiros:** 100% conseguiram facilmente
- **Entrar em comunidade:** 100% conseguiram facilmente
- **Criar comunidade:** 100% conseguiram facilmente
- **Postar em comunidade:** 100% conseguiram facilmente
- **Comentar em post de comunidade:** 100% conseguiram facilmente
- **Solicitar amizade:** 85,7% conseguiram facilmente (1 usuário relatou dificuldades)

**Métrica Geral:** O sistema atingiu uma **Taxa de Sucesso Total de 98,4%** no cumprimento das tarefas.

### Alerta Importante: Erro no Gráfico de Experiência Geral

O formulário de pesquisa veio com os polos invertidos (o número 1 estava marcado como a pior nota, mas os usuários entenderam que era a melhor nota). Por conta disso, os dados brutos mostram 57,1% das respostas na "Nota 1", mas os comentários em texto provam que os usuários queriam dar nota máxima pelo design e pela facilidade do sistema.

## 3. O que os usuários disseram (Feedback Real)

### O que eles elogiaram

- O visual é limpo, elegante e bonito.
- O sistema é muito simples de mexer, direto e transparente.
- Está excelente para um MVP (versão inicial) e as pessoas usariam com frequência.

### O que eles reclamaram / O que precisa corrigir

- **Visual e Cores:** Acharam as cores do site um pouco genéricas. Os botões precisam de mais destaque e o texto de erro no login deve ficar em vermelho para chamar a atenção.
- **Tela de Cadastro:** O botão de cadastrar precisa sumir ou mudar de cor para se destacar. Na Etapa 2, o aviso do código enviado por e-mail deve ficar acima de "Usar outro email" (e tirar a cor verde que confunde). Na Etapa 3, o texto "Email verificado com sucesso" é redundante e pode ser tirado.
- **Navegação e Mobile:** O ícone de configurações ("Config.") fica quebrado/bugado no celular. Além disso, o link do perfil na barra de baixo deve ser movido para depois de comunidades e amizades.
- **Performance:** O site está um pouco lento para carregar as páginas. Falta colocar um sistema de cache para não ter que recarregar a página inteira toda vez que o usuário voltar para uma tela anterior.
