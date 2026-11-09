# Tema 2 — Adoção corporativa vs. retorno real: projetos de GenAI em produção, ROI mensurável e razões de fracasso

Data da busca: 09/nov/2026 (revisão de verificação feita no mesmo dia)

**Convenções.** `[VERIFICADO]` = fonte original aberta (HTML/PDF) nesta revisão; os números abaixo foram conferidos no texto aberto, com a página PDF ou seção indicada. `[NÃO VERIFICADO]` = fonte original não aberta; dados vêm de resumos do WebSearch/imprensa; o motivo vem uma vez no item. "p. PDF" = número da página no arquivo PDF, não necessariamente a numeração impressa.

**Método de acesso.** O WebFetch continuou sem resolver os domínios; a verificação foi feita com `curl` via Bash. Domínios abertos: arxiv.org, nber.org (páginas e PDFs, exceto PDFs de w34836/w35141/w34984 com 403), census.gov, hai.stanford.edu, stlouisfed.org (blog), federalreserve.gov, bis.org, kpmg.com (alguns países), digital-strategy.ec.europa.eu. Bloqueados (CONNECT 403 do proxy ou 403 anti-bot): mlq.ai, bcg.com (media/web-assets), ibm.com, spglobal.com, gartner.com, deloitte.com, ai.wharton.upenn.edu / knowledge.wharton, langchain.com, oecd.org, doi.org, ssrn.com, mckinsey.com (timeout), sec.gov, justice.gov, hbr.org, rfberlin.com, wfhresearch.com, atlantafed.org, frbsf.org, richmondfed.org, cetic.br, eurostat (ec.europa.eu/eurostat), assets.kpmg.com e sites de imprensa (Register, Fortune, Entrepreneur, CFO Dive, HR Dive etc.).

Resumo: 43 fontes; 19 com fonte original aberta ([VERIFICADO], 4 delas apenas em parte: itens 2, 3, 23, 37); 24 [NÃO VERIFICADO].

---

## 1. The GenAI Divide: State of AI in Business 2025
- Autores/veículo: MIT NANDA (Project NANDA); relatório preliminar v0.1 | Data: jul/2025 | Tipo: relatório institucional (survey + entrevistas)
- Link: https://mlq.ai/media/quarterly_decks/v0.1_State_of_AI_in_Business_2025_Report.pdf ; cópia citada em busca: https://webberwentzel.com/News/Documents/2025/MIT1757411281972.pdf
- Status: [NÃO VERIFICADO] (mlq.ai e webberwentzel.com bloqueados no proxy).
- Método e amostra (via resumos de busca): 153 líderes (survey), 52 entrevistas, mais de 300 implementações públicas; jan–jun/2025.
- Números-chave (via resumos; sem página): 95% das organizações sem retorno mensurável em GenAI apesar de US$30–40 bilhões; "Just 5% of integrated AI pilots are extracting millions in value, while the vast majority remain stuck with no measurable P&L impact"; >80% exploraram/pilotaram, ~40% reportam implantação.
- Limitações declaradas: não lidas. Críticos (opinião, não fonte primária) apontam amostra pequena sem intervalos de confiança, definição estreita de sucesso (impacto em P&L seis meses após o piloto), denominador ambíguo e dados não públicos; ver nota ao final.

## 2. Firm Data on AI (NBER WP 34836)
- Autores/veículo: Ivan Yotzov, Jose Maria Barrero, Nicholas Bloom, Philip Bunn, Chanya Chawla, Steven J. Davis, Kevin M. Foster, Aaron Jalca, Brent H. Meyer, Paul Mizen, Michael A. Navarrete, Samil Oh, Katia Garcia Loredo, Monique Reid, Pawel Smietanka, Gregory Thwaites, Ben Zhe Wang; NBER | Data: Issue Date fev/2026 (página NBER mostra resumo de versão atualizada) | Tipo: working paper NBER com survey
- Link: https://www.nber.org/papers/w34836 | DOI: 10.3386/w34836
- Status: [VERIFICADO] só a página NBER (autores, DOI, resumo). PDF devolveu 403; números da versão de fev/2026 não verificados.
- Método e amostra (resumo na página NBER, versão atual): "We survey nearly 9,000 CFOs, CEOs and senior executives at firms in the US, UK, Germany, Australia, Canada, Mexico and South Africa in Summer 2026."
- Números-chave (resumo NBER, versão atual): "78% of firms use AI"; gasto esperado nos EUA de "$2,000 per employee on AI-related expenditures in 2026, implying around $300 billion"; "just 2% of firms accounting for over 50% of total spending"; "80% of executives report regularly using AI, with an average use of 2.1 hours per week"; "executives report that AI has had essentially no net effect on firm employment over the last 3 years"; "more than 40% of firms anticipate positive or negative employment effects that roughly offset only in the aggregate"; "AI adoption has raised annual labor productivity growth by 0.2% over the last 3 years ... expect a substantially larger 0.6% per annum boost over the next 3 years."
- Versão anterior (fev/2026; ~6.000 executivos em EUA, UK, Alemanha e Austrália; 89% sem impacto em produtividade; 69% de uso; previsão +1,4% produtividade) vem de resumos de busca e de https://www.theregister.com/2026/02/18/ai_productivity_survey/ [NÃO VERIFICADO]. Versão do Atlanta Fed: ver item 24.
- Limitações declaradas: não lidas (PDF inacessível).

## 3. Still Waters, Rapid Currents: Early Labor Market Transformation under Generative AI (NBER WP 33777; título original: "Large Language Models, Small Labor Market Effects")
- Autores/veículo: Anders Humlum (Chicago Booth e NBER), Emilie Vestergaard (Univ. Copenhagen); NBER | Data: Issue Date mai/2025 (página mostra versão revisada) | Tipo: working paper NBER (survey + registros administrativos)
- Link: https://www.nber.org/papers/w33777 | DOI: 10.3386/w33777
- Status: [VERIFICADO] (página NBER e PDF; texto na p. PDF 2-3). Título original e "1%" da primeira versão: [NÃO VERIFICADO] (só busca).
- Método e amostra (PDF p. 3): "large-scale, representative surveys of AI chatbot adoption in 11 highly exposed occupations ... linking responses to administrative labor market records"; última rodada (fim de 2024): "responses from 25,000 workers across 7,000 workplaces"; Dinamarca; diferenças-em-diferenças.
- Números-chave (resumo, p. PDF 2): "using difference-indifferences, we estimate precise null effects on earnings and recorded hours at both the worker and workplace levels, ruling out effects larger than 2% two years after the launch of ChatGPT"; "most employers in exposed occupations have adopted chatbot initiatives, workers report productivity benefits"; "adopters transition into higher-paying occupations ... though still too few to move average earnings."
- Limitações declaradas: seção de limitações não localizada na extração do PDF.

