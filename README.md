# Projeto de Análise de Dados Model Fitness

## Descrição do Projeto
Este projeto consiste em uma análise dos clientes de uma rede de academias, Model Fitness. A rede de academias está desenvolvendo uma estratégia de interação com o cliente baseados em dados analíticos, para tentar resolver um dos problemas mais comuns que academias e oitros serviços enfrenta, que é a rotatividade de clientes. Indicadores de rotatividade varia de área para área. A Model Fitness, em vez de lutar com a rotatividade, digitalizou uma parte dos perfis dos clientes para poder analisá-los e criar uma estratégia de retenção de clientes. Para isso, é preciso aprender a predizer a probabilidade de rotatividade para cada cliente, elaborar retratos típicos, analisar os fatores que mias impactam a roratividade oara com isso tirar conclusões básicas e desenvolver recomendações sobre como melhorar o serviço ao cliente. 

## As tarefas são:
- Análise exploratória de dados
- Modelo para predizer a rotatividade de clientes
- Criar um agrupamento de clientes
- Analisar os fatores que mais impactam a rotatividade

## Dicionário de dados
- gym_churn_us.csv: dados sobre rotatividade em um determinado mês e informações sobre o mês anterior
  - 'Churn': a rotatividade do mês em questão
  - 'gender': gênero
  - 'Near_Location': se o cliente morar ou trabalhar na vizinhança onde a academia está localizada
  - 'Partner': se o usuário foi um funcionário de uma companhia parceira (a academia tem emrpesas parceiras cujos funcionários conseguem descontos; nesses casos, a academia armazena informações sobre clientes que são funcionários)
  - 'Promo_friends': se o cliente originalmente se inscrever através de uma oferta "traga um amigo" eles m=normalmente usam o código de promoção do amigo quando pagam pela primeira filiação
  - 'Phone': se o usuário fornece o seu número de teledone
  - 'age': idade
  - 'Lifetime': o tempo (em meses) desde a primeira vez que o cliente veio à academia
  - 'Contract_period': 1 mês, 3 meses, 6 meses ou um ano
  - 'Month_to_end_contract': os meses remanescentes até que o contrato expira
  - 'Group_visits': se o cliente participa de sessões em grupo
  - 'Avg_class_frequency_total': frequência média de idas por semana por toda a vida do cliente
  - 'Avg_class_frequency_current_month': frequência média de visitas por semana durante o mês corrente
  - 'Avg_additional_charges_total': a quantidade total de dinheiro gasto em outros serviços da academia: café, artigos esportivos, cosméticos, massagem, etc

## Ferramentas e Bibliotecas utilizadas
- Python: Linguagem principal utilzaida para análise
- Pandas: Biblioteca para manipulação e análise gráfica
- Matplotlib: Biblioteca para gerar gráfico
- Seaborn: Biblioteca de visualização de dados
- Scipy: Biblioteca para testes estatísticos
- Sklearn: Biblioteca utilizada para agrupar os dados com machine learn

## Imagens

### Histograma de gênero
<img ssrc="https://github.com/user-attachments/assets/8412551d-9e9b-4b4b-a5c8-6c2e50343817" alt="Projeto 13" width="200"/>

### Histograma localização
<img src="https://github.com/user-attachments/assets/efe3b652-f6f7-4708-af46-3575f33f7d02" alt="Projeto 13" width="200"/>

### Histograma parceiro
<img src="https://github.com/user-attachments/assets/b1c9d7fe-14dd-4199-98ba-f6a42278c43f" alt="Projeto 13" width="200"/>

### Histograma promoção amigos
<img src="https://github.com/user-attachments/assets/1406fc4e-eb8d-4df5-8b85-4d9be80c147f" alt="Projeto 13" width="200"/>

### Histograma telefone
<img src="https://github.com/user-attachments/assets/e59fa785-36a8-41f7-ab2c-278b9234bbf0" alt="Projeto 13" width="200"/>

