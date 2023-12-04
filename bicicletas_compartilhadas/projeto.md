# Projeto de Análise de Dados
***

Autor: Breno Francisco
Data de atualização: 04/12/2023
Estudo de Caso: Análise do compartilhamento de bicicletas da Cyclistic

***

### Passo 1 - Perguntar

#### Cenário
Você é um analista de dados júnior que trabalha na equipe de analistas de marketing da Cyclistic, uma empresa de compartilhamento de bicicletas em Chicago. O diretor de marketing acredita que o sucesso futuro da empresa depende da maximização do número de planos anuais contratados. Portanto, sua equipe quer entender como os ciclistas casuais e os membros anuais usam as bicicletas da Cyclistic de forma diferente. A partir desses insights, sua equipe criará uma nova estratégia de marketing para converter passageiros casuais em membros anuais. Mas, primeiro, os executivos da Cyclistic devem aprovar suas recomendações que, portanto, devem ser apoiadas com insights de dados convincentes e visualizações de dados profissionais.

#### Empresa
* Em 2016, lançou uma oferta bem-sucedida de compartilhamento de bicicletas.
* Atualmente, frota de 5.824 bicicletas e uma rede de 692 estações em Chicago.
* Os clientes que adquirem passes de viagem única ou de dia inteiro são chamados de passageiros casuais.
* Os clientes que adquirem planos anuais são membros Cyclistic.

#### Problema

1. Como os membros anuais e os ciclistas casuais usam as bicicletas da Cyclistic de forma diferente?
2. Por que os passageiros casuais iriam querer adquirir planos anuais da Cyclistic?
3. Como a Cyclistic pode usar a mídia digital para influenciar os passageiros casuais a se tornarem membros?
    
#### Stakeholders
* Cyclistic: empresa de compartilhamento de bicicletas.
* Equipe executiva: equipe com poder de decisão.
* Lily Moreno: diretora de marketing e gerente do projeto.
* Equipe de análise de marketing: equipe de apoio responsável pela manipulação dos dados.
* Ciclistas: usuários de bicicletas.

#### Produtos
* Compartilhamento de bicicletas tradicionais, bicicletas reclináveis, bicicletas de carga e triciclos manuais.
* Estações de compartilhamento.
    
#### Entregas
* Uma declaração clara da tarefa de negócios.
* Uma descrição de todas as fontes de dados usadas.
* Documentação de qualquer limpeza ou manipulação de dados.
* Um resumo da sua análise.
* Como justificar visualizações e descobertas-chave.
* Suas três principais recomendações com base em sua análise.

#### Tarefa de negócio
* Usar os dados históricos de compartilhamento das biclicletas para identificar padrões de comportamento dos ciclistas, com o objetivo de criar estratégias que possibilitem a tomada de descisões baseada em dados.


### Passo 2 - Preparar

#### Fonte de Dados
* Fornecedor: Motivate International Inc.
* Licença: [Contrato](https://divvybikes.com/data-license-agreement).
* Repositório: [Download](https://divvy-tripdata.s3.amazonaws.com/index.html).
    *  Obs.: Os conjuntos de dados têm um nome diferente, porque a Cyclistic é uma empresa fictícia.
* Integridade dos dados: Para os propósitos deste estudo de caso, os conjuntos de dados são adequados e permitem a solução das perguntas de negócios.
* Organização dos dados: Os dados estão organizados no formato longo, onde cada linha representa um registro. Além disso, cada coluna tem um cabeçalho que representa uma variável.
* Período dos dados: Os dados abrangem o período de 2014 até 2023.
* Descrição dos dados: Os arquivos registram dados sobre as viagens (trips) e as estações (stations) de compartilhamento.
