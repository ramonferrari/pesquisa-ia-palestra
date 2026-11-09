# Tema 7: Concentração de mercado, dependência de fornecedores, custo de compute e energia — implicações estratégicas para empresas usuárias

Data da busca: 09/nov/2026
Período-alvo: jan/2025 a nov/2026
Nota de método: "Verificado na origem" = documento original aberto (PDF/HTML via curl) e números conferidos no texto. Páginas citadas = índice de página do arquivo PDF (não o número impresso), salvo indicação. Itens ou campos não abertos na origem levam [NÃO VERIFICADO]. Sem análise ou conclusões neste arquivo.

---

## 1. Artificial Intelligence Index Report 2025
- Título | autores ou veículo | data | tipo: The AI Index 2025 Annual Report | AI Index Steering Committee, Stanford HAI (Maslej et al.) | abr/2025 | relatório institucional com metodologia (compilação de dados de Epoch AI, Artificial Analysis, LMSYS etc.)
- Link: https://hai.stanford.edu/ai-index/2025-ai-index-report (PDF: https://hai.stanford.edu/assets/files/hai_ai_index_report_2025.pdf)
- Status: verificado na origem (PDF de 457 páginas aberto)
- Método e amostra: compilação anual de dados de terceiros; preços de inferência a partir de bases de Artificial Analysis e Epoch AI (preço reportado = média ponderada 3:1 entre tokens de entrada e saída); custos de treino estimados pela Epoch AI a partir de preços de aluguel de nuvem; comparação open vs. closed via Chatbot Arena (LMSYS).
- Números-chave (exatos):
  - "the inference cost for a system performing at the level of GPT-3.5 dropped over 280-fold between November 2022 and October 2024" (p. 5, Top Takeaway 7; p. 13)
  - "dropped from $20.00 per million tokens in November 2022 to just $0.07 per million tokens by October 2024 (Gemini-1.5-Flash-8B)" (p. 13; p. 65)
  - "Depending on the task, LLM inference prices have fallen anywhere from 9 to 900 times per year." (p. 13)
  - "At the hardware level, costs have declined by 30% annually, while energy efficiency has improved by 40% each year." (p. 5)
  - "In early January 2024, the leading closed-weight model outperformed the top open-weight model by 8.0% on the Chatbot Arena Leaderboard. By February 2025, this gap had narrowed to 1.7%." (p. 14; p. 87 traz 8.04% e 1.70%)
  - "Nearly 90% of notable AI models in 2024 came from industry, up from 60% in 2023" (p. 5)
  - "training compute doubles every five months, datasets every eight, and power use annually" (p. 5)
  - Custos de treino estimados: Transformer (2017) "around $670"; RoBERTa Large "around $160,000"; GPT-4 (2023) "around $79 million"; Llama 3.1-405B "estimated cost of $170 million" (p. 67)
- Limitações declaradas: "companies are disclosing less about their training processes, making it increasingly difficult to estimate computational costs" (p. 67); queda de 8% para 1.7% é "on some benchmarks" (p. 5).

## 2. Artificial Intelligence Index Report 2026 (9ª edição)
- Título | autores ou veículo | data | tipo: The AI Index 2026 Annual Report | AI Index Steering Committee, Stanford HAI (Sajadieh, Fattorini, Perrault, Gil et al.) | abr/2026 | relatório institucional com metodologia (dados Epoch AI, Chatbot Arena, FMTI etc.)
- Link: https://hai.stanford.edu/ai-index/2026-ai-index-report (PDF: https://hai.stanford.edu/assets/files/ai_index_report_2026.pdf); DOI indicado no relatório para citação: https://doi.org/10.48550/arXiv.2606.15708
- Status: verificado na origem (PDF aberto, texto extraído)
- Método e amostra: compilação anual; capacidade de energia de data centers de IA estimada pela Epoch AI a partir da potência nominal dos chips de IA vendidos, com multiplicador de ~2.5 para infraestrutura (p. 31); diferença open vs. closed via Arena Leaderboard.
- Números-chave (exatos):
  - "A single company, TSMC, fabricates almost every leading AI chip, making the global AI hardware supply chain dependent on one foundry in Taiwan" (p. 10, Top Takeaway 3); "TSMC is a single point of dependency in the global AI supply chain" (p. 32)
  - "The United States hosts 5,427 data centers, more than 10 times any other country" (p. 10)
  - "Industry produced over 90% of notable frontier models in 2025" (p. 10)
  - "Total AI data center power capacity reached approximately 29.6 GW by Q4 2025, enough to power all of New York state at peak demand"; "AI chip power ... roughly 11.8 GW of the total" (p. 31)
  - "The computing power behind these models has grown roughly 3.3 times per year since 2022" (p. 13)
  - Open vs. closed: "In May 2023 ... outperformed the top open-weight model ... by 174 points (15.2%)"; "narrowed the gap to just 7 points (0.5%) by August 2024. Over the past year, that trend reversed ... As of March 2026, the top closed-weight model, Claude Opus 4.6 (1,503), led the top open-weight model GLM-5 (1,454) by 49 points (3.4%)" (p. 76)
  - "the average score dropped to 40 in 2025" no Foundation Model Transparency Index, após 37 para 58 entre 2023 e 2024 (p. 128)
  - "U.S. private AI investment reached $285.9 billion in 2025, more than 23 times the $12.4 billion invested in China" (p. 11)
  - "the most capable systems are also the least transparent, with training code, dataset sizes, and parameter counts increasingly withheld" (p. 13)
