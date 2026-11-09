# Tema 6: Trabalho e competências — substituição vs. complementação, deskilling e efeitos em profissionais juniores

Data da busca: 09/nov/2026
Período-alvo: jan/2025 a nov/2026
Nota de método: "Verificado na fonte original" = documento original aberto (PDF/HTML via curl) e números conferidos no texto. Dados que não foram conferidos na origem recebem o marcador de não verificado, aplicado somente a esses dados. Itens 37 a 49 são pistas localizadas, não abertas na origem. Sem análise ou conclusões neste arquivo. Páginas citadas = página do PDF (contagem de páginas do arquivo), salvo indicação.

---

## 1. How AI Impacts Skill Formation
- Autores/veículo: Judy Hanwen Shen (Anthropic Fellows Program), Alex Tamkin (Anthropic) | arXiv:2601.20245 (v2, 1/fev/2026; documento datado 3/fev/2026) | Tipo: preprint, experimento randomizado (pré-registrado)
- Link: https://arxiv.org/abs/2601.20245 (PDF: https://arxiv.org/pdf/2601.20245) | DOI: https://doi.org/10.48550/arXiv.2601.20245
- Método e amostra: experimentos randomizados em que programadores (freelancers/profissionais, maioria com 25-35 anos e bacharelado) aprendem a biblioteca Python assíncrona Trio com ou sem assistente de IA em chat; tarefa de até 35 min seguida de quiz de 27 pontos (sem IA); amostra principal n=52 (26 por grupo), pré-registro em osf.io/w49e7 (§5.2, p. 7-9).
- Números-chave: Abstract (p. 1): "AI use impairs conceptual understanding, code reading, and debugging abilities, without delivering significant efficiency gains on average". §1 (p. 2): redução do escore de avaliação "by 17% or two grade points (Cohen's d = 0.738, p = 0.010)"; sem aceleração estatisticamente significativa do tempo de conclusão. §5.2.2 (p. 9): "There is a 4.15 point difference between the means of the treatment and control groups. For a 27-point quiz, this translates into a 17% score difference or 2 grade points"; com covariável de tempo de aquecimento, "Cohen's d=0.725, p=0.016". Seis padrões de interação com IA, três deles preservam aprendizado (Abstract; Fig. 1, p. 2).
- Limitações declaradas (§7.1, p. 19): tarefa única com interface de chat ("lower bound" para offloading cognitivo; agentes de código não testados); duração de ~1 h ("skill formation takes place over months to years"); "Participant Realism": participantes sem o mesmo incentivo de aprender que teriam em um emprego real; habilidade de prompting medida só por autorrelato; avaliação por quiz; sem contrafactual de assistência humana. Piloto com não conformidade (35% dos participantes sem IA usaram IA em um piloto; ~25% em outro) descrita no apêndice (p. 7).
- Status: Verificado na fonte original.

## 2. Your Brain on ChatGPT: Accumulation of Cognitive Debt when Using an AI Assistant for Essay Writing Task
- Autores/veículo: Nataliya Kosmyna, Eugene Hauptmann, Ye Tong Yuan, Jessica Situ, Xian-Hao Liao, Ashly Vivian Beresnitzky, Iris Braunstein, Pattie Maes (MIT Media Lab e outros) | arXiv:2506.08872 (junho/2025) | Tipo: preprint ("under review"), experimento com EEG
- Link: https://arxiv.org/abs/2506.08872 (PDF: https://arxiv.org/pdf/2506.08872) | DOI: https://doi.org/10.48550/arXiv.2506.08872
- Método e amostra: 54 participantes (MIT, Wellesley, Harvard, Tufts, Northeastern etc.) divididos em 3 grupos (LLM, motor de busca, sem ferramenta), 3 sessões de redação de ensaio; na 4ª sessão, os grupos LLM e sem ferramenta trocaram de condição (18 participantes completaram); EEG, análise de NLP, entrevistas e pontuação por professores e "AI judge" (Abstract, p. 2; §Participants, p. 22).
- Números-chave: Abstract (p. 2): "We recruited a total of 54 participants for Sessions 1, 2, 3, and 18 participants among them completed session 4"; "LLM assistance elicited the weakest overall coupling" de conectividade neural; "the LLM group's participants performed worse than their counterparts in the Brain-only group at all levels: neural, linguistic, scoring". Capacidade de citar (p. 31): "83.3 % of participants (15/18) failed to provide a correct quotation, whereas only 11.1 % (2/18) in both the Search-Engine and Brain-Only groups encountered the same difficulty".
- Limitações declaradas (seção "Limitations and Future Work", p. 151): "a limited number of participants recruited from a specific geographical area, several large academic institutions"; amostra a ampliar com profissionais e faixas etárias diversas e maior equilíbrio de gênero; resultados da sessão 4 descritos como "preliminary, as a larger participant sample is needed to confirm" (p. 151); estudo feito só com ChatGPT; documento marcado "Preprint, under review" (não revisado por pares no momento da versão consultada).
- Status: Verificado na fonte original.

## 3. Artificial Intelligence and the Labor Market
- Autores/veículo: Menaka Hampole, Dimitris Papanikolaou, Lawrence D.W. Schmidt, Bryan Seegmiller | NBER Working Paper 33509 (fev/2025; revisão set/2025) | Tipo: working paper NBER (dados de currículos e vagas; inclui IA/ML em geral, 2010-2023)
- Link: https://www.nber.org/papers/w33509 | DOI: https://doi.org/10.3386/w33509 | PDF: https://www.nber.org/system/files/working_papers/w33509/w33509.pdf
- Método e amostra: medida de exposição de tarefas a IA construída com NLP sobre dados da Revelio Labs (currículos e vagas, "near-universe of LinkedIn profiles and job postings"), O*NET, 2010-2023; adoção de IA por empresas via "AI integrators"; modelo que separa substituição direta de realocação indireta; instrumento baseado em redes históricas de contratação universitária; amostra de empresas de capital aberto da Compustat (§1.1, p. 9-10).
- Números-chave: Abstract (página NBER): "Despite strong substitution at the task level, overall employment effects are modest, as reduced demand in exposed occupations is offset by productivity-driven increases in labor demand at AI-adopting firms." p. 6: "a one-standard deviation increase in mean task exposure reduces the occupation's within-firm employment share by about 14.5 percent over five years, while a similar increase in concentration raises it by about 7.5 percent"; "employment in highly exposed occupations (90th percentile of the pay distribution) falls by about 3.1% relative to the least exposed (bottom percentile)", efeito "mildly reversed" após considerar o crescimento das empresas. p. 17: aumento de 1 desvio-padrão na exposição de tarefa "lowers demand for the associated skills by about 2 percent over five years". p. 5: estimativas IV da adoção de IA "about 30 percent larger than OLS", com maior crescimento de receita, produtividade, lucro e emprego.
- Limitações declaradas: p. 10: dados de currículos "are not a random sample of the U.S. workforce"; sobre-representam "professional occupations, younger cohorts, and digitally engaged workers"; p. 11: só captura aplicações de IA desenvolvidas internamente; p. 36: análise restrita a empresas de capital aberto da Compustat, e "our estimates may overstate the overall economic impact of AI during our sample".
- Status: Verificado na fonte original.

## 4. The AI Index Report 2026, Capítulo 4 "Economy" (seção 4.4 Jobs; "AI's Labor Impact")
- Autores/veículo: Stanford Institute for Human-Centered AI (HAI), AI Index Steering Committee | abr/2026 (edição 2026 do AI Index) | Tipo: relatório institucional (compilação de estudos e dados de terceiros, com fontes declaradas)
- Link: https://hai.stanford.edu/ai-index/2026-ai-index-report/economy | PDF do capítulo: https://hai.stanford.edu/assets/files/ai_index_report_2026_chapter_4_economy.pdf
- Método e amostra: capítulo que compila estudos micro (produtividade por trabalhador) e macro (emprego), dados de Brynjolfsson et al. (2025, ADP), McKinsey (pesquisa de organizações) e outros; tabela-resumo de estudos (Figura 4.4.28, p. 51 do PDF do capítulo).
- Números-chave: Destaque 7 (p. 3): "AI's labor market effects are showing up unevenly, concentrated in hiring pipelines and the youngest workers in exposed occupations. Employment for software developers ages 22 to 25 has fallen nearly 20% from 2024." Destaque 8 (p. 3): "One-third of organizations expect AI to reduce their workforce in the coming year, even though large-scale job losses have not yet shown up in overall employment data. Almost half of organizations surveyed expected little to no change." Texto (p. 51): "The evidence does not point to broad, uniform displacement"; "By September 2025, employment for software developers ages 22–25 had fallen close to 20% from its 2022 peak" (nota: o destaque diz "from 2024", o corpo do texto diz "from its 2022 peak"; ambas as formulações constam do documento). Micro (p. 49): agentes de suporte resolveram "14%–15% more issues per hour", desenvolvedores com Copilot "26% more pull requests", times de marketing "50% increase in output per worker"; "the less experienced workers tended to benefit the most"; METR "19 percent slower", com ressalva de que a equipe "has not been able to replicate the results in a later study"; sobre habilidades, "mixed results", citando "learning penalties" (Shen e Tamkin). Tabela (p. 51): Aldasoro et al. (2026), ~12.000 empresas europeias, "AI adoption increases efficiency without reducing short-run employment", "+4% increase in labor productivity"; Penn Wharton Budget Model (2025) "+0.01 percentage points contribution to TFP (negligible)"; Hosseini e Lichtinger (2025), 62 milhões de trabalhadores/285.000 empresas; Brynjolfsson et al. (2025) "-15% to -16% employment for early-career workers"; Frank et al. (2026) "Deterioration in AI-exposed labor markets (unemployment risk) began in early 2022, pre-ChatGPT".
- Limitações declaradas (p. 49 e p. 51): "It is challenging to measure AI's impact on employment, particularly because the technology is still in the early stages of widespread deployment"; "as with any emerging research area, results vary in methodology, scope, and context"; "AI's productivity effects are highly context dependent"; "Early macro-level evidence" (p. 49).
- Status: Verificado na fonte original (PDF do capítulo; números das tabelas e destaques conferidos no texto; os estudos citados são secundários neste item).