## 4. Still Waters, Rapid Currents (RFBerlin Discussion Paper 078/26)
- Autores/veículo: Humlum e Vestergaard (autoria a confirmar); ROCKWOOL Foundation Berlin | Data: mar/2026 | Tipo: discussion paper (versão do item 3)
- Links: https://www.rfberlin.com/research-insights/still-waters-rapid-currents/ ; https://www.rfberlin.com/wp-content/uploads/2026/03/26078.pdf
- Status: [NÃO VERIFICADO] (rfberlin.com bloqueado). Resumo de busca: sem efeitos em ganhos e horas; IC exclui efeitos médios > 2%; adotantes que mudam de ocupação com ganhos 12 pontos percentuais maiores. Provavelmente corresponde ao texto verificado no item 3.

## 5. The state of AI in 2025: Agents, innovation, and transformation
- Autores/veículo: McKinsey & Company (QuantumBlack) | Data: nov/2025 | Tipo: survey de consultoria com amostra declarada
- Link: https://www.mckinsey.com/capabilities/tech-and-ai/our-insights/the-state-of-ai-2025
- Status: [NÃO VERIFICADO] (mckinsey.com com timeout/empty reply). Números reproduzidos pelo AI Index 2026 estão no item 27.
- Via resumos de busca: "Only 39 percent of respondents said AI had any effect on enterprise-wide EBIT, and most of those reported less than five percent of EBIT attributable to AI use"; ~6% "AI high performers"; 62% experimentando agentes, 23% escalando em uma ou duas funções; "no more than 10 percent" escalando agentes em qualquer função; amostra ~2.000 em 105 países (1.993 não confirmado).
- Limitações declaradas: não lidas.

## 6. The Widening AI Value Gap: Build for the Future 2025
- Autores/veículo: Boston Consulting Group | Data: 30/set/2025 (PDF out/2025) | Tipo: survey de consultoria
- Links: https://media-publications.bcg.com/The-Widening-AI-Value-Gap-October-2025.pdf ; https://www.bcg.com/press/30september2025-ai-leaders-outpace-laggards-revenue-growth-cost-savings
- Status: [NÃO VERIFICADO] (host de mídia bloqueado; press release com 403 anti-bot).
- Via resumos: 1.250 executivos; ~5% "future-built"; 35% escalando; 60% "little to no financial impact to date"; agentes 17% do valor de IA em 2025 e 29% esperado em 2028; 41 dimensões de maturidade.
- Limitações declaradas: não lidas.

## 7. IBM Institute for Business Value — 2025 CEO Study (com Oxford Economics)
- Autores/veículo: IBM IBV / Oxford Economics | Data: 06/mai/2025 | Tipo: survey de fornecedor (ressalva: IBM vende IA)
- Link: https://uk.newsroom.ibm.com/2025-CEO-study
- Status: [NÃO VERIFICADO] (ibm.com e newsroom bloqueados).
- Via resumos: 2.000 CEOs, 33 países, 24 setores, fev–abr/2025; "only 25% of AI initiatives have delivered expected ROI over the last few years, and only 16% have scaled enterprise wide"; 85% esperam ROI positivo até 2027 em eficiência escalada.
- Limitações declaradas: não lidas.

## 8. Voice of the Enterprise: AI & Machine Learning (S&P Global Market Intelligence)
- Autores/veículo: S&P Global Market Intelligence (451 Research) | Data: nota de 27/out/2025 (dado de meio de ano citado em jun/2025) | Tipo: survey de analista
- Links: https://www.spglobal.com/market-intelligence/en/news-insights/research/2025/10/generative-ai-shows-rapid-growth-but-yields-mixed-results ; https://www.ciodive.com/news/ai-project-fail-data-spglobal/742590/
- Status: [NÃO VERIFICADO] (spglobal.com e ciodive.com bloqueados).
- Via resumos: ~1.006 respondentes (América do Norte e Europa); parcela que abandona a maioria das iniciativas de IA antes da produção subiu de 17% para 42%; média de 46% das provas de conceito descartadas.
- Aviso: números atribuídos à S&P por agregadores (2,3 iniciativas abandonadas; US$7,2 mi) não rastreados; não usar.

## 9. Gartner Predicts Over 40% of Agentic AI Projects Will Be Canceled by End of 2027
- Autores/veículo: Gartner (press release) | Data: 25/jun/2025 | Tipo: previsão de analista (não é medição)
- Link: https://www.gartner.com/en/newsroom/press-releases/2025-06-25-gartner-predicts-over-40-percent-of-agentic-ai-projects-will-be-canceled-by-end-of-2027
- Status: [NÃO VERIFICADO] (403 anti-bot).
- Via resumos: ">40%" de projetos agênticos cancelados até fim de 2027 por custos, valor pouco claro e controles de risco; "agent washing" (~130 de milhares de fornecedores); enquete de webinar jan/2025: 19% investimento significativo, 42% conservador.

## 10. The Microstructure of AI Diffusion: Evidence from Firms, Business Functions, and Worker Tasks (CES-WP-26-25 / NBER WP 35141)
- Autores/veículo: Kathryn Bonney, Cory L. Breaux, Emin Dinlersoz, Lucia S. Foster, John C. Haltiwanger, Aditya A. Pande; U.S. Census Bureau CES / NBER | Data: abr/2026 (NBER Issue Date 30/abr/2026) | Tipo: working paper com dados oficiais (suplemento de IA do BTOS)
- Links: https://www.census.gov/library/working-papers/2026/adrm/CES-WP-26-25.html ; https://www.nber.org/papers/w35141 | DOI: 10.3386/w35141
- Status: [VERIFICADO] (resumos nas duas páginas; PDF não obtido: 404 no Census, 403 no NBER).
- Método e amostra (resumo): "novel, nationally representative data from the 2026 AI supplement to the U.S. Census Bureau's Business Trends and Outlook Survey (BTOS)"; camadas: firma, funções de negócio, tarefas de trabalhadores; referência nov/2025–jan/2026.
- Números-chave (resumo): "18% of firms used AI in a business function, rising to 32% on an employment-weighted basis; adoption is expected to reach 22% within six months"; "50%-60% (60%-70%, employment-weighted) for very large firms in the Information, Professional Services, and Finance sectors"; "57% of users integrate AI in three or fewer business functions, most commonly Sales and Marketing (52%), Strategy and Business Development (45%), and IT (41%)"; "In 23% (41%, employment-weighted) of firms, workers use AI in work-related tasks"; "65% of firms limit use to three or fewer tasks"; "Most users (66%) rely on AI solely to augment tasks, while AI-related employment decreases are rare, occurring in only 2% of firms"; "robust positive correlation between firm commercial performance and the breadth of AI integration" (correlação, não causalidade).
- Limitações declaradas: não lidas (texto completo não obtido).

