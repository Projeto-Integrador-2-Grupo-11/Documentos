# Termo de Abertura do Projeto
## Descrição do Projeto

O projeto apresentado neste relatório consiste em uma máquina seletora de laranjas. Esta seleção será por meio de processamento de imagens e classificações mecânicas. A seleção realizada por meio de imagens classifica as frutas por parâmetros de qualidade previamente definidos, ausência ou presença de manchas na casca. Já a classificação mecânica, segmenta as laranjas por tamanhos. Esses critérios de seleção são embasados em padrões comerciais. Somado a isso, o projeto fornece ao usuário informações resultantes do processo de seleção, por meio de um aplicativo compatível com o sistema.
Por fim, o projeto integra uma etapa de pré-processamento que inclui a preparação das frutas, por meio da limpeza das mesmas. Essa etapa tem como objetivo garantir uma classificação mais eficiente, minimizando a probabilidade de erros no processo.


## Justificativa do Projeto

:: A  busca constante por maior produtividade e qualidade dos produtos rurais exige que produtores utilizem cada vez mais equipamentos tecnológicos em suas atividades agrícolas, pecuárias e industriais. Aqueles que não utilizam a tecnologia a seu favor acabam perdendo espaço no mercado, uma vez que se tornam menos competitivos.
A automação de processos tem oferecido novas oportunidades de alavancar a produtividade, reduzindo custos e ampliando o uso eficiente dos recursos disponíveis. O processo de detecção, classificação e separação baseada em trabalho manual demanda um alto consumo de tempo e elevado custo de mão de obra, limitando a cadeia de produção de algumas culturas agrícolas (ABBAS et al., 2019).

Além disso, a busca por um elevado padrão de qualidade faz com que muitos critérios sejam avaliados. Nos alimentos, a aparência é o principal critério na escolha de compra dos consumidores. A aparência dos produtos é avaliada considerando seu tamanho, forma, cor e ausência de defeitos visuais (COSTA et al., 2011).
A laranja é a principal fruta produzida no Brasil em volume, com 16,7 milhões de toneladas saídas dos pomares em 2018, correspondendo 40,9% das colheitas totais da fruticultura. Dessa forma, grande parte da economia do país é movimentada pela citricultura. O Produto Interno Bruto (PIB) desse setor corresponde a US$ 6,5 bilhões (2009), sendo US$ 4,39 bilhões no mercado interno e US$ 2,15 bilhões no mercado externo.

No processo pós colheita de laranjas, uma das maiores dificuldades consiste no método de seleção e padronização das frutas. Sistemas mecânicos baseados em peneiras com diferentes diâmetros são bastante utilizados pela indústria citrícola. Apesar disso, a movimentação intensa das frutas pode gerar grandes perdas. Por esse motivo, o presente projeto visa maximizar o processo de classificação através de técnicas que não comprometam a integridade física do produto, utilizando visão computacional. Isto é, ciência e tecnologia que obtêm informações a partir de identificação de padrões e interpretação de imagens. ::

## Objetivos do Projeto

O objetivo deste projeto é fornecer uma solução para classificação de laranjas, de forma não destrutiva, eficaz e computacionalmente otimizada. Além disso, visa implementar soluções encontradas na agricultura de precisão, caracterizada pelo alto uso de aparatos tecnológicos no campo, aplicadas de forma modular para pequenos e médios produtores.
Somado a isso, propõe a disponibilização de dados sobre os resultados da classificação com o intuito de proporcionar um elevado padrão de qualidade do produto final. Estas informações são relevantes no processo de estudo e produção da cultura.
   

## Requisitos de Alto Nível

Os requisitos de alto nível associados ao projeto estão descritos a seguir: 

- A máquina deve ser capaz de realizar a classificação de laranjas em não apropiadas para consumo, com manchas e sem manchas,  através de imagens em tempo real.
- A máquina deve ser capaz de classificar as laranjas sem manchas em tamanhos pequeno, médio e grande.
- A máquina deve ser capaz de armazenar todas a laranjas após a classificação.
- A máquina deve ser capaz de gerar informações das laranjas que são classificadas.

## Premissas

