# Tema 7: Concentração de mercado, dependência de fornecedores, custo de compute e energia — implicações estratégicas para empresas usuárias

Data da busca: 09/nov/2026
Período-alvo: jan/2025 a nov/2026
Nota de método: "Verificado na origem" = documento original aberto (PDF/HTML via curl) e números conferidos no texto. Páginas citadas = índice de página do arquivo PDF (não o número impresso), salvo indicação. Itens ou campos não abertos na origem recebem o marcador de não verificado, aplicado apenas ao dado em questão. Itens 1 a 29: origem aberta (nos itens 3, 4, 10, 11, 19, 26 e 29 apenas resumo ou página oficial, não o texto integral). Itens 30 a 40: origem não aberta. Sem análise ou conclusões neste arquivo.

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

## 22. Is Your LLM Overcharging You? Tokenization, Transparency, and Incentives
- Título | autores ou veículo | data | tipo: Is Your LLM Overcharging You?... | Ander Artola Velasco, Stratis Tsirtsis, Nastaran Okati, Manuel Gomez-Rodriguez | arXiv:2505.21627, 27/mai/2025 | preprint teórico com experimentos
- Link: https://arxiv.org/abs/2505.21627
- Status: verificado na origem (resumo e PDF abertos)
- Método e amostra: análise teórica do preço por token (provedores podem declarar tokenização mais fina sem que o usuário consiga provar); algoritmo heurístico de prova de conceito; experimentos com modelos Llama, Gemma e Ministral e prompts da LMSYS Chatbot Arena.
- Números-chave (exatos): "users cannot prove, or even know, whether a provider is overcharging them" (resumo); para Llama-3.2-1B-Instruct, "a provider who uses Algorithm 2 can overcharge users by up to 11.2%, 1.8% and 0.28%, respectively for p = 0.99, 0.95, 0.90" (p. 9); "a pricing mechanism must price tokens linearly on their character count" para eliminar o incentivo (resumo). Resultado demonstra vulnerabilidade, não comportamento observado de provedores reais.
- Limitações declaradas (p. 12, Seção 5): análise foca em mecanismos de preço aditivos; "providers would arguably only be forced to report plausible tokenizations if the users have a mechanism to verify"; heurística proposta como prova de conceito, "there may exist other, more sophisticated methods"; experimentos usam modelos das famílias Llama, Gemma e Ministral (fato do método, não limitação declarada como tal).

## 23. Measuring the environmental impact of delivering AI at Google Scale
- Título | autores ou veículo | data | tipo: Measuring the environmental impact of delivering AI at Google Scale | Cooper Elsworth, Keguo Huang, David Patterson, Ian Schneider, Robert Sedivy, Savannah Goodman, Ben Townsend, Parthasarathy Ranganathan, Jeff Dean, Amin Vahdat, Ben Gomes, James Manyika (Google) | arXiv:2508.15734, 21/ago/2025 | preprint técnico com instrumentação em produção (autoria do próprio fornecedor; dados internos não auditáveis externamente)
- Link: https://arxiv.org/abs/2508.15734
- Status: verificado na origem (resumo e PDF abertos)
- Método e amostra: instrumentação da infraestrutura de serviço do Gemini Apps em produção; inclui potência de aceleradores ativos, energia do host (CPU/DRAM), máquinas ociosas e overhead do data center; referência de maio/2025.
- Números-chave (exatos): "the median Gemini Apps text prompt consumes 0.24 Wh of energy - a figure substantially lower than many public estimates"; "a 33x reduction in energy consumption and a 44x reduction in carbon footprint for the median Gemini Apps text prompt over one year"; "0.26 mL" de água por prompt mediano (resumo); abordagem restrita "Existing Approach (10,000 prompts per kWh)" vs. completa "Comprehensive Approach (4,167 prompts per kWh)" (p. 4); "Llama 3.1 (70B) varies from ~580 to ~3600 prompts per kWh" conforme a metodologia de medição (p. 4).
- Limitações declaradas: "External networking energy consumption is excluded due to a lack of operational control" e energia de dispositivos do usuário final fora do escopo (p. 5); medição refere-se ao prompt de texto mediano (não média) de um único fornecedor; o resumo ressalva que "these impacts are low compared to other daily activities, reducing the environmental impact of AI serving continues to warrant important attention".

