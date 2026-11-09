# Tema 1: Evidência empírica do impacto da IA generativa em produtividade e qualidade do trabalho (estudos de campo e RCTs, incluindo resultados nulos/negativos)

Data da busca: 09/nov/2026
Período-alvo: jan/2025 a nov/2026
Nota de método: fontes abertas diretamente (arXiv/NBER/etc.) via curl/pdftotext são marcadas "Verificado na fonte original". Itens sem abertura do original levam [NÃO VERIFICADO]. Sem análise ou conclusões neste arquivo.

---

## 1. Measuring the Impact of Early-2025 AI on Experienced Open-Source Developer Productivity
- Autores/veículo: Joel Becker, Nate Rush, Beth Barnes, David Rein (METR) | arXiv:2507.09089 (v1 12/jul/2025; v2 25/jul/2025) | Tipo: working paper/preprint, RCT de campo
- Link: https://arxiv.org/abs/2507.09089 (PDF: https://arxiv.org/pdf/2507.09089) | DOI: https://doi.org/10.48550/arXiv.2507.09089
- Método e amostra: RCT; 16 desenvolvedores open-source com experiência moderada em IA; 246 tarefas (média 2,0 h) em repositórios maduros (média 23.000 estrelas) nos quais têm ~5 anos de experiência; cada tarefa aleatorizada para permitir/proibir IA (principalmente Cursor Pro com Claude 3.5/3.7 Sonnet); desfecho = tempo de conclusão autorrelatado; 143 h de gravações de tela rotuladas (29% das horas) (Abstract; §1, p. 1-2).
- Números-chave (Abstract, p. 1; §1): "developers forecast that allowing AI will reduce completion time by 24%"; "developers estimate that allowing AI reduced completion time by 20%"; "we find that allowing AI actually increases completion time by 19%"; previsões de especialistas: "economics (39% shorter) and ML (38% shorter)". Diferença bruta sem ajuste por dificuldade: 34% (nota 12, p. 7). Fatores: 5 contribuem para a lentidão, 10 mistos/sem evidência, 6 com evidência contra (§1, p. 2).
- Limitações declaradas (§4.1 "Key Caveats", p. 12): "We caution readers against overgeneralizing on the basis of our results. The slowdown we observe does not imply that current AI tools do not often improve developer's productivity"; resultados "consistent with small greenfield projects or development in unfamiliar codebases seeing substantial speedup"; Abstract: "the influence of experimental artifacts cannot be entirely ruled out".
- Status: Verificado na fonte original (PDF v2 e página arXiv).

## 2. We are Changing our Developer Productivity Experiment Design (follow-up METR, 2º estudo ago/2025 a início de 2026)
- Autores/veículo: Joel Becker, Nate Rush, Tom Cunningham, David Rein, Khalid Mahamud (METR), post institucional | 24/fev/2026 | Tipo: relatório institucional com dados (RCT de campo, resultado declarado como não confiável)
- Link: https://metr.org/blog/2026-02-24-uplift-update/
- Método e amostra: novo experimento iniciado em ago/2025; 57 desenvolvedores (10 do estudo original + 47 novos), 143 repositórios, "800+ tasks"; pagamento de US$ 50/h (era US$ 150/h no original); tarefas aleatorizadas AI-allowed/AI-disallowed (seção "Details of the productivity study").
- Números-chave (texto de abertura): "Our early 2025 study found the use of AI causes tasks to take 19% longer, with a confidence interval between +2% and +39%. For the subset of the original developers who participated in the later study, we now estimate a speedup of -18% with a confidence interval between -38% and +9%. Among newly-recruited developers the estimated speedup is -4%, with a confidence interval between -15% and +9%." Também: "30% to 50% of developers told us that they were choosing not to submit some tasks because they did not want to do them without AI."
- Limitações declaradas (texto de abertura e seção "Wider adoption of AI has made it more difficult..."): "we believe that the data from our new experiment gives us an unreliable signal of the current productivity effect of AI tools"; viés de seleção por desenvolvedores que recusam trabalhar sem IA ("likely biases downwards our estimate of AI-assisted speedup"); medição de tempo pouco confiável com múltiplos agentes simultâneos; "our data is only very weak evidence for the size of this increase".
- Status: Verificado na fonte original (página METR).

