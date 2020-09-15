# Requisitos de produto

## Estrutural

- A Máquina deve possuir um recipiente para armazenar frutas.
- A área de entrada das frutas não deve possuir altura excessiva.
- A máquina deve ser capaz de manter a fruta no mecanismo até a eliminação da mesma.
- A máquina deve ser capaz de suportar a carga.

## Pré-Processamento

- A máquina deve ser capaz de organizar as frutas introduzidas sem interferência Manual
- A máquina deve ser capaz de retirar sujeiras, através de lavagem.
- A máquina deve ser capaz de manter um fluxo automatizado de processamento.

## Classificação

- A máquina deve ser capaz de classificar a qualidade da fruta através de imagens.
- A máquina deve capaz de classificar o tamanho da fruta
- A máquina deve ser capaz de segregar em caminhos diferentes todas as categorizações propostas

## Pós-classificação

- A máquina deve ser capaz de armazenar todas a laranjas após a classificação.
- A máquina deve ser capaz de triturar os frutos descartados na classificação de imagem.
- A máquina deve ser capaz de separar e armazenar o rejeito da trituração entre sólido e líquido.




!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!
!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!
!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!
DAQUI PRA BAIXO CADA DIRETOR DEVE PEGAR SEUS RESPECTIVOS REQUISITOS DE ACORDO COM SUA ÁREA, MELHORANDO OS REQUISITOS E ADEQUANDO DA FORMA QUE ACHAREM MAIS CONVENIENTES 
!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!
!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!
!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!
!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!


## Estrutura
|US01|Eu, como produtor, desejo um recipiente com satisfatória capacidade para que eu não precise reabastece-la frequentemente|-|
|US02|Eu, como produtor, espero que o modo de abastecer a máquina com laranja seja ergonômico para que o usuário não sofra lesões corporais ou perturbação funcional|-|
|US01|Eu, como produtor, espero que não precisar descongestionar a saída do recipiente para que o fluxo se mantenha contínuo.|-|
|US01|Eu como operador, espero que a máquina ordene as frutas de forma linear e sequencial, para que estas sejam enviadas ao processamento de forma constante.|-|
|US01|Eu, como usuário, espero que a máquina armazene corretamente os frutos, baseado na classificação|
|US02|Eu, como usuário, espero que a máquina, transporte o fruto, de forma adequada, até os recipientes, após a classificação.|
|US01|Eu, como usuário, espero que a máquina classifique as frutas em grande,média e pequena.|
|US02|Eu, como usuário, espero que a máquina seja a prova de falhas, quanto a classificação de dimensão da fruta.|

## Estrutura e energia
|US01|Eu, como produtor, espero que haja uma economia para que os custos de operação não sejam altos|-|
|US02|Eu, como produtor, espero que a máquina não vaze água durante sua operação

## Software
|US01| Eu, como usuário, espero que a máquina seja capaz de fazer discernimento de qualidade, de forma comparável a um humano.
|US02| Eu, como produtor, espero que a máquina otimize o tempo de classificação da fruta.
|US03|Eu, como usuário, espero que a máquina seja capaz de distinguir a fruta entre boa e ruim
|US04|Eu, como usuário, espero que a máquina seja a prova de falhas, quanto a seleção de boas e más frutas.|
|US05|Eu, como usuário, desejo que os dados sejam apresentados de maneira agradável na interface do sistema
|US06|Eu, como usuário, desejo saber quantas frutas foram classificadas e em que tipos
|TS01|Usuário deve ser visualizar somente o programa que esteja mostrando os dados, sem mostrar o sistema operacional
|TS02|Ao desligar a máquina, o sistema deve desligar a raspberry
|TS03|O sistema deve sincronizar o banco de dados local com o banco de dados na núvem,quando houver conexão com a internet, periodicamente
|TS04|O sistema deve ser capaz de identificar quando a raspberry tem conexão de internet ativa
|TS05|O sistema deve ser capaz de realizar a interpretação dos dados enviados pelos sensores
|TS06|O sistema deve ter uma arquitetura que permita a excução de múltiplas tarefas assíncronas
|TS07|A máquina deve possuir um botão de reinicar todo o mecânismo
|TS08|O banco embarcado no sistema deve ser leve e rápido, não gerando muito esforço de processamento.

## Software e eletrônica
|US03|Eu, como produtor, espero que a automatização facilite o processo de classificação.

|US02|Eu, como usuário, espero que a máquina não cause danos e perdas a produção, durante a automatização.|-|