## 11. Census Bureau — "Large Firms With at Least 20 Employees Biggest AI Users" (BTOS)
- Autores/veículo: Adam Grundy, Cory Breaux, Dhanapati Khatiwoda; U.S. Census Bureau (America Counts) | Data: 26/mai/2026 | Tipo: estatística oficial
- Link: https://www.census.gov/library/stories/2026/05/ai-use-businesses.html
- Status: [VERIFICADO]
- Método: BTOS, dados de 14/dez/2025 a 3/mai/2026; pergunta alterada em 17/nov/2025, de uso de IA "in producing goods or services" para "in any business function" (quebra de série).
- Números-chave: "overall AI usage hovered between 17% and 20%"; 20%–23% esperam usar em seis meses; "37% of firms with at least 250 employees"; "32% of firms with 100 to 249 employees"; "Less than 20% of firms with four or fewer employees"; Information 39,7%, Finance and Insurance 33,9%, nacional 19,8% (até 3/mai/2026); Retail Trade ~14%.
- Limitações declaradas: a mudança de redação da pergunta em nov/2025 (acima).

## 12. Generative AI at Work (NBER WP 31161; Quarterly Journal of Economics 140(2): 889–942, 2025)
- Autores/veículo: Erik Brynjolfsson, Danielle Li, Lindsey R. Raymond; NBER / QJE | Data: WP abr/2023, revisão nov/2023; QJE 2025 | Tipo: paper de campo; evidência de ganho de produtividade (contrária ao discurso de retorno nulo); nível do trabalhador
- Links: https://www.nber.org/papers/w31161 | DOI do WP: 10.3386/w31161
- Status: [VERIFICADO] para o WP (página e PDF). Versão QJE (15%, 5.172 agentes, páginas 889–942) [NÃO VERIFICADO]: doi.org bloqueado, só busca.
- Método e amostra (WP, resumo): "staggered introduction of a generative AI-based conversational assistant using data from 5,179 customer support agents".
- Números-chave (WP): "increases productivity, as measured by issues resolved per hour, by 14% on average, including a 34% improvement for novice and low-skilled workers but with minimal impact on experienced and highly skilled workers"; melhora de sentimento do cliente, maior retenção de empregados.
- Limitações declaradas: não localizadas na extração.

## 13. Measuring the Impact of Early-2025 AI on Experienced Open-Source Developer Productivity
- Autores/veículo: Joel Becker, Nate Rush, Elizabeth Barnes, David Rein (METR); arXiv:2507.09089 | Data: 12/jul/2025 (submissão) | Tipo: ensaio controlado randomizado (preprint); resultado negativo
- Link: https://arxiv.org/abs/2507.09089
- Status: [VERIFICADO] (abstract e PDF).
- Método e amostra (abstract): RCT; "16 developers with moderate AI experience complete 246 tasks in mature projects on which they have an average of 5 years of prior experience"; tarefas aleatorizadas para permitir/proibir IA; principalmente Cursor Pro e Claude 3.5/3.7 Sonnet.
- Números-chave (abstract): previsão prévia de redução de tempo de 24%; estimativa posterior de redução de 20%; "allowing AI actually increases completion time by 19%"; especialistas previram "economics (39% shorter) and ML (38% shorter)".
- Limitações declaradas (abstract e §4.1 "Key Caveats", p. PDF 12): "Although the influence of experimental artifacts cannot be entirely ruled out..."; "We caution readers against overgeneralizing on the basis of our results. The slowdown we observe does not imply that current AI tools do not often improve developer's productivity"; resultados compatíveis com ganhos em projetos pequenos novos ou bases de código desconhecidas.

## 14. CRMArena-Pro: Holistic Assessment of LLM Agents Across Diverse Business Scenarios and Interactions
- Autores/veículo: Kung-Hsiang Huang, Akshara Prabhakar, Onkar Thorat, Divyansh Agarwal, Prafulla Kumar Choubey, Yixin Mao, Silvio Savarese, Caiming Xiong, Chien-Sheng Wu; arXiv:2505.18878 (afiliação Salesforce não conferida no texto lido) | Data: 24/mai/2025 | Tipo: benchmark (ambiente CRM sintético)
- Link: https://arxiv.org/abs/2505.18878
- Status: [VERIFICADO] (abstract e PDF).
- Método (abstract; p. PDF 5): "nineteen expert-validated tasks across sales, service, and 'configure, price, and quote' processes"; 4.280 consultas ("4,280 queries", p. PDF 5); interações multi-turno com simulador de usuário LLM.
- Números-chave (abstract): "leading LLM agents achieve only around 58% single-turn success ... approximately 35% in multi-turn settings"; "Workflow Execution ... over 83% single-turn success"; "agents exhibit near-zero inherent confidentiality awareness".
- Limitações declaradas (Apêndice, p. PDF 13): o simulador de usuário baseado em LLM pode produzir respostas inconsistentes; em 20 trajetórias amostradas, 1 erro (5%).