## 24. Holistic Agent Leaderboard: The Missing Infrastructure for AI Agent Evaluation
- Título | autores ou veículo | data | tipo: Holistic Agent Leaderboard (HAL) | Sayash Kapoor, Benedikt Stroebl, ..., Percy Liang, Arvind Narayanan (Princeton e colaboradores); aceito no ICLR 2026 segundo resultado de busca [NÃO VERIFICADO: aceite] | arXiv:2510.11977, 13/out/2025 | preprint empírico (avaliação de agentes com custo)
- Link: https://arxiv.org/abs/2510.11977
- Status: verificado na origem (resumo e PDF abertos)
- Método e amostra: "21,730 agent rollouts across 9 models and 9 benchmarks in coding, web navigation, science, and customer service with a total cost of about $40,000"; 2.5 bilhões de tokens de chamadas de modelos; fronteiras de Pareto acurácia x custo (dólar e tokens).
- Números-chave (exatos): "higher reasoning effort reducing accuracy in the majority of runs" (resumo); "For 21 of 36 runs, higher reasoning effort does not improve accuracy" (p. 6); no ScienceAgentBench "o4-mini scores 27% while being about 5x cheaper than GPT-5, which scores 30%" (p. 5); modelos mais frequentes na fronteira: "Gemini 2.0 Flash (7 of 9 benchmarks), GPT-5 (4 of 9), and o4-mini Low (4 of 9)"; menos frequente "DeepSeek R1 (0 of 9)" (Figura 2, p. 7); "agents vary widely in costs, but evaluations rarely report these costs" (p. 2).
- Limitações declaradas: seção de limitações específica não localizada na extração do texto [NÃO VERIFICADO]; a restrição a 9 modelos e 9 benchmarks é do desenho do estudo.

## 25. Regulamento (UE) 2022/2554 (DORA): concentração de risco TIC e provedores críticos
- Título | autores ou veículo | data | tipo: Regulation (EU) 2022/2554 on digital operational resilience for the financial sector (DORA) | Parlamento Europeu e Conselho da UE | adotado 14/dez/2022; aplicável desde 17/jan/2025 | ato regulatório
- Link: https://eur-lex.europa.eu/legal-content/EN/TXT/?uri=CELEX:32022R2554
- Status: verificado na origem (texto em HTML aberto: Art. 29, Art. 31, Art. 64)
- Fatos (texto legal): Art. 29(1): entidades financeiras devem avaliar se um contrato levaria a "contracting an ICT third-party service provider that is not easily substitutable" ou a "multiple contractual arrangements ... with the same ICT third-party service provider"; Art. 31(1)(a): as ESAs "designate the ICT third-party service providers that are critical for financial entities"; critérios do Art. 31(2) incluem impacto sistêmico, dependência para funções críticas e "the degree of substitutability", considerando "the lack of real alternatives, even partial, due to the limited number of ICT third-party service providers active on a specific market" e "difficulties in relation to partially or fully migrating the relevant data and workloads ... due either to significant financial costs, time or other resources"; Art. 64: "It shall apply from 17 January 2025."
- Consequência concreta: primeira lista de 19 provedores críticos (incluindo AWS, Google Cloud e Microsoft) publicada pelas ESAs em nov/2025 segundo cobertura de imprensa; a lista oficial não foi aberta (domínios das ESAs inacessíveis) [NÃO VERIFICADO].
- Limitações declaradas: não se aplica (texto normativo).