## 3. Measuring the Self-Reported Impact of Early-2026 AI on Technical Worker Productivity
- Autores/veículo: METR (post institucional) | 11/mai/2026 (URL /blog/2026-05-11-ai-usage-survey/) | Tipo: relatório institucional com survey (autorrelato)
- Link: https://metr.org/blog/2026-05-11-ai-usage-survey/
- Método e amostra: survey fev-abr/2026 com 349 trabalhadores técnicos (87 engenheiros de software, 71 pesquisadores, 129 acadêmicos/doutorandos, 48 fundadores/gestores).
- Números-chave: "Participants self-reported a median 1.4–2x change in the value in their work due to AI tools. The median self-reported speed change (which we expect to be higher than value change) is 3x."; mediana retrospectiva de uplift em mar/2025: ~1,3x; "the median participant claims that they would sacrifice 29% of their salary to keep access to AI tools for 1 month".
- Limitações declaradas: "There are tentative reasons to be skeptical of the magnitude of responses"; "survey results are not necessarily grounded in reality"; cita que no estudo de 2025 os participantes superestimaram o efeito da IA no tempo em "40 percentage points on average".
- Status: Verificado na fonte original (página METR); números de página não se aplicam (HTML).

## 4. Still Waters, Rapid Currents: Early Labor Market Transformation under Generative AI (antes: "Large Language Models, Small Labor Market Effects")
- Autores/veículo: Anders Humlum, Emilie Vestergaard | NBER Working Paper 33777, mai/2025, revisado mar/2026 (versões de 9/mai/2025 e 20/out/2025 listadas) | Tipo: working paper NBER (dados administrativos + survey, Dinamarca); resultado nulo
- Link: https://www.nber.org/papers/w33777 | DOI: https://doi.org/10.3386/w33777 | PDF: https://www.nber.org/system/files/working_papers/w33777/w33777.pdf
- Método e amostra: surveys representativos com Statistics Denmark em 11 ocupações expostas (contadores, atendimento, assessores financeiros, RH, suporte de TI, jornalistas, jurídico, marketing, escriturários, desenvolvedores, professores); última rodada (fim de 2024) com "25,000 workers across 7,000 workplaces" (p. 3 do PDF), ligada a registros administrativos; diferenças-em-diferenças.
- Números-chave (Abstract, p. 2 do PDF): "we estimate precise null effects on earnings and recorded hours at both the worker and workplace levels, ruling out effects larger than 2% two years after the launch of ChatGPT"; seção de resultados (p. 25): "The confidence intervals of our dynamic difference-in-differences estimates rule out changes larger than 3%, and our pooled difference-in-differences estimates rule out effects larger than 2%." Conclusão (p. 36): resultados nulos valem "even among workers who report substantial daily time savings". Observação: a versão de mai/2025 (via busca, não aberta por mim) reportava limite de 1% e economia média de tempo de 3% [NÃO VERIFICADO para a versão antiga].
- Limitações declaradas: conclusão (p. 36) afirma que "the absence of measurable labor market effects is not evidence that nothing is happening"; resultados valem para 11 ocupações da Dinamarca; benefícios de produtividade são autorrelatados em survey.
- Status: Verificado na fonte original (PDF versão mar/2026).

## 5. Shifting Work Patterns with Generative AI (Microsoft 365 Copilot, experimento de campo)
- Autores/veículo: Eleanor W. Dillon, Sonia Jaffe, Nicole Immorlica, Christopher T. Stanton (Microsoft Research / HBS) | NBER Working Paper 33795, mai/2025, revisado nov/2025 | Tipo: working paper NBER, experimento de campo randomizado (autores com vínculo à Microsoft; há declaração de "additional relationships of potential relevance")
- Link: https://www.nber.org/papers/w33795 | PDF: https://www.nber.org/system/files/working_papers/w33795/w33795.pdf | DOI: https://doi.org/10.3386/w33795 [DOI inferido do padrão NBER; não aberto]
- Método e amostra: 66 empresas, 7.137 trabalhadores do conhecimento; atribuição aleatória de licenças Copilot (pilot com 300 licenças por empresa); 6 meses; dados de telemetria dos produtos Microsoft (tempo em e-mail, reuniões, documentos); "we do not observe the content of any work nor any measures of productivity or performance evaluation" (p. 4 do PDF).
- Números-chave (Abstract, p. 2): "the 80% of treated workers who used this tool spent two fewer hours on email each week and reduced their time working outside of regular hours. Apart from these individual time savings, we do not detect shifts in the quantity or composition of workers' tasks resulting from individual-level AI provision." Introdução (p. 4): efeito ITT de redução de 1,4 h/semana em e-mail (12% vs pré-período); LATE de 2 h (17%).
- Limitações declaradas (seção 1, amostra): "we caveat that participating workers may not be representative of the overall worker population at participating firms, or of knowledge workers more broadly"; acordos de uso de dados impedem comparar a amostra com o restante dos trabalhadores das empresas; sem medidas de produtividade ou desempenho.
- Status: Verificado na fonte original (PDF).

