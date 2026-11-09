# Tema 5: Viés, privacidade e propriedade intelectual — processos judiciais e decisões recentes sobre dados de treinamento e direitos autorais

Data da busca: 09/nov/2026
Período coberto: jan/2025 a 09/nov/2026

---
Nota de método: fontes abertas diretamente (arXiv/NBER/páginas oficiais) via curl/pdftotext são marcadas "Verificado na fonte original". Itens baseados apenas em resultados de busca (resumos de terceiros) levam [NÃO VERIFICADO]. Documentos primários de tribunais (CourtListener, sites de tribunais, EUR-Lex/Curia) não puderam ser abertos neste ambiente (ver seção final "Buscas realizadas / lacunas"). Sem análise ou conclusões neste arquivo.

---

## 1. Extracting books from production language models
- Autores/veículo: Ahmed Ahmed, A. Feder Cooper, Sanmi Koyejo, Percy Liang (Stanford; Yale) | arXiv:2601.02671v1, 6/jan/2026 | Tipo: preprint, estudo empírico (extração de dados de treinamento)
- Link: https://arxiv.org/abs/2601.02671 (PDF: https://arxiv.org/pdf/2601.02671) | DOI: https://doi.org/10.48550/arXiv.2601.02671
- Método e amostra: procedimento em duas fases (sonda inicial, com jailbreak Best-of-N quando necessário; depois prompts iterativos de continuação) aplicado a 4 LLMs de produção (Claude 3.7 Sonnet, GPT-4.1, Gemini 2.5 Pro, Grok 3); métrica "nv-recall" (aproximação em blocos da maior subsequência comum); experimentos de meados de ago a meados de set/2025; livros testados: 11 protegidos por copyright nos EUA publicados antes de 2020 e 2 em domínio público (Seção 1; Seção 3).
- Números-chave (Abstract, p. 1; Fig. 1, p. 2; Seção 1): "nv-recall of 76.8% and 70.3%, respectively, for Harry Potter and the Sorcerer's Stone" (Gemini 2.5 Pro e Grok 3, sem jailbreak); "jailbroken Claude 3.7 Sonnet outputs entire books near-verbatim (e.g., nv-recall = 95.8%)" (BoN N = 258); "GPT-4.1 requires significantly more BoN attempts (e.g., 20×), and eventually refuses to continue (e.g., nv-recall = 4.0%)" (N = 5179); "most experiments result in far less extraction (nv-recall ≤ 10%)"; Claude 3.7 Sonnet: "almost the entire text of two in-copyright books (and two in the public domain) (nv-recall ≥ 94%)". Divulgação: provedores notificados em 9/set/2025; janela de 90 dias terminou em 9/dez/2025 e "our procedure still works on some of the systems" (Seção 1).
- Limitações declaradas (Seção 5.1, p. 18): "we only ran experiments on fourteen specific books, so our results do not speak to memorization and extraction more generally" (o texto também cita "thirteen books" na Seção 3 — inconsistência interna do artigo); "we do not make general claims about books extraction overall, or claims comparing overall extraction risk across production LLMs"; custo: "for Claude 3.7 Sonnet ... it often cost over $100 per run"; configurações diferentes por LLM; "We do not claim we maximized possible extraction for each LLM" (Fig. 1).
- Status: Verificado na fonte original (PDF).

## 2. Extracting memorized pieces of (copyrighted) books from open-weight language models
- Autores/veículo: A. Feder Cooper, Mark A. Lemley, Allison Casasola, Ahmed Ahmed, Aaron Gokaslan, Amy B. Cyphert, Christopher De Sa, Daniel E. Ho, Percy Liang | arXiv:2505.12546 (v1 18/mai/2025; v6 20/jul/2026; versão curta em COLM 2026) | Tipo: preprint, estudo empírico (memorização)
- Link: https://arxiv.org/abs/2505.12546 | DOI: https://doi.org/10.48550/arXiv.2505.12546
- Método e amostra (v6): técnica probabilística de extração com janela deslizante, aplicada a 200 livros do Books3 ("a torrented corpus of nearly 200,000 books") e 14 LLMs open-weight; "over 3000 experiments" (Abstract; Seção 1).
- Números-chave (Abstract, p. 1; Tabela da Seção 7): "most LLMs do not memorize most books either in whole or in part, but there are notable exceptions"; "Llama 3.1 70B entirely memorizes some books, like Harry Potter and the Sorcerer's Stone"; Harry Potter extraído do Llama 3.1 70B com pz ≥ τ: 90,89% (τ=1%), 75,44% (τ=10%), 43,26% (τ=50%); Llama 1: 25,48% / 15,00% / 4,40%; Pythia: 0,40% / 0,10% / 0,08%.
- Limitações declaradas (Seção de discussão/limitações; texto do PDF): "we only explore a limited set of open-weight models, and we only test 200 of the nearly 200,000 books in Books3"; resultados são limites inferiores ("we under-count memorization"); "We need to run more books to make general claims about overall memorization"; nota "Written April 2025".
- Status: Verificado na fonte original (PDF v6).

## 3. Can LLMs Hire Fairly? Racial Bias in Resume Screening
- Autores/veículo: Zhenyu Gao, Wenxi Jiang, Yutong Yan (CUHK Business School) | arXiv:2606.28978v1, 27/jun/2026 | Tipo: preprint, estudo empírico de auditoria (paired-resume); inclui resultado nulo e reversão de sinal
- Link: https://arxiv.org/abs/2606.28978 (PDF: https://arxiv.org/pdf/2606.28978) | DOI: https://doi.org/10.48550/arXiv.2606.28978
- Método e amostra: metodologia de pares de currículos de Kline, Rose e Walters (2022); 14 LLMs (GPT-3.5-turbo a modelos de 2026); 24.024 pares por modelo no eixo raça e 48.048 por modelo no eixo gênero (13 modelos), a partir de 6.007 vagas reais dos EUA (Revelio Labs); decisão "yes/no" para triagem telefônica, temperatura zero (Seção 1; Tabelas I e II).
- Números-chave (Abstract, p. 1; Tabela I, p. 14; Tabela II, p. 15): GPT-3.5-turbo: "+2.12 pp, significant at the 1% level" (pró-brancos); "Every model released in 2024 or after shows either a null gap or a significant pro-Black reversal (up to −3.01 pp)" (Llama-3.1-8B: −3,01 pp); gênero: GPT-3.5-turbo +1,92 pp (pró-homem); Claude 3 Haiku −5,80 pp; GPT-5.4-mini +0,11 pp (não significativo) em gênero e −0,14 pp (não significativo) em raça. Referência de campo citada: 1,6 pp (Kline, Rose e Walters, 2022).
- Limitações declaradas: o PDF não contém seção de limitações (busca por "limitation" no texto retorna apenas uma ocorrência na revisão de literatura); a discussão (p. 9-10) afirma que "neither the original pro-White bias nor its pro-Black reversal is desirable from a fairness standpoint"; desenho com prompt único de "HR hiring manager" e resposta de uma palavra (Seção 2).
- Status: Verificado na fonte original (PDF).