## 26. Proposal for the Cloud and AI Development Act (CADA), COM(2026) 502
- Título | autores ou veículo | data | tipo: Proposal for the Cloud and AI Development Act (CADA) | Comissão Europeia (DG CONNECT) | 03/jun/2026 | proposta legislativa (ainda não é lei; em tramitação)
- Link: https://digital-strategy.ec.europa.eu/en/library/proposal-cloud-and-ai-development-act-cada
- Status: página oficial da Comissão aberta na origem; texto integral da proposta, anexos e avaliação de impacto não abertos (domínio de download ec.europa.eu inacessível)
- Fatos (página oficial): "The Commission has adopted a proposal for the Cloud and AI Development Act (CADA)"; três objetivos: pesquisa/desenvolvimento/inovação, capacidade ("accelerating the conditions for deploying data centres across the EU") e autonomia ("introducing a single EU-wide assessment framework for cloud and AI sovereignty, accompanied by a public sector adoption mechanism"); complementa "Chips Act 2.0 and the EU Open Source Strategy"; documentos listados: COM(2026) 502 (proposta e anexos) e SWD(2026) 502 (avaliação de impacto, partes 1 e 2, e resumo).
- Números: "more than 70% of the European cloud market" detido por três hiperescaladores não europeus e meta de triplicar capacidade de data centers até 2035 aparecem só em resumos de escritórios de advocacia [NÃO VERIFICADO].
- Limitações declaradas: não se aplica (texto legislativo em tramitação; conteúdo pode mudar).

## 27. The AI Ecosystem: Structure, Financing, and Financial Stability Considerations (IMF Technical Notes and Manuals 2026/13)
- Título | autores ou veículo | data | tipo: The AI Ecosystem: Structure, Financing, and Financial Stability Considerations | Yingyuan Chen, Deepali Gautam, Jason Wu (FMI) | 2026 (mês exato não localizado no PDF; dados até 2026:Q2) | nota técnica institucional com dados de mercado e modelagem GARCH
- Link: https://www.imf.org/-/media/files/publications/tnm/2026/english/tnmea2026013.pdf
- Status: verificado na origem (PDF aberto)
- Método e amostra: mapeamento do "AI Value Stack" por camadas; dados Bloomberg; análise de 14 maiores acordos de financiamento circular nos EUA com divulgação pública; modelos DCC-GARCH e multivariado-GARCH com retornos semanais de ações desde 2016.
- Números-chave (exatos): "Hyperscalers alone accounted for roughly $500 billion in capital expenditure (capex) in 2025, while total AI-related capex is projected to exceed $4 trillion by 2029, with close to 75 percent originating from hyperscalers" (p. 8); "the largest AI firms accounting for about 35 percent of total market capitalization" (p. 8); "The IMF staff have investigated 14 of the largest circular financing deals in the United States ... account for close to 50 and 40 percent of revenue and market capitalization, respectively ... their market-implied valuation is about $20 trillion" (p. 14); "Some of the most systemically relevant nodes remain private and operate with limited disclosure. Foundational model labs—including OpenAI, Anthropic ..." (p. 12); "Current financial stability risks appear manageable, but vulnerabilities could build as leverage, concentration, and interconnectedness increase" (p. 4).
- Limitações declaradas: "Current estimates on financing and revenue commitments likely represent a lower bound on the eventual scale of a circular financing arrangement" (p. 14); acordos analisados são os que têm "public disclosures and were subject to media reports" (p. 14); "Loss-making GPU/Neocloud firms are excluded from valuation comparisons" (p. 11); aviso padrão de que as opiniões não representam necessariamente as do FMI.

## 28. Certificates without Electrons? Theory and Evidence on Impacts from AI-Driven Power Demand
- Título | autores ou veículo | data | tipo: Certificates without Electrons?... | Dana Golden, Aruna Balasubramanian, Niranjan Balasubramanian | arXiv:2606.00811, 30/mai/2026 (v2 de 2/ago/2026) | preprint empírico (diferenças em diferenças) com modelo teórico
- Link: https://arxiv.org/abs/2606.00811
- Status: verificado na origem (resumo e PDF abertos)
- Método e amostra: modelo de teoria dos jogos (RECs, PPAs, colocação atrás do medidor) e diferenças em diferenças escalonadas usando lançamentos de LLMs como experimento natural, com base de dados nova ligando atividade de IA a resultados da rede local; seção de identificação com testes placebo e de tendências paralelas.
- Números-chave (exatos): "Data centers now account for 4.4% of United States electricity demand"; "AI demand significantly increases fossil generation, wholesale prices (up to 25% in treated PJM zones), and outage frequency (0.5-1 additional outages per year) near data centers, with impacts scaling in model size" (resumo, p. 2); "Data centers with on-site generation exhibit a sign reversal in power-quality effects"; "REC-only strategies do not" mitigar impactos (resumo); aumento de geração fóssil próxima "on the order of terawatt-hours" (p. 5).
- Limitações declaradas (p. 4): "There is a lack of specific information about when and where models are trained and released"; "The DiD method at its core relies on the parallel trends assumption"; possíveis fatores de confusão; autores relatam testes de robustez (placebo, tendências paralelas).

