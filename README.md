# -Implementando-Infraestrutura-Automatizada-com-AWS-CloudFormation
 Repositório organizado contendo anotações e insights adquiridos durante a prática Implementando Infraestrutura Automatizada com AWS CloudFormation.


# Benefícios AWS CloudFormatiom #
Os benefícios do AWS CloudFormation incluem a automação e o gerenciamento de recursos, a criação de ambientes repetíveis e escaláveis, a capacidade de implantar e gerenciar a infraestrutura como código e o escalonamento global. Ele permite o provisionamento previsível e repetível, a implantação de infraestrutura como uma única unidade lógica ("pilha") e o uso de um modelo para descrever todos os recursos da AWS necessários para uma aplicação. 
O AWS CloudFormation modelo é pré-carregado com séries temporais de destino, séries temporais relacionadas e conjuntos de dados de demonstração de metadados de itens. Os campos relevantes no console são pré-preenchidos com as respectivas localizações no S3.

# Implantando um AWS CloudFormation modelo para automação do Forecast

1- Creat Stack
2- Aceite os padrões e escolha Próximo
3- Forneça um endereço de e-mail para notificações e escolha Próximo
4- Aceite os padrões e escolha Próximo
5- Em Capacidades, marque as duas caixas de seleção AWS CloudFormation para permitir a criação de recursos AWS Identity and Access Management (IAM) e pilhas aninhadas. Selecione Criar pilha.
6- Você implantou um AWS CloudFormation modelo no Forecast.

# LIMPAR
Depois de implantar esse AWS CloudFormation modelo, você pode limpar os recursos recém-criados, implantar a AWS CloudFormation pilha usando seus próprios conjuntos de dados e explorar outras opções de implantação.

Limpeza: a exclusão da pilha de demonstração mantém a pilha “Improving Forecast Accuracy with Machine Learning”. A exclusão da pilha “Improving Forecast Accuracy with Machine Learning” retém todos os dados do S3, Athena QuickSight e Forecast.

Usando seus próprios conjuntos de dados: para implantar esse AWS CloudFormation modelo com seus próprios dados de série temporal, insira as localizações S3 dos seus conjuntos de dados na seção Configuração de conjuntos de dados na Etapa 2.

Outras opções de implantação: para ver outras opções de implantação, consulte Automated Deployment. Se os dados já estiverem disponíveis, você poderá implantar a pilha sem os dados de demonstração.


As informações desse repositótio foram retiradas da aula prática e do site https://docs.aws.amazon.com/pt_br/forecast/latest/dg/tutorial-cloudformation.html 
📖Última atualização realizada em 31/10/2025
