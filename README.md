# Azure Cognitive Search: Utilizando AI Search para indexação e consulta de Dados  
  
## Parte 1 - Azure AI search  
0 - Acessar o portal do Azure em portal.azure.com;  
1 - Procurar por Azure AI Search;  
2 - Botão Create;  
3 - Selecionar o Resource Group;  
4 - Dar um nome exclusivo;  
5 - Location = East US;  
6 - Pricing tier = basic;  
7 - Botão Review + Create.  
  
## Parte 2 - Azure AI services  
8 - Criar um recurso de Ia = AI + Machine Learning > Azure Ai Search > Botão Create;  
9 - Selecionar o Resource Group;  
10 - East US;  
11 - Definir Name;  
12 - Pricing tier = Standard S0;  
13 - Marcar a check box;  
14 - Botão Review + Create.  
  
## Parte 3 - conta de armazenamento  
15 - Storage account;
16 - Create;  
17 - Assinatura;  
18 - Selecionar o Resource Group;  
19 - Storage account name precisa ser único e ter de 3 a 24 caracteres;  
20 - Region = East US;  
21 - Perfomance = Standard;  
22 - Redundancy = locally-redundant storage (LRS);  
23 - Review + Create.
  
## Parte 4 - Configuração e teste  
24 - Selecionar o storage;  
25 - Configuration;  
26 - Allow Blob anonymous access = Enabled;  
27 - Botão Save;  
28 - Containers - New container;  
29 - Anonymous accesss level = Container (anonymous read access for containers and blobs);  
30 - Name = coffeereviews;  
31 - Clicar no storage account criado;  
32 - Baixar os arquivos para upload de https://aka.ms/mslearn-coffee-reviews para carregar no storage account criado;  
33 - Ir no Ai Search;  
34 - Aba Import data e selecionar os dados que haviamos criado;  
35 - Preencher campos de conexão;  
36 - Aba Search explorer;  
37 - Pesquisa por Chicago sobre os arquivos que deixei no storage = (search=locations:'Chicago');  
38 - Abaixo mostra os resultados de pesquisa.
  
Posso desenvolver tanto dentro do azure ou fora, em uma aplicação.  
Em resumo, seria criar o serviço de AI, fazer o link com a automação e redirecionar para um repositório.  

  