## 29. Siting and Curtailment Depth Limit the Grid Headroom Available to New Large Loads
- Título | autores ou veículo | data | tipo: Siting and Curtailment Depth Limit the Grid Headroom Available to New Large Loads | Nils Johnson, Geoff Blanford, John E.T. Bistline | arXiv:2611.00462, 30/out/2026 | preprint (modelagem de sistema energético, 16 regiões dos EUA)
- Link: https://arxiv.org/abs/2611.00462
- Status: resumo verificado na origem; leitura parcial do PDF
- Método e amostra: modelo nacional de sistemas de energia que co-otimiza geração horária e curtailment de carga em 16 regiões dos EUA.
- Números-chave (exatos, resumo): "Data center demand is increasing faster than generation can be built"; "50 GW can be served while curtailing less than 0.1% of its annual energy"; "Most regions require curtailment deeper than 90% in at least one hour, so the load must disconnect or have sufficient on-site resources to provide full back up"; "announced data center locations are not aligned with modeled headroom and relying on existing generation fleets raises CO2 emissions and wholesale electricity prices".
- Limitações declaradas: premissas do modelo (por exemplo, localização das cargas alinhada à folga de flexibilidade) discutidas na introdução (p. 2); seção formal de limitações [NÃO VERIFICADO].

---

# Fontes localizadas, mas não abertas na origem (domínio bloqueado na rede da sessão)

Os itens 30 a 40 foram identificados por busca na web. O documento original não pôde ser aberto; os dados citados vêm de trechos de resultados de busca e de resumos secundários e não foram conferidos no texto original. Páginas e seções de origem não disponíveis.

## 30. Energy and AI (IEA)
- Título | autores ou veículo | data | tipo: Energy and AI | International Energy Agency | abr/2025 | relatório institucional com cenários
- Link: https://www.iea.org/reports/energy-and-ai (domínio iea.org bloqueado)
- Status: [NÃO VERIFICADO]
- Método e amostra: modelagem de cenários de demanda elétrica de data centers (detalhes do método não conferidos).
- Números-chave conforme resultados de busca: [NÃO VERIFICADO] demanda global de data centers de ~415 TWh em 2024 (~1,5% da eletricidade mundial), ~945 TWh em 2030 no caso-base, faixa de 700 a 1.700 TWh em 2035; ~20% dos projetos planejados de data centers em risco de atraso por restrições de rede.
- Verificação parcial indireta: a nota FEDS de out/2025 (item 13) cita "the IEA projects that global electricity consumption from data centers will more than double by 2030"; o AI Index 2026 usa dados do IEA (2025) nas Figuras 1.4.12 e 1.4.13 (p. 41).
- Limitações declaradas: [NÃO VERIFICADO]

## 31. 2024 United States Data Center Energy Usage Report (LBNL)
- Título | autores ou veículo | data | tipo: 2024 United States Data Center Energy Usage Report | Lawrence Berkeley National Laboratory (encomendado pelo DOE) | dez/2024 (divulgação pública em 2025 segundo resultados; data de publicação fora do período-alvo por poucos dias) | relatório técnico de laboratório nacional
- Link: https://www.energy.gov/articles/doe-releases-new-report-evaluating-increase-electricity-demand-data-centers e https://newscenter.lbl.gov/2025/01/15/berkeley-lab-report-evaluates-increase-in-electricity-demand-from-data-centers/ (domínios energy.gov e lbl.gov bloqueados)
- Status: [NÃO VERIFICADO]
- Números-chave conforme resultados de busca: [NÃO VERIFICADO] consumo de data centers de 58 TWh em 2014 para 176 TWh em 2023 (~4,4% do consumo anual dos EUA, sem criptomoedas); projeção de 325 a 580 TWh em 2028.
- Limitações declaradas: [NÃO VERIFICADO]; resultado de busca registra que a revisão de 2024 alterou a linha de base de 2014 em relação ao relatório de 2016, o que exige cuidado em comparações de crescimento.