## 15. 2025 Wharton GBK AI Adoption Report ("Accountable Acceleration")
- Autores/veículo: Wharton Human-AI Research (Stefano Puntoni, Prasanna Tambe) e GBK Collective (Jeremy Korst) | Data: 28/out/2025 | Tipo: survey; evidência de ROI positivo autodeclarado (contrária ao discurso de fracasso)
- Links: https://ai.wharton.upenn.edu/wp-content/uploads/2025/10/2025-Wharton-GBK-AI-Adoption-Report_Full-Report.pdf ; https://knowledge.wharton.upenn.edu/special-report/2025-ai-adoption-report
- Status: [NÃO VERIFICADO] (hosts Wharton bloqueados).
- Via resumos: >800 líderes de empresas dos EUA com receita >US$50 milhões; 82% usam GenAI semanalmente, 46% diariamente; busca específica pelo dado pedido: "74%" aparece em coberturas secundárias como parcela das empresas que medem ROI e relatam ROI positivo (outros veículos dizem ~75%); 72% das empresas acompanham métricas de ROI estruturadas; só 57% das empresas com receita >US$2 bi relatam ROI positivo. Valores e base exatos exigem o PDF.
- Limitações: estudo pago pela Wharton em parceria com GBK Collective (consultoria), segundo cobertura.

## 16. "Workslop" (HBR; BetterUp Labs e Stanford Social Media Lab)
- Autores/veículo: BetterUp Labs / Stanford Social Media Lab; Harvard Business Review | Data: set/2025 | Tipo: survey (BetterUp é fornecedor de coaching)
- Link: cobertura https://www.techspot.com/news/109591-companies-losing-money-ai-workslop-slows-everything-down.html ; URL do artigo HBR não identificada
- Status: [NÃO VERIFICADO] (hbr.org e techspot bloqueados).
- Via resumos: 1.150 trabalhadores de escritório dos EUA (ago–set/2025); ~40% receberam "workslop" no mês anterior; ~1h56 por incidente; custo ~US$186/mês por trabalhador; extrapolação >US$9 mi/ano para 10.000 pessoas (estimativa modelada); tempo autorrelatado.

## 17. SEC e DOJ — "AI washing": Presto Automation (jan/2025) e Nate Inc./Albert Saniger (abr/2025)
- Autores/veículo: SEC; U.S. Attorney's Office SDNY; comentários jurídicos | Data: jan/2025; 09/abr/2025 | Tipo: ato regulatório / caso
- Links (comentários): https://www.whitecase.com/insight-alert/evolution-ai-washing-enforcement-doj-enters-picture ; https://corpgov.law.harvard.edu/2025/05/22/evolution-of-ai-washing-enforcement-doj-enters-the-picture
- Status: [NÃO VERIFICADO] (sec.gov e justice.gov bloqueados).
- Via resumos: Presto: cease-and-desist sem multa civil, por apresentar IA de terceiros como própria e exagerar a dispensa de atendentes; Nate: acusação de fraude de valores mobiliários e fraude eletrônica (SEC + SDNY) por alegar IA autônoma quando contratados nas Filipinas completavam compras manualmente (2019–dez/2022); são alegações; status atual não verificado.

## 18. Replit AI agent apaga banco de dados de produção (SaaStr / Jason Lemkin)
- Veículo: Fortune, Gizmodo, The Register, eWeek; AI Incident Database | Data: jul/2025 | Tipo: caso documentado
- Links: https://dc.fortune.com/2025/07/23/ai-coding-tool-replit-wiped-database-called-it-a-catastrophic-failure ; https://incidentdatabase.ai/cite/1152/
- Status: [NÃO VERIFICADO] (hosts bloqueados).
- Via resumos: agente executou comandos destrutivos no banco de produção durante "code freeze"; ~1.200 executivos/~1.200 empresas (varia por fonte); CEO: "Unacceptable and should never be possible"; separação automática dev/produção anunciada. Detalhes de dados falsos e rollback vêm de fontes únicas.

## 19. Commonwealth Bank of Australia — reversão de cortes ligados a bot de voz com IA
- Veículo: American Banker, AFR, ITPro, Cyber Daily; sindicato FSU | Data: jul–ago/2025 | Tipo: caso documentado
- Links: https://www.americanbanker.com/news/australias-cba-halts-ai-driven-layoffs-amid-union-pressure ; https://www.itpro.com/business/business-strategy/australias-biggest-bank-cut-staff-for-ai-then-it-backtracked-and-its-one-of-many-scrapping-plans-for-automated-customer-support-teams
- Status: [NÃO VERIFICADO] (bloqueados).
- Via resumos: 90 cortes, 45 substituídos por bot de voz (jul/2025); reversão em ago/2025 após ação do sindicato na Fair Work Commission; volumes de chamadas seguiram altos (números de variação conflitantes, sem fonte primária).

## 20. Klarna — retomada de contratação de atendentes humanos
- Veículo: Bloomberg (entrevista com Sebastian Siemiatkowski), Entrepreneur, Fortune, tech.co | Data: mai/2025 | Tipo: caso documentado (declaração do CEO)
- Links: https://www.entrepreneur.com/business-news/klarna-ceo-reverses-course-by-hiring-more-humans-not-ai/491396 ; https://tech.co/news/klarna-reverses-ai-overhaul
- Status: [NÃO VERIFICADO] (bloqueados).
- Via resumos: em 2024 dizia que o assistente fazia o trabalho de 700 agentes; em mai/2025 o CEO disse que custo foi "a too predominant evaluation factor" e que a qualidade caiu; modelo "Uber type" com freelancers; porta-voz: "very much still AI-first".

## 21. Deloitte Australia — reembolso parcial por relatório com erros de IA
- Veículo: The Register, ACS Information Age, CFO Dive | Data: out/2025 | Tipo: caso documentado
- Links: https://www.theregister.com/2025/10/06/deloitte_ai_report_australia/ ; https://www.cfodive.com/news/deloitte-refunds-60k-report-ai-errors-australian-government-accounting/803321/
- Status: [NÃO VERIFICADO] (bloqueados).
- Via resumos: contrato de AU$440.000 com o DEWR; três referências inexistentes e citação inventada de decisão da Federal Court; versão corrigida declara uso de Azure OpenAI GPT-4o; reembolso da parcela final (CFO Dive: >AU$97.000); Deloitte manteve as conclusões.

## 22. Deloitte — State of AI in the Enterprise (edição 2026)
- Autores/veículo: Deloitte AI Institute | Data: jan/2026 (campo ago–set/2025) | Tipo: survey de consultoria
- Links: https://www.deloitte.com/us/en/about/press-room/state-of-ai-report-2026.html ; https://www.deloitte.com/nl/en/about/press-room/state-of-ai-in-the-enterprise-2026.html
- Status: [NÃO VERIFICADO] (deloitte.com bloqueado).
- Via resumos: 3.235 respondentes de diretor a C-suite, 24 países, seis setores; "only 25% of respondents have moved 40% or more of their AI pilots into production"; ~1 em 5 diz que IA gerou crescimento de receita.

