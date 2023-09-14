Data: 13/09/2023
Empresa: Abstergo Industries 
Responsável: Flavio de Andrade

## Introdução
Este relatório apresenta o processo de implementação de ferramentas na empresa Abstergo Industries, realizado por Flavio de Andrade. O objetivo do projeto foi elencar 3 serviços AWS, com a finalidade de realizar diminuição de custos imediatos.

## Descrição do Projeto
O projeto de implementação de ferramentas foi dividido em 3 etapas, cada uma com seus objetivos específicos. A seguir, serão descritas as etapas do projeto:

Etapa 1: 
- Amazon DynamoDB
- É um serviço Servless (O administrador não precisa gerenciar um servidor para entrega do serviço) de banco de dados NoSQL rápido e flexível para desempenho de milissegundos. Além de fornecer uma escalabilidade ilimitada, possui um sistema de backup e restauração sob demanda sem afetar o seu desempenho.
- O Amazon DynamoDB seria usado para rastreamento de estoque e perfis dos cliente no site de compras. Além disso, nosso recursos On-Primisses não estão suportando uma altas demandas que ocorrem nos fins de semana. Se aumentarmos a capacidade dos servidores, ficaremos com recurso inutilizado durante a semana.
Como o Amazon DynamoDB é auto scaling, ele se ajustaria à demanda exata de recursos necessários para melhor entrega do serviço aos nossos cliente.

Etapa 2: 
- Amazon EC2
- oferece a plataforma de computação mais ampla e profunda, com mais de 600 instâncias e escolha do mais recente processador, armazenamento, rede, sistema operacional e modelo de compra para ajudá-lo a melhor atender às necessidades de sua carga de trabalho.
- Usando ferramentas familiares de administração do AD, você pode aplicar objetos de política de grupo (GPOs) do AD para gerenciar centralmente suas instâncias do Amazon EC2 para Windows ou Linux unindo suas instâncias ao seu domínio AWS gerenciado do Microsoft AD.
Além disso, os usuários podem fazer login em suas instâncias com as credenciais do AD. Isso elimina a necessidade de usar credenciais de instâncias individuais ou distribuir arquivos de chave privada (PEM). Isso faz com que seja mais fácil para você conceder ou revogar, instantaneamente, o acesso a usuários, usando ferramentas de administração de usuário do AD já usadas.

Etapa 3: 
- Amazon S3
- O Amazon S3 é um serviço de armazenamento de objetos que oferece escalabilidade, disponibilidade de dados, segurança e desempenho líderes do setor. 
- O Amazon S3 será usado para armazenar e recuperar qualquer quantidade de dados, a qualquer momento. Usando esse serviço, pode-se criar facilmente aplicações que fazem uso de armazenamento nativo em nuvem.



## Conclusão
A implementação de ferramentas na empresa Abstergo Industries tem como esperado Reduzir o tempo os custos de gerenciamento de armazenamento, alem de personalizar os processos de backup graças ao armazenamento ilimitado o que aumentará a eficiência e a produtividade da empresa. Recomenda-se a continuidade da utilização das ferramentas implementadas e a busca por novas tecnologias que possam melhorar ainda mais os processos da empresa.

## Links
[Natura utiliza cloud para lançar nova plataforma de vendas para suas consultoras com suporte da AWS](https://aws.amazon.com/pt/solutions/case-studies/natura-waf/)

[Mercado Livre na AWS](https://aws.amazon.com/pt/solutions/case-studies/natura-waf/)

[Itaú Unibanco entende perfil de 65 milhões de clientes com serviços AWS](https://aws.amazon.com/pt/solutions/case-studies/itau-keynote/)

[Produtos da nuvem AWS](https://aws.amazon.com/pt/products/?aws-products-all.sort-by=item.additionalFields.productNameLowercase&aws-products-all.sort-order=asc&awsf.re%3AInvent=*all&awsf.Free%20Tier%20Type=*all&awsf.tech-category=*all)



#### Assinatura do Responsável pelo Projeto:

Flavio de Andrade Silva