## 5. AI-exposed jobs deteriorated before ChatGPT
- Autores/veículo: M. R. Frank, A. Javadian Sabet, L. Simon, S. H. Bana, R. Yu (Case Western Reserve University, Stanford Digital Economy Lab, Microsoft AI Economy Institute, Revelio Labs, LSE, Columbia) | arXiv:2601.02554 (v2, 16/out/2026; documento datado 19/out/2026) | Tipo: preprint com dados administrativos e de plataformas (resultado contrário ao discurso dominante)
- Link: https://arxiv.org/abs/2601.02554 (PDF: https://arxiv.org/pdf/2601.02554) | DOI: https://doi.org/10.48550/arXiv.2601.02554
- Método e amostra: (i) registros mensais de seguro-desemprego (ETA 203, Dept. of Labor) por ocupação e estado, jan/2015 a out/2025, combinados com BLS OEWS para medir "unemployment risk"; (ii) milhões de perfis LinkedIn (Revelio Labs), coortes de graduados 2017-2024, seguidas por até 3 anos; (iii) milhões de ementas universitárias para medir exposição curricular a LLMs. Exposição de ocupações = parcela de tarefas O*NET afetáveis por LLMs (§ "Unemployment risk for AI exposed occupations", p. 4-5).
- Números-chave: Abstract (p. 1): "risk rose in AI-exposed occupations beginning in early 2022, months before ChatGPT was released"; "graduate cohorts from 2021 onward entered AI-exposed jobs at lower rates than earlier cohorts, with gaps opening before late 2022"; "graduates taking more LLM-exposed curricula had shorter job searches after ChatGPT and higher first-job pay when entering highly exposed occupations". p. 2: "generative AI may not be the root cause of these labor market hardships and that the launch of ChatGPT is a faulty natural experiment". p. 4: dados de seguro-desemprego mensais de jan/2015 a out/2025; coortes de 2017 a 2024. p. 5: exposição varia de 0,069 (construção) a 0,741 (computação e matemática).
- Limitações declaradas: p. 16: "One caveat to our analysis is our inability to control for students' self-selection into college majors, universities, or occupations upon graduation"; resultados sobre currículo "not causal"; p. 15: a representatividade das coortes no LinkedIn é uma limitação; p. 5: o risco de desemprego não capta saídas para empregos de menor remuneração sem pedido de seguro; p. 20: "Our analysis does not rule out the potential for AI to create job loss in the future"; p. 8: em alguns estados (AK, CA, WA) há aumento do risco após o lançamento, onde "timing alone cannot rule out a contribution from LLM diffusion".
- Status: Verificado na fonte original.

## 6. AI adoption, productivity and employment: evidence from European firms
- Autores/veículo: Iñaki Aldasoro, Leonardo Gambacorta, Rozalia Pal, Debora Revoltella, Christoph Weiss, Marcin Wolski | BIS Working Paper No 1325 | 23/jan/2026 | Tipo: working paper de banco central (BIS), dados de firmas; resultado de ausência de efeito adverso no emprego
- Link: https://www.bis.org/publ/work1325.htm (PDF: https://www.bis.org/publ/work1325.pdf)
- Método e amostra: dados pareados EIBIS-ORBIS de "more than 12,000 non-financial firms in the European Union (EU) and United States (US)"; adoção de IA por firmas da UE instrumentada pelas taxas de adoção de pares dos EUA (Abstract, página BIS).
- Números-chave (Abstract e "Findings", página BIS; o PDF completo com paginação não foi lido, apenas a página de resumo): "AI adoption increases the level of labor productivity by 4%"; "Productivity gains are due to capital deepening, as we find no adverse effects on firm-level employment. This suggests that AI increases worker output rather than replacing labor in the short run, though longer-term effects remain uncertain"; "productivity benefits of AI adoption are unevenly distributed and concentrate in medium and large firms"; "AI-adopting firms are more innovative and their workers earn higher wages"; destaca investimentos complementares em "software and data or workforce training". O valor "+5.9 percentage point gain for every 1% spent" em treinamento consta apenas na tabela do AI Index 2026 (item 4) e não foi conferido neste documento [NÃO VERIFICADO].
- Limitações declaradas: "longer-term effects remain uncertain"; efeito de curto prazo; página de resumo traz ressalva institucional de que as opiniões são dos autores e não do BIS.
- Status: Verificado na fonte original (página de resumo/abstract do BIS); detalhes metodológicos e limitações do corpo do artigo não lidos.

## 7. Firm Data on AI
- Autores/veículo: Ivan Yotzov, Jose Maria Barrero, Nicholas Bloom, Philip Bunn, Chanya Chawla, Steven J. Davis, Kevin M. Foster, Aaron Jalca, Brent H. Meyer, Paul Mizen, Michael A. Navarrete, Samil Oh, Katia Garcia Loredo, Monique Reid, Pawel Smietanka, Gregory Thwaites, Ben Zhe Wang | NBER Working Paper 34836 (fev/2026; revisão out/2026) | Tipo: working paper NBER, survey de executivos (resultado de efeito nulo líquido no emprego)
- Link: https://www.nber.org/papers/w34836 | DOI: https://doi.org/10.3386/w34836
- Método e amostra: survey no verão de 2026 com "nearly 9,000 CFOs, CEOs and senior executives at firms in the US, UK, Germany, Australia, Canada, Mexico and South Africa" (Abstract, versão revisada out/2026). A versão anterior (mar/2026) tinha amostra menor (~6.000 executivos em 4 países, segundo resultados de busca; não aberta) [NÃO VERIFICADO].
- Números-chave (Abstract, página NBER): "78% of firms use AI"; "80% of executives report regularly using AI, with an average use of 2.1 hours per week, up from 1.5 hours per week in Winter 2026"; "executives report that AI has had essentially no net effect on firm employment over the last 3 years, and predict little net impact over the next 3 years"; "more than 40% of firms anticipate positive or negative employment effects that roughly offset only in the aggregate"; "AI adoption has raised annual labor productivity growth by 0.2% over the last 3 years", com expectativa de "0.6% per annum" nos próximos 3 anos; gasto de ~US$ 2.000 por empregado nos EUA em 2026, "just 2% of firms accounting for over 50% of total spending".
- Limitações declaradas: dados autorrelatados por executivos (survey); o texto completo (PDF) não foi acessível (403), de modo que limitações do corpo do artigo não foram lidas [NÃO VERIFICADO].
- Status: Verificado na fonte original apenas no nível do abstract (página NBER).

## 8. Anthropic Economic Index report: Economic primitives (jan/2026)
- Autores/veículo: Anthropic, Economics team (relatório institucional de fornecedor de IA; dados do próprio serviço) | 15/jan/2026 | Tipo: relatório institucional com metodologia declarada (análise de uso do Claude; não é amostra de trabalhadores)
- Link: https://www.anthropic.com/research/anthropic-economic-index-january-2026-report
- Método e amostra: "random sample of 1M conversations from Claude.ai Free, Pro and Max" e "1M transcripts from our first-party (1P) API traffic", de 13 a 20/nov/2025 (nota 1 da Introdução); conversas classificadas em cinco tipos de interação agrupados em automação vs. augmentation; exercício de remoção de tarefas inspirado em Autor e Thompson (2025) com nível de escolaridade previsto por modelo a partir de embeddings de tarefas (Cap. 4).
- Números-chave (Cap. 1, 4): "In January 2025, augmented use of Claude was dominant: 56% of conversations were classified as augmentation compared to 41% automated"; em ago/2025 automação superou augmentation; "Data from November 2025 points to a broad-based shift back toward augmented use on Claude.ai: The share of conversations classified as augmented jumped 5pp to 52% and the share deemed automated fell 4pp to 45%"; conversas "directive" foram de 27% (jan/2025) a 39% (ago/2025) e 32% (nov/2025). Cap. 4: "removing tasks Claude can already handle from the economy would produce a net deskilling effect: the tasks remaining for humans have lower educational requirements than those handled by AI"; exemplos: agentes de viagem "would experience deskilling", gestores de propriedades "would experience upskilling"; produtividade implícita de "1.8 percentage points per year over the next decade", que cai para "about 1.0 percentage points" ao ajustar pela confiabilidade das tarefas.
- Limitações declaradas (Cap. 4): o resultado de deskilling é "highly suggestive" mas "may miss an important detail: the most complex tasks where Claude is used tend also to be those where it struggles most", o que poderia "reinforce the value of their complementary expertise"; estimativas "reflect current model capabilities"; amostras de uma semana; exclusão de Seychelles e Wyoming por tráfego abusivo (notas 5-6, Cap. 3); a tradução de uso em efeitos de emprego é indireta.
- Status: Verificado na fonte original (HTML; sem numeração de páginas).

## 9. Anthropic Economic Index report: Learning curves (mar/2026)
- Autores/veículo: Anthropic, Economics team | 24/mar/2026 | Tipo: relatório institucional com metodologia declarada (dados de uso do Claude)
- Link: https://www.anthropic.com/research/economic-index-march-2026-report
- Método e amostra: uso do Claude de 5 a 12/fev/2026; análise de "learning curves" comparando usuários por tempo de adesão (tenure) e seleção de modelo.
- Números-chave (Cap. 1, "What has changed"): "the rate of augmentation ... increased slightly in both Claude.ai and API traffic"; "Coding tasks continue to migrate from augmentative usage in Claude.ai to more automated workflows in our first-party API traffic"; "the top 10 tasks made up 19% of all traffic in February, down from 24% in November"; "About 49% of jobs have seen at least a quarter of their tasks performed using Claude"; "more experienced users not only attempt higher-value tasks, but are also more likely to elicit successful responses in their conversations"; "the top 20 countries account for 48% of all per-capita usage, up from 45%".
- Limitações declaradas: o relatório descreve que a evidência de "learning-by-doing" é "consistent with" (compatível com) e não prova causalidade [seção "Learning to use AI"; trecho lido apenas na introdução do relatório]. Apêndice com limitações não lido em detalhe [NÃO VERIFICADO].
- Status: Verificado na fonte original (introdução e Cap. 1 do HTML).

## 10. You're (not) Hired: Artificial Intelligence and Early Career Hiring in the Quarterly Workforce Indicators
- Autores/veículo: Lee C. Tucker | U.S. Census Bureau, Center for Economic Studies Working Paper CES-26-27 | abr/2026 | Tipo: working paper de instituição oficial (dados administrativos empregador-empregado)
- Link: https://www.census.gov/library/working-papers/2026/adrm/CES-WP-26-27.html (PDF em www2.census.gov: domínio bloqueado nesta sessão)
- Método e amostra: tabulações detalhadas dos Quarterly Workforce Indicators (dados administrativos pareados empregador-empregado) por célula setor-estado; trabalhadores de início de carreira (22-24 anos); event study, triple difference, projeções locais por choques de política monetária e decomposição histórica (Abstract).
- Números-chave (Abstract): "Regression adjusted employment of early career workers in the most AI-exposed quintile of industry-state cells declined by 12% over the 10 quarters following the introduction of ChatGPT, even as employment in less exposed industries has remained stable"; "The decline in hires is the primary cause of large observed declines in employment"; "The rate of hiring largely recovered by early 2025, attributable to a smaller employment base"; "Earnings growth of early career workers in the most exposed industries slowed slightly"; "up to one quarter of relative early career employment declines through 2025q2 may be attributable to monetary policy shocks through 2023"; "industries with high AI exposure are not particularly sensitive to unexpected fluctuations in monetary policy on average".
- Limitações declaradas (Abstract): "triple difference estimates provide some evidence of earlier trend shifts on employment, hiring, and separations around the onset of the COVID pandemic"; discute explicações alternativas, incluindo "increase in remote work and increased educational attainment among workers in AI-exposed occupations". Corpo do artigo (PDF) não acessível.
- Status: Verificado na fonte original apenas no nível do abstract (página do Census).

