# AppProjeto

## Projetos

### Dashboard
- Minhas tarefas atrasadas
- Minhas tarefas em aberto
- Tarefas Finalizadas este mês
- Gráfico com atraso de tarefas de todos operadores
- Tarefas em aberto por operador

### Lançamentos
- Quadro de Projetos: (Nome do projeto, clique para ver detalhes)
- Modo lista
- Background color
- Editar Projetos
- Diagrama de Gantt
- Agenda de Tarefas:
  - Separado por dia, semana, mês, ano
  - Mostra todas as tarefas agendáveis
  - Possível criar tarefas

### Tarefas
- Código - título - status - projeto - tempo de - para - criado - vencimento - notas - checklist - anexos
- Criar tarefas:
  - Projeto, status, operador, template (criar template para que possa ser replicado depois)
  - Operador, título, versão, squad, descrição
  - Início em - hora, vence em - hora - horas previstas
  - Concluído % (Também é possível criar uma checklist)

  - Alertas:
    - Alerta via sistema - data - hora - enviar alerta a cada 24 horas
    - Alerta via email - data - hora - enviar alerta a cada 24 horas
    - Enviar Alertas de Atraso por Email, caso a tarefa não seja concluída
    - Compartilhar visualização: solicitantes
    - Anexos: anexar arquivos

## Cadastro

### Projetos
- Nome, cliente, tags, participantes
- Criar projetos:
  - Nome, descrição, gerente do projeto
  - Operadores (limitados às tarefas adicionadas)
  - Cliente, tipo de finalização, previsão/finalização
  - Previsão (horas), status, andamento/concluído/template
  - Orçamento
  - Avançado:
    - Tags, operadores sem botão de tempo
    - Operadores com permissões específicas
    - Enviar email ao concluir tarefa
    - Obrigatório inserir nota antes de concluir
    - Ver todas as notas ao visualizar
    - Calcular tempo de permanência

    - Mais informações:
      - Data de início de previsão
      - Data de início
      - Valor do setup
      - Valor mensal

### Squads
- Nome, projeto, operadores visíveis
- Em um projeto pode ter inúmeros squad, ou nenhum squad
- 

### Automação de Tarefas
- Cadastro:
  - Nome, tipo (clonar/sprint (conjuntos de tarefas que tem que ser executadas e desenvolvidas em um período pré-definido de tempo. )-play/pause)
  - De: projeto, status, operador, label
  - Para: projeto, status, operador, label, data de vencimento
  - Não são clonados:
    - Vence em - hora
    - Labels (mesmo nome)
    - Concluído %
    - Alerta via sistema - data - hora (a cada 24 horas)
    - Alerta via email - data - hora (a cada 24 horas)
    - Compartilhar
    - Anexos

### Gestão de Horas do Projeto
- Projeto, grupo, operador, horas, descrição, quem notificar

### Tags
- Criar tags:
  - Nome

## Configurações

### Tarefa Programada
- Título, nome do projeto, status, operador, próximo envio
- Geral:
  - Título, projeto, status - operador, descrição, labels
  - Checklist

- Envio Programado:
  - Hora, dias do mês, mês, dias da semana, ano

### Criar Relatório de Tarefas
- Possível importar e exportar XLS
- Nome, tipo, operadores, grupos
- Dashboard adicional: exibir no dashboard (não/sim ícone)
