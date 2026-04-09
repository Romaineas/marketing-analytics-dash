# Marketing Analytics Strategy Dashboard



Este dashboard de Marketing Analytics foi desenvolvido para consolidar dados de múltiplas fontes de tráfego pago (Meta Ads, Google Ads, TikTok Ads) em uma única visão estratégica. O diferencial deste projeto é a interatividade, permitindo que o gestor filtre os dados por período e por canal específico para entender o comportamento granular de cada campanha.

Link do Projeto Online: https://marketing-analytics-dash.vercel.app/

#  O Problema de Negócio
No marketing moderno, os dados estão fragmentados em diversas plataformas. O desafio do Analista de Dados é criar uma "Fonte Única de Verdade" (Single Source of Truth) para responder a perguntas críticas:

# Qual canal possui o melhor ROAS (Retorno sobre Gasto em Anúncio)?

Nosso CAC (Custo de Aquisição de Cliente) está dentro da margem de lucro?

Como as conversões estão performando ao longo das semanas por rede social?

# Métricas e KPIs Analisados

O painel foca em métricas de eficiência (Performance-based):

Investimento (Ad Spend): Total de capital alocado no período.

ROAS Global/Canal: Eficácia direta de cada real investido.

CAC (Custo por Aquisição): Valor gasto para converter um novo cliente.

CTR (Click-Through Rate): Saúde e atratividade dos criativos/anúncios.

Atribuição de Receita: Distribuição percentual de conversões por origem.

# Funcionalidades Técnicas

Filtros Dinâmicos: Sistema de filtragem via JavaScript que simula a requisição de dados de diferentes bancos de dados ou APIs.

Gráficos Reativos: Utilização da biblioteca Chart.js para renderização de tendências e market share.

UI/UX Premium: Design limpo utilizando Tailwind CSS, focado em reduzir a carga cognitiva do tomador de decisão.

# Lógica de Dados (Data Stack)

Para este projeto, a arquitetura simulada seguiu o seguinte fluxo:

Extração: Extração hipotética via APIs (Python/Airbyte) do Facebook Graph e Google Ads API.

Transformação: Modelagem de dados para padronizar métricas de diferentes fontes em um esquema comum.

Visualização: Entrega de um front-end leve e rápido que não depende de licenças caras de BI, podendo ser embutido em portais internos.

# Desenvolvido por Romaine Data Analyst & Performance Specialist.