## 4. Gender and Positional Biases in LLM-Based Hiring Decisions: Evidence from Comparative CV/Résumé Evaluations
- Autores/veículo: David Rozado | arXiv:2505.17049 (v1 maio/2025); versão posterior indicada em busca como PeerJ Computer Science vol. 12, e3628 (2026) [NÃO VERIFICADO: página da PeerJ inacessível] | Tipo: preprint, estudo empírico (experimento com CVs sintéticos)
- Link: https://arxiv.org/abs/2505.17049 (PDF: https://arxiv.org/pdf/2505.17049) | DOI: https://doi.org/10.48550/arXiv.2505.17049
- Método e amostra: 22 LLMs; 70 profissões; 10 CVs sintéticos e 10 descrições de vaga por profissão; cada par de CVs (um nome masculino, outro feminino) apresentado duas vezes com nomes trocados; "30,800 models' decisions"; 0,4% de respostas inválidas excluídas (seção Results, Experiment 1).
- Números-chave (Abstract; Experiment 1, Experiment 2): "all LLMs consistently favored female-named candidates across 70 different professions"; mulheres selecionadas em 56,9% dos casos vs 43,1% dos homens (Cohen's h = 0,28; odds = 1,32, IC 95% [1,29; 1,35]); com campo explícito de gênero: 58,9% vs 41,1% (Cohen's h = 0,36; odds = 1,43); com identificadores neutros "Candidate A/B" e contrabalanceamento, "gender parity"; ao avaliar CVs isoladamente "the effect size was negligible"; maioria dos modelos mostrou "substantial positional bias" a favor do primeiro candidato.
- Limitações declaradas (seção Discussion): "synthetic nature of the CVs and job descriptions"; "the generalizability of the findings to actual hiring contexts may be constrained"; CVs de qualificação muito semelhante, o que "may not reflect the broader range of applicant qualifications".
- Status: Verificado na fonte original (PDF arXiv).

## 5. Social Group Bias in AI Finance
- Autores/veículo: Thomas R. Cook (Federal Reserve Bank of Kansas City), Sophia Kazinnik (Stanford) | arXiv:2506.17490v1, 20/jun/2025 (rascunho de 9/jun/2025) | Tipo: working paper/preprint com dados simulados (teste contrafactual em LLMs open-source)
- Link: https://arxiv.org/abs/2506.17490 (PDF: https://arxiv.org/pdf/2506.17490) | DOI: https://doi.org/10.48550/arXiv.2506.17490
- Método e amostra: tarefas de crédito hipotecário (taxa de juros recomendada e aprovação) com solicitantes simulados idênticos exceto raça; 5 LLMs locais (Llama 3.1 8B e 70B, Mistral v0.3, Command R, Command R+), temperatura zero; análise camada a camada e intervenção por "control vector" (Seções 3-5).
- Números-chave (Abstract; Tabela 3, p. 14): "significant race-based discrepancies, exceeding historically observed bias levels"; "control-vector intervention that effectively reduces racial disparities by up to 70% (33% on average)"; Tabela 3 (prompt simples): diferença média de juros 59 pb (Llama 3.1 8B), 13 pb (Llama 3.1 70B), 20 pb (Mistral), -97 pb (Command R, favorável ao solicitante negro), 10 pb (Command R+); comparação com 13,1 pb de Popick (2022); "(51% of cases)" de discrepância no experimento simples com Mistral.
- Limitações declaradas (final da Seção de conclusão, p. 36): "we focus solely on racial bias in a single application (credit decisions)"; "we evaluate only a handful of local LLMs"; "alternative models may behave differently"; ressalva institucional: opiniões não refletem as do FRB-KC.
- Status: Verificado na fonte original (PDF arXiv).

## 6. Generative AI in Equilibrium: Evidence from a Creative Goods Marketplace
- Autores/veículo: Samuel G. Goldberg (Stanford GSB), H. Tai Lam (UCLA Anderson) | Marketing Science Institute Working Paper Series, Report No. 25-129, 19/mai/2025 | Tipo: working paper, estudo empírico (diferenças-em-diferenças, plataforma de imagens de banco de imagens)
- Link: https://thearf-org-unified-admin.s3.amazonaws.com/MSI/2025/MSI_Report_25-129.pdf (publicação MSI/ARF; sem DOI localizado)
- Método e amostra: modelo teórico + diferenças-em-diferenças com mercados em nível de palavra-chave; em dez/2022 a plataforma permitiu entrada de imagens GenAI em alguns mercados e não em outros (grupo de controle); medidas de similaridade/variedade por embeddings de imagem (Seção 1, p. 3-6).
- Números-chave (Abstract p. 1-2; Introdução p. 6): "GenAI is a substitute for non-GenAI products and crowds out the production of non-GenAI content. Still, substantial GenAI firm entry leads to an increase in the quality and variety of produced and sold goods, expanding sales"; "the number of active firms per month increases by 88%, or about 940 additional firms. Meanwhile, non-GenAI firms exit the market at a rate of around 23%, or 230 firms per month"; aumento de imagens de ~78% (4.900 por mês), apesar de queda de ~800 imagens/mês de produção não-GenAI; mercados de nicho: "production tipping almost completely to GenAI". Os autores afirmam que os resultados "add empirical evidence to an ongoing debate over the use of copyrighted material in GenAI training".
- Limitações declaradas (Apêndice 8.1.4, p. 38): "we observe if an image is sold, but not precisely when it was sold" (hipótese simplificadora de venda no 1º mês); contexto de uma única plataforma de imagens de banco de imagens com preços fixos.
- Status: Verificado na fonte original (PDF).

## 7. Stanford AI Index Report 2026 — Capítulo 3 "Responsible AI"
- Autores/veículo: Stanford HAI (AI Index Steering Committee) | abril/2026 | Tipo: relatório institucional (compilação de dados e estudos de terceiros)
- Link: https://hai.stanford.edu/ai-index/2026-ai-index-report | PDF: https://hai.stanford.edu/assets/files/ai_index_report_2026.pdf
- Método e amostra: compilação de benchmarks, AI Incident Database, Foundation Model Transparency Index, pesquisas de organizações e índice GIRAI; capítulo cobre incidentes, benchmarks, governança de dados para privacidade (3.6) e viés/justiça (3.7).
- Números-chave (Chapter Highlights, p. 128; Seção 3.7, p. 155-157): "the AI Incident Database recording 362 in 2025, up from 233 in 2024"; "the average score dropped to 40 in 2025" no Foundation Model Transparency Index (após subir de 37 para 58 entre 2023 e 2024), com "Major gaps persist in disclosure around training data, compute resources, and post-deployment impact"; "the share of businesses with no responsible AI policies in place fell sharply from 24% to 11%"; "GDPR remains the most cited regulatory influence but slipped from 65% in 2024 to 60% in 2025"; sobre trade-offs: Kemmerzell e Schreiner (2024) — privacidade diferencial "improved privacy scores across all datasets but reduced explainability, fairness, and accuracy, with accuracy falling by up to 33 percentage points on some configurations" (Seção 3.10 "Tradeoffs Across RAI Dimensions", p. 170).
- Limitações declaradas (Seção 3.7, p. 155): "Fairness and bias are among the hardest-to-measure dimensions of responsible AI, in part because what counts as fair depends heavily on context"; relatório compila dados de terceiros.
- Status: Verificado na fonte original (PDF).