- Limitações declaradas: "frontier labs are disclosing less, and independent testing does not always confirm what developers report" (p. 4); estimativa de potência baseada em chips vendidos e multiplicador (p. 31); o próprio relatório observa que investimento privado "likely understates China's total AI spending" (p. 11).

## 3. The Emerging Market for Intelligence: Pricing, Supply, and Demand for LLMs
- Título | autores ou veículo | data | tipo: The Emerging Market for Intelligence: Pricing, Supply, and Demand for LLMs | Mert Demirer, Andrey Fradkin, Nadav Tadelis, Sida Peng | NBER Working Paper 34608, dez/2025 | working paper empírico
- Link: https://www.nber.org/papers/w34608 ; DOI: https://doi.org/10.3386/w34608
- Status: página/resumo NBER aberto na origem; PDF completo com acesso negado (Access denied) — números abaixo vêm do resumo (abstract), sem página; detalhes de método além do resumo [NÃO VERIFICADO]
- Método e amostra (conforme resumo): dados de uso de API do OpenRouter e do Microsoft Azure.
- Números-chave (exatos, do resumo): "rapid growth in the number of models, creators, and inference providers, driven by open-source entrants"; "open-source models being 90% cheaper than comparable closed-source models of the same intelligence"; "frequent turnover among leading models and creators"; "no single model dominating across use cases"; "preliminary short-run price elasticities just above one, suggesting limited scope for Jevons-Paradox effects"; "most firms concentrate their use on a single model, consistent with experimentation rather than persistent reliance on multiple models."
- Limitações declaradas: elasticidades descritas como "preliminary" (resumo). Divulgações de conflito de interesse na página: Demirer é consultor remunerado da Microsoft; Peng é funcionária e acionista minoritária da Microsoft; Fradkin é empregado da Amazon; "The views of this paper do not necessarily reflect the views of Microsoft or Amazon." Limitações completas no corpo do texto [NÃO VERIFICADO].

## 4. Concentrating Intelligence: Scaling and Market Structure in Artificial Intelligence
- Título | autores ou veículo | data | tipo: Concentrating Intelligence: Scaling and Market Structure in Artificial Intelligence | Anton Korinek, Jai Vipra | NBER Working Paper 33139 (nov/2024); versão publicada em Economic Policy (2025) segundo resultado de busca [NÃO VERIFICADO: dados da publicação na revista] | paper analítico (estrutura de custos e economia de escala; sem experimento próprio)
- Link: https://www.nber.org/papers/w33139 ; DOI: https://doi.org/10.3386/w33139
- Status: resumo NBER aberto na origem; PDF completo inacessível (acesso negado); números e seções do texto [NÃO VERIFICADO]
- Método e amostra (conforme resumo): análise da estrutura de custos de modelos de fundação (computação, dados, talento), economias de escala e escopo, risco de "market tipping", integração vertical e remédios de política.
- Números-chave: o resumo não traz números; afirma "significant economies of scale and scope that may create a tendency towards greater market concentration in the future" e discute "the risk of market tipping and the implications of vertical integration".
- Limitações declaradas: nota de agradecimento informa que é versão revisada de trabalho apresentado no 79º painel da Economic Policy, Bruxelas, abr/2024. Limitações no corpo do texto [NÃO VERIFICADO].