## 32. FTC Staff Report on AI Partnerships and Investments (6(b) study)
- Título | autores ou veículo | data | tipo: Staff Report on AI Partnerships & Investments 6(b) Study | Federal Trade Commission (Office of Technology) | 17/jan/2025 | relatório de autoridade de concorrência com base em ordens 6(b)
- Link: https://www.ftc.gov/system/files/ftc_gov/pdf/p246201_aipartnerships6breport_redacted.pdf (domínio ftc.gov bloqueado)
- Status: [NÃO VERIFICADO]
- Fatos conforme resultados de busca: [NÃO VERIFICADO] cobre três parcerias (Microsoft-OpenAI, Amazon-Anthropic, Google-Anthropic) e cinco empresas; ordens 6(b) emitidas em jan/2024 e informações fornecidas até set/2024; termos destacados incluem participações societárias relevantes, direitos de participação em receita, direitos de consulta e obrigações de exclusividade; Comissão votou 5-0 para divulgar; comissários Ferguson e Holyoak discordaram parcialmente da seção "Areas to Watch".
- Limitações declaradas conforme resultados de busca: [NÃO VERIFICADO] "A comprehensive analysis of the subject partnerships is beyond the scope of the report."

## 33. Cloud services market investigation: final decision (CMA, Reino Unido)
- Título | autores ou veículo | data | tipo: Cloud services market investigation, final decision | Competition and Markets Authority | 31/jul/2025 | decisão de autoridade de concorrência
- Link: https://www.gov.uk/cma-cases/cloud-services-market-investigation (domínio gov.uk bloqueado)
- Status: [NÃO VERIFICADO]
- Fatos conforme resultados de busca: [NÃO VERIFICADO] AWS e Microsoft com cada uma entre 30% e 40% do gasto em nuvem no Reino Unido; barreiras apontadas: taxas de egress, arquiteturas incompatíveis e regras de licenciamento de software da Microsoft; remédio recomendado: investigações de Status de Mercado Estratégico (SMS) sob a lei DMCC, com decisão sobre priorização prevista para o 1º trimestre de 2026; um artigo de abril/2026 do Diginomica (opinião, não verificado) relata que a CMA teria optado por investigar apenas a Microsoft.
- Limitações declaradas: [NÃO VERIFICADO]

## 34. Investigações de mercado da Comissão Europeia sobre computação em nuvem sob o Digital Markets Act (AWS e Azure)
- Título | autores ou veículo | data | tipo: Market investigations into cloud computing under the DMA | Comissão Europeia | aberto em 18/nov/2025 | procedimento regulatório (ato da Comissão)
- Link: sem link oficial aberto (domínios ec.europa.eu e digital-markets-act.ec.europa.eu bloqueados); cobertura de imprensa citada na busca, por exemplo https://www.theregister.com/2025/11/18/amazon_microsoft_cloud_dma/
- Status: [NÃO VERIFICADO]
- Fatos conforme resultados de busca: [NÃO VERIFICADO] três investigações: duas para avaliar designação de AWS e Azure como controladores de acesso (gatekeepers) mesmo abaixo dos limiares quantitativos, e uma sobre o setor de nuvem como um todo, com relatório final em até 18 meses; meta de concluir as duas primeiras em 12 meses; relatos de visão preliminar da Comissão em junho de 2026 de que ambas deveriam ser designadas (apenas imprensa); decisão final de designação não localizada.
- Limitações declaradas: [NÃO VERIFICADO]