## 11. Graduating into Disruption: Labor Market Outcomes for AI-Exposed College Majors
- Autores/veículo: Cody Orr, Lee C. Tucker, Lawrence Warren | U.S. Census Bureau, CES Working Paper CES-26-56 | set/2026 | Tipo: working paper de instituição oficial (registros administrativos de graduados)
- Link: https://www.census.gov/library/working-papers/2026/adrm/CES-WP-26-56.html
- Método e amostra: registros administrativos de graduados universitários, comparando cursos (majors) por exposição a IA desde a disponibilidade dos LLMs; estimativas ajustadas por regressão (Abstract).
- Números-chave (Abstract): "the most AI-exposed decile of college majors saw their likelihood of initial employment decline by five percentage points, while full-quarter initial earnings declined by thirteen percent"; "This earnings decline is comparable in magnitude to the earnings losses associated with graduating into a large recession"; "Roughly half of the decline in earnings is attributable to lower earnings within the industry sectors that employ these graduates, with the remainder resulting from a shift in the industry mix into lower-wage sectors such as restaurants and retail"; "The effects attenuate as graduates move further from labor market entry but remain substantial for the most exposed majors".
- Limitações declaradas: não lidas (apenas abstract acessível; PDF em www2.census.gov bloqueado) [NÃO VERIFICADO].
- Status: Verificado na fonte original apenas no nível do abstract.

## 12. The Microstructure of AI Diffusion: Evidence from Firms, Business Functions, and Worker Tasks
- Autores/veículo: Kathryn Bonney, Cory Breaux, Emin Dinlersoz, Lucia Foster, John Haltiwanger, Aditya Pande | U.S. Census Bureau, CES Working Paper CES-26-25 | abr/2026 | Tipo: working paper de instituição oficial (survey nacionalmente representativo)
- Link: https://www.census.gov/library/working-papers/2026/adrm/CES-WP-26-25.html
- Método e amostra: suplemento de IA de 2026 do Business Trends and Outlook Survey (BTOS) do Census, referência nov/2025 a jan/2026; três camadas (uso pela firma, funções de negócio, tarefas dos trabalhadores); regressões (Abstract).
- Números-chave (Abstract): "18% of firms used AI in a business function, rising to 32% on an employment-weighted basis"; "Most users (66%) rely on AI solely to augment tasks, while AI-related employment decreases are rare, occurring in only 2% of firms"; "Employment declines tend to concentrate among large firms and firms that use AI to substitute for worker tasks"; "Functional breadth and operational investment are positively associated with employment decreases, whereas worker-task integration shows no significant link to headcount reduction"; 57% dos usuários integram IA em até 3 funções.
- Limitações declaradas: não lidas (apenas abstract acessível) [NÃO VERIFICADO]; o abstract registra correlação, não causalidade ("robust positive correlation").
- Status: Verificado na fonte original apenas no nível do abstract.

## 13. Youth employment amidst cooling labour demand (ECB Economic Bulletin, Issue 5/2026, Box)
- Autores/veículo: David Chaloupka, António Dias da Silva (ECB staff) | Banco Central Europeu, Economic Bulletin 5/2026 | 2026 (edição 5/2026) | Tipo: relatório de banco central com dados Eurostat/ECB
- Link: https://www.ecb.europa.eu/press/economic-bulletin/focus/2026/html/ecb.ebbox202605_04~faa9ef5955.en.html
- Método e amostra: dados trimestrais do Eurostat dessazonalizados (1T2008 a 1T2026); lei de Okun dinâmica relacionando crescimento do emprego (jovens e total) ao PIB/VAB real; Pesquisa de Expectativas do Consumidor do BCE de out/2025 (texto do box).
- Números-chave (texto do box): "The ratio of the youth unemployment rate to the total unemployment rate rose to 2.4 in the first quarter of 2026 from 2.1 in the first quarter of 2023"; taxa de desemprego jovem (15-24) 15,1% no 1T2026, "0.6 percentage points higher than its 2023 average"; desemprego total 6,3%; "employment among young workers declined by 18.6% in ICT, 5.3% in professional services and 3.1% in financial services" entre 1T2023 e 1T2026; "recent developments in youth employment are broadly in line with normal cyclical dynamics"; resíduos de Okun "particularly negative in the ICT segment".
- Limitações declaradas: "Existing evidence does not yet allow this pattern to be attributed to generative AI or remote work specifically"; a fraqueza "could in part be seen as a normal rebalancing" após criação de emprego incomum; o box cita estudos dos EUA "consistent with generative AI negatively affecting employment outcomes for young workers".
- Status: Verificado na fonte original (HTML; sem paginação).

## 14. Labor market impacts of AI: A new measure and early evidence
- Autores/veículo: Maxim Massenkoff, Peter McCrory (Anthropic, Economics) | publicação institucional/working paper no site da Anthropic | 5/mar/2026 | Tipo: relatório institucional com metodologia declarada (dados do CPS + dados de uso do Claude; autores são do fornecedor de IA)
- Link: https://www.anthropic.com/research/labor-market-impacts
- Método e amostra: medida de "observed exposure" que combina capacidade teórica de LLMs (Eloundou et al.) com uso real do Anthropic Economic Index, ponderando mais usos automatizados e relacionados a trabalho; ligação a respondentes do Current Population Survey (CPS); diferença-em-diferenças entre o quartil mais exposto e trabalhadores sem exposição; análise de taxa de "job finding" de jovens de 22-25 anos usando a dimensão de painel do CPS (seção "Initial results").
- Números-chave (Key findings e "Initial results"): "We find no systematic increase in unemployment for highly exposed workers since late 2022, though we find suggestive evidence that hiring of younger workers has slowed in exposed occupations"; "The average change in the gap since the release of ChatGPT is small and insignificant"; aumentos diferenciais de desemprego "on the order of 1 percentage point would be detectable"; "Job finding rates at the less exposed occupations remain stable at 2% per month, while entry into the most exposed jobs decreases by about half a percentage point. The averaged estimate in the post-ChatGPT era is a 14% drop in the job finding rate compared to that in 2022 in the exposed occupations, although this is just barely statistically significant. (There is no such decrease for workers older than 25.)"; "Occupations with higher observed exposure are projected by the BLS to grow less through 2034"; "We find that the unemployment rate for young workers in the exposed occupations is flat"; programadores, atendentes de suporte e analistas financeiros estão entre os mais expostos.
- Limitações declaradas: "there are several alternative interpretations. The young workers who are not hired may be remaining at their existing jobs, taking different jobs, or returning to school. A further data-related caveat is that job transitions may be more vulnerable to mismeasurement in surveys"; "Our work is a first step toward cataloging the impact of AI on the labor market" (Discussion).
- Status: Verificado na fonte original (HTML).

## 15. The Cybernetic Teammate: A Field Experiment on Generative AI Reshaping Teamwork and Expertise
- Autores/veículo: Fabrizio Dell'Acqua, Charles Ayoubi, Hila Lifshitz, Raffaella Sadun, Ethan Mollick, Lilach Mollick, Yi Han, Jeff Goldman, Hari Nair, Stewart Taub, Karim Lakhani | NBER Working Paper 33641 | abr/2025 | Tipo: working paper NBER, experimento de campo randomizado e pré-registrado (complementação)
- Link: https://www.nber.org/papers/w33641 | DOI: https://doi.org/10.3386/w33641 | PDF: https://www.nber.org/system/files/working_papers/w33641/w33641.pdf
- Método e amostra: "pre-registered field experiment with 776 professionals at Procter & Gamble"; atribuição aleatória a trabalhar com ou sem IA e individualmente ou em dupla (P&D + comercial) em desafios reais de inovação de produto (Abstract, p. 2).
- Números-chave: Abstract (p. 2): "individuals with AI matched the performance of teams without AI"; "Professionals using AI produced balanced solutions, regardless of their professional background". p. 14 e 20: indivíduos com IA "0.37 standard deviation increase (p < 0.01)", times com IA "0.39 standard deviation"; times sem IA com ganho "modestly better" de "0.24 standard deviation" sobre indivíduos sem IA; desempenho de times com IA "not significantly different from that of individuals using AI" (p. 20). A Tabela (p. 42) traz Individual + AI 0,373 e Team + AI 0,392.
- Limitações declaradas (p. 20): participantes "relatively inexperienced with AI prompting techniques" (benefício possivelmente "lower bound"); ferramentas "not optimized for collaborative work"; "our experiment relied on one-day virtual collaborations that did not fully capture the day-to-day complexities of team interactions in organizations"; foco em pares multifuncionais de humanos.
- Status: Verificado na fonte original.

## 16. Does AI Assistance Enhance or Erode Expertise? Evidence from a Three-Month Field Experiment in Patent Drafting
- Autores/veículo: David Autor, Tanya Rodchenko, Josh Martin, Zanna Iscenko, Scott Strand, David Pearl, Melissa Ferere | NBER Working Paper 35720 | set/2026 (revisão out/2026) | Tipo: working paper NBER, RCT pré-registrado (AEARCTR-0015823); estudo conduzido pelo Google
- Link: https://www.nber.org/papers/w35720 | DOI: https://doi.org/10.3386/w35720
- Método e amostra: "pre-registered three-month randomized controlled trial" com "133 practicing patent lawyers at eleven U.S. intellectual property law firms" com acesso a um assistente de IA personalizado para redação de patentes; trabalho avaliado por advogados de patentes especialistas às cegas; após 3 meses, todos revisaram (redline) um pedido de patente sem IA (Abstract, página NBER).
- Números-chave (Abstract): "AI access raised the quality of work delivered on benchmark patent drafting tasks at 10 days (0.34 SD, p = 0.03) and 90 days (0.38 SD, p = 0.01), with larger gains among junior lawyers"; na tarefa sem IA, "Treated lawyers outperformed controls by 0.32 SD (p = 0.04), but this advantage was concentrated entirely among senior lawyers (0.45 SD, p = 0.02). Junior lawyers showed no average gain"; escores dos juniores "bifurcated, with sharply fewer mediocre scores offset by more poor and more good ones"; "Foundational expertise may be a prerequisite for extracting durable skill from AI-assisted practice". (Os símbolos de valor-p no texto da página aparecem como "?"; os valores acima foram lidos como p na ordem do Abstract.)
- Limitações declaradas: "The study was conducted by Google" e vários autores são do Google (Disclosures); apoio de programas financiados por Google; limitações do corpo do artigo não lidas (PDF com acesso negado) [NÃO VERIFICADO].
- Status: Verificado na fonte original apenas no nível do abstract e das divulgações (página NBER).