## 5. Trends in AI Supercomputers
- Título | autores ou veículo | data | tipo: Trends in AI Supercomputers | Konstantin F. Pilz, James Sanders, Robi Rahman, Lennart Heim | arXiv:2504.16026, 22/abr/2025 | preprint empírico (base de dados)
- Link: https://arxiv.org/abs/2504.16026 (DOI arXiv: https://doi.org/10.48550/arXiv.2504.16026)
- Status: verificado na origem (resumo e PDF abertos)
- Método e amostra: base de dados de 500 supercomputadores de IA (2019 a 2025); define supercomputador de IA como sistema com chips de IA que atingiu ao menos 1% do desempenho do líder quando entrou em operação (p. 2); tendências de desempenho, potência, custo de hardware, propriedade e distribuição geográfica.
- Números-chave (exatos): "computational performance of AI supercomputers has doubled every nine months, while hardware acquisition cost and power needs both doubled every year" (p. 1); "xAI's Colossus, used 200,000 AI chips, had a hardware cost of $7B, and required 300 MW of power" (p. 1); "industry's share of total AI compute surged from 40% in 2019 to 80% in 2025, as the public sector's share fell below 20%" (p. 3); "the United States accounts for about 75% of total performance in our dataset, with China in second place at 15%" (p. 1); projeção 2030: "$200 billion" e "9 GW" (p. 1).
- Limitações declaradas: "We estimate our dataset captures 10-20% of all existing AI supercomputer capacity" (p. 2); seção 3.4 e Apêndice C (Limitations): dados incompletos de propriedades-chave, dificuldade de definir supercomputador de IA, limitações dos dados da China.

## 6. Tiered Super-Moore's Law: Price Evolution, Production Frontiers, and Market Competition in Large Language Model Inference Services
- Título | autores ou veículo | data | tipo: Tiered Super-Moore's Law... | Mingdeng Du | arXiv:2603.28576, 30/mar/2026 | preprint empírico (não revisado por pares)
- Link: https://arxiv.org/abs/2603.28576
- Status: verificado na origem (resumo e PDF abertos)
- Método e amostra: dados OpenRouter (318 modelos), registros Epoch AI (3,237 modelos) e 62 observações de marcos validadas cruzadamente (2020 a 2026); teste de quebra estrutural de Chow; DEA/Malmquist; decomposição de custos; HHI com participação de mercado estimada por proxy.
- Números-chave (exatos): "approximately 600-fold decline in token prices" (p. 1); meia-vida de preço "1.10 years" (economy) e "1.55 years" (mid-tier); "flagship models display near-zero exponential fit (R^2 = 0.031) due to a reasoning premium averaging 31.5 times non-reasoning prices" (p. 1); quebra em maio/2024 "(F = 5.74, p = 0.005)" (p. 1); "Market concentration declined sharply, with HHI falling from 4,558 to 2,086 over three years" (p. 1); tabela HHI: 2023Q1 4,558; 2024Q1 3,215; 2024Q3 2,650; 2025Q1 2,290; 2026Q1 2,086 (p. 11); "OpenAI's market share declined from 65% to 34%, while DeepSeek rose from zero to 13%" (p. 11); "63-fold training cost gap between U.S. and Chinese firms" atribuída a inovação arquitetural (p. 1, p. 11); "GPU hardware contributing only -0.9%" da queda de custo (p. 1).
- Limitações declaradas (p. 16): "the cross-validated milestone sample (62 observations) constrains the precision of tiered decay estimates"; "the absence of transaction volume data necessitates proxy-based market share estimation"; "structural relationships identified here may shift as the industry matures."

## 7. How Hungry is AI? Benchmarking Energy, Water, and Carbon Footprint of LLM Inference
- Título | autores ou veículo | data | tipo: How Hungry is AI?... | Nidhal Jegham, Marwan Abdelatti, Chan Young Koh, Lassad Elmoubarki, Abdeltawab Hendawi | arXiv:2505.09598, mai/2025 (v. revisada nov/2025; a versão aberta cita GPT-5) | preprint empírico
- Link: https://arxiv.org/abs/2505.09598
- Status: verificado na origem (resumo e PDF abertos)
- Método e amostra: 30 modelos em data centers comerciais; combina dados públicos de desempenho de API com multiplicadores ambientais por empresa e inferência estatística da configuração de hardware; DEA de eficiência cruzada.
- Números-chave (exatos, resumo): "the most energy-intensive models exceed 29 Wh per long prompt, over 65 times the most efficient systems"; "a 0.42 Wh short query, when scaled to 700M queries/day, aggregates to annual electricity comparable to 35,000 U.S. homes, evaporative freshwater equal to the annual drinking needs of 1.2M people"; paradoxo: "as AI becomes cheaper and faster, global adoption drives disproportionate resource consumption".
- Limitações declaradas (p. 13): considera "conservatively" apenas a energia de GPUs ativamente atribuídas; usa utilização fixa de estudos anteriores para o consumo fora de GPU; para modelos proprietários sem tamanho divulgado, "we classified their scale based on observed API performance"; extensão a imagem/vídeo/áudio fica para trabalho futuro.