## 35. PJM Independent Market Monitor: análise dos leilões de capacidade e carga de data centers
- Título | autores ou veículo | data | tipo: Análises do Monitoring Analytics (monitor de mercado independente da PJM) sobre os leilões de capacidade 2025/26, 2026/27 e 2027/28 | Monitoring Analytics | 2025 a 2026 | relatório de monitor de mercado
- Link: https://www.monitoringanalytics.com (domínio bloqueado); cobertura secundária: https://www.utilitydive.com/news/pjm-capacity-energy-market-reliability-monitoring-analytics/814647/
- Status: [NÃO VERIFICADO]
- Números-chave conforme resultados de busca: [NÃO VERIFICADO] preço de compensação de US$ 329,17/MW-dia para 2026/27 em todas as zonas (no teto de preço aprovado pela FERC); data centers creditados com US$ 9,3 bilhões dos US$ 14,7 bilhões do leilão 2025/26 e com US$ 7,3 bilhões (82%) do aumento de receita; estimativas divergentes para o total acumulado em três leilões (US$ 21,3 bilhões em US$ 47,2 bilhões segundo um resumo; US$ 23,1 bilhões segundo outro); para 2027/28 cerca de US$ 6,5 bilhões (40%) de US$ 16,4 bilhões; recomendação do monitor de um leilão separado para data centers.
- Limitações declaradas: [NÃO VERIFICADO]; os próprios resultados de busca registram números conflitantes de custos e de déficit de capacidade.

## 36. Summary of the Amazon DynamoDB Service Disruption in the Northern Virginia (US-EAST-1) Region
- Título | autores ou veículo | data | tipo: Post-event summary | Amazon Web Services | 19 a 20/out/2025 (evento); resumo publicado após o evento | caso real documentado (incidente de nuvem)
- Link: https://aws.amazon.com/message/101925/ (domínio aws.amazon.com bloqueado)
- Status: [NÃO VERIFICADO]
- Fatos conforme resultados de busca: [NÃO VERIFICADO] falha na região us-east-1 de 23:48 PDT de 19/out a 14:20 PDT de 20/out (cerca de 14,5 horas segundo o resumo oficial citado); causa-raiz: condição de corrida em serviço interno de automação de DNS do DynamoDB, que gerou registro DNS vazio para o endpoint regional; afetou DynamoDB, APIs do EC2 e Network Load Balancer; relatos de terceiros (não conferidos) citam aplicativos e bancos fora do ar e divergem quanto ao horário final e ao número de serviços.
- Consequência concreta e limitações: [NÃO VERIFICADO]

## 37. The Latent Role of Open Models in the AI Economy
- Título | autores ou veículo | data | tipo: The Latent Role of Open Models in the AI Economy | Frank Nagle, Daniel Yue | SSRN (nov/2025; id 5767103 segundo busca) | working paper empírico
- Link: https://papers.ssrn.com/abstract=5767103 (ssrn.com bloqueado; mirrors também bloqueados)
- Status: [NÃO VERIFICADO]
- Método e amostra conforme resultados de busca: [NÃO VERIFICADO] uso diário de tokens no OpenRouter de maio a setembro de 2025, estimado em ~1% do gasto global com inferência de IA.
- Números-chave conforme resultados de busca: [NÃO VERIFICADO] modelos fechados com em média 80% dos tokens mensais apesar de preços cerca de seis vezes maiores; modelos abertos com preços ~84% menores e desempenho de 90% ou mais em benchmarks comuns; economia adicional estimada de US$ 24,8 bilhões ao consumidor em 2025 (outros resumos citam US$ 20 a 48 bilhões, com premissas diferentes).
- Limitações declaradas: [NÃO VERIFICADO]; a amostra (OpenRouter) cobre fração pequena do mercado conforme os próprios resultados.

## 38. Artificial Intelligence Markets: Recent Developments and Competition Issues (OECD)
- Título | autores ou veículo | data | tipo: Artificial Intelligence markets: recent developments and competition issues | OECD | 2025/2026 (data exata não conferida) | relatório institucional de organização internacional
- Link: https://www.oecd.org/en/publications/artificial-intelligence-markets_d531d73f-en/full-report.html (oecd.org retorna 403 na rede da sessão)
- Status: [NÃO VERIFICADO]
- Fatos conforme resultados de busca: [NÃO VERIFICADO] aponta forte concentração de insumos (computação, dados e habilidades), vantagens de pioneiro e integração vertical crescente; ao mesmo tempo desempenho crescente, preços em queda e mais desenvolvedores e provedores de modelos de fundação; concentração mais entrincheirada a montante (hardware e dados); evidências iniciais de concorrência de provedores especializados contra as grandes empresas. Resultado de busca separado cita working paper da OECD segundo o qual a adoção de IA não generativa não está associada a aumentos significativos de poder de mercado.
- Limitações declaradas: [NÃO VERIFICADO]