## 17. AI and Coder Employment: Compiling the Evidence
- Autores/veículo: Leland D. Crane, Paul E. Soto (Board of Governors of the Federal Reserve System) | FEDS Working Paper 2026-018 | 20/mar/2026 | Tipo: working paper de banco central (dados CPS + O*NET)
- Link: https://www.federalreserve.gov/econres/feds/files/2026018pap.pdf
- Método e amostra: ligação O*NET-CPS para ocupações intensivas em programação ("coders", ~3,7% do emprego total em 2022 pelo limiar de 2,76 de importância de programação); event study em torno de nov/2022 com variável de controle de choques setoriais (p. 2, 11).
- Números-chave (Abstract, p. 1-2): "aggregate employment of coders has decelerated sharply since the introduction of ChatGPT"; "the deceleration is not attributable to the exposure of coders to slowing industries, suggesting instead that coders experienced an occupation-specific shock around the introduction of ChatGPT"; "Coder employment has continued to grow in recent years, though much more slowly than it did pre-2022"; p. 2: "annual coder employment growth is about 3 percent lower now than it was pre-ChatGPT"; p. 7: ocupações de computação e matemática "account for more than 1/3 of Claude queries, despite comprising only 3.4% of the workforce".
- Limitações declaradas (p. 2): "The interpretation of this estimate is subject to several caveats: among other issues, we are not controlling for AI's effects on aggregate" [demais caveats não transcritos]; nota 2: o lançamento de LLMs para código "is not a single event" (GPT-3.5 e Copilot existiam antes de nov/2022); opiniões dos autores, não do Federal Reserve.
- Status: Verificado na fonte original.

## 18. Designing Against Deskilling: Metacognitive Feedback Reduces Cognitive Offloading to LLM Assistants
- Autores/veículo: Sebastian Maier, Kai Schwabe, Manuel Schneider, Stefan Feuerriegel (LMU Munich / MCML) | arXiv:2609.20143 (v1, 17/set/2026) | Tipo: preprint, experimento online pré-registrado (inclui resultado nulo para o efeito da IA sozinha)
- Link: https://arxiv.org/abs/2609.20143 (PDF: https://arxiv.org/pdf/2609.20143)
- Método e amostra: experimento pré-registrado N = 704 (Prolific, residentes no Reino Unido), desenho 2x2 mais controle sem IA; prática de aritmética de frações com assistente LLM que só dá soluções sob pedido, seguida de teste sem IA (Abstract, p. 1; p. 13).
- Números-chave: p. 14 (H1): desempenho no teste sem IA "higher in the control condition (M = 0.65, SD = 0.32) than in the AI-only condition (M = 0.62, SD = 0.34). However, AI-only participants did not have significantly lower odds of answering a final test item correctly (b = -0.22, SE = 0.32, OR = 0.80, 95% CI [0.42, 1.51], p = .244)"; p. 15 (H2): feedback metacognitivo reduziu o offloading ("OR = 0.47, 95% CI [0.22, 1.00], p = .026") e aumentou a chance de acerto no teste sem IA ("OR = 1.51, 95% CI [0.98, 2.33], p = .030"); a recompensa por esforço "changed neither outcome" (Fig. 1).
- Limitações declaradas (§6.5, p. 21): desempenho sem IA medido "immediately after a brief practice session"; "it remains unclear whether these effects translate into durable skill acquisition"; necessários estudos longitudinais; a recompensa usou pontos simbólicos.
- Status: Verificado na fonte original.

## 19. Generative AI and the Reorganization of Labor Demand
- Autores/veículo: Fangyan Wang, Zaiyan Wei, Yang Wang (Purdue University) | arXiv:2605.23159 (v1, 22/mai/2026) | Tipo: preprint (dados de vagas)
- Link: https://arxiv.org/abs/2605.23159 (PDF: https://arxiv.org/pdf/2605.23159)
- Método e amostra: dados da Lightcast com todas as vagas online dos EUA, jan/2021 a jun/2025 ("more than 188 million postings", p. 3); medida dinâmica de exposição a IA generativa por vaga via pipeline de LLM em dois estágios; decomposição em realocação de demanda entre vagas e redesenho de tarefas dentro das vagas; decomposição Oaxaca-Blinder.
- Números-chave (Abstract, p. 1): "Hiring reallocation explains the largest share of the aggregate decline in exposure, accounting for 52% on average, while within-job redesign becomes increasingly important, accounting for 39.5%"; "shifts in occupational composition account for about 90% of the exposure change attributable to observable job characteristics"; "Senior jobs adjust earlier and mainly through reallocation, whereas junior jobs adjust through a broader mix of reallocation, redesign, and their interaction".
- Limitações declaradas (p. 44): "Job postings capture employers' stated demand at the point of hiring, but they do not directly measure realized work inside firms or the experiences of incumbent workers"; medidas por ocupação "may miss within-occupation task redesign".
- Status: Verificado na fonte original.

## 20. AI and jobs. A review of theory, estimates, and evidence
- Autores/veículo: R. Maria del Rio-Chanona, Ekkehard Ernst, Rossana Merola, Daniel Samaan, Ole Teutloff (UCL, ILO, Oxford Internet Institute, Copenhagen) | arXiv:2509.15265 (v1, 18/set/2025; pre-print de 22/set/2025) | Tipo: revisão sistemática/pre-print (inclui RCTs, experimentos de campo, dados de traço digital, pesquisas e vagas)
- Link: https://arxiv.org/abs/2509.15265 (PDF: https://arxiv.org/pdf/2509.15265)
- Método e amostra: revisão em três níveis (teoria; comparação quantitativa de medidas de exposição ex-ante; evidência ex-post de RCTs, experimentos de campo, dados de plataformas e repositórios), com classificação de tarefas simples vs. complexas por quatro dimensões (Abstract, p. 1).
- Números-chave (Abstract): "productivity gains are sizable but context-dependent—on the order of ∼20–60% in controlled RCTs, and 15-30% in field experiments"; "Novice workers tend to benefit more from LLMs in simple tasks. Across complex tasks, evidence is mixed on whether low or high-skilled workers benefit more"; "Digital trace data show substitution between humans and machines in writing/translation alongside rising demand for AI, with mild evidence of declining demand for novice workers. A more substantial decrease in demand for novice jobs across AI complementary work emerges from recent studies using surveys, platform payment records, or administrative data".
- Limitações declaradas (Abstract): "Research gaps include the focus on simple tasks in experiments, the limited diversity of LLMs studied, and technology-centric AI exposure measures that overlook adoption dynamics"; nota de que são visões dos autores, não da OIT.
- Status: Verificado na fonte original (abstract e primeira página; corpo não lido integralmente).

## 21. Still Waters, Rapid Currents: Early Labor Market Transformation under Generative AI (antes "Large Language Models, Small Labor Market Effects")
- Autores/veículo: Anders Humlum, Emilie Vestergaard | NBER Working Paper 33777 | mai/2025 (revisão mar/2026) | Tipo: working paper NBER, dados administrativos + surveys (Dinamarca); resultado nulo
- Link: https://www.nber.org/papers/w33777 | DOI: https://doi.org/10.3386/w33777 (leitura detalhada do PDF já registrada no arquivo do Tema 1; aqui, conferência do abstract da página NBER na versão de mar/2026)
- Método e amostra: surveys de adoção de chatbots ligados a registros administrativos da Dinamarca; diferença-em-diferenças (Abstract).
- Números-chave (Abstract, página NBER): "most employers in exposed occupations have adopted chatbot initiatives, workers report productivity benefits, and new AI-related tasks are widespread. Yet these currents have not broken the surface: using difference-in-differences, we estimate precise null effects on earnings and recorded hours at both the worker and workplace levels, ruling out effects larger than 2% two years after the launch of ChatGPT"; "employers absorb AI through task reorganization—including new tasks in content generation, AI oversight, and AI integration—and adopters transition into higher-paying occupations where AI chatbots are more relevant, though still too few to move average earnings"; "Technological change reshapes work well before it surfaces in earnings or hours".
- Limitações declaradas: ver registro do Tema 1 (PDF p. 36: ausência de efeito mensurável "is not evidence that nothing is happening").
- Status: Verificado na fonte original (abstract na página NBER nesta busca; PDF no Tema 1).

## 22. Shifting Work Patterns with Generative AI
- Autores/veículo: Eleanor W. Dillon, Sonia Jaffe, Nicole Immorlica, Christopher T. Stanton | NBER Working Paper 33795 | mai/2025 (revisão nov/2025) | Tipo: working paper NBER, experimento de campo randomizado (autores parcialmente da Microsoft; resultado nulo para composição de tarefas)
- Link: https://www.nber.org/papers/w33795 | DOI: https://doi.org/10.3386/w33795
- Método e amostra: experimento de campo em "66 firms and 7,137 knowledge workers", com acesso aleatório a uma ferramenta de IA generativa integrada a e-mail, reuniões e escrita, ao longo de 6 meses (Abstract).
- Números-chave (Abstract): "the 80% of treated workers who used this tool spent two fewer hours on email each week and reduced their time working outside of regular hours. Apart from these individual time savings, we do not detect shifts in the quantity or composition of workers' tasks resulting from individual-level AI provision".
- Limitações declaradas: divulgação de que "Some authors were employed by Microsoft, the maker of M365 Copilot, at the time of the study. Microsoft reviewed this paper for privacy concerns, but authors had full discretion over the results"; corpo do artigo (PDF) não aberto [NÃO VERIFICADO].
- Status: Verificado na fonte original apenas no nível do abstract e divulgações (página NBER).