Para que o projeto seja executado da melhor maneira possível, algumas premissas foram elaboradas pela equipe de projeto. Essas foram utilizadas no processo de planejamento.

- O local de instalação do maquinário deve possuir energia elétrica;
- O local de instalação do maquinário deve possuir água;
- O local de instalação do maquinário não deve apresentar grandes desníveis;
- O usuário deve possuir meios de armazenar de forma separada as frutas selecionadas;
- É necessário 1 (um) operador.

## Restrições 

Para que o projeto seja executado da melhor maneira possível, algumas restrições foram elaboradas pela equipe de projeto. Essas foram utilizadas no processo de planejamento.

### Restrições de Produto

- Restrito à classificação de laranjas.
- Restrito à classificação de uma laranja por vez.

### Projeto

- Os integrantes devem trabalhar 8 horas semanais;
- Conhecimento da equipe em relação à algumas tecnologias;
- Tempo limitado à duração do semestre;

## Lista das Partes Interessadas
### Equipe de projeto
```eval_rst
========================================= ========================= =======================
**NOME**                                     **MATRICULA**                 **CURSO**
========================================= ========================= =======================
Lucas Alves Ferreira De Sousa             14/0026002                Engenharia Aeroespacial
Davi Henrique dos Santos                  15/0032994                Engenharia Aeroespacial
Lucas Afonso Rodrigues Raimundo           12/0125960                Engenharia Automotiva
Camilla Alves de Oliveira                 16/0003873                Engenharia Eletrônica
Beatriz Freitas Calheira                  16/0003032                Engenharia Eletrônica
Giovanna Amorim de Farias                 16/0007356                Engenharia Eletrônica
Guilherme Siqueira Brandão                16/0007763                Engenharia de Software
Gustavo Barbosa Carvalho                  16/0007780                Engenharia de Software
Natália Maria Rodrigues Queiroz           16/0015839                Engenharia de Software
Maria Luiza Ferreira Assumção Alme        16/0014433                Engenharia de Software
João pedro Gomes Cabral Ferreira          14/0145842                Engenharia de Software
Thiago Ferreira                           15/0149948                Engenharia de Software
Matheus Henrique Almeida de Souza         16/0036569                Engenharia de Energia
Letícia Marinho de Souza                  16/0131898                Engenharia de Energia
========================================= ========================= =======================
```
### Professores
```eval_rst
========================================= ========================= 
**Docente**                               **Área**
========================================= ========================= 
Alex Reis                                 Engenharia de Energia
José Felício da Silva                     Engenharia Eletrônica
Rhander Viana                             Engenharia Automotiva
Ricardo Matos Chaim                       Engenharia de Software
Paolo Gessini                             Engenharia Aeroespacial
========================================= ========================= 
```
## Riscos
### Riscos Gerais
```eval_rst
+----------------------------------+----------------------------------+
| Risco                            | Plano de ação                    |
+==================================+==================================+
| Abandono da matéria por parte de | Realocação de membros da equipe, |
| algum dos integrantes da equipe  | possível redução de escopo e     |
|                                  | aumento da carga horária dos     |
|                                  | membros                          |
+----------------------------------+----------------------------------+
| Agravamento da pandemia          | Toda comunicação e pareamento    |
|                                  | será feita de forma remota       |
+----------------------------------+----------------------------------+
| Falta de conhecimento            | Realizar treinamentos e estudos  |
| experiência em relação as        | em relação ao tema com           |
| tecnologias                      | dificuldade, pareamento com a    |
|                                  | equipe de EPS                    |
+----------------------------------+----------------------------------+
| Defeito de algum equipamento da  | Alocar pareamentos com um membro |
| equipe                           | que tenha disponibilidade        |
|                                  | parecida facilitando encontros   |
|                                  | presenciais                      |
+----------------------------------+----------------------------------+
``` 
### Riscos de Estrutura
### Riscos de Energia
### Riscos de Eletrônica
```eval_rst
+-----------+----------------+-----------------------------------------------------------------------------+-----------------------------------------------------+---------------------------------------------------------------------------------------+
| Categoria | Subcategoria   | Causa                                                                       | Risco                                               | Efeito                                                                                |
+===========+================+=============================================================================+=====================================================+=======================================================================================+
| Técnico   | Instrumentação | Escolha do micro controlador                                                | Insuficiência na capacidade de processamento        | Comunicação falha entre o microcontrolador e os periféricos                           |
+-----------+----------------+-----------------------------------------------------------------------------+-----------------------------------------------------+---------------------------------------------------------------------------------------+
| Técnico   | Instrumentação | Escolha do microcontrolador                                                 | Insuficiência na capacidade de processamento        | Comunicação falha entre o microcontrolador e os software de processamento de imagens  |
+-----------+----------------+-----------------------------------------------------------------------------+-----------------------------------------------------+---------------------------------------------------------------------------------------+
| Técnico   | Instrumentação | Escolha do servo motor                                                      | Falha na definição da rota do fruto                 | Erro na classificação                                                                 |
+-----------+----------------+-----------------------------------------------------------------------------+-----------------------------------------------------+---------------------------------------------------------------------------------------+
| Técnico   | Tecnologia     | Sincronismo entre a velocidade da esteira e velocidade de captura da imagem | Atraso entre o tempo de resposta da câmera          | Ausência de imagens do fruto                                                          |
+-----------+----------------+-----------------------------------------------------------------------------+-----------------------------------------------------+---------------------------------------------------------------------------------------+
| Técnico   | Tecnologia     | Implementação das rotinas de hardware                                       | Dificuldade em descrever as rotinas dos periféricos | Não implementar a solução proposta                                                    |
+-----------+----------------+-----------------------------------------------------------------------------+-----------------------------------------------------+---------------------------------------------------------------------------------------+
``` 
### Riscos de Software
## Cronograma e Marcos

