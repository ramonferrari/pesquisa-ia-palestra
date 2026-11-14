**Levantamento parcial: 7 documentos originais consultados e 4 fontes adicionais com verificação incompleta. Não foi possível atingir o mínimo de 15 fontes verificadas; as lacunas estão marcadas como [NÃO VERIFICADO].**

Recorte de publicação: **01/01/2025 a 10/11/2026**. As fichas abaixo apenas registram fontes, métodos, dados e limitações, sem análise ou conclusão.

## Documentos originais consultados

### 1. Mercados de IA — OECD

**Developments in Artificial Intelligence markets: New indicators based on model characteristics, prices and providers | Christophe André, Manuel Bétin, Peter Gal e Paul Peltier | 17/06/2025 | Working paper institucional, OECD Artificial Intelligence Papers, n.º 37.** [Registro original e DOI](https://doi.org/10.1787/9302bf46-en).

- **Link direto:** https://doi.org/10.1787/9302bf46-en
- **Método e amostra:** coleta internacional de características, desempenho e preços de modelos generativos, desenvolvedores, provedores de nuvem e aplicações downstream; cobertura dos dois anos anteriores à publicação. Quantidade de observações e critérios detalhados de inclusão: **[NÃO VERIFICADO]**, pois o PDF integral não foi examinado. ([Original](https://www.oecd.org/en/publications/developments-in-artificial-intelligence-markets-new-indicators-based-on-model-characteristics-prices-and-providers_9302bf46-en.html), seção “Abstract”.)
- **Números-chave:** **[NÃO VERIFICADO]**. O resumo consultado não apresenta as estimativas numéricas do estudo; não foram importados números de resumos secundários.
- **Resultado contrário registrado pelos autores:** redução dos preços ajustados pela qualidade e crescimento da quantidade de participantes e modelos. ([Original](https://www.oecd.org/en/publications/developments-in-artificial-intelligence-markets-new-indicators-based-on-model-characteristics-prices-and-providers_9302bf46-en.html), seção “Abstract”.)
- **Limitações declaradas:** **[NÃO VERIFICADO]**. O resumo menciona gargalos em dados, computação e competências, mas não permite verificar as limitações metodológicas declaradas no documento integral.

### 2. Preços e fornecedores — OECD

**Artificial Intelligence markets: Recent developments and competition issues | OECD | 10/07/2026 | Policy brief institucional com atualização empírica.** [Original e DOI](https://doi.org/10.1787/d531d73f-en).

- **Link direto:** https://doi.org/10.1787/d531d73f-en
- **Método e amostra:** atualização dos indicadores de André et al. com dados da Artificial Analysis; fronteira preço–desempenho e índice de preços ajustados pela qualidade. Universo e quantidade total de observações: **[NÃO VERIFICADO]**. ([Original](https://oecd.org/en/publications/artificial-intelligence-markets_d531d73f-en/full-report.html), figuras 1–2 e respectivas notas.)
- **Números-chave:** desenvolvedores de modelos de linguagem: **“9 in January 2024”** e **“47 in April 2026”**; modelos texto–texto ativos: **“22 to 453”**; desenvolvedores na fronteira econômica: **“2 to 8”**. Localização: seção “Why competition in AI markets matters for the economy?”. ([Original](https://oecd.org/en/publications/artificial-intelligence-markets_d531d73f-en/full-report.html).)
- **Resultado contrário registrado pelos autores:** o índice agregado de preços de modelos texto–texto caiu **“nearly 80% between January 2024 and April 2026”**. Localização: texto associado à figura 2. ([Original](https://oecd.org/en/publications/artificial-intelligence-markets_d531d73f-en/full-report.html).)
- **Limitações declaradas:** os autores registram dificuldade para obter participações de mercado; a qualidade utiliza um índice ponderado de benchmarks; a nota da figura 3 esclarece que capacidade em MW não mede diretamente poder computacional. ([Original](https://oecd.org/en/publications/artificial-intelligence-markets_d531d73f-en/full-report.html), texto anterior à figura 1 e notas das figuras 1 e 3.)

### 3. Energia de agentes — KAIST

**The Cost of Dynamic Reasoning: Demystifying AI Agents and Test-Time Scaling from an AI Infrastructure Perspective | Jiin Kim, Byeongjun Shin, Jinha Chung e Minsoo Rhu | 04/06/2025, versão 1 | Preprint arXiv com experimentos.** [Original](https://arxiv.org/html/2506.04301v1).

- **Link direto:** https://arxiv.org/html/2506.04301v1
- **Método e amostra:** cinco configurações — CoT, ReAct, Reflexion, LATS e LLMCompiler —; HotpotQA, WebShop, MATH, HumanEval e baseline ShareGPT; Llama-3.1-8B e 70B; GPUs A100 de 40 GB; infraestrutura vLLM. Na exploração de configurações da seção V-B, **50 perguntas por configuração**. ([Original](https://arxiv.org/html/2506.04301v1), seção III, tabelas I–II e seção V-B.)
- **Números-chave:** **“9.2 times more”** chamadas ao LLM, em média, para agentes com ferramentas versus CoT; LATS: **“71.0 LLM calls per request”**. Localização: seção IV-A, figura 4. ([Original](https://arxiv.org/html/2506.04301v1).)
- **Números-chave de energia:** tabela III, modelo 70B: ShareGPT, **“2.55 Wh/query”**; Reflexion, **“348.41 Wh/query”**; LATS, **“158.48 Wh/query”**. São resultados das configurações experimentais apresentadas, não médias de produtos comerciais. ([Original](https://arxiv.org/html/2506.04301v1), tabela III.)
- **Resultado de redução de custo registrado:** prefix caching reduziu a latência de prefill em **“58.6%”**, em média, e a latência de inferência ponta a ponta em **“15.7%”**. ([Original](https://arxiv.org/html/2506.04301v1), seção IV-B, figuras 10–11.)
- **Limitações declaradas:** algumas combinações agente–benchmark foram excluídas por inadequação; as projeções energéticas não incluem CPU, memória, rede, armazenamento ou refrigeração, e não incorporam batching das requisições. ([Original](https://arxiv.org/html/2506.04301v1), seção III e seção VI.)

### 4. Energia de reasoning — Harvard

**The Energy Cost of Reasoning: Analyzing Energy Usage in LLMs with Test-time Compute | Yunho Jin, Gu-Yeon Wei e David Brooks | 2025; data exata [NÃO VERIFICADO] | Preprint arXiv com experimentos.** [Original](https://arxiv.org/html/2505.14733v1).

- **Link direto:** https://arxiv.org/html/2505.14733v1
- **Método e amostra:** Qwen2.5 de **1.5B, 7B, 14B e 32B** parâmetros; três condições — baseline, majority vote e reasoning tokens —; **12 benchmarks**; **10 repetições**, batch **16**, comprimento máximo **32768**, Bfloat16; medição de potência por NVML em A100. ([Original](https://arxiv.org/html/2505.14733v1), seção 3, tabela 1 e início da seção 4.)
- **Números-chave:** reasoning tokens consumiram, em média, **“3.66×, 10.4×, and 1.08×”** a energia do baseline em matemática, código e senso comum, respectivamente; máximo de **“97.48×”** no HumanEval com modelo 7B. ([Original](https://arxiv.org/html/2505.14733v1), seção 4.1, “Normalized Energy”.)
- **Resultado contrário registrado:** em código, passar do baseline 1.5B ao baseline 7B aumentou a acurácia em **“16.8%”** e reduziu a energia por consulta em **“40.1%”**. ([Original](https://arxiv.org/html/2505.14733v1), seção 4.1, “Accuracy vs Energy per Query”.)
- **Resultado negativo registrado:** em senso comum, o baseline 1.5B superou as configurações com reasoning tokens de 1.5B e 7B; os autores descrevem desempenho limitado ou adverso nesse grupo de tarefas. ([Original](https://arxiv.org/html/2505.14733v1), seção 4.1.)
- **Limitações declaradas:** somente energia operacional da inferência; exclusão de fabricação, treinamento, interconexões, CPU, DRAM, SSD e escalonamento; quantização, speculative decoding e arquiteturas alternativas ficaram fora do escopo. ([Original](https://arxiv.org/html/2505.14733v1), seção 5, “Limitations and Future Work”.)

### 5. Emissões na inferência — artigo revisado

**Energy costs of communicating with AI | Maximilian Dauner e Gudrun Socher | 19/06/2025 | Artigo revisado por pares, Frontiers in Communication, volume 10.** [Original e DOI](https://doi.org/10.3389/fcomm.2025.1572947).

- **Link direto:** https://doi.org/10.3389/fcomm.2025.1572947
- **Método e amostra:** **14 modelos**, de **7 a 72 bilhões** de parâmetros; **500 questões de múltipla escolha e 500 respostas livres**, em cinco disciplinas do MMLU; A100 de 80 GB; Perun; fator de emissão **“480 gCO₂/kWh”**; respostas livres avaliadas por o4-mini. ([Original](https://www.frontiersin.org/journals/communication/articles/10.3389/fcomm.2025.1572947/full), seção 3.)
- **Números-chave:** nas 1.000 questões, Qwen 7B: **“27.7 g CO₂eq”**, acurácia **“32.9%”**; Deepseek-R1 70B: **“2,042.4 g CO₂eq”**, acurácia **“78.9%”**. ([Original](https://www.frontiersin.org/journals/communication/articles/10.3389/fcomm.2025.1572947/full), seção 4, texto da figura 4.)
- **Resultado contrário registrado:** Cogito 70B com reasoning: acurácia **“84.9%”**, emissões **“1,341.1 g”**, **“34.3% less”** que Deepseek-R1 70B. ([Original](https://www.frontiersin.org/journals/communication/articles/10.3389/fcomm.2025.1572947/full), seção 4, figura 4.)
- **Limitações declaradas:** transferência limitada entre famílias e arquiteturas; ausência de modelos de centenas de bilhões de parâmetros; resultados dependentes da A100 e do fator de emissão; impossibilidade de extrapolação direta para outras infraestruturas. ([Original](https://www.frontiersin.org/journals/communication/articles/10.3389/fcomm.2025.1572947/full), seção 6.)

### 6. Microsoft–OpenAI — decisão da CMA

**Microsoft / OpenAI partnership merger inquiry — Found not to qualify decision | Competition and Markets Authority, Reino Unido | decisão de 05/03/2025; íntegra publicada em 15/04/2025 | Decisão regulatória.** [Processo oficial](https://www.gov.uk/cma-cases/microsoft-slash-openai-partnership-merger-inquiry).

- **Link direto:** https://www.gov.uk/cma-cases/microsoft-slash-openai-partnership-merger-inquiry — contém os links para a decisão integral e o resumo oficial.
- **Fatos e consequência:** a CMA decidiu que a parceria Microsoft–OpenAI não se qualificava para investigação sob as disposições sobre fusões do Enterprise Act 2002; o processo foi encerrado. ([Original](https://www.gov.uk/cma-cases/microsoft-slash-openai-partnership-merger-inquiry), “Found not to qualify decision”.)
- **Números-chave/localização:** cronologia oficial: abertura formal em **“4 March 2025”** e decisão em **“5 March 2025”**. Percentuais de participação, investimentos e critérios quantitativos da decisão integral: **[NÃO VERIFICADO]**. ([Original](https://www.gov.uk/cma-cases/microsoft-slash-openai-partnership-merger-inquiry), “Statutory timetable”.)
- **Resultado contrário registrado:** classificação oficial do desfecho: **“Mergers - phase 1 found not to qualify”**. ([Original](https://www.gov.uk/cma-cases/microsoft-slash-openai-partnership-merger-inquiry), cabeçalho do processo.)
- **Limitações declaradas:** ressalvas e delimitações da fundamentação integral: **[NÃO VERIFICADO]**; a página processual foi consultada, não o PDF completo da decisão.

### 7. AWS — interrupção operacional documentada

**Update — AWS services operating normally; acompanhado de Summary of the Amazon DynamoDB Service Disruption in the Northern Virginia (US-EAST-1) Region | Amazon/AWS | incidente de 19–20/10/2025; atualização publicada em 22/10/2025 | Caso real, comunicado e post-mortem técnico do fornecedor.** [[aboutamazon](https://www.aboutamazon.com/news/aws/aws-service-disruptions-outage-update)][[aws.amazon](https://aws.amazon.com/premiumsupport/technology/pes/)]

- **Links diretos:** [comunicado oficial](https://www.aboutamazon.com/news/aws/aws-service-disruptions-outage-update) e [post-mortem](https://aws.amazon.com/message/101925/).[[aboutamazon](https://www.aboutamazon.com/news/aws/aws-service-disruptions-outage-update)]
- **Fatos e consequência:** falha de resolução DNS dos endpoints regionais do DynamoDB; recuperação seguida de problemas em subsistemas dependentes; limitação temporária de operações, incluindo lançamento de instâncias EC2; impacto também em Amazon.com, subsidiárias e suporte AWS.[[aboutamazon](https://www.aboutamazon.com/news/aws/aws-service-disruptions-outage-update)]
- **Números-chave:** o comunicado registra **“11:49 PM PDT on October 19”**, mitigação do problema DNS em **“2:24 AM PDT”** de 20/10 e retorno de todos os serviços à operação normal em **“3:01 PM PDT”**. Localização: corpo do comunicado.[[aboutamazon](https://www.aboutamazon.com/news/aws/aws-service-disruptions-outage-update)]
- **Registro contrário dentro do caso:** o post-mortem informa que clientes com DynamoDB Global Tables conseguiram acessar réplicas em outras regiões, embora com atraso de replicação envolvendo US-EAST-1. Localização: seção sobre DynamoDB.[[aws.amazon](https://aws.amazon.com/fr/message/101925/?tag=zdipcmmeamzae-21)]
- **Limitações declaradas:** não foi localizada, no material consultado, uma seção formal de limitações. Valores de prejuízo financeiro e número total de empresas afetadas: **[NÃO VERIFICADO]**.
- **Natureza da fonte:** documentação de incidente pelo próprio fornecedor, não estudo independente; incluída como caso operacional, não como material promocional.

## Fontes com verificação incompleta

Os registros seguintes **não substituem fontes integralmente verificadas**. Os campos não confirmados na fonte original permanecem explicitamente sinalizados.

### 8. Parcerias de IA — FTC

**Staff Report on AI Partnerships & Investments | Federal Trade Commission | 17/01/2025 | Relatório institucional de investigação, estudo sob a seção 6(b).** Título e publicação identificados em fonte secundária. [[squirepattonboggs](https://www.squirepattonboggs.com/insights/publications/ftc-report-on-ai-sector-illuminates-future-enforcement/)]

- **Link:** [descrição documental do relatório](https://www.squirepattonboggs.com/insights/publications/ftc-report-on-ai-sector-illuminates-future-enforcement/). **Link direto ao original: [NÃO VERIFICADO].**
- **Método e amostra:** segundo a descrição consultada, informações e documentos internos de **cinco empresas** — Microsoft, Amazon, Google, OpenAI e Anthropic —, relativos às respectivas parcerias. **[NÃO VERIFICADO NO ORIGINAL]**.[[squirepattonboggs](https://www.squirepattonboggs.com/insights/publications/ftc-report-on-ai-sector-illuminates-future-enforcement/)]
- **Números-chave:** quantidade de empresas: **cinco**, conforme a descrição secundária; valores contratuais, páginas e seções originais: **[NÃO VERIFICADO]**.[[squirepattonboggs](https://www.squirepattonboggs.com/insights/publications/ftc-report-on-ai-sector-illuminates-future-enforcement/)]
- **Limitações atribuídas ao relatório:** não constituiria análise jurídica ou econômica formal; informações restritas às cinco respondentes; análise abrangente das parcerias fora do escopo. **Redação e localização no original: [NÃO VERIFICADO]**.[[squirepattonboggs](https://www.squirepattonboggs.com/insights/publications/ftc-report-on-ai-sector-illuminates-future-enforcement/)]

### 9. Custo de agentes — NBER

**AI Agents and Prompt Engineering in Econometric Coding | NBER Working Paper n.º 35588; autores [NÃO VERIFICADO] | data de publicação [NÃO VERIFICADO] | Working paper com experimento.** [[nber](https://www.nber.org/system/files/working_papers/w35588/w35588.pdf)]

- **Link direto:** https://www.nber.org/system/files/working_papers/w35588/w35588.pdf
- **Método e amostra:** comparação entre chatbot e agente restrito em tarefas de programação econométrica; o texto recuperado menciona **seis modelos**. Quantidade de tarefas, execuções e identificação dos autores: **[NÃO VERIFICADO]**.[[nber](https://www.nber.org/system/files/working_papers/w35588/w35588.pdf)]
- **Números-chave recuperados do original:** sucesso de **“84 to 97 percent”**; execuções do agente **“3.4 times as much”** em custo; custo por resposta correta adicional de **“$0.02 to $1.13”**. **Páginas: [NÃO VERIFICADO]**.[[nber](https://www.nber.org/system/files/working_papers/w35588/w35588.pdf)]
- **Resultado contrário registrado:** permitir ao chatbot revisar o próprio script alcançou a maior parte do ganho de sucesso atribuído ao aumento de agência. **Página/seção: [NÃO VERIFICADO]**.[[nber](https://www.nber.org/system/files/working_papers/w35588/w35588.pdf)]
- **Limitações declaradas:** **[NÃO VERIFICADO]**.
- **Elegibilidade temporal:** **[NÃO VERIFICADO]**; não contabilizado como fonte confirmada no intervalo solicitado.

### 10. Infraestrutura de IA — OECD

**Competition in artificial intelligence infrastructure | OECD | 2025; dia e mês [NÃO VERIFICADO] | Relatório institucional.** Registro identificado nas referências do documento OECD de julho de 2026. ([Documento que o referencia](https://oecd.org/en/publications/artificial-intelligence-markets_d531d73f-en/full-report.html), referência “OECD, 2025b”.)

- **Link direto/DOI:** https://doi.org/10.1787/623d1874-en
- **Método e amostra:** **[NÃO VERIFICADO]**; original integral não consultado.
- **Números-chave e páginas:** **[NÃO VERIFICADO]**.
- **Limitações declaradas:** **[NÃO VERIFICADO]**.
- **Elegibilidade como estudo com metodologia explícita:** **[NÃO VERIFICADO]**; permanece como pista bibliográfica, não como estudo empírico confirmado.

### 11. Cadeia de fornecedores — BIS

**Global giants in the AI supply chain | Jon Frost, K. Rishabh e V. Shreeti | 2026; dia e mês [NÃO VERIFICADO] | BIS Bulletin, n.º 122.** Metadados identificados nas referências do documento OECD de julho de 2026. ([Documento que o referencia](https://oecd.org/en/publications/artificial-intelligence-markets_d531d73f-en/full-report.html).)

- **Link direto:** https://www.bis.org/publ/bisbull122.htm
- **Método e amostra:** **[NÃO VERIFICADO]**; original integral não consultado.
- **Números-chave e páginas:** **[NÃO VERIFICADO]**. Não foram atribuídos a este boletim números reproduzidos pela OECD sem conferência no original.
- **Limitações declaradas:** **[NÃO VERIFICADO]**.
- **Elegibilidade como estudo com metodologia explícita:** **[NÃO VERIFICADO]**; permanece como pista bibliográfica.