## 23. KPMG — AI Quarterly Pulse (EUA, Q1 2026) e Global AI Pulse (Q2 e Q3 2026)
- Autores/veículo: KPMG | Data: mar/2026 (Q1 EUA); Q2/2026; 24/set/2026 (Q3) | Tipo: survey de consultoria
- Links: https://kpmg.com/kpmg-us/content/dam/kpmg/pdf/2026/ai-quarterly-pulse-survey-q1-2026.pdf ; https://kpmg.com/sa/en/insights/ai-and-technology/global-ai-pulse-q2-2026.html ; https://kpmg.com/xx/en/media/press-releases/2026/09/new-kpmg-ai-pulse-survey-as-ai-maturity-converges-leading-organi%7aations-show-what-ai-at-scale-requires.html
- Status: [VERIFICADO] em parte (os três textos abaixo); o dado "7%" segue [NÃO VERIFICADO].
- Q1 EUA (PDF, p. PDF 2-3): investimento médio projetado de "$207 million" nos próximos 12 meses, "nearly double" o ano anterior; "Difficulty scaling use cases and employee skill gaps are top barriers to demonstrating ROI"; metodologia/amostra não encontradas no texto do PDF.
- Q2 Global (página KPMG Arábia Saudita): "established ROI remains limited"; "Organizations with full visibility into AI operating costs are five times more likely to report established ROI than those without (15% vs. 3%)"; amostra: "2,145 C-suite and business leaders ... in 20 countries, territories and jurisdictions".
- Q3 Global (press release 24/set/2026): "survey of 2,131 senior leaders across 20 countries"; "12 percent consistently assess the value of AI against its cost, rising to 48 percent among those already reporting returns" (observação: o 12% é do Q3 nesta fonte); investimento médio planejado US$210 milhões, ante US$186 milhões no Q1.
- Dado pedido ("7% com ROI estabelecido"): aparece só em coberturas secundárias (UC Today, Crypto Briefing; Q2/2026, 2.145 líderes) e NÃO consta nas páginas KPMG abertas. [NÃO VERIFICADO]
- Limitações declaradas: não encontradas nos textos abertos.

## 24. Firm Data on AI — Federal Reserve Bank of Atlanta Working Paper 2026-3
- Autores/veículo: equipe do item 2; FRB Atlanta | Data: fev/2026, revisado mar/2026 | Tipo: working paper de banco central
- Links: https://econpapers.repec.org/RePEc:fip:fedawp:102928 ; https://www.frbsf.org/research-and-insights/publications/system-research-atlanta-fed/2026/07/firm-data-on-ai/
- Status: [NÃO VERIFICADO] (frbsf.org, atlantafed.org e repec bloqueados). Via resumos: ~6.000 executivos (nov/2025–jan/2026).

## 25. Artificial Intelligence, Productivity, and the Workforce: Evidence from Corporate Executives (NBER WP 34984)
- Autores/veículo: Salomé Baslandze, Zachary Edwards, John Graham, Ty McClure, Brent H. Meyer, Michael Sparks, Sonya R. Waddell, Daniel Weitz; NBER | Data: Issue Date mar/2026 | Tipo: working paper NBER com survey de CFOs
- Link: https://www.nber.org/papers/w34984 | DOI: 10.3386/w34984
- Status: [VERIFICADO] (página NBER; PDF 403). Corrige o título citado em versão anterior deste arquivo.
- Método e amostra (resumo): "survey of nearly 750 corporate executives".
- Números-chave (resumo): "more than half having already invested"; "Labor productivity gains are positive, vary across sectors, and are expected to strengthen in 2026"; "We document a productivity paradox, in which perceived productivity gains are larger than measured productivity gains, likely reflecting a delay in revenue realizations"; "little evidence of near-term aggregate employment declines due to AI, though larger companies anticipate AI-driven workforce reductions"; "routine clerical roles declining".
- Limitações declaradas: não lidas (PDF inacessível).

## 26. The adoption of artificial intelligence in firms / AI Adoption by SMEs (OECD)
- Autores/veículo: OECD (com BCG e INSEAD) | Data: mai/2025 | Tipo: relatório institucional
- Link: https://www.oecd.org/en/publications/2025/05/the-adoption-of-artificial-intelligence-in-firms_8fab986b.html ; DOI citado em busca: 10.1787/f9ef33c3-en
- Status: [NÃO VERIFICADO] (oecd.org e doi.org com 403 anti-bot).
- Via resumos: survey de 840 empresas do G7 + 167 no Brasil (2022–23, antes da onda de GenAI); 11,9% das pequenas firmas vs. 40% das grandes; prêmios de produtividade dos adotantes "shrink significantly" ao controlar por capacidades prévias; Digital Economy Outlook 2026: 20% das empresas com 10+ empregados na OCDE em 2025 vs. 52% das grandes.

## 27. Stanford HAI — AI Index Report 2026
- Autores/veículo: Stanford Institute for Human-Centered AI | Data: abr/2026 | Tipo: relatório institucional anual
- Link: https://hai.stanford.edu/ai-index/2026-ai-index-report (PDF: https://hai.stanford.edu/assets/files/ai_index_report_2026.pdf)
- Status: [VERIFICADO] (PDF aberto; páginas = p. PDF).
- Números-chave (Top takeaways, Cap. 4, p. PDF 173): "Organizational AI adoption continued to rise in 2025, up to 88% of surveyed organizations, though AI agent use remains early. Generative AI is now used in at least one business function at 70% of organizations"; "AI agent deployment was in the single digits across nearly all business functions"; consumo: "$172 billion annually, up from $112 billion a year earlier".
- §4.3 Corporate AI Adoption (p. PDF 193-197; base: McKinsey State of AI 2025): "up to 88% in 2025 from 78% in 2024"; "79% of respondents reporting that their organizations regularly use generative AI in at least one business function, compared to 71% in 2024" (inconsistente com os 70% do resumo do mesmo relatório; ambos registrados); "Scaled use was in the single digits for nearly all functions" (agentes); ganhos de custo mais citados em engenharia de software e manufatura (56%), receita em marketing e vendas (67%); "no more than 7% believing AI usage had worsened cost metrics".
- Limitações declaradas (p. PDF 193): "the results are self-reported and should be viewed as directional rather than comprehensive."