## 8. The Reaction of Financial Markets to the Releases of DeepSeek R1 and Kimi K3: A Critical Analysis
- Título | autores ou veículo | data | tipo: The Reaction of Financial Markets to the Releases of DeepSeek R1 and Kimi K3... | Marco Taboga | arXiv:2610.30886, 22/out/2026 | preprint empírico descritivo (estudo de eventos)
- Link: https://arxiv.org/abs/2610.30886
- Status: verificado na origem (resumo e PDF abertos); valores numéricos das janelas de evento não extraídos [NÃO VERIFICADO]
- Método e amostra: comparação descritiva de janelas de evento em torno dos lançamentos do DeepSeek R1 (jan/2025) e do Kimi K3 (jul/2026).
- Fatos (resumo): DeepSeek R1 "combined open weights with unusually low reported training and inference costs, prompting investors to reassess expected demand for computing infrastructure and producing large stock-price decreases among semiconductor and data-centre-related firms"; Kimi K3 "entered at broadly frontier prices" com reação concentrada em laboratórios chineses rivais; tese: "open-weight models redistribute rents across the AI value chain rather than eliminating them"; incumbentes protegidos por "distribution, product bundling, switching costs, proprietary data, serving capacity, and contractual trust".
- Limitações declaradas (p. 11): "Given the limitations of the event windows, this remains an interpretation of the observed pattern rather than a causal finding."

## 9. Who Uses Open-Weight Models? China and the Shifting Geography of AI in Science
- Título | autores ou veículo | data | tipo: Who Uses Open-Weight Models?... | Zackary Okun Dunivin | arXiv:2608.11090, 11/ago/2026 | preprint empírico
- Link: https://arxiv.org/abs/2608.11090
- Status: verificado na origem (resumo e PDF abertos)
- Método e amostra: 21 milhões de artigos de texto completo (S2ORC) até jun/2026; pipeline de NLP para identificar uso versus menção de modelos; amostra analítica final jan/2023 a jun/2026 com 157,446 artigos (p. 18); regressão logística e multinomial.
- Números-chave (exatos, resumo): "GPT-family models dominate both single- and multi-family research"; uso de open-weight em artigos de família única "reaching 44.0% in 2026"; "researchers at Chinese institutions have 2.23 times the odds of using an open-weight model"; "37.1% among papers with Chinese affiliations, a 27.9 percentage-point" acima de artigos sem vínculo com a China.
- Limitações declaradas (p. 8): "We cannot identify researchers' motives or separate the effects of performance, price, language, access, and institutional support."; cobertura do corpus e proxies de autoria limitam inferência.

## 10. Large-Scale Data Center Integration in Power Systems: Uncertainty and Multi-Scale Variation
- Título | autores ou veículo | data | tipo: Large-Scale Data Center Integration in Power Systems... | Le Xie, Dongjoo Kim, Qian Zhang, Grant Ruan, Paul L. Joskow | arXiv:2610.14264, 9/out/2026 | preprint (framework analítico com traços medidos de carga)
- Link: https://arxiv.org/abs/2610.14264
- Status: resumo verificado na origem; números do corpo do texto não extraídos [NÃO VERIFICADO]
- Método e amostra: framework de quatro quadrantes (confiabilidade, acessibilidade de preço) x (incerteza, variação); traços medidos de um conjunto público de cargas de trabalho de IA generativa.
- Fatos (resumo): data centers de IA hiperescala como "structurally new class of electricity demand", cargas pontuais concentradas em nível de transmissão com prazos rápidos; espectros de potência de GPU "strongly tonal"; implicações para reservas, rampas, estabilidade de tensão.
- Limitações declaradas (resumo): "We report this as a characterization of the measured workloads rather than a universal signature".

