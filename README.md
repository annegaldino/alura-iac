# USO DO TERRAFORM E ANSIBLE PARA CRIAR UMA INSTANCIA NO AWS


## - Instalações

### Instalação do Terraform no MacOS
	> brew tap hashicorp/tap
	> brew install hashicorp/tap/terraform

### Instalação do Python
	> brew install python3

### Instalação do Ansible
	> brew install ansible

### Instalação do AWS CLI
(https://docs.aws.amazon.com/pt_br/cli/latest/userguide/getting-started-install.html)

## - Fazer o primeiro Deploy

- Criar o arquivo main.tf
- Executar o seguinte comando para pressionar a máquina 
	> terraform apply

## Acesso SSh

- Criar pares de chaves no EC2

## - Configuração do Grupo de Segurança no EC2

- Definir as regras de entrada e saída para o grupo de segurança, para IPv4 e IPv6

## - Execução do playbook pelo Ansible

	> ansible-playbook playbook.yml --private-key key.pem -i hosts -u user