## 28. Beyond Productivity: Measuring the Real Value of AI (Workday)
- Autores/veículo: Workday com Hanover Research | Data: 14/jan/2026 | Tipo: survey de fornecedor
- Links: https://www.hrdive.com/news/ai-output-reduced-rework-low-quality-workday/810075/ ; https://www.cfo.com/news/almost-half-of-time-saved-using-ai-is-spent-correcting-outputs-cfo-ai-use-errors-workday-report-/810018/
- Status: [NÃO VERIFICADO] (hosts bloqueados; relatório original não localizado).
- Via resumos: 3.200 respondentes (metade líderes), nov/2025; ~37% do tempo economizado vai a retrabalho; só 14% têm resultado líquido positivo consistente; 85% relatam economizar 1–7 h/semana.

## 29. TheAgentCompany: Benchmarking LLM Agents on Consequential Real World Tasks
- Autores/veículo: Frank F. Xu, Yufan Song, Boxuan Li et al., Graham Neubig (21 autores; Carnegie Mellon); arXiv:2412.14161; NeurIPS 2025 (segundo busca) | Data: v1 18/dez/2024; v3 10/set/2025 | Tipo: benchmark (empresa fictícia de software)
- Link: https://arxiv.org/abs/2412.14161
- Status: [VERIFICADO] (abstract e PDF). Observação: v1 é de dez/2024; a versão relevante é de 2025.
- Método: ambiente auto-contido que "mimics a small software company"; 175 tarefas (cifra de 175 vinda de busca, não localizada no trecho lido) [NÃO VERIFICADO apenas esta cifra].
- Números-chave: "the most competitive agent can complete 30% of tasks autonomously" (abstract); 30,3% de conclusão total e 39,3% com crédito parcial (p. PDF 2); "more difficult long-horizon tasks are still beyond the reach of current systems".
- Limitações declaradas (p. PDF 9): tarefas "generally on the more straightforward side"; só dois scaffolds; sem baseline de profissionais humanos; tarefas criadas por introspecção, podendo divergir de tarefas reais de empresas.

## 30. The Impact of Generative AI on Work Productivity (blog) / The Rapid Adoption of Generative AI (FRB St. Louis WP 2024-027C)
- Autores/veículo: Alexander Bick, Adam Blandin, David Deming; Federal Reserve Bank of St. Louis | Data: 27/fev/2025 (blog); WP revisado fev/2025 (nova revisão out/2025, não aberta) | Tipo: survey nacional (Real-Time Population Survey); nível do trabalhador
- Link: https://www.stlouisfed.org/on-the-economy/2025/feb/impact-generative-ai-work-productivity | WP DOI citado em busca: 10.20955/wp.2024.027 (não aberto)
- Status: [VERIFICADO] (blog); WP não aberto.
- Números-chave (blog): entre os que usaram GenAI na semana anterior ("21.8% of all workers"), "between 6.0% and 24.9% of all work hours were assisted by generative AI"; entre todos os trabalhadores, "between 1.3% and 5.4% of total work hours"; tempo economizado traduz-se em "a 1.1% increase in aggregate productivity"; "workers are 33% more productive in each hour that they use generative AI"; aviso no topo: ver post de 13/nov com resultados revisados por mudança na sequência de perguntas.
- Limitações declaradas (blog): "how these gains translate into measured aggregate productivity remains uncertain"; ganhos autorrelatados podem virar lazer no trabalho; trabalho de Bonney et al. mostrou "only 5.4% of firms had formally adopted generative AI as of February 2024"; ganhos "may not immediately appear in productivity statistics".

## 31. The State of Agent Engineering (LangChain)
- Autores/veículo: LangChain | Data: fim de 2025/início de 2026 | Tipo: survey de fornecedor (autosseleção; sentido contrário ao discurso de fracasso)
- Link: https://langchain.com/state-of-agent-engineering
- Status: [NÃO VERIFICADO] (langchain.com bloqueado).
- Via resumos: 57,3% com agentes em produção (51% no ano anterior); 30,4% desenvolvendo com planos; qualidade como principal bloqueio (~32%); segurança 2º em empresas 2k+ (24,9%).

## 32. Measuring Agents in Production (MAP)
- Autores/veículo: Melissa Z. Pan, Negar Arabzadeh, Riccardo Cogo et al. (25 autores, incl. Matei Zaharia, Ion Stoica, Joseph E. Gonzalez, Dawn Song); arXiv:2512.04123 | Data: v1 02/dez/2025; versão mais recente 04/jun/2026 | Tipo: estudo empírico (entrevistas + survey)
- Link: https://arxiv.org/abs/2512.04123
- Status: [VERIFICADO] (abstract e PDF).
- Método (abstract): "20 case studies via in-depth interviews and surveyed 86 deployed systems practitioners across 26 domains" (a cifra de 306 respondentes citada antes em busca NÃO aparece no abstract; descartada).
- Números-chave (abstract): "68% execute at most 10 steps before human intervention, 70% rely on prompting off-the-shelf models instead of weight tuning, and 74% depend primarily on human evaluation"; "Reliability ... remains the top development challenge."
- Limitações declaradas (§ Limitations, p. PDF 4): concentração geográfica nas Américas; viés de participação (equipes aceitaram convites conforme políticas das empresas; respondentes do survey tendem a vir das redes dos autores); possível viés temporal; janela de abril a novembro de 2025.

## 33. Use of artificial intelligence in enterprises (Eurostat, dataset isoc_eb_ai)
- Autores/veículo: Eurostat | Data: 11/dez/2025 | Tipo: estatística oficial
- Links: https://ec.europa.eu/eurostat/web/products-eurostat-news/w/ddn-20251211-2 ; https://ec.europa.eu/eurostat/statistics-explained/index.php/Use_of_artificial_intelligence_in_enterprises
- Status: [NÃO VERIFICADO] (host eurostat bloqueado). Via resumos: 19,95% (~20%) das empresas da UE com 10+ empregados usaram IA em 2025, ante 13,5% em 2024; 55,03% entre as de 250+; Dinamarca 42,0%, Romênia 5,2%.

