# Criando Máquinas Virtuais no Azure:

Este repositório contém a documentação do laboratório prático realizado na DIO sobre a criação e gerenciamento de máquinas virtuais (VMs) utilizando o Microsoft Azure.

## Objetivo do Desafio:

Consolidar os conhecimentos adquiridos sobre computação em nuvem e prática com Máquinas Virtuais (VMs) no Azure, documentando passo a passo o processo de criação, configuração e acesso a uma VM no ambiente de nuvem.

## Etapas Realizadas:

### Acesso ao Portal do Azure
- Acesse o [portal.azure.com](https://portal.azure.com) com sua conta Microsoft.
- Navegue até "Máquinas Virtuais" no menu lateral.

### Criação da Máquina Virtual
- Clique em "Criar" > "Máquina virtual".
- Preencha os campos:
  - **Nome da VM**: `vm-desafio-dio`
  - **Região**: Região mais próxima (ex: Brazil South)
  - **Imagem**: Windows Server 2019 ou Ubuntu
  - **Tamanho**: Selecionar um tamanho gratuito (ex: B1s, se elegível)
  - **Usuário e senha** para acesso remoto

### Configurações de Rede
- Permitir portas RDP (Windows) ou SSH (Linux)
- Criar regras de entrada seguras no grupo de segurança da rede (NSG)

### Acesso à VM
- Se for Windows: conectar via RDP
- Se for Linux: conectar via SSH

### Finalização
- Testei comandos básicos e conectividade.
- Excluí a VM após o teste para evitar cobrança adicional.

## Conclusão

Esse lab foi fundamental para aplicar os conhecimentos teóricos sobre computação em nuvem no mundo real. Aprendi a utilizar o Azure Portal para criar e gerenciar máquinas virtuais com segurança e eficiência. Também reforcei boas práticas como o controle de custos e o uso consciente de recursos em nuvem.