## 6. The Cybernetic Teammate: A Field Experiment on Generative AI Reshaping Teamwork and Expertise
- Autores/veículo: Fabrizio Dell'Acqua, Charles Ayoubi, Hila Lifshitz, Raffaella Sadun, Ethan Mollick, Lilach Mollick, Yi Han, Jeff Goldman, Hari Nair, Stewart Taub, Karim Lakhani | NBER Working Paper 33641, abr/2025 | Tipo: working paper NBER, experimento de campo pré-registrado (declara apoio financeiro da Procter & Gamble ao D^3 / HBS e consultoria de Lakhani à P&G em 2021-22)
- Link: https://www.nber.org/papers/w33641 | PDF: https://www.nber.org/system/files/working_papers/w33641/w33641.pdf | DOI: https://doi.org/10.3386/w33641 [DOI inferido; não aberto]
- Método e amostra: 776 profissionais da Procter & Gamble; desafios reais de desenvolvimento de produto; atribuição aleatória a trabalhar com/sem IA, individualmente ou em dupla; workshop virtual de um dia.
- Números-chave (Abstract, p. 3; §Resultados, p. 14-15): "individuals with AI matched the performance of teams without AI"; qualidade: times sem IA +0,24 desvio-padrão (p<0,05) vs indivíduos sem IA; "individuals with AI demonstrate a 0.37 standard deviation increase (p < 0.01), while teams with AI show a 0.39 standard deviation improvement"; tempo: "individuals with AI spent 16.4% less time than the control group, while teams with AI spent 12.7% less time" (p. 15).
- Limitações declaradas (Discussão, p. 20): "our experiment relied on one-day virtual collaborations that did not fully capture the day-to-day complexities of team interactions in organizations — such as extended coordination challenges and iterative rework cycles"; foco em duplas multifuncionais, outras estruturas "may exhibit different patterns".
- Status: Verificado na fonte original (PDF).

## 7. Firm Data on AI
- Autores/veículo: Ivan Yotzov, Jose Maria Barrero, Nicholas Bloom, Philip Bunn, Chanya Chawla, Steven J. Davis, Kevin M. Foster, Aaron Jalca, Brent H. Meyer, Paul Mizen, Michael A. Navarrete, Samil Oh, Katia Garcia Loredo, Monique Reid, Pawel Smietanka, Gregory Thwaites, Ben Zhe Wang | NBER Working Paper 34836, fev/2026, revisado out/2026 | Tipo: working paper NBER, survey de executivos (autorrelato) em 7 países
- Link: https://www.nber.org/papers/w34836 | DOI: https://doi.org/10.3386/w34836
- Método e amostra (abstract, página NBER): survey de "nearly 9,000 CFOs, CEOs and senior executives at firms in the US, UK, Germany, Australia, Canada, Mexico and South Africa in Summer 2026".
- Números-chave (abstract): "78% of firms use AI"; "executives report that AI has had essentially no net effect on firm employment over the last 3 years"; "more than 40% of firms anticipate positive or negative employment effects that roughly offset only in the aggregate"; "executives report AI adoption has raised annual labor productivity growth by 0.2% over the last 3 years, a modest impact, but expect a substantially larger 0.6% per annum boost over the next 3 years"; "just 2% of firms accounting for over 50% of total spending".
- Limitações declaradas: não localizei seção de limitações (PDF retornou 403; li apenas o abstract da página NBER). Os dados são relatos de executivos, não medidas administrativas de produtividade. Versões anteriores (fev/2026, ~6.000 executivos em 4 países, valores "89% sem impacto em produtividade") foram citadas por resultado de busca, [NÃO VERIFICADO].
- Status: abstract verificado na página NBER; corpo do paper [NÃO VERIFICADO] (PDF inacessível).

