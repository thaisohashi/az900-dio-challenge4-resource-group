# 🚀 Desafio 4: Grupo de Recursos e Rede Virtual – Bootcamp Microsoft Azure AZ-900

Este repositório contém meu quarto desafio do bootcamp **Microsoft Azure AZ-900**, oferecido pela **DIO em parceria com a Microsoft**.  

O objetivo deste desafio é praticar a criação de um **Grupo de Recursos** e uma **Rede Virtual (VNET)** no portal do Azure.

## Criando o Grupo de Recursos

### Básico
- **Assinatura:** mantive a assinatura padrão disponível.  
- **Grupo de recursos:** `AZ-900_Lab_DIO`.  
- **Região:** selecionei **(US) East US 2**, igual à instrutora Valéria Batista no lab.  

### Marcações
- Não criei tags, pois é apenas um teste.  
- Observação: em ambientes reais, **o ideal é utilizar marcações** para ajudar no controle e visualização de custos.  

Após revisar, cliquei em **Criar** para provisionar o grupo de recursos.  

## Explorando o Grupo de Recursos

A Valéria explicou algumas funcionalidades dentro do grupo de recursos:
- **Log de atividades:** registra todas as ações, como criação ou exclusão de recursos.  
- **IAM (Controle de Acesso):** permite conceder ou remover permissões de acesso para pessoas.  
- **Marcações:** além de definir na criação, é possível adicionar tags posteriormente.  
- **Visualizador de recursos:** exibe graficamente os recursos vinculados, como uma "árvore de dependências".  
- **Eventos:** permite criar eventos automatizados.  

## Criando a Rede Virtual

### Básico
- **Assinatura:** mantive a assinatura padrão.  
- **Grupo de recursos:** selecionei o grupo que criei anteriormente (`AZ-900_Lab_DIO`).  
- **Nome da rede virtual:** `VNET1`.  
- **Região:** escolhi **(South America) Brazil South**, como demonstrado pela instrutora.  

### Analisar + Criar
Confirmei as configurações e cliquei em **Criar**.  

## Observação Importante
Foi possível perceber, na prática, que **o grupo de recursos pode estar em uma região e os recursos em outra**. Essa flexibilidade é muito útil em cenários reais de nuvem.  
