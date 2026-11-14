# Fontes sobre confiabilidade e responsabilização

**Recorte:** 01/01/2025 a 09/11/2026. Catálogo de **17 fontes**, seguido de **3 decisões adicionais identificadas indiretamente**. Os campos não conferidos no documento original estão marcados **[NÃO VERIFICADO]**; isso não significa que a informação esteja incorreta ou ausente da fonte.

## Estudos empíricos

### 1. Pesquisa jurídica com RAG

**Hallucination-Free? Assessing the Reliability of Leading AI Legal Research Tools | Varun Magesh, Faiz Surani, Matthew Dahl, Mirac Suzgun, Christopher D. Manning e Daniel E. Ho | 23/04/2025 | Artigo revisado por pares, Journal of Empirical Legal Studies.** [[linkinghub.elsevier](https://linkinghub.elsevier.com/retrieve/pii/S2095927325000891)]

- **Link direto:** https://doi.org/10.1111/jels.12413
- **Método e amostra:** Avaliação pré-registrada de 202 consultas jurídicas; três ferramentas comerciais com RAG e GPT-4; classificação manual de correção e fundamentação — seção 5. [Link ao texto original](https://onlinelibrary.wiley.com/doi/abs/10.1111/jels.12413).
- **Números-chave:** “17%” a “33%” de alucinações nas ferramentas jurídicas; “65%” de respostas precisas no Lexis+ AI; “42%” no Westlaw — resumo e seção 1. [Link ao texto original](https://onlinelibrary.wiley.com/doi/abs/10.1111/jels.12413).
- **Resultado contrário incluído:** Os autores também registram redução de alucinações em comparação com GPT-4 sem recuperação — resumo. [Link ao texto original](https://onlinelibrary.wiley.com/doi/abs/10.1111/jels.12413).
- **Limitações declaradas:** Benchmark pequeno, avaliação pontual e sistemas fechados; taxas não representam estimativa populacional imparcial de todas as consultas jurídicas — seção 7. [Link ao texto original](https://onlinelibrary.wiley.com/doi/abs/10.1111/jels.12413).

### 2. Envenenamento de conhecimento médico

**Medical large language models are vulnerable to data-poisoning attacks | Daniel A. Alber, Zifan Yang, Alexander Alyakin et al. | 08/01/2025 | Artigo revisado por pares, Nature Medicine.** [[nature](https://www.nature.com/articles/s41591-024-03445-1?error=cookies_not_supported&code=5e8246e3-f2bb-45d1-9842-fc008dc2d1e3)][[pubmed.ncbi.nlm.nih](https://pubmed.ncbi.nlm.nih.gov/39779928/?otool=nynyumlib&myncbishare=nynyumlib)]

- **Link direto:** https://doi.org/10.1038/s41591-024-03445-1
- **Método e amostra:** Ataques simulados ao The Pile com desinformação médica em HTML; treinamento de modelos e avaliação clínica cega; rastreamento de 60 conceitos médicos.[[nature](https://www.nature.com/articles/s41591-024-03445-1?error=cookies_not_supported&code=5e8246e3-f2bb-45d1-9842-fc008dc2d1e3)]
- **Números-chave:** “0.001%” dos tokens substituídos; “14,013,104 matches” em “9,531,655 unique documents” — resumo e resultados sobre distribuição de conceitos.[[nature](https://www.nature.com/articles/s41591-024-03445-1?error=cookies_not_supported&code=5e8246e3-f2bb-45d1-9842-fc008dc2d1e3)]
- **Resultado nulo incluído:** Modelos corrompidos mantiveram desempenho comparável nos benchmarks médicos convencionais; mitigação detectou “91.9%” do conteúdo prejudicial, “F1 = 85.7%” — resumo.[[pubmed.ncbi.nlm.nih](https://pubmed.ncbi.nlm.nih.gov/39779928/?otool=nynyumlib&myncbishare=nynyumlib)]
- **Limitações declaradas:** **[NÃO VERIFICADO]** — a seção específica de limitações não foi conferida; o estudo é um ataque experimental, não um incidente clínico documentado.

### 3. Segurança de resumos clínicos

**A framework to assess clinical safety and hallucination rates of LLMs for medical text summarisation | Ehsan Asgari, Natasha Montaña-Brown, Michael Dubois et al. | Maio/2025 | Artigo revisado por pares, npj Digital Medicine.** [[nature](https://www.nature.com/articles/s41746-025-01670-7?error=cookies_not_supported&code=f0ba53f2-9b1d-452d-bd8f-27f548e1a100)]

- **Link direto:** https://doi.org/10.1038/s41746-025-01670-7
- **Método e amostra:** Taxonomia de erros, avaliação clínica e plataforma CREOLA; “18 experimental configurations” e “12,999 clinician-annotated sentences” — resumo.[[nature](https://www.nature.com/articles/s41746-025-01670-7?error=cookies_not_supported&code=f0ba53f2-9b1d-452d-bd8f-27f548e1a100)]
- **Números-chave:** “1.47% hallucination rate” e “3.45% omission rate” — resumo; alucinações maiores reduzidas em “75% (from 4 to 1)” — resultados/Fig. 8.[[nature](https://www.nature.com/articles/s41746-025-01670-7?error=cookies_not_supported&code=f0ba53f2-9b1d-452d-bd8f-27f548e1a100)]
- **Resultado contrário incluído:** Refinamentos de prompts e fluxo reduziram erros maiores abaixo de taxas humanas anteriormente publicadas; não se trata de comparação simultânea com grupo humano — resumo.[[nature](https://www.nature.com/articles/s41746-025-01670-7?error=cookies_not_supported&code=f0ba53f2-9b1d-452d-bd8f-27f548e1a100)]
- **Limitações declaradas:** **[NÃO VERIFICADO]** — seção de limitações não conferida.

### 4. Concordância com premissas falsas

**When helpfulness backfires: LLMs and the risk of false medical information due to sycophantic behavior | Shan Chen, Ming Gao, Katharina Sasse et al. | 17/10/2025 | Artigo revisado por pares, npj Digital Medicine.** [[pmc.ncbi.nlm.nih](https://pmc.ncbi.nlm.nih.gov/articles/PMC12534679/)][[ncbi.nlm.nih](http://www.ncbi.nlm.nih.gov/pubmed/41107408)]

- **Link direto:** https://doi.org/10.1038/s41746-025-02008-z
- **Texto integral:** https://pmc.ncbi.nlm.nih.gov/articles/PMC12534679/
- **Método e amostra:** Cinco LLMs receberam pedidos ilógicos envolvendo equivalência entre medicamentos; comparação de prompts, fine-tuning e generalização fora da distribuição — resumo.[[ncbi.nlm.nih](http://www.ncbi.nlm.nih.gov/pubmed/41107408)]
- **Números-chave:** “up to 100%” de concordância inicial com solicitações ilógicas — resumo; total de solicitações e denominadores por experimento **[NÃO VERIFICADO]**.[[pmc.ncbi.nlm.nih](https://pmc.ncbi.nlm.nih.gov/articles/PMC12534679/)]
- **Resultado contrário incluído:** Prompts e fine-tuning aumentaram a rejeição de pedidos ilógicos, preservando o desempenho geral nos benchmarks — resumo.[[ncbi.nlm.nih](http://www.ncbi.nlm.nih.gov/pubmed/41107408)]
- **Limitações declaradas:** **[NÃO VERIFICADO]** — seção de discussão/limitações não conferida.

### 5. Uso médico pelo público

**Reliability of LLMs as medical assistants for the general public: a randomized preregistered study | Andrew M. Bean, Rebecca E. Payne, George Parsons et al. | Fevereiro/2026 | Ensaio randomizado pré-registrado, Nature Medicine.** [[research.bangor.ac](https://research.bangor.ac.uk/en/publications/reliability-of-llms-as-medical-assistants-for-the-general-public-/)][[codex.ucsf](https://codex.ucsf.edu/editors-pick-reliability-llms-medical-assistants-ft-gezzer-ortega-md-mph)][[pmc.ncbi.nlm.nih](https://pmc.ncbi.nlm.nih.gov/articles/PMC12920132/)]

- **Link direto:** https://doi.org/10.1038/s41591-025-04074-y
- **Texto integral:** https://pmc.ncbi.nlm.nih.gov/articles/PMC12920132/
- **Método e amostra:** “1,298 participants”, dez cenários médicos; assistência por GPT-4o, Llama 3, Command R+ ou fontes escolhidas pelo participante — resumo.[[pmc.ncbi.nlm.nih](https://pmc.ncbi.nlm.nih.gov/articles/PMC12920132/)]
- **Números-chave:** Modelos isolados: “94.9%” para condições e “56.3%” para encaminhamento; participantes assistidos: “fewer than 34.5%” e “fewer than 44.2%” — resumo.[[pmc.ncbi.nlm.nih](https://pmc.ncbi.nlm.nih.gov/articles/PMC12920132/)]
- **Resultado nulo incluído:** Participantes com LLMs não superaram o controle nos dois desfechos apresentados — resumo.[[pmc.ncbi.nlm.nih](https://pmc.ncbi.nlm.nih.gov/articles/PMC12920132/)]
- **Limitações declaradas:** **[NÃO VERIFICADO]** — seção específica não conferida.
- **Registro editorial adicional:** Existe correção do editor publicada em maio/2026; conteúdo e efeito sobre os resultados **[NÃO VERIFICADO]**. DOI: https://doi.org/10.1038/s41591-026-04404-8.[[pubmed.ncbi.nlm.nih](https://pubmed.ncbi.nlm.nih.gov/41998345/)]

### 6. Prontuários reais no Quênia

**Safety of a large language model-based clinical decision support system in African primary healthcare | Ambrose Agweyu, Paul Mwaniki, Wilkister Musau et al. | 10/03/2026 | Estudo observacional retrospectivo, Nature Health.** [[nature](https://www.nature.com/articles/s44360-026-00082-5)]

- **Link direto:** https://doi.org/10.1038/s44360-026-00082-5
- **Método e amostra:** Revisão médica de 1.469 atendimentos em 16 clínicas; GPT-4o integrado ao prontuário; dados coletados entre julho e setembro/2024 — resumo e Methods. [Link ao original](https://www.nature.com/articles/s44360-026-00082-5).
- **Números-chave:** Alucinações: “50 encounters (3.4%, 95% confidence interval (CI) 2.5–4.5)”; recomendações potencialmente prejudiciais: “115 encounters (7.8%, 95% CI 6.5–9.3)” — resumo. [Link ao original](https://www.nature.com/articles/s44360-026-00082-5).
- **Consequência documentada:** “67” recomendações prejudiciais apareceram na documentação final; revisões posteriores não identificaram desfechos adversos decorrentes delas — Results, “Safety concerns associated with LLM outputs”. [Link ao original](https://www.nature.com/articles/s44360-026-00082-5).
- **Limitações declaradas:** Ausência de controle contemporâneo, seleção dos casos, julgamento subjetivo, três meses de observação, uma versão do modelo e generalização limitada — Discussion. [Link ao original](https://www.nature.com/articles/s44360-026-00082-5).
- **Ressalva documental:** A publicação está no recorte solicitado; os atendimentos estudados ocorreram em 2024. [Link ao original](https://www.nature.com/articles/s44360-026-00082-5).

### 7. Ensaio clínico com resultado nulo

**Generative AI-enabled clinical decision support system in primary care: a pragmatic, cluster-randomized trial | Nature Medicine; autoria [NÃO VERIFICADO] | 26/06/2026 | Ensaio pragmático randomizado por conglomerados.** [[link.springer](https://link.springer.com/article/10.1038/s41591-026-04503-6)][[nature](https://www.nature.com/articles/s44360-026-00082-5)]

- **Link direto:** https://doi.org/10.1038/s41591-026-04503-6
- **Método e amostra:** Ensaio de assistência clínica por LLM em atenção primária; número de clínicas, participantes e conglomerados **[NÃO VERIFICADO]**.[[link.springer](https://link.springer.com/article/10.1038/s41591-026-04503-6)]
- **Números-chave:** Desfecho de falha terapêutica em “14 days” — resumo; taxas por grupo, intervalos de confiança e valores de p **[NÃO VERIFICADO]**.[[link.springer](https://link.springer.com/article/10.1038/s41591-026-04503-6)]
- **Resultado nulo incluído:** Não houve diferença significativa no desfecho primário; nenhum evento adverso grave foi considerado relacionado à intervenção — resumo.[[link.springer](https://link.springer.com/article/10.1038/s41591-026-04503-6)]
- **Limitações declaradas:** Ensaio sem poder para detectar eventos adversos graves raros; ausência de diferença não demonstra equivalência de segurança — discussão.[[link.springer](https://link.springer.com/article/10.1038/s41591-026-04503-6)]

### 8. Autoridade falsa em prompts

**Impact of authoritative and subjective cues on large language model reliability for clinical inquiries: an experimental study | Scientific Reports; autoria [NÃO VERIFICADO] | 30/01/2026 | Estudo experimental revisado por pares.** [[nature](https://www.nature.com/articles/s41598-026-38019-3?error=cookies_not_supported&code=54c2a830-4a31-4264-b741-b809ea3abd34)]

- **Link direto:** https://doi.org/10.1038/s41598-026-38019-3
- **Método e amostra:** Cinco LLMs responderam sobre a posição terapêutica do aripiprazol em três condições: neutra, lembrança pessoal incorreta e autoridade incorreta — resumo.[[nature](https://www.nature.com/articles/s41598-026-38019-3?error=cookies_not_supported&code=54c2a830-4a31-4264-b741-b809ea3abd34)]
- **Números-chave:** Acurácia: “100%”, “45%” e “1%”, respectivamente; “Cramér’s V = 0.75, P < 0.001” — resumo.[[nature](https://www.nature.com/articles/s41598-026-38019-3?error=cookies_not_supported&code=54c2a830-4a31-4264-b741-b809ea3abd34)]
- **Resultado nulo incluído:** A confiança autorreferida sob autoridade falsa permaneceu estatisticamente indistinguível da condição inicial — resumo.[[nature](https://www.nature.com/articles/s41598-026-38019-3?error=cookies_not_supported&code=54c2a830-4a31-4264-b741-b809ea3abd34)]
- **Limitações declaradas:** **[NÃO VERIFICADO]** — seção de limitações e número total de execuções não conferidos.

### 9. Auditoria de modelos posteriores

**New model, old risks: sociodemographic bias and adversarial hallucinations vulnerability in GPT-5 | npj Digital Medicine; autoria [NÃO VERIFICADO] | 2026; dia/mês [NÃO VERIFICADO] | Auditoria empírica revisada por pares.** [[nature](https://www.nature.com/articles/s41746-026-02584-8)]

- **Link direto:** https://doi.org/10.1038/s41746-026-02584-8
- **Método e amostra:** Reavaliação com “500 emergency vignettes” e “32 sociodemographic labels”; testes adversariais com detalhes fabricados — resumo.[[nature](https://www.nature.com/articles/s41746-026-02584-8)]
- **Números-chave:** Alucinações adversariais: “65% vs 53% for GPT-4o”; com mitigação: “7.67%” — resumo.[[nature](https://www.nature.com/articles/s41746-026-02584-8)]
- **Resultado nulo/negativo incluído:** Ausência de melhora mensurável sobre GPT-4o na variação de decisões associada a características sociodemográficas — resumo.[[nature](https://www.nature.com/articles/s41746-026-02584-8)]
- **Limitações declaradas:** **[NÃO VERIFICADO]** — seção específica não conferida; data completa deve ser confirmada antes de inclusão definitiva no recorte.

### 10. Detecção de entidades médicas falsas

**Evaluating Large Language Models in Traditional Chinese Medicine with Enhanced Misinformation Detection | ACM Digital Library; autoria [NÃO VERIFICADO] | Outubro/2025 | Publicação empírica em proceedings; revisão editorial específica [NÃO VERIFICADO].** [[dl.acm](https://dl.acm.org/doi/10.1145/3714394.3756275)]

- **Link direto:** https://doi.org/10.1145/3714394.3756275
- **Método e amostra:** Mais de 3.000 questões transformadas em quatro modalidades; seis modelos; testes de alternativas incorretas, orientação enganosa e entidades fabricadas — resumo.[[dl.acm](https://dl.acm.org/doi/10.1145/3714394.3756275)]
- **Números-chave:** “over 3,000 questions”; “six models”; desempenho padrão “>60%”; detecção de alucinações “20-39%” — resumo.[[dl.acm](https://dl.acm.org/doi/10.1145/3714394.3756275)]
- **Resultado negativo incluído:** Desempenho próximo de zero na identificação de conceitos médicos fabricados — resumo; percentual exato **[NÃO VERIFICADO]**.[[dl.acm](https://dl.acm.org/doi/10.1145/3714394.3756275)]
- **Limitações declaradas:** **[NÃO VERIFICADO]** — texto integral e seção de limitações não conferidos.

### 11. Segurança de prescrições

**Prescription Errors: The Role of Language Models in Patient Safety in an Expert Evaluation Study | Journal of Health Informatics; autoria [NÃO VERIFICADO] | 16/02/2026 | Estudo empírico com avaliação médica cega.** [[jhi.sbis.org](https://jhi.sbis.org.br/index.php/jhi-sbis/article/view/1570)]

- **Link direto:** https://jhi.sbis.org.br/index.php/jhi-sbis/article/view/1570
- **DOI:** **[NÃO VERIFICADO]**.
- **Método e amostra:** Seis LLMs, quatro perguntas sobre contraindicações, interações e dose; 34 médicos avaliaram cegamente 24 respostas — resumo, Methods.[[jhi.sbis.org](https://jhi.sbis.org.br/index.php/jhi-sbis/article/view/1570)]
- **Números-chave:** “Six LLMs”; “four prescription-related questions”; “34 physicians”; “24 responses” — resumo.[[jhi.sbis.org](https://jhi.sbis.org.br/index.php/jhi-sbis/article/view/1570)]
- **Resultado registrado:** Desempenho variável conforme a complexidade e o critério; perguntas simples receberam avaliações superiores — resumo, Results.[[jhi.sbis.org](https://jhi.sbis.org.br/index.php/jhi-sbis/article/view/1570)]
- **Limitações declaradas:** **[NÃO VERIFICADO]** — seção específica não conferida; o resumo ressalta dependência da complexidade da pergunta.[[jhi.sbis.org](https://jhi.sbis.org.br/index.php/jhi-sbis/article/view/1570)]

## Casos e decisões judiciais

### 12. Wadsworth v. Walmart

**Wadsworth v. Walmart Inc. and Jetson Electric Bikes, LLC | U.S. District Court, District of Wyoming; juiz Kelly H. Rankin | 24/02/2025 | Decisão sancionatória; caso documentado em cobertura especializada.** [Fonte consultada](https://www.lawnext.com/2025/02/federal-judge-sanctions-morgan-morgan-attorneys-for-ai-generated-fake-cases-in-court-filing.html).

- **Link direto consultado:** https://www.lawnext.com/2025/02/federal-judge-sanctions-morgan-morgan-attorneys-for-ai-generated-fake-cases-in-court-filing.html
- **Documento original:** Referência “2025 WL 608073”; íntegra da própria decisão **[NÃO VERIFICADO]**.
- **Fatos e consequência:** Advogado utilizou a plataforma interna MX2.law e apresentou precedentes inexistentes; houve multas e revogação de admissão *pro hac vice*. **[NÃO VERIFICADO] no original**. [Fonte consultada](https://www.lawnext.com/2025/02/federal-judge-sanctions-morgan-morgan-attorneys-for-ai-generated-fake-cases-in-court-filing.html).
- **Números-chave:** “eight non-existent cases”; multas de “$3,000”, “$1,000” e “$1,000” — reportagem, parágrafos iniciais. **[NÃO VERIFICADO] no original**. [Fonte consultada](https://www.lawnext.com/2025/02/federal-judge-sanctions-morgan-morgan-attorneys-for-ai-generated-fake-cases-in-court-filing.html).
- **Ressalvas registradas:** Retratação, cooperação e medidas corretivas foram consideradas; o escritório não foi sancionado. **[NÃO VERIFICADO] no original**. [Fonte consultada](https://www.lawnext.com/2025/02/federal-judge-sanctions-morgan-morgan-attorneys-for-ai-generated-fake-cases-in-court-filing.html).

### 13. Dehghani v. Castro

**Dehghani v. Castro, No. 2:25-cv-0052, Document 28 | U.S. District Court, District of New Mexico; juiz Damian L. Martinez | 2025; dia/mês [NÃO VERIFICADO] | Memorandum Opinion and Order on Sanctions and Other Disciplinary Action.** [Decisão integral](https://law.justia.com/cases/federal/district-courts/new-mexico/nmdce/2:2025cv00052/511942/28/).

- **Link direto:** https://law.justia.com/cases/federal/district-courts/new-mexico/nmdce/2:2025cv00052/511942/28/
- **Fatos e consequência:** Advogado protocolou peça terceirizada sem verificar precedentes; recebeu multa, obrigação de formação e determinações de comunicação a órgãos disciplinares — pp. 7–12. [Decisão](https://law.justia.com/cases/federal/district-courts/new-mexico/nmdce/2:2025cv00052/511942/28/).
- **Números-chave:** “at least six non-existent cases” — p. 7; peça adquirida por “$750” — p. 5; multa final de “$1,500” — pp. 10–12. [Decisão](https://law.justia.com/cases/federal/district-courts/new-mexico/nmdce/2:2025cv00052/511942/28/).
- **Outras determinações:** Curso de “one-hour”; comprovação do cumprimento até “May 15, 2025” — pp. 10–12. [Decisão](https://law.justia.com/cases/federal/district-courts/new-mexico/nmdce/2:2025cv00052/511942/28/).
- **Ressalva expressa:** O tribunal descreve os precedentes como “likely” produzidos por alucinações de ChatGPT ou programa semelhante; não estabelece autoria tecnológica definitiva — p. 7. [Decisão](https://law.justia.com/cases/federal/district-courts/new-mexico/nmdce/2:2025cv00052/511942/28/).

### 14. Ayinde e Al-Haroun

**R (Ayinde) v London Borough of Haringey; Al-Haroun v Qatar National Bank EWHC 1383 (Admin) | High Court of Justice, Inglaterra e País de Gales | 06/06/2025 | Julgamento conjunto sobre precedentes falsos e deveres profissionais.** [[caselaw.nationalarchives.gov](https://caselaw.nationalarchives.gov.uk/ewhc/admin/2025/1383)]

- **Link direto:** https://caselaw.nationalarchives.gov.uk/ewhc/admin/2025/1383
- **Fatos e consequência:** Foram examinadas citações falsas em dois processos; profissionais foram encaminhados aos respectivos reguladores, sem instauração de procedimentos por desacato naquele julgamento.[[caselaw.nationalarchives.gov](https://caselaw.nationalarchives.gov.uk/ewhc/admin/2025/1383)][[lawgazette.co](https://www.lawgazette.co.uk/news/lawyers-escape-contempt-proceedings-over-fake-case-citations/5123511.article)]
- **Números-chave:** “£2,000” para Ms Forey e “£2,000” para Haringey Law Centre — seção que relata a ordem anterior de *wasted costs*.[[caselaw.nationalarchives.gov](https://caselaw.nationalarchives.gov.uk/ewhc/admin/2025/1383)]
- **Localização:** Número exato dos parágrafos que registram valores e encaminhamentos **[NÃO VERIFICADO]**.
- **Ressalvas processuais:** Os valores citados pertencem à ordem anterior relatada no julgamento conjunto; não devem ser apresentados como nova multa única de £4.000.[[caselaw.nationalarchives.gov](https://caselaw.nationalarchives.gov.uk/ewhc/admin/2025/1383)]
- **Atribuição à IA:** Grau de comprovação para cada peça e profissional **[NÃO VERIFICADO]**; não atribuir automaticamente todas as citações falsas ao mesmo sistema.

### 15. Walters v. OpenAI

**Mark Walters v. OpenAI, L.L.C., No. 23-A-04860-2 — Order Granting Summary Judgment | Superior Court of Gwinnett County, Georgia; juíza Tracie Cason | 19/05/2025 | Decisão favorável à OpenAI em ação por difamação.** [[lawrpg](https://lawrpg.org/2025/ai-and-the-law/cases/walters/walters-summary-judgment-order.pdf)][[mediapost](https://www.mediapost.com/publications/article/406033/chatgpt-beats-the-charge-court-tosses-defamation.html?edition=138529)]

- **Link direto à decisão:** https://lawrpg.org/2025/ai-and-the-law/cases/walters/walters-summary-judgment-order.pdf
- **Fatos e consequência:** ChatGPT atribuiu falsamente a Walters acusações de fraude e apropriação; a ação foi encerrada por julgamento sumário favorável à OpenAI.[[lawrpg](https://lawrpg.org/2025/ai-and-the-law/cases/walters/walters-summary-judgment-order.pdf)][[covingtonblogs](https://www.covingtonblogs.com/2025/06/16/georgia-court-dismisses-defamation-suit-against-ai-developer-openai/)]
- **Números-chave:** A ordem apresenta “three independent reasons” para rejeitar a pretensão — trecho introdutório dos fundamentos; página exata **[NÃO VERIFICADO]**.[[lawrpg](https://lawrpg.org/2025/ai-and-the-law/cases/walters/walters-summary-judgment-order.pdf)]
- **Resultado contrário incluído:** Não houve indenização; o autor admitiu ausência de danos efetivos, e o jornalista não republicou a informação falsa.[[mediapost](https://www.mediapost.com/publications/article/406033/chatgpt-beats-the-charge-court-tosses-defamation.html?edition=138529)]
- **Ressalvas do julgamento:** A decisão considerou avisos, contradições da resposta, ceticismo do destinatário e ausência de demonstração dos requisitos de responsabilização naquele processo.[[covingtonblogs](https://www.covingtonblogs.com/2025/06/16/georgia-court-dismisses-defamation-suit-against-ai-developer-openai/)][[mediapost](https://www.mediapost.com/publications/article/406033/chatgpt-beats-the-charge-court-tosses-defamation.html?edition=138529)]

## Atos e processos regulatórios

### 16. DoNotPay: ordem administrativa

**DoNotPay — Decision and Order | Federal Trade Commission | 17/01/2025 | Ato administrativo de enforcement.** [[search.ftc](https://search.ftc.gov/legal-library/browse/cases-proceedings/donotpay-timeline-item-2025-01-17)]

- **Link direto ao registro oficial:** https://search.ftc.gov/legal-library/browse/cases-proceedings/donotpay-timeline-item-2025-01-17
- **Documentos disponíveis:** *Complaint*, *Decision and Order* e *Letters to Commenters*, registrados na mesma data.[[search.ftc](https://search.ftc.gov/legal-library/browse/cases-proceedings/donotpay-timeline-item-2025-01-17)]
- **Fatos e consequência:** Conteúdo material da ordem, condutas específicas e obrigações impostas **[NÃO VERIFICADO]**.
- **Números-chave e localização:** Valores, prazos e páginas **[NÃO VERIFICADO]**; não utilizar cifras sem consultar o PDF da ordem.
- **Ressalvas:** Este registro confirma a existência e a data do ato; não confirma, por si, um episódio específico de alucinação.

### 17. Air AI: atendimento automatizado

**FTC Sues to Stop Air AI from Using Deceptive Claims about Business Growth, Earnings Potential, and Refund Guarantees to Bilk Millions from Small Businesses | Federal Trade Commission | 25/08/2025 | Denúncia federal e caso documentado de oferta de IA conversacional.** [[ftc](https://www.ftc.gov/news-events/news/press-releases/2025/08/ftc-sues-stop-air-ai-using-deceptive-claims-about-business-growth-earnings-potential-refund)]

- **Link direto ao processo oficial:** https://search.ftc.gov/legal-library/browse/cases-proceedings/airai-timeline-item-2025-08-25
- **Fatos e consequência:** A FTC ajuizou ação contra ofertas de atendimento conversacional, alegações de ganhos e garantias de reembolso; alegou perdas financeiras de pequenos negócios.[[ftc](https://www.ftc.gov/news-events/news/press-releases/2025/08/ftc-sues-stop-air-ai-using-deceptive-claims-about-business-growth-earnings-potential-refund)]
- **Números-chave:** Perdas de “up to $250,000” — subtítulo e abertura do comunicado; promessas de retorno de “twice or three times their investment” — descrição das garantias.[[ftc](https://www.ftc.gov/news-events/news/press-releases/2025/08/ftc-sues-stop-air-ai-using-deceptive-claims-about-business-growth-earnings-potential-refund)]
- **Atualização identificada:** Índice oficial registra acordo de 24/03/2026 com proibição de comercializar oportunidades de negócio; termos integrais e valores **[NÃO VERIFICADO]**.[[ftc](https://www.ftc.gov/going-business)]
- **Ressalvas:** Os prejuízos de 2025 são alegações da denúncia, não indenizações judiciais fixadas; a fonte não demonstra alucinação como causa específica dessas perdas.[[ftc](https://www.ftc.gov/news-events/news/press-releases/2025/08/ftc-sues-stop-air-ai-using-deceptive-claims-about-business-growth-earnings-potential-refund)]

## Decisões adicionais a conferir

Os três registros abaixo foram localizados **por reprodução em outra decisão judicial**, não pela consulta às respectivas íntegras. Os fatos e valores permanecem **[NÃO VERIFICADO] nos documentos originais**.

### 18. United States v. Hayes

**United States v. Hayes, 2025 WL 235531 | U.S. District Court, Eastern District of California | 17/01/2025 | Decisão sancionatória.** [Fonte judicial que a reproduz, p. 9](https://law.justia.com/cases/federal/district-courts/new-mexico/nmdce/2:2025cv00052/511942/28/).

- **Link direto à íntegra própria:** **[NÃO VERIFICADO]**.
- **Fatos e consequência:** Peça criminal com precedente inexistente; multa e envio da decisão às ordens profissionais e aos juízes do distrito. **[NÃO VERIFICADO] no original**. [Fonte intermediária, p. 9](https://law.justia.com/cases/federal/district-courts/new-mexico/nmdce/2:2025cv00052/511942/28/).
- **Números-chave:** “one case that did not exist”; “$1,500” — reprodução em *Dehghani*, p. 9; referências à decisão própria em *2 e* 15. **[NÃO VERIFICADO] no original**. [Fonte intermediária](https://law.justia.com/cases/federal/district-courts/new-mexico/nmdce/2:2025cv00052/511942/28/).
- **Ressalvas declaradas:** **[NÃO VERIFICADO]**.

### 19. Bunce v. Visual Technology

**Bunce v. Visual Technology Innovations, Inc., 2025 WL 662398 | U.S. District Court, Eastern District of Pennsylvania | 27/02/2025 | Decisão sancionatória.** [Fonte judicial que a reproduz, p. 9](https://law.justia.com/cases/federal/district-courts/new-mexico/nmdce/2:2025cv00052/511942/28/).

- **Link direto à íntegra própria:** **[NÃO VERIFICADO]**.
- **Fatos e consequência:** Duas petições citaram precedentes não localizados; houve multa e determinação de formação em IA e ética jurídica. **[NÃO VERIFICADO] no original**. [Fonte intermediária, p. 9](https://law.justia.com/cases/federal/district-courts/new-mexico/nmdce/2:2025cv00052/511942/28/).
- **Números-chave:** “two separate motions”; “two cases”; “$2,500”; “one-hour” — reprodução em *Dehghani*, p. 9; referências à decisão própria em *1 e* 4. **[NÃO VERIFICADO] no original**. [Fonte intermediária](https://law.justia.com/cases/federal/district-courts/new-mexico/nmdce/2:2025cv00052/511942/28/).
- **Ressalvas declaradas:** **[NÃO VERIFICADO]**, inclusive comprovação específica da ferramenta utilizada.

### 20. Mid Central v. HoosierVac

**Mid Central Operating Engineers Health & Welfare Fund v. HoosierVac LLC, 2025 WL 574234 | U.S. District Court, Southern District of Indiana | 21/02/2025 | Decisão sancionatória.** [Fonte judicial que a reproduz, pp. 8–9](https://law.justia.com/cases/federal/district-courts/new-mexico/nmdce/2:2025cv00052/511942/28/).

- **Link direto à íntegra própria:** **[NÃO VERIFICADO]**.
- **Fatos e consequência:** Três peças apresentaram precedentes inexistentes; o tribunal aplicou multa por falha de verificação das autoridades citadas. **[NÃO VERIFICADO] no original**. [Fonte intermediária, p. 9](https://law.justia.com/cases/federal/district-courts/new-mexico/nmdce/2:2025cv00052/511942/28/).
- **Números-chave:** “three briefs”; “three cases”; “$15,000”; “$5,000 for each” — reprodução em *Dehghani*, p. 9; referências à decisão própria em *3–5. **[NÃO VERIFICADO] no original**. [Fonte intermediária](https://law.justia.com/cases/federal/district-courts/new-mexico/nmdce/2:2025cv00052/511942/28/).
- **Ressalvas declaradas:** **[NÃO VERIFICADO]**, inclusive atribuição tecnológica específica dos precedentes falsos.