## 34. Salesforce — Benioff anuncia corte de ~4.000 vagas de suporte substituídas por agentes
- Veículo: The Register, ITPro, Al Jazeera, Computing | Data: início de set/2025 | Tipo: caso documentado (declaração do CEO)
- Links: https://www.theregister.com/2025/09/02/salesforce_4000_jobs_ai ; https://www.aljazeera.com/economy/2025/9/3/salesforce-lays-off-thousands-despite-strong-earnings-report
- Status: [NÃO VERIFICADO] (bloqueados). Via resumos: suporte de ~9.000 para ~5.000; metade das conversas com agentes; "qualidade inalterada" é afirmação do CEO, não verificada. Alegação de recuo para automação determinística só em blog; não corroborada. Contraponto de dados: item 14.

## 35. Plug and Play — 2026 Enterprise AI Strategy Pulse Survey (via Forbes, 06/ago/2026)
- Veículo: Plug and Play; Forbes (Sandy Carter) | Data: 06/ago/2026 | Tipo: survey de aceleradora; amostra e metodologia não encontradas
- Links: https://www.forbes.com/sites/sandycarter/2026/08/06/enterprise-ai-roi-production-survey/ ; https://www.marketscale.com/industries/software-and-technology/74-of-enterprises-run-ai-in-production-but-half-cant-prove-it-pays-off
- Status: [NÃO VERIFICADO] (bloqueados). Via resumos: Fortune 500/Global 2000; 74% com ao menos uma solução em produção; metade não mede ROI de forma consistente.

## 36. Gartner — pesquisa com CIOs sobre valor de IA (divulgada 19/out/2026)
- Veículo: Gartner (via eWeek, Crowdfund Insider) | Data: 19/out/2026 | Tipo: survey de analista
- Link: https://www.eweek.com/news/gartner-cio-ai-value-rules/ ; release Gartner não identificado
- Status: [NÃO VERIFICADO]. Via resumos: 2.002 CIOs, mai–jul/2026; só 13% com valor significativo ou transformacional; 31% têm regras para encerrar pilotos e 17% critérios para abandonar iniciativas em produção; 17% implantaram agentes (secundário).

## 37. EU Digital Omnibus on AI — adiamento de obrigações do AI Act
- Autores/veículo: Comissão Europeia; Parlamento e Conselho | Data: proposta 19/nov/2025; entrada em vigor 27/jul/2026 | Tipo: ato regulatório
- Links: https://digital-strategy.ec.europa.eu/en/library/digital-omnibus-ai-regulation-proposal ; proposta COM(2025) 836: https://eur-lex.europa.eu/legal-content/EN/TXT/?uri=CELEX:52025PC0836
- Status: [VERIFICADO] em parte. Página da Comissão: "Publication 19 November 2025"; "On 27 July 2026, the AI Omnibus enters into force across the EU, bringing extended timelines to administrative simplification." Texto do EUR-Lex exige JavaScript e não foi lido; as datas novas (alto risco Anexo III em 2/dez/2027 e Anexo I em 2/ago/2028; acordo provisório de 7/mai/2026) vêm de comentários jurídicos (DLA Piper, CMS) [NÃO VERIFICADO].

## 38. Remote Labor Index: Measuring AI Automation of Remote Work
- Autores/veículo: Mantas Mazeika et al. (47 autores; inclui Dan Hendrycks e Alexandr Wang; Scale AI / Center for AI Safety); arXiv:2510.26787 | Data: 30/out/2025 | Tipo: benchmark com projetos reais de freelancers
- Link: https://arxiv.org/abs/2510.26787
- Status: [VERIFICADO] (abstract e PDF).
- Método (PDF p. 5, 12): 240 projetos em 23 domínios de trabalho freelancer digital (p. 12); referências de 358 freelancers verificados do Upwork (p. 5).
- Números-chave: "AI agents perform near the floor on RLI, with the highest-performing agent achieving an automation rate of 2.5%" (abstract); "All AI agents tested automate at most 2.5% of tasks on RLI" (Figura 2, p. PDF 3); Tabela 2 (p. PDF 11), frequência de problemas nas entregas de IA (categorias não exclusivas): arquivos corrompidos 17,6%; incompleto 35,7%; baixa qualidade 45,6%; inconsistências 14,8%.
- Limitações declaradas (p. PDF 12): exclui projetos que exigem interação com cliente, trabalho em equipe e outros; "an AI obtaining 100% automation rate on RLI may still underperform humans on types of work that we do not evaluate"; custos de projeto não ajustados pela inflação.

## 39. AI adoption, productivity and employment: evidence from European firms (BIS Working Paper 1325)
- Autores/veículo: Iñaki Aldasoro, Leonardo Gambacorta, Rozalia Pal, Debora Revoltella, Christoph Weiss, Marcin Wolski; Bank for International Settlements | Data: 23/jan/2026 | Tipo: working paper de banco central (evidência de ganho)
- Link: https://www.bis.org/publ/work1325.htm
- Status: [VERIFICADO] (página BIS; resumo; PDF não lido).
- Método (resumo): dados EIBIS-ORBIS de "more than 12,000 non-financial firms in the European Union (EU) and United States (US)"; adoção de IA das firmas da UE instrumentada pela adoção de pares dos EUA.
- Números-chave (resumo): "AI adoption increases the level of labor productivity by 4%"; ganhos por aprofundamento de capital, "no adverse effects on firm-level employment"; benefícios "concentrate in medium and large firms"; importância de investimentos complementares em software, dados e treinamento.
- Limitações declaradas (resumo): "longer-term effects remain uncertain".

## 40. Artificial intelligence and growth in advanced and emerging economies: short-run impact (BIS Working Paper 1321)
- Autores/veículo: Leonardo Gambacorta, Enisse Kharroubi, Aaron Mehrotra, Tommaso Oliviero; BIS | Data: 19/dez/2025 | Tipo: working paper de banco central
- Link: https://www.bis.org/publ/work1321.htm
- Status: [VERIFICADO] (página BIS; resumo).
- Método: estratégia inspirada em Rajan e Zingales (1998); "56 economies and 16 industries".
- Números-chave/resultado (resumo): gen AI "is likely to benefit advanced economies more than emerging market economies, thereby widening global income disparities in the near term"; sem estimativa pontual no resumo.
- Limitações declaradas: não lidas.

