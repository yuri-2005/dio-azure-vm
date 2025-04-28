# Configuração de Máquina Virtual no Azure

Este repositório documenta o processo de criação e configuração de uma máquina virtual (VM) na plataforma Microsoft Azure. A documentação serve como material de apoio para estudos e futuras implementações.

## Objetivo

O objetivo deste desafio é praticar a criação e configuração de uma máquina virtual no Azure e documentar o processo de forma clara e estruturada. É uma ótima oportunidade para aplicar os conhecimentos sobre o uso do Azure e desenvolver a parte prática.

## Pré-requisitos

Antes de começar, é necessário:

- Ter uma conta no [Azure](https://azure.microsoft.com/pt-br/free/).
- Acesso ao portal do Azure para criação de recursos.
- Familiaridade básica com o sistema operacional (Windows ou Linux) que será usado na máquina virtual.

## Passo a Passo: Criação da Máquina Virtual

1. **Acessar o Portal do Azure**
   - Acesse o [Portal do Azure](https://portal.azure.com/).
   
2. **Criar uma Nova Máquina Virtual**
   - Vá para "Máquinas Virtuais" no menu lateral e clique em "Criar".
   - Escolha a imagem do sistema operacional (Windows ou Linux).
   - Defina um nome para a máquina virtual e configure os recursos (tamanho, região, etc.).
   - Configure as redes e segurança (certifique-se de abrir as portas necessárias, como RDP ou SSH, para acesso remoto).
   
3. **Configuração de Acesso**
   - Para máquinas Windows: Acesse via **RDP** utilizando o IP público da VM.
   - Para máquinas Linux: Acesse via **SSH** com a chave privada gerada durante a criação.
   
4. **Testando a Conexão**
   - Após a VM ser provisionada, conecte-se a ela para verificar se está funcionando corretamente.
   
5. **Configuração Pós-Criação**
   - Realize configurações adicionais que sejam necessárias, como atualizações de sistema, instalação de software ou configuração de rede.
   

## Observações

- **Escolha de Tamanho da VM**: Para fins de teste, o tamanho padrão da VM geralmente é suficiente, mas dependendo do projeto, você pode precisar ajustar os recursos de CPU e memória.
- **Rede e Segurança**: Lembre-se de configurar corretamente as regras de segurança de rede para garantir o acesso remoto seguro.
- **Documentação Oficial**: A documentação oficial do Azure pode ser encontrada [aqui](https://learn.microsoft.com/pt-br/azure/virtual-machines/).

## Conclusão

A criação e configuração de máquinas virtuais no Azure é um processo relativamente simples, mas exige atenção aos detalhes, como segurança e conectividade. Este desafio foi uma excelente oportunidade para aprender como usar a plataforma Azure de forma prática.

---

