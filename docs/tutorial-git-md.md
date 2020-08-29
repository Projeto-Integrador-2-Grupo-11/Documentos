# Tutorial de como contribuir utilizando o Git

**Importante:** este tutorial utiliza linhas de comando no terminal do Linux/macOS ou prompt de comando do Windows. Há alternativas de interfaces gráficas para utilização git, mas não serão abordadas nesse tutorial.

1) Para clonar o repositório, utilize o seguinte comando no terminal do Linux/macOS ou prompt de comando do Windows dentro de uma pasta de sua preferência
```bash
git clone https://github.com/Projeto-Integrador-2-Grupo-11/Documentos
```
Algo parecido com isto será apresentado no seu terminal caso processo de clone for bem sucedido:
![clone](https://i.imgur.com/DyUXnHH.png)

2) Ainda dentro do mesmo terminal, navegue até a pasta do repositório que você clonou utilizando o comando:
```bash
cd Documentos/
``` 

3) Trabalharemos com **branches**, portanto, após clonar o repositório, deve-se verificar em qual branch você está. Para isso, execute o comando:
```bash
git branch
```
![branch](https://i.imgur.com/uNb7vvp.png)
o asterisco representa em qual branch o seu repositório local está. Para visualizar todas as branches que há no repositório, deve-se executar o comando:
```bash
git branch --all
```
![branch--all](https://i.imgur.com/VB37TnT.png)
Para trocar de branch, deve-se utilizar o comando
```bash
git checkout nome-da-branch
```
![checkout](https://i.imgur.com/WnxhN2r.png)
Para **CRIAR** uma branch nova, deve-se executar o comando:
```bash
git checkout -b nome-da-nova-branch
```
![checkout-b](https://i.imgur.com/tgPR3EJ.png)

4) Para realizar as suas modificações, neste tutorial utilizamos o editor de texto [Visual Studio Code](https://code.visualstudio.com/), mas pode-se utilizar outros editores de texto como o Atom, Sublime, VIM etc. Após baixar e instalar o software, pode-se abrir o diretório que o seu terminal está situado utilizando a seguinte linha de comando:
```bash 
code .
```
ou então pode-se abrir o diretório direto no Visual Studio Code da seguinte forma:

* Na barra superior do Visual Studio Code, navegue até a opção 'File'e depois até a opção 'Open'.]; 
![code1](https://i.imgur.com/hcDcSvN.png)

* Na janela que será aberta, selecione a pasta que você quer abrir no editor de texto (no nosso caso, será a pasta do projeto. 2019.1-Grupo-8):
![code2](https://i.imgur.com/RlmULgf.png)

* Na barra lateral aparecerá as pastas e arquivos do diretório aberto:
![code3](https://i.imgur.com/7sOakuv.png)

5) Após modificar os arquivos desejados, volte ao terminal anteriormente aberto na pasta do projeto e digite:
```bash
git status
```
no terminal, aparecerá os arquivos que você modificou:
![git-status](https://i.imgur.com/IGE9afJ.png)
no caso do exemplo da imagem, o arquivo contribuindo.md situado na pasta docs foi modificado. O próximo passo é adicionar os arquivos modificados ao seu index.

6) Para adicionar os arquivos, deve-se utilizar o seguinte comando no terminal:
```bash
git add nome-do-arquivo
```
no caso do exemplo utilizado neste tutorial, adicionaremos o arquivo docs/contribuindo.md:
```bash
git add docs/contribuindo.md
```
e em seguida daremos novamente o comando
```bash
git status
```
para conferir se o arquivo desejado foi adicionado corretamente:
![add](https://i.imgur.com/uVJIfUG.png)
como o arquivo apareceu na cor verde no terminal, significa que foi adicionado corretamente ao seu index local.

**Observação 1:** ao longo do projeto poderá ser realizadas várias mudanças em diferentes arquivos, então há um comando que adiciona todos os arquivos modificados de uma vez:
```bash
git add .
```

**Observação 2:** caso você tenha adicionado um arquivo por engano NESTE PASSO, basta executar o seguinte comando para remover o arquivo do index:
```bash
git reset nome-do-arquivo
```
![reset](https://i.imgur.com/SG2UUbO.png)

7) O próximo passo é enviar as mudanças para o repositório local utilizando o comando:
```bash
git commit -m "descrição do commit"
```
![commit](https://i.imgur.com/cKeB3bn.png)

8) O último passo é enviar o seu commit para o repositório remoto. Para isso, utilize o comando:
```bash 
git push
```

## Dicas Úteis:
* SEMPRE execute o comando 
```bash
git pull
```
em seus repositórios locais. Este comando pega as últimas mudanças que outros membros do time subiram no git e diminui a chance de haver conflitos nos arquivos. Por exemplo: você criou uma nova branch chamada 'bug/01' com base na branch 'development'. Enquanto você realizava a correção do bug, outro membro do time atualizou o conteúdo da branch 'development'. Então, para realizar um pull request com as suas modificações, você deve atualizar a branch 'bug/01' com as atualizações da branch 'development'. Para isso, execute o comando:
```bash
git pull origin development
``` 
e sua branch será atualizada. Caso os arquivos que você tiver mexido for os mesmos arquivos que a pessoa que atualizou a branch 'development' também mexeu, haverá um CONFLITO:
![conflito](https://i.imgur.com/WvhfgCI.png)
a imagem acima ilustra uma situação de conflito no arquivo README.md após tentar atualizar o conteúdio da nova branch com o conteúdo da branch 'master'. Para resolver este conflito, digite no terminal
```bash
code .
```
Será aberta uma janela com os arquivos do diretório no Visual Studio Code:
![merge](https://i.imgur.com/8Anog2f.png)
em que na barra lateral (onde a seta número 1 está apontando), na cor roxa, será representado o arquivo (ou arquivos) em que existe conflito. A seta número 2 representa as mudanças que VOCÊ fez, enquanto a seta 3 representa as mudanças que estão na branch em que você está tentando "puxar" a atualização.
No local que a seta 2 está apontando há três botões:
* **Accept Current Change:** aceita a mudança que você fez na sua branch;
* **Accept Incoming Change:** aceita a mudança que está na branch que você está "puxando as atualizações";
* **Accept Both Changes:** aceita as duas mudanças, colocando uma linha embaixo da outra;
* **Compare Changes:** coloca as duas linhas de conflito para serem comparadas.  

Após selecionar qual opção melhor te atende, deve-se proceder conforme o passo 5 do presente tutorial.

## Commitar quando for realizado pareamento
O pareamento é parte da metodologia abordada na disciplina de Métodos de Desenvolvimento de Software, e quando ele for realizado, no passo 7 do tutorial, o piloto não deve usar 
```bash 
git commit -m 
```
pois o commit deve mostrar todos que trabalharam nele. Ao invés de utilizar a linha acima, deve-se utilizar:
```bash
git commit -s
```
e aparecerá uma tela parecida com isto:

![pareamento](https://i.imgur.com/1eWltfh.png)

Para começar a editar nesta tela que irá aparecer no terminal, aperte a tecla **i**.

Na primeira linha, preenche-se a descrição do commit. Em Signed-off-by deve-se preencher o nome do usuário do git da pessoa que está participando do pareamento como co-piloto (pu seja, quem não está com o git logado na máquina em que está acontecendo o desenvolvimento) e na linha de baixo deve-se preencher igual à linha de Signed-off-by, só que utilizando Co-authored-by. Confira o exemplo abaixo:

![exCommit](https://i.imgur.com/wYQVg1U.png)

Após terminar de editar o template, aperte a tecla **esc** e em seguida a tecla **:** e **wq**, para fechar e salvar o que foi editado.
```bash
:wq
```

# Como utilizar MarkDown
## Negrito

> É assim que se faz texto em **negrito**.

``` É assim que se faz texto em **negrito**. ```

## Itálico

> É assim que se faz texto em *itálico*.

``` É assim que se faz texto em *itálico*. ```

## Lista com marcadores (bullet list)

> * Marcador um (não se esqueça do espaço após o asterisco)

```
* Marcador um (não se esqueça do espaço após o asterisco)
* Marcador dois
```

## Listas Numeradas

> 1. Etapa um
> 2. Etapa dois

```
1. Etapa um
2. Etapa dois
```

## Listas Aninhadas
> * Esse é o primeiro nível da lista. 
>    * Para fazer o segundo nível, adicione dois espaços antes do asterisco ou número.

```
* Esse é o primeiro nível da lista.
    * Para fazer o segundo nível, adicione dois espaços antes do asterisco ou número.
```

## Cabeçalhos

> # Cabeçalho nível um (com um espaço após o #)
> ## Cabeçalho nível dois
> ### Cabeçalho nível três

```
# Cabeçalho nível um (com um espaço após o #)
## Cabeçalho nível dois
### Cabeçalho nível três
```
Você pode adicionar até seis níveis de cabeçalho.

## Citações em bloco
> As citações em bloco tem início e fim com uma linha em branco
> E cada linha da citação começa com uma chave para a direita e um espaço

```
> As citações em bloco tem início e fim com uma linha em branco

> E cada linha da citação começa com uma chave para a direita e um espaço
```

## Código Embutido
> Este é um "código embutido".

## Bloco de Código
> ```
> Este é um bloco de código.
> ```

 ```
    ```
    Este é um bloco de código.
    ```
 ``` 

## Imagens
```

    ```eval_rst
    .. figure:: assets/seletor/img1.png
    :align: center
    :width: 400
    :alt: Alternative text

    ..

    Fig 1: laranja
    ```
```

## Links
> [Texto de exibição do link](http://www.exemplodeurl.com)

```
[Texto de exibição do link](http://www.exemplodeurl.com)
```

## Tabelas
```
    ```eval_rst
    ================== ============= ====================
    **Nome**           **Papel**     **GitHub**
    ================== ============= ====================
    Guilherme Siqueira Desenvolvedor `guilhermesiqueira`_
    ================== ============= ====================

    .. _guilhermesiqueira: https://github.com/guilhermesiqueira
    ```
```