## 39. Dynamism in generative AI markets after the release of ChatGPT (André et al.)
- Título | autores ou veículo | data | tipo: coluna VoxEU/CEPR resumindo working paper de André et al. | André et al. | 2025 | working paper e coluna de divulgação
- Link: https://cepr.org/voxeu/columns/dynamism-generative-ai-markets-release-chatgpt (cepr.org bloqueado)
- Status: [NÃO VERIFICADO]
- Números-chave conforme resultados de busca: [NÃO VERIFICADO] participação dos EUA em LLMs em janeiro de 2025 entre 86% (cenário de altos custos de troca) e 59% (cenário de baixos custos de troca); participação de desenvolvedores chineses de 5% (altos custos de troca) a 36% (baixos) no 2º trimestre de 2024; conclusão relatada de que a posição dominante de incumbentes digitais não impediu inovação nem o acesso a modelos melhores.
- Limitações declaradas: [NÃO VERIFICADO]; o intervalo depende de pressupostos sobre custos de troca (conforme os próprios resultados de busca).

## 40. Estudos sobre data centers e preços de eletricidade com resultados divergentes (CEPR DP 21854; EPRI; Dallas Fed WP 2606)
- Título | autores ou veículo | data | tipo: três working papers: (a) Scalera, Bosetti, Pecci, CEPR Discussion Paper 21854; (b) Watten et al., EPRI working paper; (c) Kay, Reaser, Taylor, Dallas Fed Working Paper 2606 | 2026 | working papers empíricos
- Link: https://econpapers.repec.org/RePEc:cpr:ceprdp:21854 ; https://www.dallasfed.org/~/media/documents/research/papers/2026/wp2606r1.pdf (domínios bloqueados); EPRI: https://esca.epri.com/_astro/2026-jun-have-data-centers-raised-your-electric-bill.CVr2j5ls.pdf (bloqueado)
- Status: [NÃO VERIFICADO]
- Números-chave conforme resultados de busca: [NÃO VERIFICADO] (a) aumento de preços residenciais de cerca de 13% para um desvio-padrão (dez data centers) e 0,182 centavos/kWh por instalação adicional; (b) dobrar a capacidade de data centers reduziria preços residenciais em cerca de 4%, sem evidência de subsídio cruzado entre classes; (c) efeitos em mercados atacadistas com heterogeneidade geográfica considerável; relatório de consultoria E3 (mai/2026) observa que muitos estudos dependem de correlação.
- Limitações declaradas: [NÃO VERIFICADO]; os sinais dos efeitos divergem entre os estudos conforme os próprios resultados de busca.

---

# Buscas realizadas / lacunas

## Termos de busca usados (web e arXiv)
- IEA Energy and AI data centre electricity 945 TWh; LBNL 2024 United States Data Center Energy Usage Report 176 TWh
- market concentration generative AI foundation models cloud compute dependence; NBER working paper LLM market structure competition pricing; NBER OR arXiv empirical data centers retail electricity prices
- Stanford AI Index 2025 inference cost 280-fold open-weight gap; Stanford AI Index 2026 key takeaways
- ECB Financial Stability Review 2025 AI concentration; BIS Annual Economic Report AI compute concentration; Federal Reserve FEDS Notes data center electricity AI
- FTC 6(b) AI partnerships January 2025; CMA cloud services market investigation final decision; European Commission DMA market investigation cloud AWS Azure; Cloud and AI Development Act; ESAs critical ICT third-party providers DORA
- PJM capacity auction data centers market monitor; AWS us-east-1 outage October 2025
- IMF working paper AI data centers electricity; IMF working paper AI market concentration; Brookings AI compute concentration; Epoch AI power demands of frontier AI training
- Nagle Yue latent role open models; André dynamism generative AI markets; OECD Artificial intelligence markets
- arXiv (busca direta, com resultados irregulares): LLM inference prices, open-weight models economic, AI supercomputers trends, data center energy AI, market concentration generative AI, cloud concentration AI vendor lock-in, energy per query LLM inference, GPU rental price, sovereign AI compute, hyperscaler capex
- Redata (Brasil), MP 1318/2025, camara.leg.br