### Histograma período de contrato
<img src="https://github.com/user-attachments/assets/506ba2c9-4dfe-445e-af9b-e3902af8548e" alt="Projeto 13" width="200"/>

### Histograma grupo de visitas
<img src="https://github.com/user-attachments/assets/ec6060b9-4fba-43ea-a04c-27a2a2f375d5" alt="Projeto 13" width="200"/>

### Histograma idade
<img src="https://github.com/user-attachments/assets/31a2464e-a2ce-4f59-9e1c-54ee81b582fe" alt="Projeto 13" width="200"/>

### Histograma quantidade total de dinheiro gasto em outros serviços
<img src="https://github.com/user-attachments/assets/13fac1c6-6b01-4d99-8bd4-2063f73cacf7" alt="Projeto 13" width="200"/>

### Histograma mês do fim do contrato
<img src="https://github.com/user-attachments/assets/87f2f144-f898-46de-879c-246703920102" alt="Projeto 13" width="200"/>

### Histograma tempo desde a primeira vez na academia
<img src="https://github.com/user-attachments/assets/084ac30f-8184-4ad7-89b6-eb3d934f7ac1" alt="Projeto 13" width="200"/>

### Histograma frequência média de idas por semana
<img src="https://github.com/user-attachments/assets/b8bc7a37-8789-4c5e-b950-572a2c3f8998" alt="Projeto 13" width="200"/>

### Histograma frequência média de visitas durante o mês corrente
<img src="https://github.com/user-attachments/assets/06a64913-e171-47dc-83b6-25d40e6aa173" alt="Projeto 13" width="200"/>

### Métricas para regressão logística
<img src="https://github.com/user-attachments/assets/0dc4bf76-2b56-4dca-9e42-406a5c43f148" alt="Projeto 13"/>

### Métricas para floresta aleatória
<img src="https://github.com/user-attachments/assets/18ec245e-2022-457e-8d02-cd66a6a74369" alt="Projeto 13"/>

### Agrupamento hierárquico
<img src="https://github.com/user-attachments/assets/73b8c3dd-cd6d-4398-b9a2-65788db8bd9f" alt="Projeto 13" width="200"/>

### Idade vs quantidade gasta
<img src="https://github.com/user-attachments/assets/54c2bbda-07c8-40c3-9a9c-7177a72d9e52" alt="Projeto 13" width="200"/>

### Idade vs mês do fim do contrato
<img src="https://github.com/user-attachments/assets/ba5a5865-6cdd-4bb8-8e96-d0a40cb2f41a" alt="Projeto 13" width="200"/>

### Tempo vs mês do fim do contrato
<img src="https://github.com/user-attachments/assets/631c65b7-d7ef-4b8e-8192-4d64843c9e15" alt="Projeto 13" width="200"/>

## Resultados
- Fazendo todas as conclusões, avaliando os métodos vendo a relação entre as características, como elas estão relacionadas entre si e como elas se relacionam com a rotatividade
- É possível ver que existem caraterísticas que influenciam mais na rotatividade
- Uma dessas caraterísticas é a localização
- Por outro lado, existem características que não influenciam mais na rotatividade
- Um exemplo é o gênero
- Indicações de amigos e aulas grupaos ajuam a fidelizar o cliente, assim como planos semestrais e anuais

## Apredizados
- Análise de dados
- Limpeza de dados
- Construção e análise de gráficos
- Tratar os dados modificando os tipos das colunas, nome das colunas, valores ausentes, valores duplicados
- Trabalhar com sklearn oara usar machine learn nas análises de dados
- Interpretar os agrupamentos

## Contexto real
- Academias
- Empresas que desejam diminuir a rotatividade de seus clientes
- Analistas de dados que estudam rotatividade de clientes

## Como executar o projeto
- Clone o repositório
- Navegue até o diretório do projeto
- Abra i proejto no seu IDE favorito
- Instale as dependências
- Execute o script principal
