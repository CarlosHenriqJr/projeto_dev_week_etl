# Análise de Gols

Este projeto tem como objetivo realizar uma análise dos gols marcados durante partidas de Futebol Virtual. Ele envolve a manipulação de dados, a correção de valores e a criação de novas colunas que indicam se houve mais de 2.5 gols, mais de 3.5 gols ou se Ambos Times Marcaram ou não.

## Pré-requisitos

Antes de executar o código deste projeto, você precisará das seguintes bibliotecas e ferramentas:

- [Pandas](https://pandas.pydata.org/): Para a manipulação de dados.
- [Python](https://www.python.org/): A linguagem de programação usada no projeto.

## Instalação

Você pode instalar as dependências usando o seguinte comando:

```bash
pip install pandas


Como Usar
Importações Necessárias: O projeto começa importando as bibliotecas necessárias, como o Pandas.

Tratamento dos Dados: Os dados são pré-processados para corrigir os valores '5+' na coluna de gols e converter as colunas 'TimeA_Gols' e 'TimeB_Gols' em tipos inteiros.

Análise de Gols:
Cria uma nova coluna chamada 'Mais_2.5' que indica se a partida teve mais de 2.5 gols.
Cria uma nova coluna chamada 'Mais_3.5' que indica se a partida teve mais de 3.5 gols.
Cria uma nova coluna chamada 'Ambos_Marcam' que indica se a partida ambos os times marcaram.

Seleção de Colunas Relevantes: São selecionadas as colunas relevantes para visualização.

Visualização Inicial: Os primeiros 10 registros do DataFrame são exibidos.

Contribuições
Se você deseja contribuir para este projeto, fique à vontade para abrir uma solicitação de pull ou reportar problemas.