## Domínios bloqueados ou sem acesso nesta sessão (testados)
- Sem resolução de DNS / bloqueados: iea.org, gov.uk (incluindo assets.publishing.service.gov.uk), ftc.gov, justice.gov, competition-policy.ec.europa.eu, ec.europa.eu (incluindo presscorner e arquivos de download), digital-markets-act.ec.europa.eu, europarl.europa.eu, curia.europa.eu, epoch.ai, lbl.gov, energy.gov, eia.gov, sec.gov, fsb.org, bankofengland.co.uk, eba/eiopa/esma.europa.eu, aws.amazon.com, cepr.org, dallasfed.org, econpapers/ideas.repec.org, monitoringanalytics.com, utilitydive.com, courtlistener.com (403), congress.gov (403), openalex (cota diária esgotada, sem uso de chave), api.semanticscholar.org (429), reuters.com, cnbc.com, ft.com, wsj.com, bloomberg.com, nature.com, sciencedirect.com, springer, wiley, cambridge.org, jstor.org, openreview.net, dl.acm.org, linuxfoundation.org, mitsloan.mit.edu, promarket.org, issues.org.
- Retornam 403 (política de rede): oecd.org, papers.ssrn.com, science.org, academic.oup.com, weforum.org.
- Acessíveis e usados: arxiv.org, nber.org (apenas páginas de resumo; PDFs retornam "Access denied"), hai.stanford.edu, bis.org, federalreserve.gov, ecb.europa.eu, eur-lex.europa.eu, digital-strategy.ec.europa.eu (instável, com respostas 429 em parte das tentativas), imf.org (apenas caminhos diretos de arquivos), doi.org (redirecionamento).
- Nenhuma tentativa de contornar bloqueios ou de alterar configurações de ambiente.

## O que não foi encontrado ou não pôde ser verificado
- Textos integrais dos working papers NBER 34608, 33139 e 35953 (PDF com acesso negado): números e limitações restritos aos resumos; corpo do texto não lido.
- Epoch AI (publicações sobre preços de inferência, demanda de energia de treino de modelos de fronteira e tendências de compute): domínio bloqueado; resumo de busca registra projeção de 4 a 16 GW para os maiores treinos em 2030 e crescimento de 2,2x a 2,9x ao ano da demanda de potência, sem conferência na origem.
- Decisões judiciais: nenhuma decisão judicial (por exemplo, processos de remédios contra a Google nos EUA ou casos de antitruste contra fornecedores de chips) pôde ser aberta em fonte primária; nenhum caso judicial verificado neste arquivo.
- Atos de concorrência primários (FTC, CMA, Comissão Europeia): apenas via resultados de busca (itens 32 a 34).
- Lista oficial de provedores críticos de TIC sob DORA (ESAs, nov/2025): não aberta; só o texto do regulamento foi verificado (item 25).
- Casos de dependência de fornecedor em nível de empresa usuária (por exemplo, restrição de acesso a APIs por um provedor a um cliente, descontinuação de modelo, mudança de preços): não localizados em fonte primária acessível.
- Brasil: Redata (MP 1318/2025, depois PL 278/2026): resultados de busca divergem quanto à situação final; texto oficial no camara.leg.br não localizado nesta sessão; nenhuma fonte brasileira verificada neste arquivo.
- OECD (relatório "Artificial intelligence markets" e roundtable de infraestrutura de IA, dez/2025): bloqueado (403).
- Preços de inferência de agentes em produção e custos de compute para empresas usuárias em contratos reais (preços de enterprise não são publicados; a nota FEDS de jul/2026 registra essa limitação).
- Dados de participação de mercado de nuvem para IA (AWS, Azure, Google) em fonte primária verificada: não localizados; o item 33 traz apenas a participação de 30% a 40% do gasto no Reino Unido segundo resultados de busca.