## 23. Regulation (EU) 2024/1689 (AI Act): Art. 4 (AI literacy), Annex III ponto 4 (emprego) e Art. 26(7) (informação a trabalhadores)
- Autores/veículo: Parlamento Europeu e Conselho da UE | Regulamento (UE) 2024/1689, de 13/jun/2024 | Tipo: ato regulatório
- Link: https://eur-lex.europa.eu/legal-content/EN/TXT/HTML/?uri=OJ:L_202401689 (EUR-Lex)
- Fatos (texto consolidado do regulamento): Art. 4 (redação original): "Providers and deployers of AI systems shall take measures to ensure, to their best extent, a sufficient level of AI literacy of their staff and other persons dealing with the operation and use of AI systems on their behalf"; Art. 113: "Chapters I and II shall apply from 2 February 2025" (o Art. 4 integra o Capítulo I); Anexo III, ponto 4 (sistemas de alto risco em emprego): "AI systems intended to be used for the recruitment or selection of natural persons ... and to evaluate candidates" e "to make decisions affecting terms of work-related relationships, the promotion or termination of work-related contractual relationships, to allocate tasks based on individual behaviour ... or to monitor and evaluate the performance and behaviour of persons in such relationships"; Art. 26(7): "Before putting into service or using a high-risk AI system at the workplace, deployers who are employers shall inform workers' representatives and the affected workers that they will be subject to the use of the high-risk AI system". Aplicação geral prevista originalmente a partir de 2 ago/2026 (Art. 113; posteriormente alterada, ver item 24).
- Consequência: obrigação de alfabetização em IA para equipes aplicável desde 2 fev/2025; sistemas de alto risco de emprego sujeitos às obrigações do Capítulo III (cronograma alterado pelo item 24).
- Limitações/observações: texto legal, sem métrica de efeito; a redação do Art. 4 foi substituída pelo Regulamento (UE) 2026/1744.
- Status: Verificado na fonte original (texto no EUR-Lex).

## 24. Regulation (EU) 2026/1744 (Digital Omnibus on AI): alteração do Art. 4 e adiamento das regras de alto risco
- Autores/veículo: Parlamento Europeu e Conselho da UE | Regulamento (UE) 2026/1744, de 8/jul/2026, publicado no Jornal Oficial em 24/jul/2026 | Tipo: ato regulatório
- Link: https://eur-lex.europa.eu/eli/reg/2026/1744/oj/eng
- Fatos (texto do regulamento): altera os Regulamentos (UE) 2024/1689, 2018/1139 e 2023/1230; novo Art. 4: "Providers and deployers of AI systems shall take measures to support the development of AI literacy of their staff and other persons dealing with the operation and use of AI systems on their behalf ... This obligation does not require providers or deployers to guarantee any specific level of AI literacy of any individual"; considerando (8): a exigência anterior de nível "sufficient" criaria "an additional compliance burden, particularly for smaller enterprises"; nova data de aplicação das Seções 1-3 do Capítulo III: "2 December 2027 as regards AI systems classified as high-risk pursuant to Article 6(2) and Annex III" (inclui emprego) e "2 August 2028" para sistemas do Art. 6(1)/Anexo I, em vez de 2 ago/2026 (considerando e Art. 113 alterado).
- Consequência: a obrigação de AI literacy passa de "ensure a sufficient level" para "support the development"; sistemas de alto risco do Anexo III (incluindo emprego e gestão de trabalhadores) têm obrigações adiadas para 2/dez/2027.
- Limitações/observações: texto legal; entrada em vigor no terceiro dia após a publicação (Art. 4 do regulamento).
- Status: Verificado na fonte original (texto no EUR-Lex).

## 25. Remote Labor Index: Measuring AI Automation of Remote Work
- Autores/veículo: Mantas Mazeika, Alice Gatti, Cristina Menghini, Udari Madhushani Sehwag, Shivam Singhal, Yury Orlovskiy et al.; Dan Hendrycks (Center for AI Safety e Scale AI) | arXiv:2510.26787 (v1, 30/out/2025) | Tipo: preprint, benchmark de agentes de IA em projetos reais de freelancers (resultado de baixa automação)
- Link: https://arxiv.org/abs/2510.26787 (PDF: https://arxiv.org/pdf/2510.26787) | DOI: https://doi.org/10.48550/arXiv.2510.26787
- Método e amostra: 240 projetos obtidos de profissionais em plataformas freelance, 23 categorias de trabalho (taxonomia Upwork), "over 6,000 hours of real work valued at over $140,000"; avaliação manual dos entregáveis dos agentes contra o padrão humano (§3, p. 4-5).
- Números-chave: Abstract (p. 1): "AI agents perform near the floor on RLI, with the highest-performing agent achieving an automation rate of 2.5%"; p. 2: agentes "failing to complete most projects at a level that would be accepted as commissioned work in a realistic freelancing environment"; Fig. 2 (p. 3): agentes testados (Manus, Grok 4, Sonnet 4.5, GPT-5, ChatGPT agent, Gemini 2.5 Pro) "automate at most 2.5% of tasks". Os resultados de modelos mais novos (taxa acima de 2,5%) constam apenas em página de leaderboard/matérias de terceiros, não conferidos aqui [NÃO VERIFICADO].
- Limitações declaradas (p. 12): RLI "excludes some types of work found commonly in the remote labor economy, including projects requiring interaction with the client (e.g. tutoring), jobs that require working on a team (e.g., project management)"; benchmark "does not fully represent every part of the remote labor economy".
- Status: Verificado na fonte original (v1).

## 26. Working with AI: Measuring the Applicability of Generative AI to Occupations (v7)
- Autores/veículo: Kiran Tomlinson, Sonia Jaffe, Will Wang, Scott Counts, Siddharth Suri (Microsoft Research) | arXiv:2507.07935 (v1 jul/2025; v7 em 23/out/2026) | Tipo: preprint com dados de uso (200 mil conversas)
- Link: https://arxiv.org/abs/2507.07935 (PDF: https://arxiv.org/pdf/2507.07935) | DOI: https://doi.org/10.48550/arXiv.2507.07935
- Método e amostra: "200k anonymized conversations with Microsoft Bing Copilot" (dados de 2024, 9 meses); pipeline com LLM que classifica atividades de trabalho O*NET assistidas ou executadas pela IA; pontuação de "AI applicability" por ocupação (Abstract, p. 1).
- Números-chave: Abstract: atividades mais comuns e bem-sucedidas "involve information work—the creation, processing, and communication of information"; "widespread AI applicability cutting across sectors"; "an increase in occupation-level AI applicability over our 9-month data period". p. 2 e 9: correlação ponderada por emprego de "r = 0.73" com as previsões de Eloundou et al.; "only a weak correlation" entre applicability e salário ("employment-weighted r = 0.13", p. 9).
- Limitações declaradas (p. 10): "our data on AI usage are from 2024; models have improved dramatically since then"; as métricas "do not capture the productivity impact on people doing that IWA"; dados cobrem "only one slice of the AI market"; "AI's effects on employment and wages will depend on hard-to-predict business decisions as well as the emergence of new types of work"; evidência inicial de mercado de trabalho "mixed".
- Status: Verificado na fonte original.

## 27. Future of Work with AI Agents: Auditing Automation and Augmentation Potential across the U.S. Workforce
- Autores/veículo: Yijia Shao, Humishka Zope, Yucheng Jiang, Jiaxin Pei, David Nguyen, Erik Brynjolfsson, Diyi Yang (Stanford University) | arXiv:2506.06576 (v3, 1/fev/2026) | Tipo: preprint, survey/auditoria (preferências de trabalhadores e avaliação de especialistas)
- Link: https://arxiv.org/abs/2506.06576 (PDF: https://arxiv.org/pdf/2506.06576) | DOI: https://doi.org/10.48550/arXiv.2506.06576
- Método e amostra: banco WORKBank com respostas de "1,500 workers across 104 occupations" e anotações de 52 especialistas em IA, cobrindo 844 tarefas; dados coletados de jan a mai/2025; Human Agency Scale (HAS); entrevistas curtas com áudio (Abstract e §1, p. 2).
- Números-chave (p. 2, 9, 11): "For 46.1% of tasks, workers express positive attitudes toward AI agent automation, even after reflecting on potential job loss concerns and work enjoyment"; "41.0% of Y Combinator company-task mappings are concentrated in the Low Priority Zone and Automation 'Red Light' Zone"; quatro zonas (Green Light, Red Light, R&D Opportunity, Low Priority); indicam "early signals" de deslocamento de competências de "information-focused skills to interpersonal ones" (Abstract).
- Limitações declaradas: as conclusões baseiam-se em preferências autorrelatadas e avaliações de especialistas, não em medidas de resultado de emprego; limitações detalhadas do corpo do artigo não transcritas [NÃO VERIFICADO].
- Status: Verificado na fonte original (abstract e seções iniciais).

## 28. The Iceberg Index: Measuring Skills-centered Exposure in the AI Economy (Project Iceberg)
- Autores/veículo: Ayush Chopra, Santanu Bhattacharya, DeAndrea Salvador, Ayan Paul, Teddy Wright, Aditi Garg, Feroz Ahmad, Alice C. Schwarze, Ramesh Raskar, Prasanna Balaprakash (MIT, Oak Ridge National Laboratory e outros) | arXiv:2510.25137 (v2, 26/nov/2025) | Tipo: preprint, simulação (Large Population Models)
- Link: https://arxiv.org/abs/2510.25137 (PDF: https://arxiv.org/pdf/2510.25137) | DOI: https://doi.org/10.48550/arXiv.2510.25137
- Método e amostra: simulação com "151 million workers as autonomous agents executing over 32,000 skills across 3,000 counties" e milhares de ferramentas de IA; índice = valor salarial das habilidades que sistemas de IA podem executar em cada ocupação (Abstract, p. 1).
- Números-chave (Abstract, p. 1): adoção visível de IA em computação e tecnologia "(2.2% of wage value, approximately $211 billion)"; exposição técnica em automação cognitiva de funções administrativas, financeiras e profissionais "(11.7%, approximately $1.2 trillion)"; indicadores tradicionais (PIB, renda, desemprego) "explain less than 5% of this skills-based variation".
- Limitações declaradas (§6, p. 14; p. 6): "The Iceberg Index captures technical exposure—where AI capabilities overlap with occupational skills—not actual displacement or labor market outcomes"; "The Index does not predict job losses, adoption timelines, or net employment effects".
- Status: Verificado na fonte original.

## 29. The (Short-Term) Effects of Large Language Models on Unemployment and Earnings
- Autores/veículo: Danqing Chen, Carina Kane, Austin Kozlowski, Nadav Kuniesvky, James A. Evans (University of Chicago, Knowledge Lab) | arXiv:2509.15510 (v1, 19/set/2025) | Tipo: preprint, Synthetic Difference-in-Differences com CPS (resultado: ganhos salariais sem mudança no desemprego)
- Link: https://arxiv.org/abs/2509.15510 (PDF: https://arxiv.org/pdf/2509.15510) | DOI: https://doi.org/10.48550/arXiv.2509.15510
- Método e amostra: dados mensais do CPS (IPUMS) de jan/2010 a ago/2025 por ocupação; exposição a LLMs a partir de Handa et al. [2025] (Anthropic Economic Index); tratamento definido pela mediana de exposição; Synthetic DiD (p. 4-8, 10).
- Números-chave: Abstract (p. 1): "workers in highly exposed occupations experienced earnings increases following ChatGPT's introduction, while unemployment rates remained unchanged"; "initial labor market adjustments to LLMs operate primarily through wages rather than worker reallocation". p. 10: nos dois anos antes do ChatGPT, desemprego médio de "4.1% for treated occupations compared to 5.8% for controls". Conclusão: "we find no systematic changes in unemployment".
- Limitações declaradas: conclusão sugere padrão consistente com oferta de trabalho pouco elástica; o artigo não apresenta seção separada de limitações nas páginas lidas [NÃO VERIFICADO quanto a limitações formais]; uso de médias não ponderadas por ocupação no CPS (p. 5).
- Status: Verificado na fonte original.

