# Projeto de Análise de Dados Model Fitness

## Descrição do Projeto
Este projeto visa realizar uma análise aprofundada dos clientes da rede de academias Model Fitness, com o objetivo de desenvolver uma estratégia de retenção de clientes baseada em dados analíticos. A rotatividade de clientes é um dos maiores desafios enfrentados por academias e outros tipos de serviços de longo prazo, e a Model Fitness decidiu adotar uma abordagem mais tecnológica para lidar com esse problema. Para isso, a empresa digitalizou uma parte dos perfis dos seus clientes, permitindo a coleta e análise de dados detalhados sobre o comportamento e características dos usuários.
O objetivo principal deste projeto é prever a probabilidade de rotatividade de cada cliente, utilizando modelos de dados que possam identificar os fatores de risco e, assim, ajudar na formulação de estratégias mais eficazes para a retenção. Além disso, busca-se elaborar retratos típicos de clientes, segmentando-os com base em suas características e comportamentos. Esse processo inclui a identificação de padrões que podem indicar os clientes mais propensos a se desligar da academia, assim como aqueles que têm maior potencial de fidelização.
Além disso, a análise dos dados permitirá entender os fatores mais impactantes na rotatividade, como frequências de visita, tipos de planos contratados, histórico de interações com a academia e outros comportamentos relacionados. Com base nesses insights, serão desenvolvidas conclusões práticas que orientem melhorias no serviço ao cliente, como promoções personalizadas, mudanças na experiência do usuário e ajustes nos planos de fidelidade. O foco é não apenas entender as razões pelas quais os clientes deixam de frequentar a academia, mas também adotar uma abordagem proativa para manter os clientes existentes e atrair novos, minimizando assim os custos com aquisição de clientes e aumentando a satisfação geral.

## As tarefas são:
- Realização de uma análise exploratória de dados para identificar padrões e insights relevantes sobre o comportamento dos clientes.
- Desenvolvimento de um modelo preditivo para estimar a probabilidade de rotatividade de clientes, utilizando técnicas de aprendizado de máquina ou estatísticas.
- Segmentação dos clientes com base em características comuns, criando grupos distintos que permitem uma compreensão mais profunda dos diferentes perfis de consumidores.
- Identificação e análise dos fatores que mais influenciam a rotatividade dos clientes, com o objetivo de otimizar as estratégias de retenção e melhorar a experiência do cliente.

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
- Python: Linguagem principal utilizada para a análise de dados, permitindo a implementação de diversas soluções analíticas e algoritmos.
- Pandas: Biblioteca essencial para a manipulação e análise de dados, facilitando operações de agregação, filtragem, e transformação de grandes volumes de informações.
- Matplotlib: Biblioteca para geração de gráficos estáticos, utilizada para criar visualizações detalhadas e facilitar a análise exploratória de dados.
- Seaborn: Biblioteca complementar a Matplotlib, especializada na criação de gráficos estatísticos e visuais mais avançados e estéticos, ideal para exploração e comunicação de dados.
- SciPy: Biblioteca que oferece funções científicas, incluindo ferramentas para testes estatísticos e otimização, auxiliando na análise e interpretação de dados.
- Scikit-learn (Sklearn): Biblioteca utilizada para implementação de algoritmos de aprendizado de máquina, especialmente útil para agrupamento de dados e construção de modelos preditivos.

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
- Relação entre Características e Rotatividade:
  - Analisamos como diferentes características dos clientes se relacionam com a rotatividade.
- Características que mais influenciam a rotatividade:
  - Localização: Clientes distantes da academia têm maior probabilidade de cancelar.
- Características com menor impacto na rotatividade:
  - Gênero: Não há diferença significativa na rotatividade entre homens e mulheres.
- Fatores que ajudam a fidelizar clientes:
  - Indicação de amigos: Clientes indicados por amigos tendem a ficar mais tempo.
  - Aulas em grupo: A participação em aulas coletivas ajuda a manter os clientes.
  - Planos semestrais e anuais: Contratos de longo prazo reduzem a rotatividade.

## Apredizados
- Análise de Dados: Processo de exploração e interpretação de dados, identificando padrões, tendências e relações importantes para gerar insights significativos.
- Limpeza de Dados: Atividades de preparação de dados, que incluem a identificação e correção de inconsistências, remoção de registros duplicados, preenchimento ou exclusão de valores ausentes, e a padronização de formatos.
- Construção e Análise de Gráficos: Criação de representações visuais dos dados, como gráficos de barras, linhas, dispersão, entre outros, com o objetivo de facilitar a interpretação dos dados e destacar informações relevantes.
- Tratamento de Dados: Ajustes no formato e estrutura dos dados, como a modificação de tipos de colunas, renomeação de variáveis, substituição de valores ausentes por alternativas viáveis ou a exclusão de valores inválidos e a remoção de duplicidades.
- Uso do Scikit-Learn em Machine Learning: Aplicação da biblioteca Scikit-learn para realizar análises de dados usando técnicas de aprendizado de máquina, como classificação, regressão e agrupamento (clustering), com o objetivo de identificar padrões e prever comportamentos futuros.
- Interpretação de Agrupamentos: Análise e entendimento de agrupamentos de dados (clusters) gerados por algoritmos de aprendizado de máquina, interpretando as características dos grupos e como eles se relacionam com os objetivos do estudo.

## Contexto real
- Empresas do setor de academias que buscam estratégias para reduzir a rotatividade de seus clientes.
- Organizações em diversos setores que desejam implementar ações para diminuir a perda de clientes e aumentar a retenção.
- Profissionais e analistas de dados especializados na análise de rotatividade de clientes, focando na identificação de padrões e fatores que influenciam a permanência ou desistência de clientes.

## Como executar o projeto
- Clone o repositório
- Navegue até o diretório do projeto
- Abra i proejto no seu IDE favorito
- Instale as dependências
- Execute o script principal
