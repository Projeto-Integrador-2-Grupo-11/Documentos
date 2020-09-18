# Especificações Rede Neural


## Como será a modelagem da Rede Neural?

A rede neural, sera arquitetada de forma convolucional, onde, esta, através da alimentação de imagens do dataset e utilizando aprendizado supervisionado, será integrada a máquina de classificação de laranjas e através de sua execução em um dispositivo Raspberry Pi, possuinte de uma ram de 8gb, será capaz de classificar as laranjas, com base nos parâmetros pre-estabelecidos durante a idealização do projeto. 

Diante disso, os requisitos abaixo, são elicitados, de forma a suprir essas necessidades e as necessidades do projeto como um todo.


# Requisitos 

## Especificação 
| Requisito| Descrição | Tipo |
| -- | -- | -- |
|Velocidade|Com relação a velocidade da classificação realizada pela rede neural, é estabelecido como baseline, a capacidade do algoritmo de processar a qualidade das laranjas, de forma mais ágil do que um ser humano treinado.|Não Funcional|
|Arquitetura|A rede neural deverá ser fundamenta e desenvolvida com base em uma rede convolucional.|Não Funcional|
|Hardware|O algoritmo não deve ser demasiadamente exigente quanto a capacidade de hardware, para ser utilizado.|Não Funcional|
|Atomicidade|A rede neural deve ser capaz de operar sem conexão a internet, realizando a classificação dos artefatos independente da qualidade ou existência de conexão.|Não Funcional|
|Classificação|A rede neural deve ser capaz de realizar a classificação das laranjas entre as categorias pre-estabelecidas em sua programação.|Funcional|
|Treinamento|A rede neural, deve ser capaz de, receber input das imagens do dataset e através de aprendizado supervisionado, ser capaz de distinguir entre a qualidades das laranjas.|Funcional|
|Dataset|A qualidade das imagens que alimentarão a rede neural, deverão possuir qualidade suficiente para serem convertidas em informação válida e consistente.|Funcional|
|Qualidade|A rede neural, deve ser capaz de realizar a classificação, sem cometer falhas grotescas.|Funcional|
|Estatística|A rede neural deve ser capaz de armazenar informações referentes aos resultados das classificações por ela realizadas.|Funcional|
|Integração|A rede neural, deve ser capaz de se comunicar com a informações enviadas para ela através da câmera de captação, em tempo real.|Funcional|
|Paralelismo|O algoritmo deve ser capaz de processar imagens referentes a diferentes câmeras, de forma simultânea e dar uma classificação, com base nestas.|Funcional|
|Classificação|O algoritmo deve ser capaz de segmentar apenas o objeto de interesse na imagem|Funcional|
|Integração|O algoritmo deve ser capaz de enviar o resultado da classificação para os outros sistemas componentes da máquina.|Funcional|
|Resiliência|Quando ocorrer uma falha ou interrupção no processamento, o algoritmo deve ser capaz de informar os demais componentes, ou paralizar o processo como um todo|Funcional|
|Classificação|O algoritmod deve ser capaz de realizar a classificação entre boas, excelentes e ok com base na área da fruta que está coberta por manchas|Funcional|