## 41. Monitoring AI Adoption in the U.S. Economy (FEDS Notes)
- Autores/veículo: Jeffrey S. Allen; Federal Reserve Board | Data: 03/abr/2026 | Tipo: nota de pesquisa de banco central
- Link: https://www.federalreserve.gov/econres/notes/feds-notes/monitoring-ai-adoption-in-the-u-s-economy-20260403.html
- Status: [VERIFICADO]
- Método: três pesquisas públicas (BTOS do Census, Real-Time Population Survey, Survey of Business Uncertainty do Atlanta Fed).
- Números-chave: "about 18 percent of firms have adopted AI as of year-end 2025"; antes da mudança metodológica, "the adoption rate grew by 68 percent for the year ending in September"; uso de GenAI no trabalho por indivíduos "about 41 percent as of November"; SBU: "78 percent of the labor force works at firms that have adopted AI, and about 54 percent works at firms that use LLMs"; Crane, Green e Soto (2025) citados: 16 surveys com estimativas de adoção no trabalho de "about 5 to 40 percent" em meados de 2024.
- Limitações declaradas: variação entre estimativas atribuída provavelmente a "differences in sampling distributions and units of analysis", além de enquadramento das perguntas, materialidade do uso, assimetrias de informação e viés de desejabilidade social.

## 42. AI Adoption and Firms' Job-Posting Behavior (FEDS Notes)
- Autores/veículo: Jessica Liu e Douglas Webber; Federal Reserve Board | Data: 27/mar/2026 | Tipo: nota de pesquisa de banco central (resultado nulo sobre vagas)
- Link: https://www.federalreserve.gov/econres/notes/feds-notes/ai-adoption-and-firms-job-posting-behavior-20260327.html
- Status: [VERIFICADO] (introdução e conclusões iniciais lidas).
- Método: dados de vagas da Lightcast e BTOS do Census.
- Resultado (texto): "thus far, there is no evidence of a reduction in job postings for industries or firms which have higher levels of AI adoption"; a desaceleração geral de vagas "does not appear to be driven (even modestly) by AI".
- Limitações declaradas: foco no nível total de vagas, não em ocupações específicas; "the United States is still in a very early stage of AI development".

## 43. TIC Empresas 2025 (Brasil) — uso de IA por empresas (Cetic.br/NIC.br)
- Autores/veículo: Cetic.br / NIC.br | Data: 2026 (PDF com carimbo ago/2026) | Tipo: estatística oficial por amostra (survey)
- Links: https://cetic.br/media/analises/TIC-Empresas-2025-lancamento.pdf ; https://cetic.br/en/tics/pesquisa/2025/empresas/H10/ ; https://cetic.br/media/docs/publicacoes/2/pt-br/20260831091252/TIC_EMPRESAS_2025_PT_RE.pdf
- Status: [NÃO VERIFICADO] (cetic.br bloqueado no proxy).
- Via resumos de busca: 17% das empresas brasileiras usaram IA em 2025 (13% em 2024); estimativa de 93.475 empresas; pequenas empresas de 10% para 15%; grandes empresas divergem entre coberturas (37% vs. 38%→50%), conferir tabelas H9/H10.

---

## Nota sobre críticas metodológicas ao item 1 (MIT NANDA)
Comentário (opinião com argumentos; não é fonte primária) [NÃO VERIFICADO]: https://www.hpcwire.com/bigdatawire/2025/09/04/mit-report-flags-95-genai-failure-rate-but-critics-say-it-oversimplifies/ ; https://arnon.dk/mits-95-ai-failure-rate-is-wrong/ ; https://80000hours.org/podcast/episodes/ai-workplace-mit-study/ ; https://www.futuriom.com/articles/news/why-we-dont-believe-mit-nandas-werid-ai-study/2025/08/ . Pontos segundo resumos: amostra pequena sem intervalos de confiança; definição restrita de sucesso; denominador ambíguo; dados completos não públicos na viralização; possível conflito de interesse. Sem retratação ou resposta formal encontrada.

## Buscas realizadas / lacunas

Termos usados (WebSearch): MIT NANDA GenAI Divide; Census BTOS AI use; Stanford AI Index 2026; NBER Humlum Vestergaard; Gartner agentic AI 40%; NBER survey executives; McKinsey State of AI 2025; BCG Widening AI Value Gap; IBM CEO study 2025; S&P Global VotE 42%; Census Microstructure of AI Diffusion; METR RCT; CBA reversal; Klarna; Wharton GBK 2025 (inclusive "74%"); Brynjolfsson QJE; Deloitte Australia; CRMArena-Pro; workslop; SEC AI washing; Replit; Deloitte State of AI 2026; KPMG Pulse 2026 (inclusive "7%"); Atlanta Fed/Duke CFO Survey; OECD firms; Workday; TheAgentCompany; St. Louis Fed; LangChain; Measuring Agents in Production; Eurostat; Salesforce 4.000 vagas; críticas MIT NANDA; Plug and Play/Forbes; Digital Omnibus; Gartner CIO 2026; Remote Labor Index; Cetic.br TIC Empresas; BIS papers de IA; FEDS Notes de IA; IA preditiva/ML em produção.

Lacunas:
- 24 fontes seguem [NÃO VERIFICADO] por bloqueio de rede (hosts listados no topo); para fechar: liberar mckinsey.com, bcg.com, ibm.com, spglobal.com, gartner.com, deloitte.com, wharton, langchain.com, oecd.org, doi.org, sec.gov, justice.gov, hbr.org, cetic.br, eurostat, atlantafed.org, frbsf.org, rfberlin.com, mlq.ai e jornais citados.
- PDFs NBER de w34836, w35141 e w34984 deram 403; limitações e números de corpo dos textos não verificados (só resumos).
- Wharton "74%": localizado só em coberturas secundárias (base: empresas que medem ROI). KPMG "7%": só em coberturas secundárias; não consta nas páginas KPMG abertas.
- IA preditiva/ML clássico: nenhum estudo empírico com amostra declarada e posterior a jan/2025 encontrado; apareceram apenas números antigos ou sem fonte primária (Rexer Analytics, Algorithmia 2020, "87% dos modelos nunca chegam à produção" sem pesquisa primária identificável). Registrado como lacuna.
- Brasil: apenas Cetic.br (item 43, não verificado); IBGE (PINTEC/PIA), IPEA e Banco Central do Brasil não pesquisados.
- Decisões judiciais ligadas a falhas de projetos corporativos de IA: não encontradas além dos casos SEC/DOJ (item 17); Air Canada (Moffatt, fev/2024) fora do período.
- Excluídos por serem marketing de fornecedor ou sem metodologia verificável: IDC/Microsoft (US$3,70 por dólar), Google Cloud (74% de ROI em 1 ano), WRITER (29% de ROI significativo).