## 11. Two AI Metrics Diverged: Will it Make All the Difference?
- Título | autores ou veículo | data | tipo: Two AI Metrics Diverged... | Alex Fogelson, Zachary A. Brown, Hans Gundlach, Jayson Lynch, Neil Thompson | arXiv:2607.00913, 1/jul/2026 | preprint teórico/empírico (modelagem de escala de compute)
- Link: https://arxiv.org/abs/2607.00913
- Status: resumo verificado na origem; seção 5.1 (Limitations) existe no texto (p. 7), conteúdo detalhado não lido [NÃO VERIFICADO]
- Método e amostra: classificação de métricas de desempenho por forma funcional em relação ao compute de treino/inferência; condições matemáticas para métricas que favorecem "meek models".
- Fatos (resumo): "while validation loss shows a shrinking gap, on other metrics frontier models grow their lead forever"; se uma capacidade é ilimitada na métrica relevante, "frontier-level capability will likely be concentrated in the hands of a few wealthy actors"; se limitada, "frontier-level capabilities proliferate through meek models".
- Limitações declaradas: seção 5.1 "Limitations" (p. 7) — [NÃO VERIFICADO] o conteúdo completo.

## 12. Global giants in the AI supply chain (BIS Bulletin 122)
- Título | autores ou veículo | data | tipo: Global giants in the AI supply chain | Jon Frost, Vatsala Shreeti, Kumar Rishabh (BIS) | 23/fev/2026 | relatório institucional (banco central de bancos centrais), análise empírica
- Link: https://www.bis.org/publ/bisbull122.htm (PDF: https://www.bis.org/publications/bulletin-122-global-giants-ai-supply-chain.pdf)
- Status: verificado na origem (PDF de 7 páginas aberto)
- Método e amostra: classificação própria dos papéis de empresas em camadas da cadeia de IA (compute, infraestrutura, ferramentas de dados, modelos, aplicações) a partir de informação pública; valores de mercado e avaliações via PitchBook; participações via S&P Global Market Intelligence, World Federation of Exchanges, Compustat e 10-Ks; análise de operações (deals) por camada.
- Números-chave (exatos): "By the end of 2025, these firms accounted for 30-40% of total market capitalisation in the US, Chinese Taipei, Korea and the Netherlands" (p. 5); "At the end of 2024, these giants accounted for 26% of the total capex in Korea, 21% in the US, 4% in the Netherlands and 1% in China" (p. 5); participação na receita total: 12% Coreia, 11% EUA, 4% Países Baixos, 2% China (p. 5); "AI-related investment ... about 4.9% of US GDP in 2025 and roughly 2.5% in the euro area and 3.5% in China in 2024" (p. 5); participação das gigantes americanas em operações: "nearly 70% of all deals in the market for AI models and 33% of all deals in the market for AI applications"; "about 30%, 32% and 15%" em ferramentas de dados, infraestrutura e compute (p. 7).
- Limitações declaradas: "If a firm both sells and uses a capability internally, it is coded as marketed. Valuations are whole-firm and are not allocated across layers" (p. 4); gráfico de operações "excludes roles where AI giants are active only for internal uses and does not cover 2025" (p. 6); papéis das operações-alvo previstos por análise textual da descrição da empresa no PitchBook (p. 7).

## 13. The State of AI Competition in Advanced Economies (FEDS Notes)
- Título | autores ou veículo | data | tipo: The State of AI Competition in Advanced Economies | Alex Haag, Federal Reserve Board (FEDS Notes) | 06/out/2025 | nota de pesquisa de banco central (comparação de indicadores)
- Link: https://www.federalreserve.gov/econres/notes/feds-notes/the-state-of-ai-competition-in-advanced-economies-20251006.html
- Status: verificado na origem (HTML aberto; sem paginação, cito seções)
- Método e amostra: comparação entre países com índices (WIPO GII, FMI, Stanford, Oxford Insights) e indicadores de infraestrutura, compute, energia e investimento; fontes incluem Tony Blair Institute, Omdia, Epoch AI, Eurostat, IEA.
- Números-chave (exatos): seção 2: "The United States hosted an estimated 4,049 data centers as of 2024, far more than the EU (~2,250), the UK (484), and China (379)"; "In 2024 alone, the United States added 5.8 gigawatts (GW) of data center capacity, compared with 1.6 GW in the EU and 0.2 GW in the United Kingdom"; "controlling an estimated 74 percent of global high-end AI compute, while China holds 14 percent and the EU 4.8 percent". Seção 3: "RAND estimates that AI could require 117 GW globally by 2028, while the IEA projects that global electricity consumption from data centers will more than double by 2030"; Apêndice C: "country level data from the past two years show a slight negative correlation between energy costs and AI use among firms, with the effect significantly stronger for large enterprises" (regressão bivariada simples com efeitos fixos de ano; Eurostat).
- Limitações declaradas: índices compostos "are subject to weighting and aggregation biases"; capacidade de supercomputadores de IA observada "covering an estimated 10-20% of the existing global aggregate" (nota da Figura 2); Top500 tem problemas de autorrelato, incluindo a China, que "stopped reporting its supercomputers in 2023" (Apêndice A).

