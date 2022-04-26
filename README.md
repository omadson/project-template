# <Título do projeto>

Insira aqui uma introdução para que o leitor entenda o contexto e os problemas identificados. Tente apresetnar uma justificativa para o projeto. É desejável que também se insira um [graphical abstract](https://www.elsevier.com/authors/tools-and-resources/visual-abstract).

## Objetivos e resultados chave

Em termos simples, os "Objetivos" se relacionam com a meta do projeto, e os "Resultados-Chave" expressam como essa meta será alcançada. Os Objetivos e resultados chave devem ser definidos no início de um projeto. A ideia é escolher uma métrica associada a um projeto e defini-la como o objetivo. Isso mostra a meta que você deseja alcançar. Em seguida, os resultados-chave são definidos para mostrar como atingir o objetivo. Os resultados principais são mensuráveis ​​e geralmente limitados a três a cinco por objetivo.

Em síntese, os objetivos estão ligados as entregas e os resultados chave aos passos que precisam se seguir para conseguir alcançar os resultados.
Exemplo de objetivos e resultados chave aplicados a projetos de ciência de dados.

 - Realizar uma análise exploratória de dados de <conjunto de dados>
    - Indentificar variáveis, descrevê-las e definir os tipos de dados
    - Realizar transformação de variáveis (codificação)
    - Tratar de valores faltantes e valores discrepantes
    - ...
 - Criar modelo de detecção de fakenews
    - Realizar transformação de dados textuais utilizando o tf-idf
    - ...
 - ...

## Conteúdo

Utilize esta seção para descrever o que cada notebook faz. Se tiver gerado algum relatório, também utilize essa seção para descrevêlo. Isso facilitará a leitura.

## Utilização

Descreva aqui quais os passos necessários (dependências externas, comandos, etc.) para replicar o seu projeto. Instalação de dependências necessárias, criação de ambientes virtuais, etc. Este modelo é baseado em um projeto utilizando o [Poetry](https://python-poetry.org/) como gerenciador de dependências e ambientes virtuais. Você pode utilizar o `conda`, ambientes virtuais genéricos do Python ou até mesmo containers do docker. Mas tente fazer algo que seja facilmente reprodutível.

## Desenvolvedores
 - [Contribuidor 1](http://github.com/contribuidor_1)
 - [Contribuidor 2](http://github.com/contribuidor_2)

## Organização de diretórios

> **Nota**: essa seção é somente para entendimento do usuário do template. Por favor removê-la quando for atualizar este `README.md`

```
.
├── data/                   # Diretório contendo todos os arquivos de dados (Geralmente está no git ignore ou git LFS)
│   ├── external/           # Arquivos de dados de fontes externas
│   ├── processed/          # Arquivos de dados processados
│   └── raw/                # Arquivos de dados originais, imutáveis
├── docs/                   # Documentação gerada através de bibliotecas como Sphinx
├── models/                 # Modelos treinados e serializados, predições ou resumos de modelos
├── notebooks/              # Diretório contendo todos os notebooks utilizados nos passos
├── references/             # Dicionários de dados, manuais e todo o material exploratório
├── reports/                # Análioses geradas como html, latex, etc
│   └── figures/            # Imagens utilizadas nas análises
├── src/                    # Código fonte utilizado nesse projeto
│   ├── data/               # Classes e funções utilizadas para download e processamento de dados
│   ├── deployment/         # Classes e funções utilizadas para implantação do modelo
│   └── model/              # Classes e funções utilizadas para modelagem
├── pyproject.toml          # Arquivo de dependências para reprodução do projeto
├── poetry.lock             # Arquivo com subdependências do projeto principal
├── README.md               # Informações gerais do projeto
└── tasks.py                # Arquivo com funções para criação de tarefas utilizadas pelo invoke

```