## 8. Template for the summary of training content of general-purpose AI models (Art. 53(1)(d) AI Act) e GPAI Code of Practice (capítulo Copyright)
- Autores/veículo: Comissão Europeia / AI Office (comunicado de imprensa "Commission presents template for General-Purpose AI model providers to summarise the data used to train their model") | 24/jul/2025 (última atualização 31/jul/2025); Code of Practice recebido em 10/jul/2025 | Tipo: ato regulatório (template adotado pela Comissão; código voluntário)
- Link: https://digital-strategy.ec.europa.eu/en/news/commission-presents-template-general-purpose-ai-model-providers-summarise-data-used-train-their | Página do Código: https://digital-strategy.ec.europa.eu/en/policies/ai-code-practice | Capítulo Copyright (versão final 10/jul/2025, site do Future of Life Institute, não oficial da UE): https://artificialintelligenceact.eu/en/cop-copyright/
- Fatos e consequência: os fornecedores de modelos de IA de uso geral devem publicar um resumo do conteúdo de treinamento segundo o template; "The public summary will provide a comprehensive overview of the data used to train a model, list main data collections and explain other sources used. This template will also assist parties with legitimate interests, such as copyright holders, in exercising their rights under Union law"; regras de GPAI aplicáveis a partir de 2/ago/2025; diretrizes sobre escopo publicadas em 18/jul/2025. Página do Código: processo com "nearly 1000 stakeholders"; consulta multi-stakeholder com "more than 430 responses" (sobre o template); código "a voluntary tool prepared by independent experts"; avaliado como adequado pela Comissão e pelo AI Board (trecho da linha do tempo da página: "Commission and AI Board approve the code via Adequacy Decisions"; página atualizada em 25/jun/2026).
- Limitações declaradas: o código é voluntário; o texto oficial do capítulo de Copyright (PDF oficial) não foi aberto, apenas a página de apresentação do FLI [NÃO VERIFICADO quanto ao conteúdo dos compromissos específicos de copyright].
- Status: Verificado na fonte original (páginas da Comissão Europeia).

## 9. AI Act — página oficial da Comissão: cronograma de aplicação e "AI Omnibus"
- Autores/veículo: Comissão Europeia, Shaping Europe's digital future, página "AI Act" | consultada em 09/nov/2026 | Tipo: ato regulatório (descrição oficial da aplicação do Regulamento e da alteração "AI Omnibus")
- Link: https://digital-strategy.ec.europa.eu/en/policies/regulatory-framework-ai
- Fatos e consequência (texto da página): "The AI Act entered into force on 1 August 2024 and became applicable on 2 August 2026, with some exceptions"; proibições e alfabetização em IA desde 2/fev/2025; "the governance rules and the obligations for GPAI models became applicable on 2 August 2025"; sistemas de alto risco do Anexo III (incluindo emprego, p. ex. "CV-sorting software for recruitment") estendidos para 2/dez/2027 e os do Anexo I para 2/ago/2028; o "AI Omnibus" foi adotado como proposta em 19/nov/2025, "political agreement was reached on 7 May 2026 and entered into force on 27 July 2026"; nova proibição (nono item) de sistemas de IA que gerem conteúdo sexualmente explícito não consensual ou CSAM ("nudification" apps) com vigência em dez/2026.
- Limitações declaradas: página descritiva; o texto legal final do Regulamento Omnibus não foi aberto (EUR-Lex bloqueado por desafio de WAF) [NÃO VERIFICADO quanto ao texto legal].
- Status: Verificado na fonte original (página oficial, conteúdo descritivo).

## 10. Regulamento (UE) 2024/1689 (AI Act), Art. 53 — obrigações dos fornecedores de modelos de IA de uso geral (política de copyright e resumo público dos dados de treinamento)
- Autores/veículo: Parlamento Europeu e Conselho da UE, Jornal Oficial (Regulamento (UE) 2024/1689) | publicado em 2024; obrigações do Art. 53 aplicáveis desde 2/ago/2025 (conforme página da Comissão, fonte 9) | Tipo: ato regulatório
- Link: https://eur-lex.europa.eu/eli/reg/2024/1689/oj/eng
- Fatos (texto do Art. 53(1), aberto no EUR-Lex): fornecedores de GPAI devem "(c) put in place a policy to comply with Union law on copyright and related rights, and in particular to identify and comply with, including through state-of-the-art technologies, a reservation of rights expressed pursuant to Article 4(3) of Directive (EU) 2019/790" e "(d) draw up and make publicly available a sufficiently detailed summary about the content used for training of the general-purpose AI model, according to a template provided by the AI Office"; Art. 53(2): a isenção para modelos open-source não se aplica a modelos com risco sistêmico; Art. 53(4): podem usar códigos de prática para demonstrar conformidade.
- Limitações declaradas: não aplicável (texto legal). Consequências sancionatórias do Art. 101 (multas a fornecedores de GPAI) não foram extraídas nesta busca [NÃO VERIFICADO].
- Status: Verificado na fonte original (EUR-Lex, texto integral).

## 11. Regulamento (UE) 2026/1744 (Digital Omnibus on AI), de 8 jul/2026
- Autores/veículo: Parlamento Europeu e Conselho da UE, Jornal Oficial série L, 24/jul/2026 | Tipo: ato regulatório (altera os Regulamentos (UE) 2024/1689, 2018/1139 e 2023/1230)
- Link: https://eur-lex.europa.eu/legal-content/EN/TXT/HTML/?uri=OJ:L_202601744
- Fatos (texto do Considerando 1-2 e novo Art. 4a): considerando que "The entry into application of its provisions is staggered, with all rules entering into application by 2 August 2027"; justificativa: "the delayed preparation of standards ... has resulted in a compliance burden that is heavier than expected"; novo Art. 4a "Processing of special categories of personal data for bias detection and correction": provedores de sistemas de alto risco "may exceptionally process special categories of personal data" na medida "strictly necessary" para detecção e correção de viés, com salvaguardas (inclusive exclusão dos dados "once the bias has been corrected or the personal data has reached the end of its retention period"); o §2 estende a possibilidade a outros provedores/implantadores, e "does not create any obligation to conduct such bias detection and correction".
- Limitações declaradas: não aplicável (texto legal). Datas exatas de aplicação dos prazos de alto risco (2/dez/2027 e 2/ago/2028) foram obtidas da página da Comissão (fonte 9), não conferidas artigo a artigo no Regulamento 2026/1744 [NÃO VERIFICADO no texto legal].
- Status: Verificado na fonte original (EUR-Lex, texto integral).

## 12. Case C-250/25, Like Company v Google Ireland Limited — pedido de decisão prejudicial (Budapest Környéki Törvényszék) e conclusões do Advogado-Geral
- Autores/veículo: Tribunal de Justiça da UE; Jornal Oficial C/2025/3039, 10/jun/2025 (pedido de 3/abr/2025) | Tipo: decisão/processo judicial em andamento (reenvio prejudicial)
- Link (OJ): https://eur-lex.europa.eu/eli/C/2025/3039/oj/eng
- Fatos (texto do OJ): 4 questões; Q1: se a exibição, nas respostas de um chatbot baseado em LLM, de texto parcialmente idêntico a páginas de editores de imprensa constitui comunicação ao público (Art. 15(1) Dir. 2019/790 e Art. 3(2) Dir. 2001/29); Q2: se "the process of training an LLM-based chatbot constitutes an instance of reproduction"; Q3: se essa reprodução se enquadra na exceção de TDM do "Article 4 of Directive 2019/790"; Q4: se a exibição em resposta a instrução do usuário constitui reprodução pelo prestador do serviço.
- Status processual (via resultados de busca, não aberto no original): conclusões do Advogado-Geral Szpunar divulgadas em 3/nov/2026 (não vinculantes); segundo resumos de imprensa, o AG propôs declarar inadmissíveis as duas questões sobre treinamento por falta de prova de que os artigos foram usados no treinamento, e concluiu que a reutilização em tempo real de publicações de imprensa por chatbots pode violar direitos de editores [NÃO VERIFICADO: opinião no site curia.europa.eu bloqueado]; acórdão do Tribunal ainda não emitido segundo as fontes consultadas (última movimentação encontrada: 3/nov/2026) [NÃO VERIFICADO].
- Limitações declaradas: reenvio prejudicial; conclusões do AG não vinculam o Tribunal.
- Status: Pedido (OJ) verificado na fonte original; conclusões do AG [NÃO VERIFICADO].