## 14. The AI Buildout and the Economy: Publicly Available Data to Assess AI's Impact (FEDS Notes)
- Título | autores ou veículo | data | tipo: The AI Buildout and the Economy... | Paul E. Soto, Mason Thieu, Jeffrey S. Allen, Federal Reserve Board | 17/jul/2026 | nota de pesquisa de banco central (indicadores públicos)
- Link: https://www.federalreserve.gov/econres/notes/feds-notes/the-ai-buildout-and-the-economy-publicly-available-data-to-assess-ais-impact-20260717.html
- Status: verificado na origem (HTML aberto; sem paginação, cito seções); a estimativa de contribuição ao PIB citada na imprensa não foi conferida no texto [NÃO VERIFICADO]
- Método e amostra: conjunto de indicadores públicos (METR, Epoch AI, Bank of Korea, SEC 10-Q, Census, BEA) agrupados em capacidades/custos, investimento/adoção, produtividade/trabalho.
- Números-chave (exatos): seção "Capabilities and Costs": "Samsung and SK Hynix account for roughly 70 percent of global DRAM supply and are the dominant share for high-bandwidth memory production"; "high-bandwidth memory in particular becoming a binding constraint as models scale"; seção "Firm Investment and Adoption": "because the hyperscalers increasingly lease data center capacity, the headline capex figures could progressively understate total AI-related infrastructure investment".
- Limitações declaradas: "Because pricing is largely proprietary and posted rates might not reflect enterprise contracts, we do not publish a series in this note"; capex de hiperescaladores "includes non-AI capex"; "adjustment costs are not directly observable and are difficult to quantify"; "The absence of a large aggregate signal as of 2026 would not necessarily invalidate future productivity impacts".

## 15. Financing the AI infrastructure boom: on- and off-balance sheet borrowing (BIS Quarterly Review, março/2026)
- Título | autores ou veículo | data | tipo: Financing the AI infrastructure boom: on- and off-balance sheet borrowing | BIS Quarterly Review (boxe/anexo; autores não extraídos do HTML) | 16/mar/2026 | relatório institucional
- Link: https://www.bis.org/publ/qtrpdf/r_qt2603u.htm
- Status: verificado na origem (HTML aberto; texto curto)
- Método e amostra: descrição de financiamento de capex de hiperescaladores (Amazon, Alphabet, Microsoft, Meta, Oracle) por bonds e estruturas fora do balanço; gráficos A1.A a A1.C (dados de mercado; fonte dos gráficos não extraída [NÃO VERIFICADO]).
- Fatos e números (exatos): emissão bruta de bonds dos hiperescaladores "topping $100 billion in 2025"; "credit default swap (CDS) spreads rose ... especially for hyperscalers with lower credit ratings"; estruturas fora do balanço são "'shadow borrowing': obligations that are economically akin to debt but largely reside outside corporate balance sheets"; o hiperescalador "commits to long-term operating leases or capacity offtake agreements (long-term commitments to purchase or reserve power and compute capacity)".
- Limitações declaradas: "The views expressed here are those of the authors and not necessarily those of the BIS"; demais limitações não localizadas no trecho aberto.

## 16. ECB Financial Stability Review, November 2025
- Título | autores ou veículo | data | tipo: Financial Stability Review, November 2025 | Banco Central Europeu | 26/nov/2025 (data de publicação conforme cobertura de imprensa; não conferida na página [NÃO VERIFICADO]) | relatório institucional de banco central
- Link: https://www.ecb.europa.eu/press/financial-stability-publications/fsr/html/ecb.fsr202511~263b5810d4.en.html
- Status: verificado na origem (HTML aberto); conteúdo é sobre concentração de mercado acionário e exposição financeira, não sobre dependência de fornecedores de IA
- Método e amostra: análise de estabilidade financeira da área do euro; seção 2.3 com dados de mercado (S&P 500, EURO STOXX).
- Números-chave (exatos, seção 2.3): "The stock prices of the seven dominant US technology companies ... have increased by 58% since 8 April. By contrast, the rest of the S&P 500 ... has gained only 24%"; "the top 1% companies of the S&P 500 now accounting for around 30% of market capitalisation"; "Whereas concentration in the EURO STOXX remains around 10% for the top 1%"; "market concentration among, and interconnection between, a handful of large US-based tech firms has risen further"; "the high valuations ... appear to be underpinned by exceptionally robust earnings performance"; "today's largest companies have more diversified business models than those of the early 2000s".
- Limitações declaradas: "it is particularly difficult to assess the likelihood of risks materialising and their related impact"; interconexão entre empresas de IA descrita como "reportedly increased" (seção 2.3).

