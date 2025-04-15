# resumo-lab-azure-dio
Este repositório contém o resumo das lições aprendidas durante o desenvolvimento do lab na DIO, no Bootcamp **XP Inc. - Cloud com Inteligência Artificial**

## Benefícios da hospedagem na nuvem:
A hospedagem na nuvem oferece diversos serviços que trazem benefícios para a sua aplicação, como escalabilidade, confiabilidade, entre outros. A Microsoft oferece o Microsoft Azure Well-Architected Framework, por exemplo, para ajudar a obter um ambiente completo e que atenda aos requisitos do cliente da melhor forma possível, seguindo boas praticas de implementação. Abaixo, seguem os aprendizados sobre estes benefícios.

### - Escalabilidade
A Escalabilidade (crescimento vertical/ na propria maquina) refere-se a alocar mais/menos recursos, como memória de disco para uma determinada máquina/servidor para que se ajuste a necessidade atual.

### - Elasticidade
Visa garantir que a sua aplicação terá os recursos suficientes para atender a demanda atual de acessos e uso. Permitir programar para que novas instancias, com ambientes identicos, sejam disponibilizadas ou desligadas conforme a demanda.

### - Confiabilidade
Trata da resiliência do ambiente, buscando garantir que falhas não deixem a aplicação fora do ar por muito tempo e garantir que seja possível recuperar de falhas criticas.

### - Previsibilidade
Diz-se do desempenho e custo das instancias, para evitar que as contas venham mais altas que o esperado.

### - Segurança
Trata de boas praticas de implementação do ambiente, controle de acessos, segurança dos dados, utilizando ferramentas de segurança especificas, realizando manutenções dos sistemas e aplicação de patches.

### - Governança
A Governança trata de auditar e gerenciar o ambiente para que os recursos sejam utilizados pelos devidos usuários. Anda muito junto com a Segurança.

### - Gerenciabilidade
É a forma como você pode gerir o seu ambiente. Pode ser pela propria plataforma web do fornecedor, por API ou por linha de comando, por exemplo.

## Lab Criando Máquinas Virtuais na Azure
### SLA
O SLA se refere ao Nível de Acordo de Serviço, que estipula métricas de referência para avaliar o serviço fornecido. No caso dos serviços de nuvem e mais especificamente das máquinas virtuais, diz-se da porcentagem do tempo total em que a VM ficou disponível dado um determinado intervalo de tempo (semana, mês ou ano). Se o SLA não é atendido, o fornecedor disponibiliza um ressarcimento em forma de crédito. Para escolher o SLA mais adequado, deve-se pensar no tempo de insdisponibilidade aceitável. Quanto maior o SLA (i.e., 99,999% > 99%) maior a disponibilidade e custo do serviço.

### Maquinas Virtuais
Ao criar uma VM, podemos escolher a região e zona onde ela será alocada, além dos recursos dela.

### Redundância de armazenamento
Podemos escolher o tipo de redundância do armazenamento, para acelerar na recuperação de falhas do sisteam ou invasões. A redundância pode ser local, geográfica, por zona, ou por zona geográfica, cada uma tendo um custo diferente.

## Lab Configurando uma instância de Banco de Dados na Azure
### Imagem da máquina virtual
Podemos escolher o sistema operacional a ser instalado na VM

### Calculadora de custo
Ao terminar de configurar uma instancia, nos é mostrado custo mensal estimado. A partir destes valores, podemos apresentar a gerência para decisão dos recursos a serem locados.
