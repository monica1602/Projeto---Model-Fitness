# Projeto de Análise de Dados Model Fitness

## Descrição do Projeto
Este projeto consiste em uma análise dos clientes de uma academia, Model Fitness. A rede de academias está desenvolvendo uma estratégoa de interação com o cliente baseados em dados analíticos, para tentar resolver o problema de rotatividade de clientes

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

## Resultados
- Quais características mais influenciam no roatividade dos clientes
- A características que mais influência é a localização
- O gênero é uma características que não influenciam na rotatividade do cliente
- Indicações de amigos e aulas grupais ajudam a fidelizar o cliente, assim como planos semestrais e anuais

## Apredizados
- Análise de dados
- Limpeza de dados
- Construção e análise de gráficos
- Tratar os dados modificando os tipos das colunas, nome das colunas, valores ausentes, valores duplicados
- Trabalhar com sklearn oara usar machine learn nas análises de dados
- Interpretar os agrupamentos

## Como executar o projeto
- Clone o repositório
- Navegue até o diretório do projeto
- Abra i proejto no seu IDE favorito
- Instale as dependências
- Execute o script principal