## 17. Regulamento (UE) 2023/2854 (Data Act), Capítulo VI: troca de provedores de serviços de processamento de dados (nuvem)
- Título | autores ou veículo | data | tipo: Regulation (EU) 2023/2854 on harmonised rules on fair access to and use of data (Data Act) | Parlamento Europeu e Conselho da UE | adotado 13/dez/2023; aplicável desde 12/set/2025 | ato regulatório
- Link: https://eur-lex.europa.eu/legal-content/EN/TXT/?uri=CELEX:32023R2854
- Status: verificado na origem (texto consolidado em HTML aberto)
- Fatos e consequência concreta (texto legal): Art. 23: provedores "shall not impose and shall remove pre-commercial, commercial, technical, contractual and organisational obstacles" à troca de provedor; Art. 25(2)(a): troca ou portabilidade "not after the mandatory maximum transitional period of 30 calendar days"; Art. 29: "From 12 January 2027, providers of data processing services shall not impose any switching charges on the customer for the switching process"; "From 11 January 2024 to 12 January 2027" podem cobrar "reduced switching charges" que "shall not exceed the costs incurred"; Art. 34: uso em paralelo (multi-cloud), com cobranças de egress "only for the purpose of passing on egress costs incurred, without exceeding such costs"; Art. 50: "It shall apply from 12 September 2025."
- Limitações declaradas: não se aplica (texto normativo). Aplicação efetiva por autoridades nacionais e dados de conformidade [NÃO VERIFICADO].

## 18. Power Hungry: How AI Will Drive Energy Demand (IMF Working Paper WP/25/81)
- Título | autores ou veículo | data | tipo: Power Hungry: How AI Will Drive Energy Demand | Christian Bogmans, Patricia Gomez-Gonzalez, Ganchimeg Ganpurev, Giovanni Melina, Andrea Pescatori, Sneha Thube (FMI) | abr/2025 | working paper institucional com modelagem (CGE)
- Link: https://www.imf.org/en/publications/wp/issues/2025/04/21/power-hungry-how-ai-will-drive-energy-demand-566304 (PDF: https://www.imf.org/-/media/files/publications/wp/2025/english/wpiea2025081-print-pdf.pdf)
- Status: verificado na origem (PDF aberto)
- Método e amostra: estatísticas descritivas de contas nacionais dos EUA e evidência de nível de empresa (10-Ks) sobre empresas de IA verticalmente integradas; simulações no modelo de equilíbrio geral computável multi-país IMF-ENV com cenários de consumo de data centers até 2030 (cenários com restrição de renováveis e de transmissão).
- Números-chave (exatos): "AI-producing sectors in the U.S. have grown nearly triple the rate of the private non-farm business sector" (p. 2); "electricity costs for vertically integrated AI companies nearly doubled between 2019-2023" (p. 2); "electricity costs as a share of total expenses ... doubled between 2019 and 2023, rising from 0.8% to 1.6% on average" (p. 6); "U.S. electricity prices could increase by 8.6%, while U.S. and global carbon emissions would rise by 5.5% and 1.2% respectively" no cenário restrito (p. 2); no cenário com subsídios a renováveis e sem limites de infraestrutura "electricity prices would rise by only 0.9%" (p. 7); "notably Virginia, where data centers accounted for 26 percent of electricity consumption in 2024" (p. 16); setor de IA "from 2.4 percent in 2013 to 3.5 percent in 2023" do PIB nominal dos EUA (p. 12).
- Limitações declaradas: "IMF Working Papers describe research in progress"; o trabalho "takes these forecasts as given" (previsões de demanda de terceiros) e foca nas implicações para preços e emissões (p. 8); definição de setor "represents a narrower scope than broader classifications like the Information and Communications Technology (ICT) sector" (p. 10); "uncertainties in forecasting due to lack of corporate transparency" (p. 8, citando Chen 2025); DeepSeek e ganhos de eficiência "may lower the compute costs ... faster than previously anticipated" (p. 16).