## 30. Payrolls to Prompts: Firm-Level Evidence on the Substitution of Labor for AI
- Autores/veículo: Ryan Stevens (Ramp, Applied Sciences) | arXiv:2602.00139 (v1, 28/jan/2026) | Tipo: preprint com dados de gastos de empresas (autor é de empresa que fornece os dados; evidência de substituição)
- Link: https://arxiv.org/abs/2602.00139 (PDF: https://arxiv.org/pdf/2602.00139) | DOI: https://doi.org/10.48550/arXiv.2602.00139
- Método e amostra: dados da plataforma Ramp (cartões corporativos e faturas) de "thousands of companies", gastos em marketplaces de trabalho online e em provedores de modelos de IA de 2021 a 2025 (p. 2, 4).
- Números-chave (Introdução, p. 2): "We find that firms are replacing labor with AI"; "businesses that spent higher shares of their total spend on online marketplaces were more likely to substitute labor for AI"; "businesses most exposed to AI shocks substitute labor for AI at a rate of $1 for $0.03 in AI spending. This implies a 20 to 25x cost savings from AI adoption".
- Limitações declaradas (p. 2): "While we find that firms are substituting labor for AI, this does not imply that in aggregate, labor will be replaced by AI"; "What we see in this paper are micro-level substitution patterns not aggregate labor market outcomes"; foco em trabalho contratado em marketplaces online (setor "most impacted by AI").
- Status: Verificado na fonte original (introdução e seção de dados).

## 31. How (un)Stable Are LLM Occupational Exposure Scores? Evidence from Multi-Model Replication
- Autores/veículo: Michelle Yin, Hoa Vu, Claudia Persico | NBER Working Paper 35110 | abr/2026 | Tipo: working paper NBER (replicação metodológica; crítica de medidas usadas em estudos de emprego)
- Link: https://www.nber.org/papers/w35110 | DOI: https://doi.org/10.3386/w35110
- Método e amostra: replicação da rubrica dominante de exposição ocupacional com três modelos de fronteira nas mesmas tarefas; diferença-em-diferenças com anotadores distintos (Abstract).
- Números-chave (Abstract): "a 3.6-fold divergence in mean exposure with agreement as low as 57%"; "individual-level coefficient magnitudes vary 2.4-fold across annotators, and county level estimates flip from a significant negative to an insignificant positive depending on annotators".
- Limitações declaradas: não lidas (apenas abstract; PDF com acesso negado) [NÃO VERIFICADO]; o abstract formaliza o erro de medida "non-classical".
- Status: Verificado na fonte original apenas no nível do abstract (página NBER).

## 32. Generative AI in Action: Field Experimental Evidence from Alibaba's Customer Service Operations
- Autores/veículo: Xiao Ni, Yiwei Wang, Tianjun Feng, Lauren Xiaoyuan Lu, Yitong Wang, Congyi Zhou (Fudan, Zhejiang, Dartmouth Tuck, Alibaba Group) | arXiv:2603.29888 (mar/2026) | Tipo: preprint, experimento de campo randomizado (complementação; efeito negativo para os melhores agentes; efeito nulo em qualidade objetiva)
- Link: https://arxiv.org/abs/2603.29888 (PDF: https://arxiv.org/pdf/2603.29888) | DOI: https://doi.org/10.48550/arXiv.2603.29888
- Método e amostra: teste A/B randomizado de 4 semanas (23/jan a 19/fev/2024) com "5,940 new customer service agents with tenure of less than one year", ~2,56 milhões de chats e ~0,39 milhão de avaliações de clientes; o assistente gera diagnóstico e proposta de solução na abertura do chat; agentes podem adotar, modificar ou ignorar (§3.4, p. 9).
- Números-chave (Abstract, p. 1): "On average, gen AI improves service speed and subjective service quality, measured by customer ratings, but has no significant effect on objective service quality, measured by customer retrials"; "Lower-performing agents benefit the most, indicating that gen AI can narrow performance gaps. Top-performing agents experience declines in both subjective and objective service quality"; para os melhores agentes, o uso de IA "increases shift-away time, response delays, and immediate customer retrials".
- Limitações declaradas (§ final, p. 26): "because agents choose when and how to use the assistant, our study cannot identify the optimal level of AI usage"; a evidência de mecanismo é baseada em medidas de processo e "should be interpreted as consistent with workflow disruption, rather than as definitive proof of a single causal channel". Um dos autores é da Alibaba Group (empresa parceira).
- Status: Verificado na fonte original.

## 33. Agentic AI and Human-in-the-Loop Interventions: Field Experimental Evidence from Alibaba's Customer Service Operations
- Autores/veículo: Yiwei Wang, Chuan Zhu, Tianjun Feng, Lauren Xiaoyuan Lu, Bingxin Jia | arXiv:2605.14830 (mai/2026) | Tipo: preprint, experimento de campo randomizado (trabalhadores supervisionando agente de IA)
- Link: https://arxiv.org/abs/2605.14830 (PDF: https://arxiv.org/pdf/2605.14830) | DOI: https://doi.org/10.48550/arXiv.2605.14830
- Método e amostra: experimento randomizado em ago/2024 na plataforma Taobao com "647 customer service workers and 680,676 service chats"; tratamento: trabalhadores supervisionam um sistema de IA agêntica que resolve chats "AI-eligible" (menos de 10% do volume de chats) e continuam atendendo os demais (p. 2, 7).
- Números-chave (Abstract, p. 1): "AI deployment reduces average chat duration and has limited effects on retrial rates, but substantially lowers ratings for AI-eligible chats"; intervenção humana "preserves service quality in algorithm-triggered technical escalations" mas é "less effective in algorithm-triggered emotional escalations"; "positive spillover effect on AI-ineligible chats".
- Limitações declaradas (p. 2): a tecnologia "remains immature in important respects. In particular, agentic AI still faces limitations in adaptability and contextual judgment"; seção de limitações do estudo não transcrita [NÃO VERIFICADO].
- Status: Verificado na fonte original (abstract e introdução).

## 34. Selective Prediction Reduces the Negative Effects of Automation Bias Overall but Increases False Negatives
- Autores/veículo: Sarah Jabbour, David Fouhey, Nikola Banovic, Stephanie D. Shepard, Ella Kazerooni, Michael W. Sjoding, Jenna Wiens (University of Michigan, NYU) | arXiv:2508.07617 (v2, 11/ago/2026) | Tipo: preprint, estudo randomizado com vinhetas clínicas (dependência/viés de automação)
- Link: https://arxiv.org/abs/2508.07617 (PDF: https://arxiv.org/pdf/2508.07617) | DOI: https://doi.org/10.48550/arXiv.2508.07617
- Método e amostra: estudo baseado em vinhetas com 259 clínicos (médicos e profissionais de prática avançada) tratando pacientes hospitalizados; comparação entre desempenho sem IA, com IA e com predição seletiva (Abstract; §4, p. 6).
- Números-chave: p. 6: acurácia de tratamento "In Clinician Alone ... 62% (95% CI: [47-75])"; "In Clinician + AI, treatment accuracy dropped significantly relative to Clinician Alone (50% [36-65] vs. 62% [47-75]; p-value < 0.001), suggesting overreliance on inaccurate predictions"; falsos positivos subiram de "40% (18-67) to 55% (28-79)" com IA; Abstract: com predição seletiva "clinicians' false negative rate is significantly elevated (i.e., they undertreat patients), particularly those who have not previously used AI in their clinical practice".
- Limitações declaradas (p. 9): ambiente de vinhetas online "differs from real clinical environments"; "AI experience was correlated with clinician demographics in our sample" (mais homens, mais velhos, médicos em vez de APPs), de modo que o efeito da experiência com IA pode refletir fatores correlacionados.
- Status: Verificado na fonte original.

## 35. How employment is changing at Anthropic
- Autores/veículo: Nathan Wilmers, Regina Catipon, Maxim Massenkoff, Peter McCrory (Anthropic, The Anthropic Institute / Economics) | 16/out/2026 | Tipo: caso real documentado com dados internos de empresa (fornecedor de IA; relato institucional, sem revisão externa)
- Link: https://www.anthropic.com/research/employment-at-anthropic
- Fatos e método: dados internos de emprego, uso de IA, métricas de produção, pesquisas com funcionários, padrões de comunicação, agendas e registros de decisões de contratação, mais 17 entrevistas com funcionários (Introdução).
- Números-chave (seções Key findings, "What jobs are missing?"): "the share of junior-level employees in technical departments at Anthropic slipped from 21% to 14% since early 2025. The proportion of junior technical hires fell even faster, from 27% to 9%"; "the overall employment share of technical departments within Anthropic has fallen, from 61% to 56% in the last year"; "By August interactive AI agent hours outnumbered employees' six to one"; "By April, engineering and research teams had deemphasized hiring for lower band technical positions"; "Around a third of ML and a fifth of SWE managers reported hiring less due to AI"; "employees working at the company for at least a year were 50% more likely to move across departments each month in 2026 than they were in 2025"; receita por empregado "2-4 times as much revenue per employee as Meta and Google as they crested in their own rapid growth".
- Consequência concreta: desaceleração relativa da contratação de juniores técnicos; criação de "early warning system to track jobs at risk of disruption" e priorização de realocações internas.
- Limitações declaradas: "Part of this shift is the natural expansion of business functions as the company scales. Part could reflect coding tools increasingly allowing non-technical employees to make software themselves"; empresa única no "frontier" de adoção; não localizei seção formal de limitações no HTML.
- Status: Verificado na fonte original (HTML).

