# Projeto: Análise de Receitas de Planos de Telefonia Móvel

## Introdução
Neste projeto, conduziremos uma análise estatística dos planos de telefonia móvel da empresa Megaline. A empresa oferece dois planos pré-pagos, Surf e Ultimate, e deseja determinar qual plano gera mais receita. Analisaremos o comportamento dos clientes com base em dados de chamadas, mensagens de texto e uso de dados da Megaline em 2018 para tomar essa decisão.

## Descrição dos Planos
Aqui está uma breve descrição dos planos oferecidos pela Megaline:

### Surf
- Preço mensal: $20
- Minutos incluídos: 500
- Mensagens de texto incluídas: 50
- Dados incluídos: 15 GB
- Taxas de excedente: $0.03/minuto, $0.03/mensagem, $10/GB

### Ultimate
- Preço mensal: $70
- Minutos incluídos: 3,000
- Mensagens de texto incluídas: 1,000
- Dados incluídos: 30 GB
- Taxas de excedente: $0.01/minuto, $0.01/mensagem, $7/GB

## Dados
O projeto utiliza cinco conjuntos de dados separados:

- `megaline_calls.csv`: dados sobre chamadas
- `megaline_internet.csv`: dados sobre uso de internet
- `megaline_messages.csv`: dados sobre mensagens de texto
- `megaline_plans.csv`: detalhes sobre os planos
- `megaline_users.csv`: informações sobre os usuários

## Etapas do Projeto
O projeto está dividido nas seguintes etapas:

### Etapa 1: Abertura e Estudo dos Dados
Nesta etapa, abriremos os arquivos de dados e estudaremos suas informações gerais.

### Etapa 2: Preparação dos Dados
Realizaremos a preparação dos dados, convertendo para os tipos necessários e eliminando erros.

### Etapa 3: Análise dos Dados
Descreveremos o comportamento dos clientes, analisando os minutos, mensagens de texto e volume de dados que cada plano necessita.

### Etapa 4: Teste das Hipóteses
Testaremos duas hipóteses relacionadas às receitas médias dos planos e à diferença de receita entre usuários de diferentes regiões.

### Etapa 5: Conclusão Geral
Faremos uma conclusão geral, resumindo nossas descobertas e resultados.

## Como Usar
Para reproduzir este projeto, você pode clonar este repositório e executar o código fornecido em um ambiente Jupyter Notebook.

## Avaliação
Este projeto será avaliado com base nos seguintes critérios:
- Identificação e tratamento de problemas nos dados
- Preparação adequada dos dados para análise
- Uso de gráficos para visualização das distribuições
- Interpretação dos resultados da análise estatística
- Formulação e teste de hipóteses
- Interpretação dos resultados dos testes de hipóteses
- Conclusões relevantes e explicativas
- Comentários explicativos ao longo do projeto
