# Mercury Soluções de Logística

Empresa fundada para realização do projeto integrador do segundo semestre de logistica com finalidade em analisar e correlacionar os dados de importação e exportação para fins academicos.

Projeto com base na metodologia agil SCRUM, que visa promover o desenvolvimento entre os membros proporcionando a proatividade, trabalho em equipe, responsabilidade. Ocasionando a colaboração e Entrega de Resultados dos universitarios enredados.

# Índice

* [Projeto](#projeto)
* [Equipe](#equipe)
* [Objetivo do Projeto](#objetivo-do-projeto)
* [Funcionalidades e registros](#Funcionalidades-e-registros-das-sprints)
* [Dados gerados](#Dados-gerados)
* [Cronograma das Sprints](#Cronograma-das-Sprints)
* [Backlog do produto](#Backlog-do-produto)
* [Burndown](#Burndown)
* [Competências desenvolvidas](#competências-desenvolvidas)
* [Autores](#autores)

# Projeto 
Esse Projeto é para fins pedagógicos e sua estrutura é baseada na Metodologia API para o ensino-aprendizado que tem como estrutura o desenvolvimento de competências e a fundamentação primordial é nos aspectos do aprendizado com problemas reais (RPBL), validação externa e mentalidade ágil. Uso de raciocínio lógico e elaboração de estratégias para analisar as lacunas e conceber uma solução viável ao desenvolver e implementar o MVP seguido de sua operação (CDIO). Os resultados obtidos através dos projetos devem obedecer ao Aviso Legal SIC com definição das datas do kickoff e das sprints.

Sprint | Previsão | Status| Histórico|
|------|--------|------|--------|
|Kick Off | 30/08/2024 | Concluido |  | 
|0| 27/09/2024 | Concluído | [Ver Relatório](https://docs.google.com/document/d/1zPJuIFDYQ2cSrrk6XRBIIfY_vp2u6Yp4/edit?usp=drive_link&ouid=108673961009193530812&rtpof=true&sd=true) | 
|1| 18/10/2024 | Concluído | [Ver Relatório](https://docs.google.com/document/d/1uM8Sw0EQS6N7pllvTRd0UUs5odZOPmyS/edit?usp=drive_link&ouid=108673961009193530812&rtpof=true&sd=true) | 
|2| 08/11/2024 | em progresso |[Ver Relatório]() | 
|3| 29/11/2024| A fazer | [Ver Relatório]()
|Feira de Soluções| 12/12/2024​ | A fazer | | 

# Equipe
<div align="center">
 <img src="https://github.com/Mercury-SL/Analise-e-otimizacao-de-uma-empresa-embarcadora/assets/128007093/b96a76e9-a742-4abe-845c-77053876f056.png" width="600px") />
</div>

# Objetivo do Projeto
* Esta pesquisa se propõe a examinar a do sistema portuário, identificando a variação mensal da prancha média operacional de carregamento de granéis (t/h) de 2014 a 2023 e desenvolvendo um modelo de projeção com base em tendência, avaliar a distribuição estatística dos tempos portuários de operação no berço para carregamento de granéis e elaborar um ranking de eficiência dos 10 principais terminais de movimentação de grãos com base na quantidade de berços e na prancha média operacional.
* Análise de produtividade de berços, utilizando SQL para criação e modelagem de banco de dados, juntamente com a ferramenta R e o Power BI para a criação de um visualizador dos indicadores.

# Funcionalidades e registros das sprints

### Sprint 2 
<div align="left">
<img src="https://github.com/user-attachments/assets/a6f22e54-985d-4388-bb4f-eb2b1b0d1b47.GIF" width="600px") />
</div>

## Tecnologias Utilizadas
  ### Produto 
  > Power BI

 ### Tecnológias Específicas/Apoio
- Github
- Jira
- Figma
- Genially
- [Gestão de Projetos](https://robsoncamargo.com.br/blog/PMBOK)
  
 ### Mindset Digital
- [Backlog](https://youtu.be/Ipg6Ox6qlC8)
- [5W2H](https://youtu.be/M4dNnrcUq9s)
- [Scrum](https://youtu.be/HlmiVz0SqNQ)

# Dados gerados

## Análise de Dados com Pandas no Google Colab

- Este repositório contém um notebook de exemplo para filtrar e manipular dados usando o Google Colab.

### Como abrir

- Clique no botão abaixo para abrir diretamente no Google Colab:

  - #### Gerar arquivo carga do ano escolhido deixando apenas granel sólido e removendo colunas desnecessarias: [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Mercury-SL/Eficiencia-no-Sistema-Portuario/blob/main/Carga1.ipynb)

   - #### Filtragem de todos idatracação que não são granel solido gerando um arquivo: [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Mercury-SL/Eficiencia-no-Sistema-Portuario/blob/main/Carga2.ipynb)

   - #### Pega o arquivo do segundo link e exclui do arquivo atracação todos idatracação que não são carga exclusiva granel solido e gera um arquivo atracação do ano escolhido: [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Mercury-SL/Eficiencia-no-Sistema-Portuario/blob/main/Atracacao.ipynb)

   - #### Junta todas as atracação define as colunas data e hora, cria três colunas novas e converte em CSV: [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Mercury-SL/Eficiencia-no-Sistema-Portuario/blob/main/AtracacaoFinal.ipynb)

    - #### Junta todas as cargas: [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Mercury-SL/Eficiencia-no-Sistema-Portuario/blob/main/Carga_Final.ipynb)

### Instruções de uso

1. Faça o upload do arquivo `.txt` usando a célula de código fornecida.
2. Siga as etapas no notebook para carregar, filtrar e salvar os dados.
3. Após executar o notebook, o resultado será salvo em um novo arquivo.


# Cronograma das Sprints
## Sprint 0
![image](https://github.com/user-attachments/assets/51d8e155-cb18-4dcb-928b-27ed2455c2ce)

## Sprint 1
![Cronograma da Sprint 1](https://github.com/user-attachments/assets/5e0ea8a0-d997-47c2-887e-d3f5c2528082)

# 5W2H
![BacklogProd](https://github.com/Mercury-SL/Eficiencia-no-Sistema-Portuario/blob/d32c074cbcb9247f6aa87be7536630672b1f66bd/Backlog%20eficiencia%20no%20sistemas.png)

# Backlog das Sprints
## Sprint 0
![_sprint 0](https://github.com/user-attachments/assets/f0541b73-6f8f-474b-9a46-32e0bf8dbb2f)

## Sprint 1
![_sprint 1](https://github.com/user-attachments/assets/a3174a28-6529-4789-84ee-b96f2970829c)

## Sprint 2
![_sprint 2](https://github.com/user-attachments/assets/00da5299-391d-492a-a0ec-a0d56a305cc0)


## Sprint 3
![5w2h sprint 3](https://github.com/user-attachments/assets/5a61e6fe-6248-4ff0-9c3e-5d2d5207f407sadsadasdsad)


# Regras de Negócio

Requisitos funcionais 
* Interface no Power BI para avaliação de indicadores portuários;
* Modelo de projeção de tendência da produtividade dos shiploaders;
* Rankeamento dos portos por meio de aplicação do DEA.

Requisitos não funcionais
* Metodologia ágil.
* Usar tecnologias específicas/apoio/tecnológicas.
* Power BI / Jira / Python / Canvas / Figma / R.
  
# Burndown
## Sprint 0
![Burndown Sprint 0](https://github.com/user-attachments/assets/4ed8c651-8f2a-4488-a242-bbe1c2732361)

## Sprint 1
![Burndown Sprint 1](https://github.com/user-attachments/assets/699b8104-3a93-459c-8161-808502160c4b)

## Sprint 0
- [x] Documentação - Sprint 0;
- [x] Criação e organização do Github;
- [x] Criação e organização do Jira Software;
- [x] Análise, compreensão e filtragem dos dados;
- [x] Aplicação do 5W2H;
- [x] Criação do banco de dados no Python;
- [x] Compreensão das etapas do projeto;

## Sprint 1
- [x] Atualização da documentação - Sprint 1;
- [x] Atualização e organização do Github;
- [x] Aprendizagem da ferramenta R;
- [x] Compreensão dos processos portuários;
- [X] Calculo de êficiencia DEA(R);
- [x] Modelagem dos dados 
- [x] Indentificação do tempo de operação dos berços (Python);
- [x] Definição do layout padrão do aplicativo (Figma);

      
# Competências desenvolvidas

## Hard Skill (saber tecnológico)
<details>
<summary>Hard Skills desenvolvidas</summary>
  
| Tecnologia/Metodologia | Classificação |
| ---------------------- | ------------- |
| Jira | ★ ★ ★ ★ ★ ★ ★ ★ ★ ☆ |
| Github | ★ ★ ★ ★ ★ ★ ★ ★ ★ ☆ |
| Excel | ★ ★ ★ ★ ★ ★ ★ ★ ★ ★ |
| Power BI | ★ ★ ★ ★ ★ ★ ★ ★ ★ ★ |
| Figma | ★ ★ ★ ★ ★ ★ ★ ★ ★ ★ |
| Canva | ★ ★ ★ ★ ★ ★ ★ ★ ★ ☆ |
| 5W2H | ★ ★ ★ ★ ★ ★ ★ ★ ★ ☆ |
| Google Maps | ★ ★ ★ ★ ★ ★ ★ ★ ★ ☆ |
| Word | ★ ★ ★ ★ ★ ★ ★ ★ ★ ★ |
| Metodologia agil | ★ ★ ★ ★ ★ ★ ★ ★ ★ ☆ |
| Scrum Master | ★ ★ ★ ★ ★ ★ ★ ★ ☆ ☆ |
| Project Owner | ★ ★ ★ ★ ★ ★ ★ ★ ★ ★ |
 
</details>

## Soft Skill (saber comportamental)
<details>
<summary>Soft Skills desenvolvidas</summary>

| Habilidades | Classificação |
| ---------------------- | ------------- |
| Adaptabilidade | ★ ★ ★ ★ ★ ★ ★ ★ ★ ☆ |
| Colaboração| ★ ★ ★ ★ ★ ★ ★ ★ ★ ☆ |
| Comunicação | ★ ★ ★ ★ ★ ★ ★ ★ ☆ ☆ |
| Autonomia | ★ ★ ★ ★ ★ ★ ★ ★ ★ ★ |
| Proatividade | ★ ★ ★ ★ ★ ★ ★ ★ ☆ ☆ |

</details>

# Autores
|    Função     | Nome                                  |                                                                                                                                                      LinkedIn & GitHub                                                                                                                                                      |
| :-----------: | :------------------------------------ | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: |
| Product Owner | João Augusto Amaral da Silva |     [![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/jo%C3%A3o-augusto-4114b0214) [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)]()              |
| Scrum Master  | Dener da Silva Barros |      [![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/dener-barros-4114739b/) [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/DENER92) |
| Development team  | Danubia Mayumi Aihara |         [![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/danubia-mayumi-aihara-74332326b/) [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/DanubiaAihara) |
|  Development team  | Graziele Cristina de Almeida Santos |   [![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/graziele-santos-38407225a/) [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/GrazieleAlmeida) |
|  Development team  | Denner Miguel de Andrade Lima |           [![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/denner-lima-874b65216/) [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/dmiguelima) |
|  Development team  | Pedro Calderaro Martins |           [![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/pedro-calderaro-175462262/) [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/calderaro190) |
