# Documentação de Prompts: Análise de Agenda e Produtividade

Este documento apresenta a descrição detalhada de prompts divididos por categorias para auxiliar no planejamento, organização, priorização e análise de produtividade pessoal ou profissional com auxílio de inteligência artificial.

---

## Categorias

1. Planejamento Diário
2. Organização Semanal/Mensal
3. Priorização e Produtividade
4. Adaptação e Reagendamento
5. Relatórios e Análise de Tempo

---

## Planejamento Diário

### Prompt 1: Análise de sobrecarga e disponibilidade

> **"Analise minha agenda desta semana e identifique: qual dia está mais sobrecarregado e onde há períodos livres para um compromisso de 2 horas."**

#### Objetivo

- Identificar o dia com maior carga de compromissos.
- Localizar espaços com pelo menos **2h livres seguidas** para novos agendamentos.

#### Entradas esperadas

- Agenda semanal com horários ocupados.
- (Opcional) Horários não disponíveis (ex: almoço, descanso).

#### Saídas esperadas

- Dia mais sobrecarregado.
- Lista de janelas livres com 2h ou mais de duração.

---

### Prompt 2: Realocação de tarefas pendentes

> **"Quais tarefas da semana passada ficaram pendentes e como posso encaixá-las no meu cronograma atual sem sobrecarga?"**

#### Objetivo

- Identificar tarefas não concluídas da semana anterior.
- Reposicionar essas tarefas de forma equilibrada na nova semana.

#### Entradas esperadas

- Lista de tarefas com status (concluído/pendente).
- Agenda semanal atual.
- (Opcional) Nível de prioridade das tarefas.

#### Saídas esperadas

- Tarefas pendentes identificadas.
- Sugestões de alocação em horários livres com menor impacto.

---

### Prompt 3: Disponibilidade para atividades pessoais

> **"Com base na minha agenda, em quais horários desta semana eu tenho disponibilidade para tempo livre ou atividades pessoais?"**

#### Objetivo

- Encontrar espaços na agenda que podem ser usados para lazer, descanso ou autocuidado.

#### Entradas esperadas

- Agenda da semana.
- (Opcional) Horários fixos de obrigações (ex: trabalho, refeições, sono).

#### Saídas esperadas

- Lista de blocos livres com pelo menos 1h de duração.
- Sinalização de melhores momentos com base na carga do dia.

---

## Organização Semanal/Mensal

### Prompt 4: Sugestão de horários para remarcar reunião

> **"Sugira 3 possíveis horários dentro das próximas 2 semanas para remarcar uma reunião de 1h, considerando meus compromissos fixos."**

#### Objetivo

- Analisar os compromissos fixos do usuário.
- Sugerir horários ideais e compatíveis para reagendar uma reunião sem conflitos.

#### Entradas esperadas

- Agenda com compromissos fixos das próximas duas semanas.
- Duração da reunião a ser reagendada (padrão: 1h).
- (Opcional) Preferências de período (manhã/tarde/noite).

#### Saídas esperadas

- 3 sugestões de horários viáveis, com justificativa (ex: menor carga no dia, espaçamento ideal).

---

### Prompt 5: Impacto de adiar uma tarefa

> **"Se eu adiar a tarefa [X] para amanhã, qual será o impacto no resto da minha semana? Há algo urgente que precise ser priorizado?"**

#### Objetivo

- Avaliar consequências de adiar uma tarefa específica.
- Detectar possíveis conflitos ou acúmulo de tarefas importantes.

#### Entradas esperadas

- Tarefa e data planejada.
- Cronograma semanal.
- (Opcional) Grau de urgência e impacto da tarefa.

#### Saídas esperadas

- Impacto direto no fluxo semanal.
- Recomendações sobre remanejamento, prioridade e riscos.

---

### Prompt 6: Verificação de tarefas atrasadas e ajustes

> **"Verifique se há tarefas atrasadas na minha lista e proponha um ajuste no cronograma para compensá-las sem prejudicar outras prioridades."**

#### Objetivo

- Detectar tarefas em atraso.
- Realocar as pendências respeitando a importância das tarefas já previstas.

#### Entradas esperadas

- Lista de tarefas com prazos e status (feito/não feito).
- Cronograma atual da semana.
- (Opcional) Tarefas críticas que não devem ser movidas.

#### Saídas esperadas

- Lista de tarefas atrasadas.
- Proposta de realocação otimizada e balanceada.

---

## Priorização e Produtividade

### Prompt 7: Ordenação de tarefas por urgência e impacto

> **"Ordene minhas tarefas de hoje por urgência e impacto, justificando a priorização de cada uma."**

#### Objetivo

- Criar uma lista de tarefas otimizada para execução com base em critérios objetivos.
- Ajudar o usuário a focar no que realmente importa.

#### Entradas esperadas

- Lista de tarefas do dia.
- (Opcional) Prazos e contexto de cada tarefa.

#### Saídas esperadas

- Tarefas organizadas por prioridade (alta, média, baixa).
- Justificativa com base na urgência (prazo) e impacto (relevância/consequência).

---

### Prompt 8: Identificação de tarefas que podem ser adiadas

> **"Quais tarefas da minha lista atual podem ser adiadas para a próxima semana sem consequências negativas?"**

#### Objetivo

- Aliviar a carga de trabalho atual.
- Evitar sobrecarga e focar no que é mais relevante neste momento.

#### Entradas esperadas