## 36. Research on AI and the labor market is still in the first inning
- Autores/veículo: Jed Kolko (The Hamilton Project, Brookings Institution) | 10/mar/2026 | Tipo: análise institucional que revisa estudos (síntese secundária; inclui resultados contrários ao discurso dominante)
- Link: https://www.brookings.edu/articles/research-on-ai-and-the-labor-market-is-still-in-the-first-inning
- Método: revisão de pesquisas recentes que combinam medidas de exposição/uso de IA com dados de emprego (Brynjolfsson, Chandar e Chen 2025; Eckhardt e Goldschlag 2025; Iscenko e Millet 2026; Frank et al. 2026; Gimbel et al. 2025).
- Pontos factuais (texto): "Brynjolfsson, Chandar, and Chen (2025) ... found employment fell more for young workers in occupations with higher AI exposure but not in occupations with lower AI exposure"; "Eckhardt and Goldschlag (2025) found that unemployment rose less for workers in occupations with higher AI exposure using publicly available jobs data from the Current Population Survey"; "Iscenko and Millet (2026) ... find that job postings declined more in AI-exposed occupations, but this trend began in 2022 prior to the public release of ChatGPT. They argue that the timing of the decline in job postings corresponds better to the macroeconomic shift of rising interest rates"; "Frank et al. (2026) found similar results"; "AI exposure and AI usage are different concepts, and many occupations rank differently on exposure than on usage".
- Limitações declaradas (as do próprio texto sobre a literatura): "the evidence on how AI is affecting the labor market today is inconclusive, and claims about harmful impacts on particular groups of workers are premature"; "any research findings based on current data ... are necessarily weak signals about the future"; riscos de "narrator's bias", de pesquisas que usam declarações das empresas ("A CEO can more proudly blame AI for a hiring freeze or layoff round than they can admit that they over-hired") e de "streetlamp bias".
- Status: Verificado na fonte original (HTML; os estudos citados não foram abertos por este item, ver itens correspondentes).

---

## Fontes localizadas mas não abertas na origem (dados vindos apenas de resultados de busca ou de citações em fontes verificadas acima)

## 37. Canaries in the Coal Mine? Six Facts about the Recent Employment Effects of Artificial Intelligence
- Autores/veículo: Erik Brynjolfsson, Bharat Chandar, Ruyu Chen | Stanford Digital Economy Lab, working paper | ago/2025; versões de nov/2025 e ago/2026 | Tipo: working paper com dados de folha de pagamento (ADP)
- Link: https://digitaleconomy.stanford.edu/publication/canaries-in-the-coal-mine/ (domínio bloqueado nesta sessão); PDF da versão de ago/2026 indicado em busca: https://digitaleconomy.stanford.edu/app/uploads/2026/08/Canaries_August2026.pdf
- Método e amostra: dados administrativos de folha do maior provedor de software de payroll dos EUA (ADP) [NÃO VERIFICADO na fonte].
- Números-chave: versão original: "13 percent relative decline in employment" para trabalhadores de 22-25 anos em ocupações mais expostas, controlando choques por empresa [NÃO VERIFICADO na fonte]; versão ago/2026: emprego de jovens de 22-25 em ocupações expostas "19% below" o esperado, com efeito via menor contratação [NÃO VERIFICADO na fonte]. Conferido apenas por citação em fonte verificada: o AI Index 2026 (item 4, p. 51) cita Brynjolfsson et al. (2025) com "-15% to -16% employment for early-career workers", e o Anthropic (item 14) cita "6—16% fall".
- Limitações declaradas: descritas em resultados de busca como "early, descriptive indicators", não estimativas causais [NÃO VERIFICADO na fonte].
- Status: [NÃO VERIFICADO] (digitaleconomy.stanford.edu bloqueado).

## 38. Generative AI as Seniority-Biased Technological Change: Evidence from U.S. Résumé and Job Posting Data
- Autores/veículo: Seyed M. Hosseini Maasoum, Guy Lichtinger (Harvard) | SSRN 5425555 (2025); versão de mai/2026 indicada em busca | Tipo: working paper (currículos e vagas)
- Link: https://papers.ssrn.com/abstract=5425555 (SSRN retorna 403 nesta sessão)
- Método e amostra: conforme tabela do AI Index 2026 (item 4, p. 51), verificada: "62 million workers/285,000 US firms"; "AI substitutes for junior labor while leaving senior roles intact. Sharp decline in junior employment driven by slower hiring". Demais números vindos de busca: queda de junior employment de 7,7% em seis trimestres relativo a não adotantes [NÃO VERIFICADO na fonte]; identificação de adoção por vagas de "GenAI integrator" [NÃO VERIFICADO na fonte].
- Limitações declaradas: [NÃO VERIFICADO]
- Status: [NÃO VERIFICADO] (SSRN bloqueado; apenas descrição por fonte secundária verificada).

## 39. Is AI Contributing to Rising Unemployment? Evidence from Occupational Variation
- Autores/veículo: Serdar Ozkan, Nicholas Sullivan | Federal Reserve Bank of St. Louis, On the Economy blog | ago/2025 | Tipo: nota institucional de banco central (correlacional)
- Link: https://www.stlouisfed.org/on-the-economy/2025/aug/is-ai-contributing-unemployment-evidence-occupational-variation (domínio bloqueado)
- Método e amostra: correlação entre exposição a IA e aumento do desemprego por ocupação, 2022-2025 [NÃO VERIFICADO na fonte].
- Números-chave: correlação de 0,47 entre exposição teórica e aumento do desemprego [NÃO VERIFICADO na fonte]; ocupações de computação e matemática com ~80% de exposição e +1,2 p.p. de desemprego entre 2022 e 2025 [NÃO VERIFICADO na fonte]. Conferido apenas via AI Index 2026 (item 4, p. 51): "St. Louis Fed (2025) ... +1.1% to +1.3% labor productivity increase" por cálculos baseados em economia de tempo autorrelatada.
- Limitações declaradas: autores descrevem resultado como preliminar e não causal [NÃO VERIFICADO na fonte].
- Status: [NÃO VERIFICADO] (stlouisfed.org inacessível).

## 40. Endoscopist deskilling after exposure to artificial intelligence in colonoscopy: a multicenter observational study
- Autores/veículo: Krzysztof Budzyń et al. | The Lancet Gastroenterology & Hepatology, 10(10):896-903 | 2025 | Tipo: estudo observacional multicêntrico (deskilling clínico)
- Link: https://doi.org/10.1016/S2468-1253(25)00133-5 (thelancet.com/doi bloqueado nesta sessão)
- Método e amostra: análise retrospectiva em quatro centros de endoscopia do ensaio ACCEPT, IA introduzida no fim de 2021 [NÃO VERIFICADO na fonte].
- Números-chave: taxa de detecção de adenomas em colonoscopias sem IA caiu de 28,4% para 22,4% (queda absoluta de 6,0 p.p.; IC 95% -10,5 a -1,6; p=0,0089) [NÃO VERIFICADO na fonte].
- Limitações declaradas: observacional, não estabelece causalidade; efeito variou entre centros [NÃO VERIFICADO na fonte].
- Status: [NÃO VERIFICADO].

## 41. Generative AI without guardrails can harm learning: Evidence from high school mathematics
- Autores/veículo: Hamsa Bastani, Osbert Bastani, Alp Sungu, Haosen Ge, Özge Kabakcı, Rei Mariman | PNAS 122(26), e2422633122 | 2025 | Tipo: experimento de campo randomizado (aprendizagem/dependência)
- Link: https://doi.org/10.1073/pnas.2422633122 (pnas.org bloqueado); preprint: https://papers.ssrn.com/abstract=4895486 (403)
- Método e amostra: experimento de campo com cerca de 1.000 estudantes de ensino médio na Turquia, comparando tutor GPT Base e GPT Tutor com salvaguardas [NÃO VERIFICADO na fonte].
- Números-chave: estudantes com GPT Base tiveram desempenho 17% menor que quem nunca teve acesso, quando a IA foi removida [NÃO VERIFICADO na fonte]; salvaguardas do GPT Tutor mitigaram em grande parte o efeito [NÃO VERIFICADO na fonte].
- Limitações declaradas: [NÃO VERIFICADO]
- Status: [NÃO VERIFICADO]. (População estudantil, não trabalhadores.)

## 42. The Impact of Generative AI on Critical Thinking: Self-Reported Reductions in Cognitive Effort and Confidence Effects From a Survey of Knowledge Workers
- Autores/veículo: Hao-Ping (Hank) Lee, Advait Sarkar et al. (Microsoft Research e Carnegie Mellon) | CHI '25, ACM | 2025 | Tipo: survey correlacional
- Link: https://doi.org/10.1145/3706598.3713778 (dl.acm.org bloqueado); PDF do autor em advait.org (bloqueado)
- Método e amostra: survey de 319 trabalhadores do conhecimento (Prolific) com 936 casos de uso reais de IA [NÃO VERIFICADO na fonte].
- Números-chave: maior confiança na IA associada a menos pensamento crítico autorrelatado; maior autoconfiança associada a mais pensamento crítico [NÃO VERIFICADO na fonte].
- Limitações declaradas: desenho correlacional, sem medida de habilidade antes/depois e sem atribuição aleatória; autorrelato [NÃO VERIFICADO na fonte].
- Status: [NÃO VERIFICADO].

## 43. AI Tools in Society: Impacts on Cognitive Offloading and the Future of Critical Thinking
- Autores/veículo: Michael Gerlich (SBS Swiss Business School) | Societies 15(1):6 | 3/jan/2025 | Tipo: estudo misto (survey + entrevistas), correlacional
- Link: https://doi.org/10.3390/soc15010006 (mdpi.com bloqueado)
- Método e amostra: 666 participantes de várias idades e escolaridades; ANOVA, correlação e análise temática [NÃO VERIFICADO na fonte].
- Números-chave: correlação negativa significativa entre uso frequente de IA e pensamento crítico, mediada por cognitive offloading; participantes mais jovens com maior dependência [NÃO VERIFICADO na fonte].
- Limitações declaradas: achados correlacionais de um único estudo, sem causalidade [NÃO VERIFICADO na fonte].
- Status: [NÃO VERIFICADO].

## 44. Evaluating the Impact of AI on the Labor Market: Current State of Affairs
- Autores/veículo: Yale Budget Lab (com pesquisadores da Brookings; Gimbel et al.) | out/2025 | Tipo: relatório institucional com dados de ocupações (CPS)
- Link: https://budgetlab.yale.edu/research/evaluating-impact-ai-labor-market-current-state-affairs (domínio bloqueado)
- Método e amostra: índices de dissimilaridade ocupacional e dados de desemprego por exposição a IA, cerca de 33 meses após o ChatGPT [NÃO VERIFICADO na fonte].
- Números-chave: ausência de "discernible disruption" no mercado de trabalho amplo; pequeno aumento de dissimilaridade ocupacional entre graduados recentes e mais velhos [NÃO VERIFICADO na fonte]. Referência a Gimbel et al. (2025) confirmada em Brookings (item 36).
- Limitações declaradas: autores advertem cautela, com amostras pequenas [NÃO VERIFICADO na fonte].
- Status: [NÃO VERIFICADO].