## 13. Acórdão do TJUE de 27/fev/2025, Processo C-203/22 (CK v Magistrat der Stadt Wien; Dun & Bradstreet Austria) — explicação da lógica de decisões automatizadas de scoring de crédito
- Autores/veículo: Tribunal de Justiça da UE (Primeira Secção) | 27/fev/2025 | Tipo: decisão judicial (IA preditiva, proteção de dados)
- Link: https://eur-lex.europa.eu/legal-content/EN/TXT/HTML/?uri=CELEX:62022CJ0203
- Fatos e consequência (dispositivo): o art. 15(1)(h) do RGPD "must be interpreted as meaning that, in the case of automated decision-making, including profiling ... the data subject may require the controller, as 'meaningful information about the logic involved', to explain, by means of relevant information and in a concise, transparent, intelligible and easily accessible form, the procedure and principles actually applied in order to use, by automated means, the personal data concerning that person with a view to obtaining a specific result, such as a credit profile"; quando o controlador alega dados de terceiros ou segredo comercial, "is required to provide the allegedly protected information to the competent supervisory authority or court, which must balance the rights and interests at issue".
- Limitações declaradas: decisão em reenvio prejudicial sobre scoring de crédito (IA preditiva), não sobre IA generativa.
- Status: Verificado na fonte original (EUR-Lex, texto integral).