- Lista de tarefas e respectivos prazos.
- Cronograma da semana atual.
- (Opcional) Prioridade percebida ou classificações anteriores.

#### Saídas esperadas

- Tarefas identificadas como adiáveis.
- Justificativas baseadas em urgência, impacto e dependências.

---

### Prompt 9: Otimização da rotina diária

> **"Analise minha rotina diária: quais atividades estão consumindo tempo sem agregar valor e como posso otimizá-las?"**

#### Objetivo

- Melhorar o uso do tempo diário com foco em produtividade e bem-estar.
- Eliminar ou reduzir hábitos improdutivos.

#### Entradas esperadas

- Rotina diária detalhada com horários e descrições de atividades.
- (Opcional) Expectativas ou metas de produtividade.

#### Saídas esperadas

- Lista de atividades de baixo valor agregado.
- Sugestões de eliminação, redução, automação ou delegação.
- Recomendações para uso mais eficaz do tempo.

---

## Adaptação e Reagendamento

### Prompt 10: Remanejamento de atividade para a próxima semana

> **"Se eu remarcar a atividade [Y] para a próxima semana, quais ajustes devo fazer no meu planejamento para evitar conflitos?"**

#### Objetivo

- Avaliar os impactos do remanejamento de uma tarefa.
- Realinhar a agenda para evitar sobreposição ou acúmulo de compromissos.

#### Entradas esperadas

- Detalhes da atividade [Y] e data atual planejada.
- Cronograma da semana seguinte.
- (Opcional) Restrições de horário e tarefas fixas.

#### Saídas esperadas

- Ajustes recomendados no planejamento semanal.
- Sugestões de realocação de outras tarefas, se necessário.
- Alerta para possíveis conflitos de horário ou sobrecarga.

---

### Prompt 11: Consequências de não realizar uma tarefa hoje

> **"Quais são as consequências imediatas se eu não concluir a tarefa [Z] hoje? Há margem para negociar prazos?"**

#### Objetivo

- Ajudar o usuário a decidir com clareza se deve adiar ou priorizar uma tarefa.
- Medir riscos associados ao adiamento.

#### Entradas esperadas

- Descrição da tarefa [Z] e prazo planejado.
- Contexto: urgência, dependências, impacto de atraso.

#### Saídas esperadas

- Avaliação de risco de adiamento.
- Consequências práticas ou emocionais de não concluir a tarefa hoje.
- Sugestão de renegociação de prazo, se aplicável.

---

### Prompt 12: Realocação ideal de tarefa cancelada

> **"Sugira o melhor horário para realocar uma tarefa cancelada, considerando minha energia produtiva (manhã/tarde) e compromissos existentes."**

#### Objetivo

- Encontrar o momento mais adequado para realocar uma tarefa cancelada.
- Alinhar cronograma com o ritmo biológico do usuário e evitar sobrecarga.

#### Entradas esperadas

- Tarefa cancelada e estimativa de duração.
- Agenda da semana.
- Preferência de horários com maior produtividade (ex: manhã/tarde).

#### Saídas esperadas

- Sugestão de horários ideais com base na disponibilidade e energia produtiva.
- Justificativa para a escolha da nova alocação.

---

## Relatórios e Análise de Tempo

### Prompt 13: Resumo do tempo gasto por categoria

> **"Gere um resumo do tempo gasto nesta semana por categoria (ex: trabalho, lazer, tarefas domésticas) e destaque desequilíbrios."**

#### Objetivo

- Analisar a distribuição do tempo entre diferentes áreas da vida.
- Identificar desequilíbrios que possam estar afetando produtividade ou bem-estar.

#### Entradas esperadas

- Registro de atividades da semana com categorias associadas.
- (Opcional) Tempo total disponível por dia.

#### Saídas esperadas

- Relatório com percentual de tempo por categoria.
- Destaque de excesso ou carência em alguma área.
- Sugestões para reequilíbrio (ex: mais tempo livre, menos tempo em tarefas repetitivas).

---

### Prompt 14: Comparação de produtividade entre semanas

> **"Compare minha produtividade nos últimos 7 dias com a semana anterior: houve melhora ou queda? Quais tarefas influenciaram?"**

#### Objetivo

- Avaliar evolução de desempenho ao longo do tempo.
- Identificar fatores que impactaram positivamente ou negativamente a produtividade.

#### Entradas esperadas

- Registro de tarefas concluídas e não concluídas nas duas últimas semanas.
- (Opcional) Classificação de dificuldade ou tempo previsto x realizado.

#### Saídas esperadas

- Comparativo percentual de produtividade.
- Destaque de tarefas-chave que impulsionaram ou prejudicaram o desempenho.
- Sugestões de ajuste para manter ou melhorar a performance.

---

### Prompt 15: Cumprimento de prazos

> **"Com base nos meus registros, estou cumprindo pelo menos 80% dos prazos estimados? Se não, onde estão os gargalos?"**

#### Objetivo

- Verificar a eficiência no cumprimento de prazos.
- Identificar causas de atrasos recorrentes e gargalos.

#### Entradas esperadas

- Histórico de tarefas com prazos e status de conclusão (dentro ou fora do prazo).
- (Opcional) Observações de contexto (ex: interrupções, urgências inesperadas).

#### Saídas esperadas

- Percentual de prazos cumpridos.
- Identificação de gargalos por tipo de tarefa, horário ou categoria.
- Recomendações para melhorar o planejamento ou execução.

---


