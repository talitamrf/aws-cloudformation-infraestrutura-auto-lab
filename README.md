# ☁️ Automação de Infraestrutura com AWS CloudFormation

## 📖 Sobre o projeto

Este projeto apresenta uma prática de automação de infraestrutura utilizando o conceito de **Infrastructure as Code (IaC)** e o serviço **AWS CloudFormation**.

Foi desenvolvido um template em YAML para provisionar um bucket Amazon S3 com versionamento habilitado. O modelo foi utilizado no **AWS Infrastructure Composer**, permitindo visualizar a infraestrutura de forma mais clara antes de realizar sua implantação.

A prática demonstra como templates podem ser utilizados para criar infraestruturas padronizadas e replicáveis na AWS.

## 🛠️ Tecnologias e serviços utilizados

- AWS CloudFormation
- AWS Infrastructure Composer
- Amazon S3
- YAML

## 📄 Template utilizado

O template utilizado nesta prática está disponível no arquivo [`template.yaml`](template.yaml).

O modelo define a criação de um bucket S3 com versionamento habilitado:

![Template YAML](images/template-yaml.png)

## 🏗️ Utilização do Infrastructure Composer

O template foi utilizado no AWS Infrastructure Composer para visualizar a estrutura da infraestrutura antes da implantação.

![Escolha do Infrastructure Composer](images/escolhendo-infrastructure-composer.png)

![Modelo no Infrastructure Composer](images/modelo-no-infrastructure-composer.png)

## 🚀 Criação da infraestrutura

Após a configuração do modelo, a criação da infraestrutura foi confirmada através do AWS CloudFormation.

![Confirmação da criação](images/confirmando-criacao-da-stack.png)

A pilha foi criada com sucesso e o recurso definido no template foi provisionado na AWS.

![Stack criada com sucesso](images/stack-criada-com-sucesso.png)

## ✅ Validação

Após a criação da pilha, o bucket S3 foi acessado para validar o recurso provisionado.

![Bucket S3 validado](images/bucket-s3-validado.png)

## 💡 Aprendizados

Esta prática permitiu compreender como a Infrastructure as Code pode ser utilizada para automatizar o provisionamento de recursos na AWS.

Também foi possível explorar o uso de templates YAML e do AWS Infrastructure Composer para criar, visualizar e gerenciar uma infraestrutura de forma padronizada e replicável.

---

## 🔍 CloudFormation x Terraform

Durante os estudos de infraestrutura como código, também é importante compreender que existem diferentes ferramentas para automatizar o provisionamento de recursos.

| AWS CloudFormation | Terraform |
|---|---|
| Serviço nativo da AWS | Ferramenta de código aberto da HashiCorp |
| Integração direta com os serviços AWS | Suporta múltiplos provedores de nuvem |
| Utiliza templates em YAML ou JSON | Utiliza principalmente a linguagem HCL |
| Gerencia recursos através de stacks | Gerencia a infraestrutura através de configurações e state |

---

Neste projeto, foi utilizado o **AWS CloudFormation**, por ser o serviço abordado na prática e possuir integração nativa com os recursos utilizados na AWS.

Desenvolvido durante os estudos de Cloud Computing 🚀