## Resumo do Orçamento

### Equipe
```eval_rst
===================================== ======================
Nome                                  Papel
===================================== ======================
Gustavo Barbosa Carvalho              Coordenador
Letícia Marinho de Souza              Diretora de qualidade
Davi Henrique dos Santos              Diretor de estrutura
Giovanna Amorim de Farias             Diretora de eletrônica
Thiago Ferreira                       Diretor de software
Lucas Afonso Rodrigues Raimundo       Desenvolvedor
Beatriz Freitas Calheira              Desenvolvedor
Camilla Alves de Oliveira             Desenvolvedor
Guilherme Siqueira Brandão            Desenvolvedor
João pedro Gomes Cabral Ferreira      Desenvolvedor
Lucas Alves Ferreira De Sousa         Desenvolvedor
Maria Luiza Ferreira Assumção Almeida Desenvolvedor
Matheus Henrique Almeida de Souza     Desenvolvedor
Natália Maria Rodrigues Queiroz       Desenvolvedor
===================================== ======================
```
## Referências


ABBAS, Hafiz Muhammad Tayyab; SHAKOOR, Usama; KHAN, Muhammad Jaleed; AHMED, Mushtaq; KHURSHID, Khurram. Automated Sorting and Grading of Agricultural Products based on Image Processing. IEEE, Karachi, Paquistão, p. 78-81, 16 nov. 2019. DOI 10.1109/ICICT47744.2019.9001971. Disponível em: https://ieeexplore.ieee.org/document/9001971/authors#authors. Acesso em: 17 set. 2020.

Gurjão, Mata e Duarte. Classificação automática de frutas por análise de imagem – o caso da manga Tommy Atkins. Em: Memórias do VIII Workshop de Tecnologia Adaptativa – WTA 2014. EPUSP, São Paulo, ISBN: 978-85-86686-76-4, pp. 77-91. 06 e 07 de Fevereiro de 2014.

BRASILAGRO. Interior de São Paulo produz quase 80% da laranja brasileira: Estado produziu 10,77 milhões de toneladas em 2017. Maior parte foi destinada à produção de suco de laranja que é exportado para o mundo todo.. Brasil, 22 jan. 2019. Disponível em: https://www.brasilagro.com.br/conteudo/interior-de-sao-paulo-produz-quase-80-da-laranja-brasileira.html. Acesso em: 19 set. 2020.