## 19. Competition in Generative AI: Evidence from Consumer Demand
- Título | autores ou veículo | data | tipo: Competition in Generative AI: Evidence from Consumer Demand | Mark L. Egan, Dominic Russel, Claire Shi, Vincent Yao | NBER Working Paper 35953, out/2026 | working paper empírico (dados transacionais + modelo estrutural)
- Link: https://www.nber.org/papers/w35953 ; DOI: https://doi.org/10.3386/w35953
- Status: resumo NBER aberto na origem; PDF completo não aberto (corpo do texto e páginas [NÃO VERIFICADO])
- Método e amostra (resumo): "novel transaction level credit and debit card data covering 174 million consumers and 114 billion transactions"; modelo estrutural de demanda e oferta. Foco em consumidores pagantes de IA generativa (não em contratos empresariais).
- Números-chave (exatos, resumo): "As of April 2026, approximately 2.9% of U.S. consumers pay for at least one major generative AI service"; "annual customer retention rates range from 20% to 45% across major AI providers, lower than those for many other subscription products"; "multihoming is common, it has declined as providers' capabilities have expanded"; "switching rises around major model releases"; "Consumers are highly price sensitive, have much weaker preferences for particular providers than for AI overall, and view AI services as increasingly close substitutes"; "absent a substantial increase in AI model quality differentiation, growing substitutability among services will constrain providers' pricing power".
- Limitações declaradas: conflitos de interesse na página: Vincent Yao é consultor remunerado da Fiserv ("Fiserv has no role in the design of the study"); Egan e Yao são membros (não remunerados) do Fiserv Advisory Council; limitações no corpo do texto [NÃO VERIFICADO].

## 20. Demand for LLMs: Descriptive Evidence on Substitution, Market Expansion, and Multihoming
- Título | autores ou veículo | data | tipo: Demand for LLMs... | Andrey Fradkin | arXiv:2504.15440, 21/abr/2025 | preprint empírico descritivo
- Link: https://arxiv.org/abs/2504.15440
- Status: verificado na origem (resumo e PDF abertos)
- Método e amostra: raspagem diária das páginas de modelos do OpenRouter a partir de 11/jan/2025, 296 modelos (p. 3); séries temporais interrompidas em torno de lançamentos de modelos.
- Números-chave (exatos): "new models experience rapid initial adoption that stabilizes within weeks"; "multihoming, using multiple models simultaneously, is common among apps"; implica "significant horizontal and vertical differentiation in the LLM market, implying opportunities for providers to maintain demand and pricing power" (resumo); uso máximo de tokens de prompt "on the order of 55 MTok per day" (Claude 3.7 Sonnet, maior média de prompt) (p. 4); Sonnet 3.7 a "$3 per million tokens" vs. Gemini 2.5 Pro a "$1.25" (p. 2).
- Limitações declaradas (p. 3): "OpenRouter does not have data on consumer usage of LLMs through native apps such as ChatGPT"; "some popular apps such as Cursor do not use OpenRouter ... my analysis is only looking at part of the market"; chamadas "come disproportionately from apps used for programming or character personas, and as a result are not representative of LLM demand for other use cases"; a análise de séries temporais interrompidas exige ausência de eventos concorrentes (p. 5).

## 21. Beyond Benchmarks: How Users Evaluate AI Chat Assistants
- Título | autores ou veículo | data | tipo: Beyond Benchmarks: How Users Evaluate AI Chat Assistants | Moiz Sadiq Awan, Muhammad Haris Noor, Muhammad Salman Munaf | arXiv:2603.25220, 26/mar/2026 | preprint empírico (survey, amostra pequena)
- Link: https://arxiv.org/abs/2603.25220
- Status: verificado na origem (resumo e PDF abertos)
- Método e amostra: survey transversal com 388 usuários ativos de chat de IA, 7 plataformas (ChatGPT, Claude, Gemini, DeepSeek, Grok, Mistral, Llama), via instrumento Qualtrics.
- Números-chave (exatos, resumo): "the top three platforms (Claude, ChatGPT, and DeepSeek) receive statistically indistinguishable satisfaction ratings"; "over 80% use two or more platforms, and switching costs are negligible"; "competitive plurality rather than winner-take-all consolidation among engaged users".
- Limitações declaradas (p. 1): "Because the sample is drawn from technology-oriented communities, our findings characterize the preferences of active, engaged AI chat users"; usuários individuais, não empresas.

