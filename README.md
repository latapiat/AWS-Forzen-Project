# Título: Construindo uma pilha LAMP resiliente na AWS com CloudFormation e Auto Scaling
Iremos provisionar a infraestrutura e hospedar uma pilha LAMP (Linux, Apache, Mysql, PHP) altamente disponível e escalável na nuvem AWS usando o serviço de infraestrutura como código (IAC) chamado CloudFormation.

# Visão geral do projeto
Criei um modelo CloudFormation para implantar uma pilha LAMP altamente disponível e escalável na AWS, onde os servidores serão lançados pelo ASG e o tráfego no aplicativo será tratado pelo ALB (Application Load Balancer).

Além disso, as métricas do servidor devem ser monitoradas pelo CloudWatch e obter o estado da pilha via notificação por e-mail usando o Amazon SNS.

# Diagrama da Arquitetura
![Lamp app project](https://user-images.githubusercontent.com/64907977/231168131-0acfc972-951a-47ee-876f-b5d163d6e0ab.png)

# Get complete demonstration of project using Following link:

## Project Demonstration Link: https://abhishek003.hashnode.dev/building-a-resilient-lamp-stack-on-aws-with-cloudformation-and-auto-scaling
