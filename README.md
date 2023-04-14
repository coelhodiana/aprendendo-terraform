# Jornada Devops de Elite
## Exercício Aula 3 - Terraform

Este repositório contém um exemplo de IaC feito com Terraform, uma ferramenta de infraestrutura como código (IaC) que permite criar, modificar e versionar infraestruturas de forma programática.

O Terraform é uma ferramenta poderosa que ajuda a automatizar a criação e gerenciamento de recursos de infraestrutura em nuvem, como máquinas virtuais, redes, instâncias de bancos de dados e muito mais. Com o Terraform, é possível definir uma infraestrutura como um código, que pode ser armazenado, compartilhado e versionado como qualquer outro código-fonte.

## Como usar
1. Instalar o terraform
2. Criar uma conta na Digital Ocean (Cloud Provider Utilizado neste exemplo)
3. Clonar este repositório
4. Entrar na pasta
6. Criar um API Token na Digital Ocean
7. Criar uma chave SSH e adicionada na Digital Ocean
8. Substituir o token no arquivo **terraform.tfvars**
9. Executar o comando:
   ```CMD
   terraform init
   ```
   e em seguida
   ```CMD
   terraform apply
   ```