## 14. Scrapers Selectively Respect robots.txt Directives: Evidence From a Large-Scale Empirical Study
- Autores/veículo: Taein Kim, Karstan Bock, Claire Luo, Amanda Liswood, Chloe Poroslay, Emily Wenger (Duke University) | arXiv:2505.21733 (v2 23/out/2025); ACM Internet Measurement Conference (IMC '25), 28-31/out/2025 | Tipo: estudo empírico revisado por pares (medição de tráfego web)
- Link: https://arxiv.org/abs/2505.21733 | DOI: https://doi.org/10.1145/3730567.3764471
- Método e amostra: logs anonimizados de 36 sites institucionais (~3,9 milhões de requisições externas) analisando 130 bots autodeclarados e anônimos durante 40 dias, mais experimentos controlados de robots.txt (Abstract; Seção 3).
- Números-chave (Abstract): "bots are less likely to comply with stricter robots.txt directives, and ... certain categories of bots, including AI search crawlers, rarely check robots.txt at all"; "relying on robots.txt to prevent unwanted scraping is risky". Apêndice (user agent spoofing): "Googlebot had a 0.65 compliance rate with the 30 second crawl delay in robots.txt" e "Amazonbot had a 0.96 compliance rate"; "Several other popular bots like GPT-Bot and bingbot had similar trends".
- Limitações declaradas (Seção 6): "only considered traffic from 36 websites owned by our institution"; segundo estudo "conducted on a single website"; "Both studies only capture a snapshot of bot behavior during a 45 day time window"; "Bot behavior will likely evolve over time".
- Status: Verificado na fonte original (PDF).

## 15. How Professional Visual Artists are Negotiating Generative AI in the Workplace
- Autores/veículo: Harry H. Jiang, Jordan Taylor, William Agnew (Carnegie Mellon University) | arXiv:2603.04537v2, 6/mar/2026; CHI EA '26 (13-17/abr/2026) | Tipo: estudo empírico (survey, autorrelato)
- Link: https://arxiv.org/abs/2603.04537 | DOI: https://doi.org/10.1145/3772363.3799003
- Método e amostra: survey com 378 artistas visuais profissionais verificados (Likert + campo aberto), com cinco seções (uso, atitudes, experiências no trabalho, impactos na carreira, demografia) (Seção 2).
- Números-chave (Figura 1, Figura 2, Seção de resultados): "85% of respondents never use generative AI in their work"; "99%" dizem não gostar de IA generativa (92% fortemente); renda diminuída por IA: 54% (neutro 43%); segurança no emprego/clientela: 75%; oportunidades de renda: 90%; "61% of respondents report disruption in employment or business".
- Limitações declaradas (Seção 4): maioria dos participantes nos EUA (218), Europa (80) ou Canadá (38); "possibility of sampling bias through recruitment strategies"; enquadramento do survey pode causar "over-representation of stronger and negative responses".
- Status: Verificado na fonte original (PDF).

## 16. Fairness Is Not Enough: Auditing Competence and Intersectional Bias in AI-powered Résumé Screening
- Autores/veículo: Kevin T. Webster (pesquisador independente) | arXiv:2507.11548 (jul/2025) | Tipo: preprint, estudo empírico de auditoria (oito plataformas comerciais de IA)
- Link: https://arxiv.org/abs/2507.11548 | DOI: https://doi.org/10.48550/arXiv.2507.11548
- Método e amostra: auditoria em duas partes de "eight widely used AI platforms" (13 variantes de modelo): Experimento 1 com currículos fictícios pareados (viés racial e de gênero, três cargos de colarinho branco); Experimento 2 de competência (incompatibilidade currículo-cargo e manipulação de palavras-chave).
- Números-chave (Abstract; Experimento 2a): "bias persists in context-dependent and intersectional forms"; "several models that appear relatively unbiased fail to distinguish relevant from irrelevant experience"; ω² de discernimento variando de 0,00 a 0,79 entre 13 variantes (ChatGPT-fast 0,79; Grok-fast 0,00).
- Limitações declaradas (Seção 5.1): "the audit was limited to three white-collar job roles"; resultados "may not generalize to other segments of the labor market"; variantes avançadas de Claude, Grok e Perplexity foram excluídas porque "daily usage limits on their free tiers made repeated experimental trials infeasible" (metodologia).
- Status: Verificado na fonte original (PDF). Autor independente, sem revisão por pares identificada [NÃO VERIFICADO quanto à publicação posterior].

## 17. Unintended Memorization of Sensitive Information in Fine-Tuned Language Models
- Autores/veículo: Marton Szep, Jorge Marin Ruiz, Georgios Kaissis, Paulina Seidl, Rüdiger von Eisenhart-Rothe, Florian Hinterwimmer, Daniel Rueckert (TUM; Imperial College London) | arXiv:2601.17480v1, 24/jan/2026 | Tipo: preprint, estudo empírico (privacidade/memorização de PII)
- Link: https://arxiv.org/abs/2601.17480 | DOI: https://doi.org/10.48550/arXiv.2601.17480
- Método e amostra: sondas controladas de extração de PII presente apenas nos inputs (não nos alvos) de modelos ajustados por QLoRA (até 12B parâmetros), com dados sintéticos multilíngues (financeiros) e dois corpora privados médicos; compara privacidade diferencial, "machine unlearning", regularização e alinhamento por preferência.
- Números-chave (Abstract): "post-training methods generally provide more consistent privacy–utility trade-offs, while differential privacy achieves strong reduction in leakage in specific settings, although it can introduce training instability" (o resumo não traz valores numéricos; tabelas de vazamento não extraídas nesta busca [NÃO VERIFICADO]).
- Limitações declaradas (seção Limitations): apenas ajuste fino eficiente (QLoRA) em LLMs "up to 12B parameters"; modelos maiores "may exhibit different memorization behaviors"; dependência de dados sintéticos e anotação semiautomática "may introduce bias".
- Status: Verificado na fonte original (PDF; resumo e limitações).

---

# Decisões judiciais e processos (documentos primários inacessíveis neste ambiente; dados abaixo vêm de resultados de busca na web, não de inteiro teor)

Observação geral: CourtListener (HTTP 403/401 e desafio de WAF), storage.courtlistener.com, govinfo.gov, copyright.gov, sites de tribunais dos EUA/Reino Unido/Alemanha/Índia/Itália, curia.europa.eu, EDPB, Garante e DPC irlandesa estavam bloqueados; não houve tentativa de contornar. Por isso os campos factuais abaixo estão [NÃO VERIFICADO] no nível do documento primário.

## 18. Bartz v. Anthropic PBC (N.D. Cal., No. 3:24-cv-05417) — ordem sobre fair use (23/jun/2025) e acordo de US$ 1,5 bi
- Autores/veículo: U.S. District Court, N.D. Cal. (Juiz William Alsup; após sua aposentadoria, Juíza Araceli Martínez-Olguín) | ordem de 23/jun/2025; aprovação final do acordo em 20/jul/2026 (segundo busca) | Tipo: decisão judicial + acordo coletivo
- Link: documento primário não acessado [NÃO VERIFICADO]; páginas secundárias consultadas via busca: https://news.bloomberglaw.com/ip-law/anthropic-authors-1-5-billion-deal-receives-final-approval ; https://authorsguild.org/news/court-grants-final-approval-anthropic-copyright-settlement/
- Fatos e consequência [NÃO VERIFICADO]: ordem de 23/jun/2025 — treinar o Claude com livros foi considerado fair use ("exceedingly transformative"); digitalização de livros comprados em papel também; mas "Anthropic had no entitlement to use pirated copies for its central library" e as cópias piratas seguiram para julgamento. Acordo: classe de proprietários de direitos de livros em versões LibGen/PiLiMi baixadas pela Anthropic, "Works List" de 482.460 obras; 440.490 obras (91,3%) reivindicadas até 16/abr/2026; ~US$ 3.000 a US$ 3.100 por obra (fontes divergem); honorários de ~US$ 101 milhões (cerca de 6,8% do fundo); liberação de reivindicações limitada a conduta passada até 25/ago/2025 e "explicitly does not release claims related to AI outputs or future conduct". Número do processo aparece como 4:24-cv-05417 em uma fonte e 3:24-cv-05417 em outra.
- Status processual na data da busca: acordo com aprovação final e sentença final (segundo resultados de busca); última movimentação encontrada: 20/jul/2026 [NÃO VERIFICADO].
- Limitações declaradas: não aplicável (decisão); Ahmed et al. (fonte 1, Seção 1) descrevem as duas decisões dos EUA (Bartz e Kadrey) segundo as quais os autores "did not demonstrate substantial extraction of training data" (Seção 1, p. 2).

## 19. Kadrey v. Meta Platforms, Inc. (N.D. Cal., No. 3:23-cv-03417) — fair use no treinamento do Llama (25/jun/2025) e reivindicações remanescentes de torrenting
- Autores/veículo: U.S. District Court, N.D. Cal. (Juiz Vince Chhabria) | 25/jun/2025 | Tipo: decisão judicial (julgamento sumário)
- Link: documento primário não acessado [NÃO VERIFICADO]; citação indicada em busca: 788 F. Supp. 3d 1028 (N.D. Cal. 2025) [NÃO VERIFICADO]
- Fatos e consequência [NÃO VERIFICADO]: julgamento sumário a favor da Meta sobre fair use no treinamento com livros; decisão "binds only these plaintiffs upon this record"; autores não apresentaram "meaningful evidence on market dilution"; juiz escreveu que "in most cases the answer will likely be yes" (treinamento sem licença seria ilícito) em dictum; reivindicação DMCA falhou porque fair use é defesa completa. Após a decisão: continuam as alegações sobre reprodução/distribuição por torrenting; quarta petição inicial emendada (6/abr/2026) com reivindicação de infração contributiva; ordem de agendamento de 27/mar/2026: audiência de julgamento sumário sobre torrenting somente em 25/fev/2027, fim da produção de provas periciais em 20/nov/2026 e petição inicial dos autores em 11/dez/2026 [NÃO VERIFICADO].
- Status processual na data da busca: em andamento (torrenting/distribuição); última movimentação encontrada: ordem de agendamento de 27/mar/2026 e petição de 6/abr/2026 [NÃO VERIFICADO].
- Limitações declaradas: decisão restrita às partes e ao registro dos autos (segundo resumos).

## 20. In re OpenAI, Inc. Copyright Infringement Litigation (S.D.N.Y., MDL No. 1:25-md-03143; inclui The New York Times Co. v. Microsoft Corp. et al., 1:23-cv-11195) — Juiz Sidney Stein
- Autores/veículo: U.S. District Court, S.D.N.Y. | decisões de mar-abr/2025 (moções de dismissal); 7/nov/2025 e 2/dez/2025 (logs); cross-motions de julgamento sumário em 4/set/2026 | Tipo: processo judicial em andamento
- Link: documento primário não acessado [NÃO VERIFICADO]; (Justia indexa Doc. 514 do processo 1:23-cv-11195, não aberto)
- Fatos [NÃO VERIFICADO]: Juiz Stein negou em grande parte as moções para dispensar a ação (26/mar/2025 ou 4/abr/2025 — fontes divergem), mantendo infração direta e contributiva e descartando parte das alegações DMCA; ordem de preservação de 13/mai/2025 (dados de output do ChatGPT), mantida em 26/jun/2025 e modificada em 26/set/2025; em 7/nov/2025 a juíza Ona Wang ordenou a produção de 20 milhões de logs de consumidores ChatGPT "de-identificados" (o NYT pedira 120 milhões), reconsideração negada em 2/dez/2025; cross-motions de julgamento sumário sobre fair use protocoladas em 4/set/2026, oposições em 23/out/2026, réplicas devidas em 6/nov/2026.
- Status processual na data da busca: fase de julgamento sumário, sem decisão sobre fair use; sem data de audiência; última movimentação encontrada: réplicas devidas em 6/nov/2026 [NÃO VERIFICADO].
- Limitações declaradas: fontes são trackers e imprensa; datas variam.

## 21. Thomson Reuters Enterprise Centre GmbH v. ROSS Intelligence Inc. (3d Cir., apelação interlocutória) — primeiro tribunal de apelação sobre treinamento de IA e fair use
- Autores/veículo: U.S. Court of Appeals for the Third Circuit (Juízes Restrepo, Montgomery-Reeves e Bove; opinião da Juíza Montgomery-Reeves); decisão de primeira instância (D. Del., Juiz Bibas) de fev/2025 | decisão do 3º Circuito em 29/set/2026 (segundo busca) | Tipo: decisão judicial
- Link: documento primário não acessado [NÃO VERIFICADO]; análises citadas em busca: https://www.lawnext.com/2026/10/no-more-than-an-ordinary-copyright-case-3rd-circuit-unseals-its-opinion-in-thomson-reuters-case-against-ross.html
- Fatos [NÃO VERIFICADO]: 3º Circuito confirmou o julgamento sumário parcial a favor da Thomson Reuters: headnotes do Westlaw protegíveis por copyright e uso pela ROSS para treinar ferramenta de pesquisa jurídica "not fair use"; uso descrito como "minimally transformative, at best"; fatores 1, 3 e 4 contra fair use, apenas o fator 2 levemente a favor da ROSS; a corte diferenciou expressamente disputas de IA generativa; o caso volta à corte distrital. A ROSS é sistema de IA não generativa (IA preditiva/busca).
- Status processual na data da busca: apelação decidida; retorno à primeira instância; última movimentação encontrada: 29/set/2026 [NÃO VERIFICADO]. Resumo da ABA em busca (set/2026) ainda registrava a decisão como pendente após argumento oral em 11/jun/2026 (divergência de data entre fontes).
- Limitações declaradas: apelação interlocutória; escopo restrito ao uso não generativo.

## 22. Getty Images (US) Inc. & Ors v Stability AI Ltd [2025] EWHC 2863 (Ch) (High Court of England and Wales)
- Autores/veículo: High Court (Chancery Division), Mrs Justice Joanna Smith | 4/nov/2025 | Tipo: decisão judicial
- Link: documento primário não acessado [NÃO VERIFICADO]; resumos indexados: https://www.mishcon.com/news/getty-images-v-stability-ai-unpacking-the-high-courts-judgment ; https://www.lw.com/en/insights/getty-images-v-stability-ai-english-high-court-rejects-secondary-copyright-claim
- Fatos e consequência [NÃO VERIFICADO]: pesos do modelo Stable Diffusion podem ser "articles" mesmo sendo intangíveis, mas não são "infringing copies" (CDPA s.27), pois nunca armazenaram ou reproduziram as imagens da Getty; reivindicação de infração secundária rejeitada; Getty prevaleceu apenas em ponto restrito de marcas (marcas d'água em saídas, descritas como históricas e extremamente limitadas); acessar modelo hospedado remotamente de fora do Reino Unido não configura importação; "passing off" não decidido. Em 16/dez/2025 foi concedida permissão para apelar da improcedência da infração secundária.
- Status processual na data da busca: apelação com permissão concedida; não encontrei decisão do Court of Appeal (fontes até jul/2026); última movimentação encontrada: 16/dez/2025 (permissão) [NÃO VERIFICADO].
- Limitações declaradas: não aplicável.

## 23. GEMA v OpenAI (Landgericht München I, Az. 42 O 14139/24) — memorização e reprodução de letras de música
- Autores/veículo: LG München I | 11/nov/2025 | Tipo: decisão judicial
- Link: documento primário não acessado [NÃO VERIFICADO]; indexado em busca: https://intellectual-property-helpdesk.ec.europa.eu/news-events/news/german-court-rules-favour-music-rights-management-organisation-against-openai-nyt-vs-openai-dispute-2025-11-14_en ; https://www.nortonrosefulbright.com/en/knowledge/publications/656613b2/germany-delivers-landmark-copyright-ruling-against-openai-what-it-means-for-ai-and-ip
- Fatos e consequência [NÃO VERIFICADO]: tribunal considerou que a memorização das letras no modelo e sua reprodução pelo ChatGPT são, cada uma, reprodução relevante para o direito autoral, exigindo licença; condenou a OpenAI a cessar, informar e indenizar; nove letras alemãs (incl. "Atemlos" e "Männer"); defesa de TDM (§ 44b UrhG) não foi acolhida; Ahmed et al. (fonte 1, Seção 1) descrevem a decisão como "currently under appeal" e como achando que saídas extraídas e a memorização no modelo podem ser cópias infratoras.
- Status processual na data da busca: OpenAI apelou (8/dez/2025, OLG München, Az. 6 U 3662/25 e segundo uma fonte); sem decisão de segunda instância encontrada; última movimentação encontrada: apelação de 8/dez/2025 [NÃO VERIFICADO]. Uma fonte de busca também menciona decisão da mesma câmara contra a Suno (Az. 42 O 763/25; data citada em outra fonte: 31/jul/2026) [NÃO VERIFICADO].
- Limitações declaradas: não aplicável.

## 24. Mobley v. Workday, Inc. (N.D. Cal., No. 3:23-cv-00770) — viés algorítmico na triagem de candidatos (idade, raça, deficiência)
- Autores/veículo: U.S. District Court, N.D. Cal. (Juíza Rita Lin) | certificação preliminar de coletiva ADEA em mai/2025; decisão sobre leis da Califórnia em jun/2026 | Tipo: processo judicial em andamento
- Link: documento primário não acessado [NÃO VERIFICADO]; indexados em busca: https://www.hklaw.com/en/insights/publications/2025/05/federal-court-allows-collective-action-lawsuit-over-alleged ; https://www.fisherphillips.com/en/insights/insights/discrimination-lawsuit-over-workdays-ai-hiring-tools-can-proceed-as-class-action-6-things
- Fatos [NÃO VERIFICADO]: em mai/2025 a juíza concedeu certificação preliminar de ação coletiva nacional por idade (candidatos com mais de 40 anos) com opt-in; um agregador cita prazo de opt-in em 7/mar/2026; em jun/2026 (16/jun ou 22/jun, fontes divergem) a juíza rejeitou o pedido da Workday para dispensar reivindicações da lei da Califórnia (FEHA), com base em Raines (Supreme Court of California, 2023), que admite responsabilidade direta de agentes que atuam por empregadores. Gao et al. (fonte 3) também citam a decisão de jun/2026 (Seção 1).
- Status processual na data da busca: em andamento; sem certificação final, acordo ou data de julgamento encontrados; última movimentação encontrada: decisão de jun/2026 [NÃO VERIFICADO].
- Limitações declaradas: não aplicável.

## 25. Disney Enterprises, Inc. & Universal City Studios v. Midjourney, Inc. (C.D. Cal.)
- Autores/veículo: U.S. District Court, C.D. Cal. | ajuizamento em jun/2025; decisão de discovery em jun/2026 | Tipo: processo judicial em andamento
- Link: documento primário não acessado [NÃO VERIFICADO]; indexado em busca: https://www.law360.com/cases/6849920dbaefe0fe54b77b08
- Fatos [NÃO VERIFICADO]: estúdios (Disney, Universal; Warner Bros. descrita em fontes posteriores como coautora) acusam a Midjourney de infração por treinamento e saídas; em jun/2026 um juiz magistrado limitou a discovery sobre o uso de IA pelos próprios estúdios a usos "consumer facing"; em 4/jul/2026 a Midjourney pediu revisão ao Juiz John Kronstadt. Número de processo não confirmado.
- Status processual na data da busca: em andamento; sem decisão sobre moção de dismissal ou mérito encontrada; última movimentação encontrada: pedido de 4/jul/2026 [NÃO VERIFICADO].
- Limitações declaradas: não aplicável.

## 26. Advance Local Media LLC et al. v. Cohere Inc. (S.D.N.Y., No. 25-cv-1305-CM) — decisão sobre dismissal parcial (13/nov/2025)
- Autores/veículo: U.S. District Court, S.D.N.Y. (Juíza Colleen McMahon) | 13/nov/2025 (Doc. 59) | Tipo: decisão judicial (moção de dismissal parcial negada)
- Link: documento primário não acessado [NÃO VERIFICADO]; PDF indexado em busca: https://www.newsmediaalliance.org/wp-content/uploads/2025/11/Doc-59-Decision-and-Order-Denying-Partial-Motion-to-Dismiss.pdf
- Fatos [NÃO VERIFICADO]: negada integralmente a moção da Cohere; teoria de "substitutive summaries" mantida; infração direta e secundária, marca e falsa designação de origem plausivelmente alegadas; juíza "need not and will not evaluate the merits of Cohere's nominative fair use argument on a motion to dismiss"; cronograma posterior prevê moções de julgamento sumário em 18/dez/2026.
- Status processual na data da busca: em andamento (fase de discovery/pré-julgamento sumário); última movimentação encontrada: ordem de cronograma citada em busca [NÃO VERIFICADO].
- Limitações declaradas: decisão em fase de pleadings, sem mérito sobre fair use.

## 27. ANI Media Pvt. Ltd. v. OpenAI OpCo LLC (Delhi High Court) — indeferimento de liminar (24/jul/2026)
- Autores/veículo: High Court of Delhi (Juiz Amit Bansal) | 24/jul/2026 (versão corrigida em 27/jul/2026) | Tipo: decisão judicial (medida liminar)
- Link: documento primário não acessado [NÃO VERIFICADO]; PDF indexado em busca: https://www.scobserver.in/wp-content/uploads/2026/08/DHC-OpenAI-v-ANI-Judgement.pdf
- Fatos [NÃO VERIFICADO]: liminar negada; o tribunal aceitou jurisdição (sede da ANI em Delhi e serviços oferecidos na Índia; Seção 62(2) do Copyright Act e Seção 20 do CPC); concluiu, em análise prima facie, que o treinamento com obras armazenadas estaria coberto por exceção (Seção 52(1)(a)(i) segundo um comentário); não identificou caso prima facie de infração nas saídas; a corte citou Bartz, Kadrey e Authors Guild v. Google; a decisão "will have no bearing" sobre o resultado final.
- Status processual na data da busca: ação principal (ajuizada em nov/2024) pendente de julgamento; última movimentação encontrada: 27/jul/2026 [NÃO VERIFICADO].
- Limitações declaradas: decisão interlocutória que não decide o mérito.

## 28. Concord Music Group et al. / UMG et al. v. Anthropic PBC (N.D. Cal.) — letras de música (ações de 2023 e jan/2026)
- Autores/veículo: U.S. District Court, N.D. Cal. (Juíza Eumi Lee) | 2025-2026 | Tipo: processo judicial em andamento
- Link: documento primário não acessado [NÃO VERIFICADO]; indexado em busca: https://www.musicbusinessworldwide.com/infringement-on-a-massive-scale-umg-concord-and-abkco-ask-court-to-rule-against-ai-company-anthropic-ahead-of-trial
- Fatos [NÃO VERIFICADO]: ação original de 2023 sobre letras de "at least 500 songs"; segunda ação (jan/2026) sobre mais de 20.000 músicas e pedido de mais de US$ 3 bilhões por alegado torrenting de bibliotecas piratas; moções de fair use ouvidas, sem decisão em 21/out/2026; outra fonte cita audiência em 4/nov/2026 com pedido de nova rodada de memoriais; uma fonte relata dismissal da reivindicação de infração direta contra o CEO (data/forma incertas); BMG teria ajuizado terceira ação em mar/2026 (493 composições).
- Status processual na data da busca: em andamento, sem decisão de fair use; última movimentação encontrada: audiência de 4/nov/2026 (segundo uma fonte) [NÃO VERIFICADO].
- Limitações declaradas: não aplicável.

## 29. Andersen v. Stability AI Ltd. et al. (N.D. Cal., Juiz William Orrick)
- Autores/veículo: U.S. District Court, N.D. Cal. | decisão de jul-ago/2024 (dismissal parcial); cronograma atualizado em fev/2026 | Tipo: processo judicial em andamento
- Link: documento primário não acessado [NÃO VERIFICADO]; indexado em busca: https://chatgptiseatingtheworld.com/2026/02/03/sarah-andersens-copyright-lawsuit-the-1st-filed-v-ai-companies-gets-pushed-back-again-at-her-request/
- Fatos [NÃO VERIFICADO]: em 2024 o juiz manteve a reivindicação de Andersen contra a Stability AI (treinamento do Stable Diffusion) e rejeitou, com permissão de emenda, as alegações contra Midjourney e DeviantArt; em 12/jan/2026 os autores pediram autorização para uma terceira petição emendada; em fev/2026 foi concedido adiamento de cerca de três meses e audiência de julgamento sumário listada para 17/fev/2027; réus em 2026: Stability AI, DeviantArt, Midjourney e Runway AI.
- Status processual na data da busca: em andamento (discovery); sem decisão de julgamento sumário encontrada; última movimentação encontrada: fev/2026 [NÃO VERIFICADO].
- Limitações declaradas: não aplicável.

## 30. Tribunale di Roma, sentença de 18/mar/2026: anulação da sanção de EUR 15 milhões do Garante contra a OpenAI (provv. n. 755 de 2/nov/2024; decisão do Garante de 20/dez/2024 divulgada)
- Autores/veículo: Tribunale di Roma (Itália) | 18/mar/2026 (segundo maioria das fontes; uma fonte indica 1/mar/2026) | Tipo: decisão judicial (proteção de dados e IA generativa)
- Link: documento primário não acessado [NÃO VERIFICADO]; PDF indexado em busca: https://dei.web.uniroma1.it/sites/default/files/allegati/2026-05/Trib_Roma_OpenAI_Garante_2026.pdf
- Fatos e consequência [NÃO VERIFICADO]: o tribunal anulou integralmente a sanção de EUR 15 milhões e a campanha de informação ordenadas pelo Garante, por falta de competência do Garante após o estabelecimento da OpenAI na Irlanda em 2024 (regra do balcão único do RGPD); o mérito das violações (base legal para treinamento e transparência) não foi examinado; R.G. 4785/2025 (e "sentenza n. 4153" segundo outra fonte). A decisão original do Garante (dez/2024) apontou treinamento "without having an adequate legal basis" e violação do princípio de transparência.
- Status processual na data da busca: não encontrei informação sobre recurso ao tribunal superior; última movimentação encontrada: 18/mar/2026 [NÃO VERIFICADO].
- Limitações declaradas: não aplicável.

## 31. OLG Köln, Beschluss de 23/mai/2025 (Az. 15 UKl 2/25) — Verbraucherzentrale NRW v. Meta Platforms Ireland: treinamento de IA com dados de usuários
- Autores/veículo: Oberlandesgericht Köln | 23/mai/2025 | Tipo: decisão judicial (medida cautelar)
- Link: documento primário não acessado [NÃO VERIFICADO]; indexado em busca: https://www.verbraucherzentrale.nrw/pressemeldungen/digitale-welt/eilantrag-der-verbraucherzentrale-nrw-gegen-meta-abgelehnt-107469
- Fatos e consequência [NÃO VERIFICADO]: pedido cautelar da associação de consumidores contra o treinamento de IA da Meta com dados públicos de Facebook/Instagram foi negado; o tribunal tratou o treinamento como interesse legítimo (Art. 6(1)(f) RGPD) e, em análise sumária, não viu violação do DMA (a questão do Art. 5(2) DMA fica reservada ao processo principal); associação defendia consentimento (opt-in) em vez de opt-out; sem recurso cabível contra a decisão cautelar; Meta ativou o opt-out a partir de 27/mai/2025.
- Status processual na data da busca: sem informação sobre processo principal; última movimentação encontrada: 23/mai/2025 [NÃO VERIFICADO].
- Limitações declaradas: decisão sumária.

## 32. Irish Data Protection Commission, "AI Insights Report" (set/2026) e acompanhamento de Meta, X e LinkedIn
- Autores/veículo: Data Protection Commission (Irlanda) | set/2026 | Tipo: relatório institucional de autoridade de proteção de dados
- Link: documento primário não acessado [NÃO VERIFICADO]; URL indexada em busca: https://www.dataprotection.ie/sites/default/files/uploads/2026-09/DPC-AI-Insights-Report-AC.pdf
- Fatos [NÃO VERIFICADO]: relatório sobre supervisão de IA entre 2021 e 2025; a maioria das interações resultou em recomendações; "any training of a new AI model with personal data will require a Data Protection Impact Assessment" (segundo resumo); recomendações a Meta sobre filtragem e desidentificação antes do treinamento teriam sido seguidas; inquérito sobre uso de dados pessoais da UE/EEE pela X para treinar o Grok e declaração do DPC de que não aprovou o uso de dados da LinkedIn para treinamento (data da declaração não verificada); não encontrei multa ou decisão final em 2026 contra Meta, X ou LinkedIn por treinamento de IA.
- Status: relatório publicado; sem decisões finais encontradas; última movimentação encontrada: set/2026 [NÃO VERIFICADO].
- Limitações declaradas: não aplicável.

## 33. The Labor Market Effect of Generative Artificial Intelligence on Artists (resultado nulo/modesto em ganhos de artistas)
- Autores/veículo: Christos Makridis [autoria conforme resumo de busca] | SSRN 5992400; CESifo Working Paper 12368 (2025) | Tipo: working paper (event study; dados do Census ACS 2017-2024 segundo busca)
- Link: https://papers.ssrn.com/abstract=5992400 (bloqueado, HTTP 403); https://www.ifo.de/en/cesifo/publications/2025/working-paper/labor-market-effect-generative-artificial-intelligence-artists (inacessível) [NÃO VERIFICADO]
- Método e amostra [NÃO VERIFICADO]: event study comparando ocupações artísticas mais e menos expostas, 2017-2024.
- Números-chave: não obtidos [NÃO VERIFICADO]. Resumos de terceiros (Gallup, via busca) dizem que tendências de ganhos de ocupações mais expostas parecem semelhantes às menos expostas, com pequeno ganho em 2023 que diminuiu em 2024 [NÃO VERIFICADO].
- Limitações declaradas: não obtidas [NÃO VERIFICADO].

---

# Buscas realizadas / lacunas

Termos usados (WebSearch): "Bartz v. Anthropic settlement final approval"; "Kadrey v. Meta summary judgment fair use"; "Kadrey v. Meta 2026 torrenting"; "In re OpenAI copyright litigation Judge Stein 2026"; "Thomson Reuters v. Ross Third Circuit"; "Getty Images v Stability AI High Court appeal"; "GEMA v OpenAI Landgericht München"; "Like Company v Google C-250/25 Advocate General"; "Disney Universal v. Midjourney 2026"; "Concord UMG v. Anthropic"; "Andersen v. Stability AI 2026"; "ANI v OpenAI Delhi High Court"; "Advance Local v. Cohere"; "Mobley v. Workday"; "EU AI Act GPAI Code of Practice copyright template"; "Garante OpenAI sanzione / Tribunale di Roma annullata"; "OLG Köln Meta KI-Training"; "Irish DPC AI training decision 2026"; "NYT v OpenAI preservation order logs"; "arXiv extracting copyrighted books production LLMs"; "arXiv memorized pieces of books open-weight"; "arXiv LLM resume screening bias audit"; "Rozado gender positional biases hiring"; "NBER/Fed LLM discrimination mortgage"; "NIST AI 100-2 E2025"; "arXiv PII memorization extraction"; "data provenance consent robots.txt"; "diffusion models memorization copyright"; "robots.txt compliance AI crawlers"; "Stanford AI Index 2026 responsible AI"; "generative AI artists earnings labor market".

Domínios bloqueados ou inacessíveis (HTTP 000/403/401/desafio de WAF): www.courtlistener.com (403; API 401 sem credencial; desafio WAF em páginas de opinião), storage.courtlistener.com, www.govinfo.gov, www.copyright.gov, www.supremecourt.gov, cdn.ca9.uscourts.gov, www.cand.uscourts.gov, law.justia.com, curia.europa.eu, www.edpb.europa.eu, www.garanteprivacy.it, www.dataprotection.ie, www.gov.br (ANPD), www.cnil.fr, www.ico.org.uk, www.judiciary.uk, www.bailii.org, www.landgericht-muenchen.de, www.bundesgerichtshof.de, dejure.org, openjur.de, www.law360.com, news.bloomberglaw.com, www.nytimes.com, www.wipo.int, papers.ssrn.com (403), www.oecd.org (403), www.imf.org (403), www.science.org (403), www.congress.gov (403), academic.oup.com (403), aiindex.stanford.edu (usei hai.stanford.edu, acessível), nvlpubs.nist.gov / csrc.nist.gov (NIST AI 100-2 E2025 não aberto), peerj.com, econpapers.repec.org, ifo.de, e dezenas de sites de escritórios de advocacia e imprensa jurídica. WebFetch falhou com ENOTFOUND; usei curl com o CA bundle do ambiente. Domínios acessíveis e usados: arxiv.org, nber.org, hai.stanford.edu, digital-strategy.ec.europa.eu, eur-lex.europa.eu (somente URLs /eli/.../eng e /legal-content/EN/TXT/HTML/?uri=...), artificialintelligenceact.eu, thearf-org-unified-admin.s3.amazonaws.com (MSI).

Não encontrado / não verificado:
- Inteiro teor de todas as decisões judiciais dos EUA, Reino Unido, Alemanha, Índia e Itália (fontes 18-31): apenas resumos de busca.
- Conclusões do Advogado-Geral em C-250/25 (3/nov/2026): somente via resultados de busca.
- US Copyright Office, relatório sobre IA generativa e treinamento (Parte 3, pré-publicação de mai/2025): domínio bloqueado; não consultado.
- EDPB (Parecer 28/2024 e posteriores), Garante (provimento original), ANPD (Brasil), CNIL, ICO: domínios bloqueados.
- Decisões sobre "Digital Omnibus" de proteção de dados/GDPR (treinamento de IA com interesse legítimo): não pesquisadas nesta rodada.
- UMG/Udio/Suno (acordos de licenciamento) e Doe v. GitHub (9º Circuito): não localizados em resultados abertos.
- Estudos NBER/SSRN 2025-2026 sobre dano de mercado de direitos autorais em IA: SSRN bloqueado; NBER w32106 (Gans, 2024) tem versão publicada no Journal of Law and Economics 69(1) em 2026 segundo busca, não aberta [NÃO VERIFICADO].
- NIST AI 100-2 E2025 (taxonomia de ataques à privacidade): domínio bloqueado.
- Resultados numéricos de extração para Gemini 2.5 Pro e Grok 3 além dos citados no abstract de Ahmed et al.: consultados apenas no resumo.
