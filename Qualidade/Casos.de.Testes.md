
# CASOS DE TESTE

Projeto: Sistema de Controle de TCC

Responsável: Sofia Albuquerque (Quality Assurance) 

Sprint: Sprint 1

| ID | História de Usuário | Caso de Teste | Passos | Resultado Esperado | Status |
| ----- | ----- | ----- | ----- | ----- | ----- |
| CT01 | HU01 | Cadastrar um novo TCC com todos os campos preenchidos | Informar título, aluno, descrição e prazo final. Clicar em "Cadastrar". | O TCC deve ser cadastrado e exibido na listagem. | Aprovado |
| CT02 | HU01 | Verificar se o campo "Título" é obrigatório | Deixar o campo título vazio e tentar cadastrar. | O sistema deve impedir o cadastro e informar que o campo é obrigatório. | Aprovado |
| CT03 | HU01 | Verificar se o campo "Aluno" é obrigatório | Deixar o campo aluno vazio e tentar cadastrar. | O sistema deve impedir o cadastro e informar que o campo é obrigatório. | Aprovado |
| CT04 | HU01 | Verificar se o campo "Descrição" é obrigatório | Deixar a descrição vazia e tentar cadastrar. | O sistema deve impedir o cadastro e informar que o campo é obrigatório. | Aprovado |
| CT05 | HU01 | Verificar se o prazo final pode ser informado | Selecionar uma data válida e concluir o cadastro. | O sistema deve registrar corretamente o prazo final. | Aprovado |
| CT06 | HU02 | Cadastrar uma atividade vinculada a um TCC | Selecionar um TCC, preencher título, responsável e status. | A atividade deve ser cadastrada corretamente. | Aprovado |
| CT07 | HU02 | Verificar se a atividade exige um título | Deixar o título vazio e tentar cadastrar. | O sistema deve impedir o cadastro da atividade. | Aprovado |
| CT08 | HU02 | Verificar se o responsável é obrigatório | Deixar o campo responsável vazio. | O sistema deve impedir o cadastro. | Aprovado |
| CT09 | HU02 | Validar os status permitidos | Selecionar "A Fazer", "Em Andamento" e "Concluído". | O sistema deve aceitar apenas os três status definidos. | Aprovado |
| CT10 | HU02 | Verificar se a atividade fica vinculada ao TCC correto | Cadastrar uma atividade para um TCC específico. | A atividade deve aparecer somente no TCC selecionado. | Aprovado |
| CT11 | HU03 | Visualizar todos os TCCs cadastrados no Dashboard | Acessar a tela Dashboard. | Todos os TCCs cadastrados devem ser exibidos. | Aprovado |
| CT12 | HU03 | Verificar a quantidade de atividades concluídas | Marcar atividades como "Concluído". | O Dashboard deve atualizar a quantidade de atividades concluídas. | Aprovado |
| CT13 | HU03 | Validar o cálculo do percentual de conclusão | Alterar o status das atividades para "Concluído". | O percentual de progresso deve ser atualizado corretamente. | Aprovado |
| CT14 | HU03 | Verificar atualização automática do Dashboard | Alterar o status de uma atividade. | O Dashboard deve refletir imediatamente a alteração realizada. | Aprovado |
| CT15 | Geral | Validar navegação entre as telas do sistema | Navegar entre Cadastro de TCC, Cadastro de Atividades e Dashboard. | Todas as telas devem funcionar corretamente, sem erros de navegação. | Aprovado |

## Resumo da Execução dos Testes

* Total de casos de teste executados: **15**  
* Casos aprovados: **15**  
* Casos reprovados: **0**  
* Bugs críticos encontrados: **0**  
* Bugs médios encontrados: **0**  
* Bugs baixos encontrados: **0**

## Conclusão

Todos os casos de teste previstos para a Sprint foram executados com sucesso. As funcionalidades implementadas atenderam aos critérios de aceitação definidos pelo Product Owner, não apresentaram falhas críticas e estão em conformidade com a Definition of Done (DoD). Dessa forma, o incremento da Sprint foi validado pelo setor de Quality Assurance e considerado apto para entrega.

