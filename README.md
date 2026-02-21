<h2>Aluguel de Locações em Nova York</h2>

Projeto aplicado de Análise de Dados e Business Intelligence para a empresa fictícia TudoAqui, com foco na identificação de padrões de preços, volume de acomodações, desempenho, evolução temporal  (de 2011 a 2019) e distribuição geográfica por bairros para o aluguel temporário de locações em Nova York.
<br>

<h2>🔎 O que foi desenvolvido</h2>

O projeto contempla todo o fluxo analítico, desde o tratamento dos dados até a construção de painéis interativos:

<h3>🔹 Tratamento e Qualidade dos Dados</h3>
1. Carregamento da base de dados público disponível no <a href="kaggle.com/datasets/dgomonov/new-york-city-airbnb-open-data/versions/3?resource=download)<br>">Kaggle</a><br><br>
2. Tratamento dos dados no Power Query para garantir:
<ul>
  <li>Remoção de valores nulos e campos em branco;</li>
  <li>Eliminação de registros inconsistentes;</li>
  <li>Aplicação do recurso Remover Erros;</li>
  <li>Criação de colunas calculadas.</li>
</ul>

<h3>🔹 Modelagem e Estruturação</h3>
<ul>
  <li>Construção de tabela calendário para análises temporais;</li>
  <li>Criação de medidas em DAX, como <em>CALCULATE</em>, <em>DATEADD</em>, <em>SAMEPERIODLASTYEAR</em> e <em>DIVIDE</em>, para KPIs e variações anuais</li>
</ul>

<h3>🔹Dashboard</h3>
</ul>
1. Indicadores (KPIs)<br>
<ul>
  <li>Total de acomodações;</li>
  <li>Preço total por noite;</li>
  <li>Preço mínimo final (preço × mínimo de noites);</li>
  <li>Crescimento percentual ano a ano (preço e volume);</li>
  <li>Crescimento percentual mês a mês.</li>
</ul>
2. Análise Geográfica e Pareto<br>
<ul>
  <li>Gráfico de Pareto (80/20) – Top 100 bairros por preço final;</li>
  <li>Análise de valor acumulado e participação percentual;</li>
  <li>Mapa interativo com distribuição por bairro e grupo de bairro;</li>
  <li>Dimensionamento das bolhas com base no volume financeiro.</li>
</ul>
3. Análise Temporal<br>
<ul>
  <li>Comparativo Ano Atual vs Ano Anterior;</li>
  <li>Comparativo Mês Atual vs Mês Anterior;</li>
  <li>Variação do preço final ao longo do tempo;</li>
  <li>Variação da quantidade de acomodações.</li>
</ul>
4. Visualização em formato Treemap para identificar o padrão de acomodação criada com base no Preço Mínimo Final (preço × mínimo de noites):
<ul>
  <li>≤ US$1.000 → Baixo Padrão</li>
  <li>US$1.001 a US$10.000 → Médio Padrão</li>
  <li>US$10.001 a US$100.000 → Alto Padrão</li>
  <li>> US$100.000 → Altíssimo Padrão</li>
</ul>
5. Tabela Analítica Detalhada de todas as variáveis:
<ul>
  <li>ID e Nome do Anfitrião</li>
  <li>ID e Nome da Acomodação</li>
  <li>Grupo e Bairro</li>
  <li>Tipo de Quarto</li>
  <li>Padrão da Acomodação</li>
  <li>Número de Avaliações</li>
  <li>Última Avaliação</li>
  <li>Preço por Noite</li>
  <li>Mínimo de Noites</li>
  <li>Preço Final</li>
</ul>

Visualização estática abaixo:<br>
<div align ="center"> 
  <img width="300" alt="Image" src="https://github.com/user-attachments/assets/6b23abfa-3224-44a7-8cab-8ba1eef7b48a" />
  <img width="300" alt="Image" src="https://github.com/user-attachments/assets/3baba5f7-a9d8-48d5-a51f-261550977af4" />
  <img width="300" alt="Image" src="https://github.com/user-attachments/assets/8d93b0c5-bf81-4467-a728-a43caf190c52" />
</div>


