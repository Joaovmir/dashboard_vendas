# 📊 Dashboard de Vendas

## 📌 Resumo
Este projeto é um dashboard interativo desenvolvido com Streamlit e Plotly para análise de vendas. Ele permite a visualização de métricas importantes como receita, quantidade de vendas, desempenho por região e vendedores, além de oferecer filtros personalizados para análise detalhada dos dados.

## 📖 Introdução
A análise de dados é essencial para entender padrões de vendas e identificar oportunidades de melhoria. Este dashboard foi criado para facilitar a visualização de dados de vendas, permitindo que os usuários filtrem informações conforme suas necessidades e tomem decisões baseadas em dados concretos.

## 🌍 Contexto
Empresas que lidam com grandes volumes de vendas precisam de ferramentas eficazes para analisar seus dados. Este projeto busca fornecer uma solução acessível e dinâmica para monitoramento e avaliação do desempenho das vendas, permitindo insights valiosos a partir de dados reais.

## 🎯 Objetivo
O principal objetivo deste projeto é disponibilizar um painel interativo e dinâmico para análise de vendas, permitindo:
- Analisar a receita por região e categoria de produto.
- Monitorar a quantidade de vendas ao longo do tempo.
- Identificar os vendedores com melhor desempenho.
- Exportar dados brutos para análises mais aprofundadas.

## 🛠 Tecnologias Utilizadas
- **Python**: Linguagem de programação principal.
- **Streamlit**: Para construção do dashboard interativo.
- **Plotly**: Para geração de gráficos dinâmicos.
- **Pandas**: Para manipulação e análise dos dados.
- **Requests**: Para obtenção de dados via API.

## 📈 Funcionalidades
### 1️⃣ Dashboard Interativo
- Exibição de métricas gerais (receita total, quantidade de vendas).
- Gráficos dinâmicos de receita e vendas por categoria, região e mês.
- Mapa interativo com a distribuição de vendas por estado.
- Filtros para segmentação dos dados por região, ano e vendedor.

### 2️⃣ Exportação de Dados Brutos
- Tabela interativa com os dados filtrados.
- Filtros avançados para refinar os dados desejados.
- Download dos dados filtrados em formato CSV.

## 📊 Visualizações
- **Mapa interativo**: Receita e vendas por estado.
- **Gráficos de linha**: Evolução mensal de receita e quantidade de vendas.
- **Gráficos de barra**: Comparação de receita e vendas por categorias e estados.
- **Análises por vendedor**: Ranking dos melhores vendedores em receita e quantidade de vendas.

## 🚀 Como Executar o Projeto
1. Clone este repositório:
   ```sh
   git clone https://github.com/Joaovmir/dashboard_vendas/
   ```
2. Acesse a pasta do projeto:
   ```sh
   cd dashboard-vendas
   ```
3. Instale as dependências:
   ```sh
   pip install -r requirements.txt
   ```
4. Execute o dashboard:
   ```sh
   streamlit run Dashboard.py
   ```
5. Acesse o dashboard no navegador no endereço fornecido pelo Streamlit.

## 📄 Estrutura do Projeto
```
📂 dashboard-vendas
│── Dashboard.py         # Código principal do dashboard
│── pages                # Pasta contendo páginas adicionais da aplicação
  │── Dados_brutos.py    # Exportação e manipulação de dados brutos
│── requirements.txt     # Dependências do projeto
│── README.md            # Documentação do projeto
```

## 📌 Resultados
Este projeto proporciona um painel intuitivo e prático para a análise de dados de vendas, facilitando a extração de insights e tomada de decisões estratégicas.