## 45. Looking for the Ladder: Is AI Impacting Entry-Level Jobs? (e AI and Jobs: The Final Word (Until the Next One))
- Autores/veículo: Zanna Iscenko, Fabien Curto Millet (jan/2026); Sarah Eckhardt, Nathan Goldschlag (ago/2025) | Economic Innovation Group, working papers | Tipo: working papers com dados de vagas (Lightcast) e CPS
- Link: https://eig.org/wp-content/uploads/2026/01/TAWP-Iscenko-Millet.pdf e https://eig.org/wp-content/uploads/2025/08/EIG-AI-and-Jobs.pdf (eig.org bloqueado)
- Números-chave: conferido apenas via Brookings (item 36), verificado: vagas em ocupações expostas caíram desde 2022, antes do ChatGPT; Eckhardt e Goldschlag: "unemployment rose less for workers in occupations with higher AI exposure". Resultado de busca (não aberto): vagas de juniores e seniores em ocupações expostas caíram "roughly in parallel" desde o pico de primavera de 2022 [NÃO VERIFICADO na fonte].
- Limitações declaradas: [NÃO VERIFICADO]
- Status: [NÃO VERIFICADO] (documentos originais inacessíveis).

## 46. 2025 Year-End Challenger Report (demissões anunciadas atribuídas à IA)
- Autores/veículo: Challenger, Gray & Christmas | 8/jan/2026 | Tipo: relatório de consultoria com contagem de anúncios de demissões (metodologia por motivos declarados nos anúncios)
- Link: https://www.challengergray.com/?p=27592 (domínio bloqueado)
- Fatos: anúncios de corte de 1.206.374 empregos em 2025, dos quais 54.836 atribuídos à IA; 71.825 desde 2023 [NÃO VERIFICADO na fonte]; análise posterior com 112.713 cortes atribuídos à IA até jul/2026 [NÃO VERIFICADO na fonte].
- Limitações declaradas: [NÃO VERIFICADO]; observação de Brookings (item 36, verificada) de que incentivos levam empresas a "over-attribute" decisões à IA.
- Status: [NÃO VERIFICADO].

## 47. Klarna: reversão do modelo de atendimento centrado em IA (maio/2025)
- Autores/veículo: reportagens (ex.: tech.co) a partir de entrevista do CEO Sebastian Siemiatkowski | mai/2025 | Tipo: caso real documentado por imprensa
- Link: https://tech.co/news/klarna-reverses-ai-overhaul (domínio bloqueado)
- Fatos e consequência: a empresa voltou a contratar atendentes humanos após o CEO reconhecer qualidade inferior no atendimento totalmente por IA ("lower quality") [NÃO VERIFICADO na fonte]; mantém uso de IA [NÃO VERIFICADO na fonte].
- Limitações declaradas: [NÃO VERIFICADO]
- Status: [NÃO VERIFICADO] (fonte primária da empresa não localizada).

## 48. Commonwealth Bank of Australia: reversão de 45 demissões ligadas a bot de voz com IA (ago/2025)
- Autores/veículo: reportagens (ia.acs.org.au, American Banker, babl.ai) | ago/2025 | Tipo: caso real documentado por imprensa; disputa sindical e Fair Work Commission
- Link: https://ia.acs.org.au/article/2025/cba-reverses-ai-driven-job-cuts--admits--error-.html (domínio bloqueado)
- Fatos e consequência: o banco planejava substituir 45 funções de atendimento por bot de voz; sindicato levou a disputa à Fair Work Commission; o banco reverteu e admitiu "error" ao declarar as funções redundantes [NÃO VERIFICADO na fonte]. Data exata reportada de forma inconsistente entre fontes [NÃO VERIFICADO].
- Limitações declaradas: relato da reversão vem em boa parte do lado sindical [NÃO VERIFICADO na fonte].
- Status: [NÃO VERIFICADO].

## 49. Evidência europeia/nórdica e de outros países citada em buscas (não abertas)
- Fairlie e Wu, "The Early Impacts of AI on Employment among Recent College Graduates", IZA DP 18945 (set/2026), docs.iza.org bloqueado [NÃO VERIFICADO].
- Lodefalk, Löthman, Koch, Engberg, working paper com dados de empregadores suecos (Örebro University, WP 2/2026), oru.se bloqueado: menor contratação de jovens sem redução do total de empregos, segundo resumo de busca [NÃO VERIFICADO].
- Chandar e Klein Teeselink, "How Does AI Change Labor Demand? Evidence from 41 Countries" (set/2026), digitaleconomy.stanford.edu bloqueado [NÃO VERIFICADO].
- Lambert e Schindler, "The Broken Ladder: AI, Remote Work, and Early-Career Hiring" (set/2026): trabalho remoto explicaria a queda de contratação de iniciantes melhor que IA, segundo resumo de busca [NÃO VERIFICADO].
- Federal Reserve Bank of New York, Liberty Street Economics (2026): atribui parte majoritária do aumento do desemprego de graduados jovens ao trabalho remoto (64%, segundo cobertura) [NÃO VERIFICADO].
- Rodgers e Kassens, St. Louis Fed (jun/2026): cerca de um terço do aumento do desemprego de 18-24 anos atribuído à demanda por habilidades de IA, segundo cobertura [NÃO VERIFICADO].
- Status: [NÃO VERIFICADO] (todos).

---

## Buscas realizadas / lacunas

### Termos usados (WebSearch)
- "Canaries in the Coal Mine" Brynjolfsson Chandar Chen; seniority-biased technological change Lichtinger Hosseini; junior employment generative AI resume postings
- St. Louis Fed AI exposure unemployment; Yale Budget Lab evaluating impact of AI labor market; Brookings AI entry-level 2026; Federal Reserve FEDS notes generative AI young workers
- Budzyń deskilling colonoscopy; Bastani generative AI without guardrails; Microsoft Lee Sarkar critical thinking CHI 2025; Gerlich cognitive offloading; AI skill atrophy deskilling arXiv; clinician automation bias randomized
- Anthropic Economic Index (jan e mar/2026); Massenkoff McCrory labor market impacts; Anthropic "How employment is changing"
- Stanford AI Index 2026 economy chapter; BIS Aldasoro AI adoption European firms; ECB Economic Bulletin youth employment AI; IMF SDN "Bridging Skill Gaps"; Census CES working papers AI early career
- Yotzov Bloom "Firm Data on AI"; Humlum; Dell'Acqua Cybernetic Teammate; Tomlinson Working with AI; Remote Labor Index; Johnston Makridis; customer service novice field experiment; Challenger year-end 2025; Klarna e Commonwealth Bank reversões; EU AI Act Art. 4 / Digital Omnibus
- Buscas com filtro de domínio em federalreserve.gov, arxiv.org, nber.org

### Domínios bloqueados ou inacessíveis nesta sessão (a rede é restrita; nenhum bloqueio foi contornado)
- digitaleconomy.stanford.edu (Canaries; Chandar e Teeselink) e siepr.stanford.edu
- papers.ssrn.com (HTTP 403; Hosseini e Lichtinger, Bastani preprint, Johnston e Makridis)
- stlouisfed.org (páginas On the Economy / Open Vault), thelancet.com, pnas.org, doi.org para Elsevier/PNAS, dl.acm.org, mdpi.com, nature.com, science.org, sciencedirect.com, springer, wiley, tandfonline, jamanetwork, pubmed/ncbi/europepmc, crossref
- budgetlab.yale.edu, eig.org, advait.org, aaas.org, sd13.senate.ca.gov, wfhresearch.com, atlantafed.org, frbsf.org, newyorkfed.org, dallasfed.org, clevelandfed.org, chicagofed.org e demais Federal Reserve Banks
- www2.census.gov (PDFs dos working papers do Census; só as páginas de resumo em www.census.gov foram lidas)
- docs.iza.org, oru.se, promarket.org, hiringlab.org, openknowledge.worldbank.org, theregister.com
- challengergray.com, tech.co, ia.acs.org.au, americanbanker.com, babl.ai, klarna.com, commbank.com.au, fwc.gov.au, reuters, nytimes, ft, bloomberg, cnbc, guardian, bbc, apnews, wikipedia
- oecd.org (403), weforum.org (403), ilo.org, mckinsey.com, bankofengland.co.uk, dol.gov, congress.gov (403), courtlistener.com (403), law.justia.com, govinfo.gov, sec.gov, eeoc.gov, nyc.gov, ilga.gov, calcivilrights.ca.gov
- imf.org: página de publicação e PDF do SDN 2026/001 retornaram 403 ao acesso programático; só o resultado de busca foi visto
- NBER: abstracts em www.nber.org/papers/wNNNNN abriram; vários PDFs em www.nber.org/system/files retornaram 403 de forma intermitente (w34836, w35720, w35123, w35110); nber.org sem "www" bloqueado
- bis.org/publ/work1325.pdf devolveu a página de resumo em HTML (não o PDF completo)

### Não encontrado ou não verificado
- Textos completos: Canaries (todas as versões), Hosseini e Lichtinger, St. Louis Fed (Ozkan e Sullivan; Rodgers e Kassens), Yale Budget Lab, Iscenko e Millet, Eckhardt e Goldschlag, Budzyń (Lancet), Bastani (PNAS), Lee et al. (CHI), Gerlich (Societies), IMF SDN 2026/001, OECD Employment Outlook 2025, WEF Future of Jobs 2025, ILO exposure index.
- Casos com data e consequência (Klarna, CBA, Challenger, Salesforce, IBM, Duolingo, Amazon): sem fonte primária ou jornalística acessível; entradas 46 a 48 ficam sem verificação.
- Decisões judiciais: Mobley v. Workday e outras ações sobre IA em contratação não foram obtidas (courtlistener/justia/congress.gov bloqueados). Atos estaduais americanos (NYC Local Law 144, Illinois HB 3773, Colorado SB 24-205, regulamentos de IA em emprego da Califórnia) não foram abertos por bloqueio de domínio.
- Dados de plataformas de vagas (Indeed Hiring Lab, Lightcast, Revelio, LinkedIn Economic Graph) em original: inacessíveis; só estudos acadêmicos que usam esses dados foram lidos (itens 3, 5, 19).
- RCTs clínicos de deskilling: apenas o estudo observacional de Budzyń foi localizado (não aberto); ensaio com 1.222 participantes (arXiv, abr/2026) e RCT com 111 estudantes de medicina (2026) mencionados em busca, sem identificação confirmada [NÃO VERIFICADO].
- Estudos citados no AI Index 2026 (Brynjolfsson 2026 sobre produtividade dos EUA; Penn Wharton Budget Model; Filippucci et al. OECD 2025) não abertos nas fontes originais.
- Segunda edição do experimento da METR (item 2 do arquivo do Tema 1) e Humlum e Vestergaard (item 4 do Tema 1) estão cobertas naquele arquivo; aqui só o abstract do segundo foi reconferido (item 21).