## 8. How AI Impacts Skill Formation
- Autores/veículo: Judy Hanwen Shen (Anthropic Fellows Program), Alex Tamkin (Anthropic) | arXiv:2601.20245 (v2, 1/fev/2026; v1 jan/2026) | Tipo: preprint, experimento randomizado (pré-registrado em https://osf.io/w49e7). Observação de interesse: autores vinculados à Anthropic, desenvolvedora de modelos de IA.
- Link: https://arxiv.org/abs/2601.20245 | PDF: https://arxiv.org/pdf/2601.20245 | DOI: https://doi.org/10.48550/arXiv.2601.20245 [DOI no padrão arXiv; não aberto]
- Método e amostra: experimento randomizado com 52 programadores profissionais/freelancers (26 por grupo) aprendendo a biblioteca assíncrona Trio (Python); 35 min de tarefa seguidas de quiz de 27 pontos (§5.2, p. ~11-12).
- Números-chave (§1.1, p. 2; §5.2.2): "using AI assistance ... resulted in a reduction in the evaluation score by 17% or two grade points (Cohen's d = 0.738, p = 0.010). Meanwhile, we did not find a statistically significant acceleration in completion time with AI assistance"; diferença de 4,15 pontos em quiz de 27 pontos. Abstract: "AI use impairs conceptual understanding, code reading, and debugging abilities, without delivering significant efficiency gains on average."
- Limitações declaradas (§7.1 "Future Work", p. 19): tarefa única com interface de chat; horizonte de uma hora ("skill formation takes place over months to years"); participantes sem o mesmo incentivo de aprender que teriam no emprego; habilidade de prompting medida por autorrelato; ausência do contrafactual de assistência humana.
- Status: Verificado na fonte original (PDF v2).

## 9. The Rapid Adoption of Generative AI (estimativa de ganho agregado por tempo autorrelatado; versão revisada fev/2025)
- Autores/veículo: Alexander Bick (St. Louis Fed), Adam Blandin (Vanderbilt), David J. Deming (Harvard Kennedy School) | NBER Working Paper 32966, set/2024, revisado fev/2025 | Tipo: working paper NBER, survey nacionalmente representativo (Real-Time Population Survey; financiado em parte pela Walmart Foundation)
- Link: https://www.nber.org/papers/w32966 | PDF: https://www.nber.org/system/files/working_papers/w32966/w32966.pdf | DOI: https://doi.org/10.3386/w32966 [DOI inferido; não aberto]
- Método e amostra: surveys nacionais dos EUA (adultos 18-64) sobre uso de IA generativa; economia de tempo autorrelatada ("how many additional hours they would have needed to complete the same amount of work in the previous week if they had not had access to genAI") (p. 3-4).
- Números-chave (Abstract, p. 2; p. 3-4; conclusão p. 29): "nearly 40 percent of the U.S. population age 18-64 uses generative AI"; "23 percent of employed respondents had used generative AI for work at least once in the previous week, and 9 percent used it every work day"; "Between 1 and 5 percent of all work hours are currently assisted by generative AI, and respondents report time savings equivalent to 1.4 percent of total work hours"; "mean time savings of 5.4 percent among all genAI work users" (2,2 h/semana); "potential aggregate productivity gain of 1.1 percent at current levels of worker genAI usage"; comparação com Acemoglu (2024): 0,7%.
- Limitações declaradas (conclusão, p. 29): "we caution that this assumes all of the gains are internalized as higher worker output rather than increased leisure"; autores descrevem a estimativa como "rough" e o impacto de longo prazo como "uncertain".
- Status: Verificado na fonte original (PDF). Observação de data: versão original é de set/2024; a revisão com estes números é de fev/2025.

## 10. Generative AI at Work (atendimento ao cliente; versão publicada em 2025 no QJE)
- Autores/veículo: Erik Brynjolfsson, Danielle Li, Lindsey R. Raymond | NBER WP 31161 (abr/2023, rev. nov/2023); publicação em Quarterly Journal of Economics, 2025 [NÃO VERIFICADO: página do periódico bloqueada (403); dados de volume/páginas não confirmados por mim] | Tipo: working paper NBER / artigo revisado por pares; estudo de campo quase-experimental (introdução escalonada)
- Link: https://www.nber.org/papers/w31161 | PDF: https://www.nber.org/system/files/working_papers/w31161/w31161.pdf | DOI do periódico: https://doi.org/10.1093/qje/qjae044 [NÃO VERIFICADO; acesso bloqueado]
- Método e amostra: introdução escalonada de assistente conversacional de IA generativa; dados de 5.179 atendentes de suporte ao cliente; ~3 milhões de conversas; 89% dos atendentes fora dos EUA, principalmente nas Filipinas (p. 11-12 do PDF, seção de dados).
- Números-chave (Abstract, versão nov/2023, p. 2): "Access to the tool increases productivity, as measured by issues resolved per hour, by 14% on average, including a 34% improvement for novice and low-skilled workers but with minimal impact on experienced and highly skilled workers."; resolutions/hora: base 2,6, aumento de ~14%; queda de 9% no tempo médio de atendimento.
- Limitações declaradas (Conclusão, p. 29): "our results do not capture the potential longer-term impacts of generative AI on skill demand, job design, wages, or customer demand"; sugere que top performers, que geram os exemplos usados para treinar a IA, "may even see a reduction in their pay because bonuses are calculated relative to other agents' performance". Nota: os números do Abstract são da versão NBER de 2023; a versão do QJE pode diferir [NÃO VERIFICADO].
- Status: números verificados na versão NBER; publicação 2025 não verificada na fonte.

## 11. The 2026 AI Index Report, capítulo "Economy" (Stanford HAI)
- Autores/veículo: Stanford Institute for Human-Centered AI (AI Index Steering Committee) | AI Index 2026 (edição de 2026; data exata de publicação não consta na página aberta) | Tipo: relatório institucional (síntese de estudos)
- Link: https://hai.stanford.edu/ai-index/2026-ai-index-report/economy
- Método e amostra: síntese de dados e estudos de terceiros; o texto da página de destaques não detalha os estudos subjacentes (o capítulo completo está em "Download Full Chapter", não aberto).
- Números-chave (destaque 9 da página): "Productivity gains from AI are largest in structured, measurable work where outputs are easy to monitor. Studies report gains of 14% to 15% in customer support, 26% in software development, and 50% in marketing output. Gains are smaller in tasks requiring deeper reasoning, and recent evidence raises concerns that heavy AI reliance may carry long-term learning penalties that slow skill development over time." Destaque 7: "Employment for software developers ages 22 to 25 has fallen nearly 20% from 2024." Destaque 8: "One-third of organizations expect AI to reduce their workforce in the coming year, even though large-scale job losses have not yet shown up in overall employment data." Destaque 4: consumo "estimated U.S. consumer surplus reached $172 billion annually by early 2026".
- Limitações declaradas: não localizadas na página de destaques. Os estudos subjacentes (14-15%, 26%, 50%) não foram abertos por mim neste item; o item 10 corresponde ao 14%.
- Status: página de destaques verificada na fonte original; capítulo completo [NÃO VERIFICADO].

## 12. The AI Buildout and the Economy: Publicly Available Data to Assess AI's Impact (FEDS Note)
- Autores/veículo: Paul E. Soto, Mason Thieu, Jeffrey S. Allen (Federal Reserve Board) | FEDS Notes, 17/jul/2026 | Tipo: nota de pesquisa de banco central, dados públicos agregados (BLS, BEA)
- Link: https://www.federalreserve.gov/econres/notes/feds-notes/the-ai-buildout-and-the-economy-publicly-available-data-to-assess-ais-impact-20260717.html
- Método e amostra: produtividade do trabalho setorial (valor adicionado real menos horas×emprego) por nível de exposição à IA (Alta: Informação, Finanças, Serviços Profissionais e de Negócios; Média; Baixa), Figura 9; indicadores de adoção, investimento e mercado de trabalho.
- Números-chave (seção de produtividade): "Micro-level experiments consistently find productivity gains from AI tools (Brynjolfsson, Li, and Raymond, 2025; Cui et al. 2026)."; "While sectors with more exposure appear to have higher labor productivity growth, we see that productivity trends across all three levels have been relatively consistent over time, suggestive of micro-level productivity gains not adding up in aggregate." Conclusão: "the evidence as of the publication of this note is consistent with a buildout phase rather than the onset of broad-based displacement."
- Limitações declaradas: "AI-exposed sectors may have ex-ante different productivity trends unrelated to AI"; "The absence of a large aggregate signal as of 2026 would not necessarily invalidate future productivity impacts, given the shallow adoption"; "AI's productivity effects are inherently hard to measure" (atribuição entre capital e TFP, intangíveis, preços em serviços).
- Status: Verificado na fonte original (página HTML; sem numeração de páginas).

## 13. The effects of generative AI on productivity, innovation and entrepreneurship (revisão de estudos experimentais)
- Autores/veículo: Flavio Calvino, Jelmer Reijerink, Lea Samek (OECD) | OECD Artificial Intelligence Papers No. 39, jun/2025 | Tipo: relatório institucional (revisão de pesquisa experimental, fonte secundária)
- Link: https://www.oecd.org/content/dam/oecd/en/publications/reports/2025/06/the-effects-of-generative-ai-on-productivity-innovation-and-entrepreneurship_da1d085d/b21df222-en.pdf
- Método e amostra: "reviews experimental research on the impact of generative AI on productivity, innovation, and entrepreneurship" (Abstract, p. 3), com tabela de estudos (final do documento); não é estudo primário.
- Números-chave (Abstract e seções 2-3, valores citados de estudos de terceiros): "Findings suggest that AI's effectiveness depends on the user's experience and the task carried out"; citações: 14% mais questões resolvidas (atendimento), 26% mais tarefas concluídas (desenvolvedores), 55% mais linhas de código, escrita 40% mais rápida [números de página específicos não anotados].
- Limitações declaradas (Introdução): "A key limitation of experimental approaches is often their difficulty in capturing long-term impacts, often due to constrains in study duration and data tracking"; o documento aponta lacunas sobre efeitos de longo prazo e sobre o entendimento dos trabalhadores quanto às limitações da IA (Abstract).
- Status: Verificado na fonte original (PDF); números de página por afirmação não anotados.

## 14. Does AI Save Time on Product Design? A Randomized Controlled Experiment of AI Prompt-to-Design Workflows
- Autores/veículo: Remy Stewart, Olabode Anise, Andrew Hogan, Augustus Griffin (todos Figma, fornecedor da ferramenta testada) | arXiv:2609.26725v1, 22/set/2026 | Tipo: preprint, RCT. Observação: estudo conduzido pelo fornecedor da ferramenta (Figma Make); incluído por ter método e limitações explícitos.
- Link: https://arxiv.org/abs/2609.26725 | PDF: https://arxiv.org/pdf/2609.26725 | DOI: https://doi.org/10.48550/arXiv.2609.26725 [padrão arXiv; não aberto]
- Método e amostra: RCT com 50 designers de produto e 50 gerentes de produto; três tarefas padronizadas, com ou sem acesso ao Figma Make.
- Números-chave (Abstract; §Resultados): "Among participants who completed the study tasks, access to Figma Make was associated with approximately 20% shorter completion times, with larger gains among product managers."; gerentes de produto: redução de 35% no tempo total (p<0,0001); designers: 17% "marginally significant" (p=0,049), concentrada na Tarefa 3 (26%).
- Limitações declaradas (§5.2, 5 limitações): análise de tempo "limited to successfully completed tasks", e a ferramenta afetou a probabilidade de conclusão, de modo que os grupos de concluintes podem diferir ("reported time reduction should be interpreted alongside the completion results"); tarefas padronizadas e em ordem fixa que não capturam a ambiguidade e as mudanças de requisitos de projetos profissionais.
- Status: Verificado na fonte original (PDF).

## 15. Does AI Assistance Enhance or Erode Expertise? Evidence from a Three-Month Field Experiment in Patent Drafting
- Autores/veículo: [autores não extraídos: página NBER aberta mostrou apenas o abstract; nomes não anotados] | NBER Working Paper 35720, set/2026, revisado out/2026 | Tipo: working paper NBER, RCT de campo pré-registrado
- Link: https://www.nber.org/papers/w35720 | DOI: https://doi.org/10.3386/w35720
- Método e amostra (abstract): "pre-registered three-month randomized controlled trial"; 133 advogados de patentes em onze escritórios de propriedade intelectual dos EUA; acesso a assistente de redação de patentes personalizado; trabalho avaliado por advogados de patentes especialistas, às cegas.
- Números-chave (abstract): qualidade com IA "at 10 days (0.34 SD, p = 0.03) and 90 days (0.38 SD, p = 0.01), with larger gains among junior lawyers" [valores de p renderizados como "?" na página; leitura "p" é inferência do contexto]; tarefa sem IA após 3 meses: "Treated lawyers outperformed controls by 0.32 SD (p = 0.04), but this advantage was concentrated entirely among senior lawyers (0.45 SD, p = 0.02). Junior lawyers showed no average gain."; juniores "bifurcated, with sharply fewer mediocre scores offset by more poor and more good ones".
- Limitações declaradas: não lidas (PDF retornou 403; só abstract). 
- Status: abstract verificado na página NBER; corpo [NÃO VERIFICADO].

## 16. Does Generative AI Narrow Education-Based Productivity Gaps? Evidence from a Randomized Experiment
- Autores/veículo: [autores não anotados; também disponível como arXiv:2608.04198 segundo resultado de busca, não aberto] | NBER Working Paper 34851, fev/2026, revisado out/2026 | Tipo: working paper NBER, experimento randomizado online (fora de empresas)
- Link: https://www.nber.org/papers/w34851 | DOI: https://doi.org/10.3386/w34851
- Método e amostra (abstract): 1.174 adultos de 25-45 anos; tarefa de resolução de problema de negócios incentivada, com ou sem assistente de IA generativa, seguida de módulo de acompanhamento sem IA.
- Números-chave (abstract): "In the control group without AI, higher-education participants outperform lower-education participants by 0.548 standard deviations; with AI, this gap falls to 0.139 standard deviations"; "treated participants do not perform worse than controls once AI is removed, and lower-education participants retain part of their gain, although a sizable education gap re-emerges"; desempenho de acompanhamento "substantially higher only when intensive AI use is combined with sustained effort on the task".
- Limitações declaradas: não lidas (só abstract).
- Status: abstract verificado na página NBER; corpo [NÃO VERIFICADO].

## 17. Canaries in the Gold Mine (AI, capital organizacional e produtividade das firmas)
- Autores/veículo: [autores não anotados] | NBER Working Paper 35684, ago/2026 | Tipo: working paper NBER, estudo observacional em nível de firma
- Link: https://www.nber.org/papers/w35684 | DOI: https://doi.org/10.3386/w35684
- Método e amostra (abstract): medida de investimento em IA baseada em emprego com habilidades de IA (de machine learning a IA generativa e agêntica), ligada à produtividade das firmas; medida de capital organizacional a partir de descrições de cargos.
- Números-chave (abstract): "AI investments are associated with productivity growth in recent years, but not over the previous decade"; ganhos atribuídos ao acúmulo de capital organizacional ("durable firm-specific knowledge acquired through learning-by-doing"). Nenhum coeficiente numérico no abstract.
- Limitações declaradas: não lidas (só abstract); desenho observacional.
- Status: abstract verificado na página NBER; corpo [NÃO VERIFICADO].

## 18. Randomized Controlled Trials for Phishing Triage Agent (agente de IA, triagem de phishing em SOC)
- Autores/veículo: James Bono (Microsoft Corporation) | arXiv:2511.13860v1, 17/nov/2025 (documento datado de out/2025) | Tipo: preprint, RCT; estudo de funcionário do fornecedor (Microsoft Security Copilot Phishing Triage Agent)
- Link: https://arxiv.org/abs/2511.13860 | PDF: https://arxiv.org/pdf/2511.13860 | DOI: https://doi.org/10.48550/arXiv.2511.13860 [padrão arXiv; não aberto]
- Método e amostra: 167 analistas de segurança externos, 3 braços (Controle N=52; Aware N=56, vê veredictos do agente; Blind N=59, fila ordenada pelo agente sem referência à IA); fila de 25 e-mails reais reportados por funcionários da Microsoft, com falsos positivos/negativos simulados inseridos (§2).
- Números-chave (Abstract; §3, Tabela 4): "agent-augmented analysts achieved up to 6.5 times as many true positives per analyst minute and a 77% improvement in verdict accuracy"; analistas gastaram "53% more time on malicious emails". Resultado contrário na Tabela 4: precisão do grupo Aware vs Controle em falsos negativos plantados do agente (SFN): 46% vs 17% (diferença 29 p.p., p=0,001), e em verdadeiros negativos confirmados 86% vs 65% (p=0,009), ou seja, mais concordância com o agente, inclusive quando ele errava (§3, ~p. 7; página exata não anotada).
- Limitações declaradas: seção de limitações explícita não localizada [NÃO VERIFICADO]; autor afiliado ao fornecedor.
- Status: Verificado na fonte original (PDF) quanto aos números citados.

## 19. Estimating AI productivity gains from Claude conversations
- Autores/veículo: Anthropic, Economics team (Economic Index) | 25/nov/2025 | Tipo: relatório institucional de fornecedor de IA, com método declarado (estimativas feitas pelo próprio modelo; sem validação com dados reais)
- Link: https://www.anthropic.com/research/estimating-productivity-gains
- Método e amostra: amostra de 100.000 conversas reais do Claude.ai; Claude estima o tempo da tarefa com e sem IA; agregação a tarefas O*NET.
- Números-chave (Overview): "Claude estimates that AI reduces task completion time by 80%"; tarefas de "about 90 minutes" sem IA; extrapolação: "could increase US labor productivity growth by 1.8% annually over the next decade". Atualização de jan/2026 (relatório "Economic primitives") reportada em resultado de busca como ajuste por taxa de sucesso que reduz o ganho implícito para ~1,0 p.p. e 0,8 p.p. [NÃO VERIFICADO; página do relatório de jan/2026 não aberta].
- Limitações declaradas (seção "Limitations"): "we lack real-world validation of Claude's time estimates"; "we can't account for additional time humans spend on tasks outside of their conversations with Claude, including validating the quality or accuracy of Claude's work"; amostra de Claude.ai "not representative"; cita que "a recent randomized controlled trial studying end-to-end software features did not see time savings due to AI".
- Status: Verificado na fonte original (página Anthropic).

## 20. The Effects of Generative AI on High-Skilled Work: Evidence from Three Field Experiments with Software Developers
- Autores/veículo: Kevin Zheyuan Cui, Mert Demirer, Sonia Jaffe, Leon Musolff, Sida Peng, Tobias Salz | Management Science (DOI 10.1287/mnsc.2025.00535, via resultado de busca); versão SSRN postada em 2024, última revisão ago/2025 | Tipo: artigo revisado por pares / RCTs de campo (Microsoft, Accenture, empresa anônima Fortune 100)
- Link: https://papers.ssrn.com/abstract=4945566 (SSRN; acesso retornou 403) | https://doi.org/10.1287/mnsc.2025.00535 [NÃO VERIFICADO: página do periódico não aberta]
- Método e amostra (informação de busca, NÃO VERIFICADA na fonte): RCTs com acesso aleatório ao GitHub Copilot; 4.867 desenvolvedores no conjunto agrupado.
- Números-chave [NÃO VERIFICADO na fonte original]: "26.08% increase in completed tasks (SE 10.3%)" no abstract SSRN, segundo a busca; desenvolvedores menos experientes com maior adoção e ganhos maiores. O FEDS Note de jul/2026 (item 12) cita "Cui et al. 2026" como evidência de ganhos em experimentos micro (verificado nessa nota).
- Limitações declaradas: [NÃO VERIFICADO]; a busca relata que os autores enfatizam que cada experimento é ruidoso e os resultados variam entre eles.
- Status: [NÃO VERIFICADO] (fonte original inacessível).

## 21. AI IDEs or Autonomous Agents? Measuring the Impact of Coding Agents on Software Development
- Autores/veículo: Shyam Agarwal, Hao He, Bogdan Vasilescu (Carnegie Mellon University) | arXiv:2601.13597v2 (27/jan/2026); aceito no MSR '26 (13-14/abr/2026, Rio de Janeiro) | Tipo: preprint/artigo de conferência; estudo observacional quase-experimental (diferenças-em-diferenças escalonadas)
- Link: https://arxiv.org/abs/2601.13597 | PDF: https://arxiv.org/pdf/2601.13597 | DOI: https://doi.org/10.48550/arXiv.2601.13597 [padrão arXiv; não aberto]
- Método e amostra: dataset AIDev (v3); adoção = primeiro pull request gerado por agente; resultados mensais por repositório (commits, linhas adicionadas, avisos de análise estática, complexidade cognitiva, duplicação); repositórios com ≥10 estrelas; amostras heterogêneas: 401 repositórios "agent-first" (AF) pareados a 606 controles e 117 repositórios com uso prévio de IDE com IA (IF) pareados a 73 controles (§Método).
- Números-chave (Abstract; §Resultados): "large, front-loaded velocity gains only when agents are the first observable AI tool in a project; repositories with prior AI IDE usage experience minimal or short-lived throughput increases"; "static-analysis warnings and cognitive complexity rising by roughly 18% and 39%"; AF: +36,3% commits, +76,6% linhas adicionadas; IF: +3,1% e -6,3% (texto de resultados, p. não anotada).
- Limitações declaradas (Discussão): coeficientes pré-tratamento significativos isolados em avisos de análise estática e complexidade, "not pervasive enough to indicate a sustained pre-trend or clear violation of parallel trends, but they are concerning and highlight a limitation of our quasi-experimental design and the underlying data"; amostra de repositórios open-source.
- Status: Verificado na fonte original (PDF).
