# dio-lab-azure-criando-maquinas-virtuais
Este repositório contém o resumo das lições aprendidas durante o desenvolvimento do lab na DIO


No lab foi aprensentado a tabela de SLA dos serivços.
A tabela pode ser encontrada no link: https://learn.microsoft.com/pt-br/azure/well-architected/reliability/metrics

| Objetivo | Não conformidade por semana | Não conformidade por mês | Não conformidade por ano |
|----------|-----------------------------|--------------------------|--------------------------|
| 99%      | 1,68 hora                   | 7,20 horas               | 3,65 dias                |
| 99,90%   | 10,10 minutos               | 43,20 minutos            | 8,76 horas               |
| 99,95%   | 5 minutos                   | 21,60 minutos            | 4,38 horas               |
| 99,99%   | 1,01 minuto                 | 4,32 minutos             | 52,56 minutos            |
| 99,999%  | 6 segundos                  | 25,90 segundos           | 5,26 minutos             |

Foi apresentado também o processo para criar maquinas virtuais e criação de contas de armazenamento. 
Além da relação da criação dos recursos com a sua disponibilidade, por exemplo: se um recurso for replicado em mais de uma região, sua disponibilidade aumenta, obviamente seu custo também aumenta. 