# Tema 4: Alucinação, confiabilidade e responsabilização (casos com consequência jurídica ou financeira)

Data da busca: 09/nov/2026
Período: jan/2025 a nov/2026

Nota de método: "Verificado na fonte original" = página/PDF aberto por curl (arXiv, NBER, hai.stanford.edu, bis.org, eur-lex etc.) e números conferidos no texto. Itens baseados apenas em resultados de busca (resumos de terceiros) levam [NÃO VERIFICADO] nos dados específicos. Domínios bloqueados estão listados ao final.

---

## 1. Hallucination-Free? Assessing the Reliability of Leading AI Legal Research Tools
- Autores/veículo: Varun Magesh, Faiz Surani, Matthew Dahl, Mirac Suzgun, Christopher D. Manning, Daniel E. Ho (Stanford RegLab/HAI; Yale) | arXiv:2405.20362 (v1 30/mai/2024; versão em periódico citada como "Magesh et al., 2025" em arXiv:2606.21155; dados do periódico [NÃO VERIFICADO]) | Tipo: estudo empírico pré-registrado (preprint)
- Link: https://arxiv.org/abs/2405.20362 (PDF: https://arxiv.org/pdf/2405.20362) | DOI: não consta na página arXiv; DOI do periódico [NÃO VERIFICADO]
- Método e amostra: primeira avaliação pré-registrada de ferramentas de pesquisa jurídica com IA (Lexis+ AI, Westlaw AI-Assisted Research, Ask Practical Law AI) e GPT-4 como referência; 202 consultas jurídicas ("over 200 legal queries"); revisão manual das respostas; tipologia de alucinação (incorreta/ não fundamentada) (Abstract; §1, p. 3).
- Números-chave: "each hallucinate between 17% and 33% of the time" (Abstract, p. 1); "Lexis+ AI is the highest-performing system we test, answering 65% of our queries accurately. Westlaw's AI-Assisted Research is accurate 42% of the time, but hallucinates nearly twice as often as the other legal tools" (§1, p. 3); "Ask Practical Law AI provides incomplete answers (refusals or ungrounded responses...) on more than 60% of our queries" (§1, p. 3); "Over 1 in 6 of our queries caused Lexis+ AI and Ask Practical Law AI to respond with misleading or false information. And Westlaw hallucinated substantially more—one-third of its responses contained a hallucination" (§6.1); "accurate ... for 65% of queries, compared to much lower accuracy rates of 41% and 19% by Westlaw and Practical Law AI" (§6.1; o texto traz 42% em §1 e 41% em §6.1, como no original). Contrário ao marketing: o artigo cita as promessas "hallucination-free" (LexisNexis), "eliminating" (Casetext), "avoid[ing]" (Thomson Reuters).
- Limitações declaradas (§7, p. 21-22): só 3 produtos; "our evaluation only captures a point in time"; amostra de 202 consultas "small in comparison to other evaluations"; avaliação de ferramentas de acesso restrito; groundedness "may exist on a spectrum".
- Status: Verificado na fonte original (PDF v1).

## 2. Who Checks the Citations? Benchmarking Legal Hallucination Detection (LePhantom)
- Autores/veículo: Patty Liu, Dominik Stammbach, Peter Henderson (Princeton) | arXiv:2606.21155 (versão de 19/jun/2026; online 04/out/2026 conforme metadados) | Tipo: estudo empírico (preprint) com compilação de casos reais + benchmark semissintético
- Link: https://arxiv.org/abs/2606.21155 (PDF: https://arxiv.org/pdf/2606.21155) | DOI: não consta
- Método e amostra: (a) compilação de petições judiciais com citações fabricadas, combinada com dados de Charlotin (2026); (b) experimento controlado com oito gerações de modelos ChatGPT em 92 prompts de redação jurídica; (c) benchmark de 1.300 trechos de petições com erros injetados (1.000 trechos de petições reais de apelação, 5.648 segmentos de origem), cinco modelos em modo agêntico e não agêntico mais Claude Code (Abstract; §1; §2; §5).
- Números-chave: "we found over 1,000 filings containing fabricated citations—with this number growing year-over-year" (Abstract, p. 1); "Early GPT-4o models released in mid-2024 exhibit the lowest hallucination rates at 1.23%, substantially improving over citation rates of around 25% in earlier GPT-3.5 models. However, this trend does not persist ... The GPT-5.1 model generates hallucinated citations at 6.57%, a higher rate than the August 2024 GPT-4o release (using bootstrapping, p = 0.001)" (§2, p. 4); "GPT-5 achieves 84.4% recall and a 55.0% F1 score in an agentic framework"; "GPT-5 averaging 15.3 steps per excerpt" (Abstract). Cita sanções judiciais, ex.: Mid Cent. Operating Eng'rs Health & Welfare Fund v. HoosierVac LLC, 2025 WL 574234 (S.D. Ind. 21/fev/2025), e Noland v. Land of the Free, 114 Cal.App.5th 426 (2025) (p. 1-2) (citações de decisões como aparecem no paper; decisões em si [NÃO VERIFICADO]). Resultado contrário à narrativa de "alucinação em queda": o paper afirma que os dados desafiam a premissa de que "hallucination rates would diminish as models improve" (§1, p. 2).
- Limitações declaradas (§5.3, p. 12): "the semi-synthetic nature of our benchmark means that results may not fully generalize to the distribution of hallucinations in real filings"; "Our benchmark should primarily be treated as a controlled lower bound on verification difficulty"; definição de alucinação "captures only the most obvious hallucinations and provides a conservative lower bound" (§2); avaliação em trechos curtos, não briefs completos.
- Status: Verificado na fonte original (PDF).

## 3. From Incidents to Insights: Patterns of Responsibility following AI Harms
- Autores/veículo: Isabel Richards, Claire Benn, Miri Zilka | arXiv:2505.04291 | 07/mai/2025 | Tipo: estudo empírico (preprint), análise mista do AI Incident Database
- Link: https://arxiv.org/abs/2505.04291 (PDF: https://arxiv.org/pdf/2505.04291) | DOI: não consta
- Método e amostra: análise de três níveis, método misto, de 962 incidentes e 4.743 relatos do AIID (download em 10/mar/2025), com foco nos incidentes com resposta pública registrada (Abstract; §3).
- Números-chave: "962 incidents and 4,743 related reports" (Abstract); "We find that the presence of identifiable responsible parties does not necessarily lead to increased accountability" (Abstract). Sobre LLMs implantados por terceiros: "there were no responses in the cases of LLMs deployed by third parties" (§4, seção sobre desenvolvedores/implantadores, p. ~11); caso citado: mudanças no uso de reconhecimento facial pela polícia de Detroit "following 3 false arrests and one successful lawsuit" (mesma seção).
- Limitações declaradas (§3.2.4, p. 6): "The incidents captured in the AIID are not a full, nor a representative set of the type and frequency of AI-related harms worldwide"; "accumulated data typically reflects reporting behaviour more than occurrence"; relatos de mídia "lack detailed information about the implemented systems"; quase só mídia em inglês.
- Status: Verificado na fonte original (PDF).

## 4. AI Index Report 2025, cap. 3 (Responsible AI): AI Incident Database
- Autores/veículo: Stanford HAI, AI Index Steering Committee | abr/2025 | Tipo: relatório institucional (compilação; fonte primária dos incidentes: AI Incident Database)
- Link: https://hai.stanford.edu/ai-index/2025-ai-index-report (PDF: https://hai.stanford.edu/assets/files/hai_ai_index_report_2025.pdf)
- Método e amostra: contagem anual de incidentes registrados no AIID, que depende de relatos públicos de mídia (§3.2 "AI Incidents", PDF p. 168).
- Números-chave: "AI-related incidents sharply increased in 2024, reaching a record high of 233—a 56.4% increase from 2023 (Figure 3.2.1)" (§3.2, PDF p. 168; também nos destaques do cap. 3).
- Limitações declaradas (§3.2): "Current incident tracking relies on publicly available media reports, meaning the actual number of incidents is likely higher, as many go unreported"; "no consensus has been reached on a standard definition" de incidente; o aumento "likely reflects both the expanding use of AI and heightened public awareness" e possivelmente mais reporte.
- Status: Verificado na fonte original (PDF).

## 5. AI Index Report 2026, cap. 3 (Responsible AI): incidentes, alucinação e incidentes em organizações
- Autores/veículo: Stanford HAI, AI Index Steering Committee | 2026 | Tipo: relatório institucional (compilação de AIID, OECD AIM, McKinsey Survey, benchmarks Vectara HHEM e AA-Omniscience)
- Link: https://hai.stanford.edu/ai-index/2026-ai-index-report (PDF: https://hai.stanford.edu/assets/files/ai_index_report_2026.pdf)
- Método e amostra: contagem do AIID (editores humanos, mídia em inglês); OECD AI Incidents and Hazards Monitor (pipeline automático multilíngue); survey McKinsey 2025 de organizações; benchmark HHEM (resumo de documentos CNN/Daily Mail, top 15 modelos); AA-Omniscience (6.000 perguntas, 6 domínios incl. direito e saúde, 26 modelos) (§3.2, §3.3).
- Números-chave: "Documented AI incidents rose to 362, up from 233 in 2024" (Top takeaways, PDF p. 9); "In 2025, 362 incidents were reported, while the annual number of incidents had stayed under 100 until 2022" (§3.2, PDF p. 132); OECD AIM: "monthly incidents hitting a peak of 435 in January 2026 and setting a six-month moving average of 326" (§3.2); HHEM: taxas de alucinação "range from 1.8% to 5.4%—with most clustering in the 4%–5% range"; "Last year's leaderboard showed top models achieving rates of 1.3%–2.9%, but the current results reflect a different set of models" (§3.2); AA-Omniscience: "Across 26 models, hallucination rates range from 22% to 94% ... Grok 4.20 Beta 0305 had the lowest rate (22%), followed by Claude 4.5 Haiku (26%) ... gpt-oss-20B (high) reached 94% and Gemini 3 Flash reached 92%" (§3.2, PDF p. 136); survey de organizações: "The share of organizations reporting AI incidents remained steady at 8% in both 2024 and 2025"; entre as que reportaram, "the share that experienced 3–5 incidents rose from 30% in 2024 to 50% in 2025"; resposta a incidentes "excellent": 28% (2024) para 18% (2025); inexatidão como risco relevante: 60% para 74% (§3.3, PDF p. 141).
- Limitações declaradas: AIID tem "coverage that is skewed toward English-language media and high-visibility incidents"; nota 2: o número de incidentes "is continually updated, including for previous years"; as escalas de HHEM e AA-Omniscience "are not directly comparable" (§3.2).
- Status: Verificado na fonte original (PDF).

## 6. Project Vend: Can Claude run a small shop? (fase 1)
- Autores/veículo: Anthropic Frontier Red Team em parceria com Andon Labs (post institucional do desenvolvedor do modelo avaliado; relato do próprio fornecedor, não terceiro independente) | 27/jun/2025 | Tipo: caso real documentado/experimento de campo (n = 1 agente, ~1 mês)
- Link: https://www.anthropic.com/research/project-vend-1
- Fatos e consequência: Claude Sonnet 3.7 ("Claudius") operou por cerca de um mês uma loja automatizada no escritório de São Francisco, com busca na web, e-mail simulado, Slack e controle de preços. Falhas relatadas: "Hallucinating important details: Claudius received payments via Venmo but for a time instructed customers to remit payment to an account that it hallucinated"; vendas abaixo do custo ("Selling at a loss"); concessão de descontos e itens grátis após insistência de clientes; recusou oferta de US$ 100 por seis latas de Irn-Bru "which can be purchased online in the US for $15". Em 31/mar-1/abr/2025 alucinou uma conversa com "Sarah at Andon Labs" (pessoa inexistente) e disse que entregaria produtos "in person" de blazer azul e gravata vermelha. Conclusão do texto sobre o negócio: "did not succeed at making money" (seção "Claude's performance review"); "we would not hire Claudius".
- Números-chave: o texto não traz tabela numérica; o gráfico "net value over time" (Fig. 3) não tem valor extraído [NÃO VERIFICADO].
- Limitações declaradas: "Many of the mistakes Claudius made are very likely the result of the model needing additional scaffolding"; o experimento é de uma única instância em um escritório com clientes que são funcionários da própria empresa (os "customers" são "Anthropic employees").
- Status: Verificado na fonte original (página).

## 7. Project Vend: Phase two
- Autores/veículo: Anthropic Frontier Red Team (post institucional do fornecedor) | 18/dez/2025 | Tipo: caso real documentado/experimento de campo (continuação), com resultados mistos
- Link: https://www.anthropic.com/research/project-vend-2
- Fatos e consequência: segunda fase com mais ferramentas (CRM, regras de margem) e um agente "CEO" (Seymour Cash) supervisor; três lojas (San Francisco, New York, London). O texto diz que o negócio melhorou ("weeks with negative profit margin were largely eliminated"), mas "the same eagerness to please that we observed in phase one still made Claudius a mark for some of the more adversarial testers among our staff" e "the gap between 'capable' and 'completely robust' remains wide".
- Números-chave: "After introducing the CEO, the number of discounts was reduced by about 80% and the number of items given away cut in half"; o CEO "denied over one hundred requests from Claudius for lenient financial treatment of customers" mas "authorized such requests about eight times as often as it denied them"; "It's possible that a more disciplined leader could have led to a more profitable phase two. But Seymour Cash does not seem to have been the right executive for this business." Valores monetários agregados de lucro: não há tabela numérica no texto [NÃO VERIFICADO].
- Limitações declaradas: "there is not a completely clean demarcation between phases; we continued to iterate on the architecture throughout"; red teaming interno desacelerou ao longo do tempo (o que afeta a leitura da robustez).
- Status: Verificado na fonte original (página).

## 8. Clinical knowledge in LLMs does not translate to human interactions (RCT com 1.298 participantes; resultado negativo para uso público)
- Autores/veículo: Andrew M. Bean, Rebecca Payne, Guy Parsons, Hannah Rose Kirk, Juan Ciro, Rafael Mosquera, Sara Hincapié Monsalve, Aruna S. Ekanayaka, Lionel Tarassenko, Luc Rocher, Adam Mahdi (Oxford Internet Institute e outros) | arXiv:2504.18919 (v1 26/abr/2025) | Tipo: estudo empírico (preprint), ensaio randomizado
- Link: https://arxiv.org/abs/2504.18919 (PDF: https://arxiv.org/pdf/2504.18919) | DOI: não consta na página arXiv
- Método e amostra: ensaio randomizado controlado com 1.298 participantes do Reino Unido (maiores de 18, amostra estratificada para refletir a demografia do UK via Prolific) em 10 cenários médicos; braços: GPT-4o, Llama 3, Command R+ ou fonte de escolha (controle); desfechos: identificar condições e escolher a disposição (nível de cuidado); comparação com LLM sozinho e com participantes simulados por LLM (Abstract; Methods).
- Números-chave (Abstract, p. 1): "Tested alone, LLMs complete the scenarios accurately, correctly identifying conditions in 94.9% of cases and disposition in 56.3% on average. However, participants using the same LLMs identified relevant conditions in less than 34.5% of cases and disposition in less than 44.2%, both no better than the control group." Resultados: participantes com LLM identificaram condições relevantes menos que o controle (n1 = n2 = 600, p < 0,001 para os três modelos); "Participants in the control group had 1.76 (95% CI = 1.45 − 2.13) times higher odds of identifying a relevant condition than the aggregate of the participants using LLMs" (Results, p. ~5-6). "Standard benchmarks for medical knowledge and simulated patient interactions do not predict the failures we find with human participants" (Abstract).
- Limitações declaradas (Discussion, p. 12-13): o desempenho do LLM sozinho é "a minimum estimate" (sem chain of thought); modelos testados são os mais usados, não modelos ajustados para saúde; no estudo os usuários "have all of the information" do cenário, o que "is not representative of clinical practice"; participantes simulados por LLM "do not seem to accurately reflect human-LLM interactions".
- Status: Verificado na fonte original (PDF v1). Publicação em periódico: o PDF cita Nature Medicine só em referências; versão publicada [NÃO VERIFICADO].

## 9. Medical Hallucinations in Foundation Models and Their Impact on Healthcare
- Autores/veículo: Yubin Kim, Hyewon Jeong, Shan Chen, Shuyue Stella Li, Chanwoo Park, Mingyu Lu e outros | arXiv:2503.05777 (v1 26/fev/2025; versão de nov/2025) | Tipo: estudo empírico (preprint): benchmark + auditoria por médicos + survey
- Link: https://arxiv.org/abs/2503.05777 (PDF: https://arxiv.org/pdf/2503.05777) | DOI: não consta na página arXiv
- Método e amostra: 11 modelos de fundação (7 de uso geral, 4 médicos especializados) em sete tarefas de alucinação médica (raciocínio médico e recuperação de informação biomédica); auditoria por médicos das alucinações residuais; survey global com profissionais de saúde/pesquisa (set-dez/2024) (Abstract; §6; §8).
- Números-chave (Abstract, p. 1): "General-purpose models achieved significantly higher proportions of hallucination-free responses than medical-specialized models (median: 76.6% vs 51.3%, difference = 25.2%, 95% CI: 18.7-31.3%...p = 0.012)"; "Gemini-2.5 Pro exceeded 97% accuracy when augmented with chain-of-thought prompting (base: 87.6%), while medical-specialized models like MedGemma ranged from 28.6-61.9%"; "Physician audits confirmed that 64-72% of residual hallucinations stemmed from causal or temporal reasoning failures rather than knowledge gaps"; "A global survey of clinicians (n = 70) ... 91.8% had encountered medical hallucinations, and 84.7% considered them capable of causing patient harm". Inconsistência interna: §8 (p. 28) descreve "A total of 75 professionals participated" enquanto o Abstract diz n = 70.
- Limitações declaradas: seção específica de limitações do estudo não localizada no texto (a seção 8.7 trata de limitações dos LLMs) [NÃO VERIFICADO quanto a declaração de limitações do estudo]. Survey por conveniência de profissionais com MD/PhD, 94 dias (§8).
- Status: Verificado na fonte original (PDF).

## 10. Directional AI Advice: Experimental Evidence from Healthcare (campo, hospital chinês)
- Autores/veículo: Yuyu Chen, Hongbin Li, Lingsheng Meng, Xinyao Qiu, Qingxu Yang | arXiv:2607.08706 | 09/jul/2026 | Tipo: estudo empírico (preprint), experimento de campo pré-registrado
- Link: https://arxiv.org/abs/2607.08706 (PDF: https://arxiv.org/pdf/2607.08706) | DOI: não consta
- Método e amostra: randomização em duas camadas (médicos e pacientes) de acesso a um chatbot de IA antes de consulta ambulatorial em um grande hospital público na China; "over 10,000 outpatient visits" (Introdução).
- Números-chave (Introdução): 17% dos pacientes com acesso usaram o chatbot; cautelas contra medicamentos em 69,7% das menções gerais de medicação, 90,8% das menções a Medicina Tradicional Chinesa e 87,6% das menções a antibióticos, contra "clean recommendations ... 94.5%" para testes diagnósticos; acesso ao chatbot "reduces the likelihood of receiving any prescription by 4.6 percentage points relative to a baseline of 87%" e "increases the probability that a visit includes diagnostic testing by 2.7 percentage points from a baseline of 23%"; o texto liga o padrão a "liability-driven guardrails" e a limitar "legal exposure" dos desenvolvedores (Introdução). Efeitos de uso (LATE): prescrição -27 p.p., testes +16 p.p. (Introdução).
- Limitações declaradas: efeitos principais são intent-to-treat; take-up de 17% e estimativas de uso são "local average treatment effects"; persistência "suggestive". Seção formal de limitações [NÃO VERIFICADO].
- Status: Verificado na fonte original (PDF).

## 11. Language Model Agents Under Attack: A Cross Model-Benchmark of Profit-Seeking Behaviors in Customer Service
- Autores/veículo: Jingyu Zhang | arXiv:2512.24415 | 30/dez/2025 | Tipo: estudo empírico (preprint), benchmark
- Link: https://arxiv.org/abs/2512.24415 (PDF: https://arxiv.org/pdf/2512.24415) | DOI: não consta
- Método e amostra: 10 domínios de atendimento (reembolso, remarcação, disputas de cobrança etc.), 100 scripts de ataque (injeção de prompt direta) em cinco famílias de técnicas; cinco modelos (DeepSeek v3.2, Claude Opus 4.1, GPT-5, GPT-4o, Gemini 2.5 Pro); avaliação por dois LLMs juízes (GPT-5 e Claude Opus 4.1) com rubrica 0-5.
- Números-chave: "airline support is most exploitable"; probabilidade ajustada de sucesso de ataque por modelo: DeepSeek 0,265 (IC 95% [0,209; 0,317]), GPT-5 0,225 ([0,161; 0,263]), Gemini 0,140 ([0,102; 0,190]), GPT-4o 0,085 ([0,057; 0,123]), Claude 0,065 ([0,039; 0,107]) (§5.2); companhia aérea excede outros domínios "by roughly 0.28–0.54 in absolute success rate units" (§5.1).
- Limitações declaradas (§6.1): "should be interpreted as relative diagnostics over the benchmark scope (10 scenarios, 100 injected conversations), not as universal real-world risk rankings"; é "an initial-exposure stress test for conversational customer-service agents"; extensão a agentes com ferramentas exige avaliação multi-etapas; juízes são LLMs.
- Status: Verificado na fonte original (PDF).

## 12. Acórdão do TJUE, Processo C-203/22 (CK v Magistrat der Stadt Wien; Dun & Bradstreet Austria): explicação de decisão automatizada (scoring de crédito)
- Autores/veículo: Tribunal de Justiça da União Europeia (Primeira Secção), reenvio prejudicial do Verwaltungsgericht Wien | 27/fev/2025 | Tipo: decisão judicial
- Link: https://eur-lex.europa.eu/legal-content/EN/TXT/HTML/?uri=CELEX:62022CJ0203 (CELEX 62022CJ0203)
- Fatos e consequência: pedido de acesso a "informação significativa sobre a lógica envolvida" em uma decisão automatizada de crédito (scoring de solvabilidade, IA preditiva), com a empresa invocando segredo comercial. Dispositivo (item 1): o titular dos dados pode exigir do controlador "to explain, by means of relevant information and in a concise, transparent, intelligible and easily accessible form, the procedure and principles actually applied in order to use, by automated means, the personal data concerning that person with a view to obtaining a specific result, such as a credit profile". Item 2: se o controlador alega segredo comercial ou dados de terceiros, "is required to provide the allegedly protected information to the competent supervisory authority or court, which must balance the rights and interests at issue". No texto (considerando ~59-62), "the complexity of the operations to be carried out in the context of automated decision-making [is not] capable of relieving the controller of the duty to provide an explanation" e a mera comunicação de "a complex mathematical formula, such as an algorithm" não satisfaz o requisito.
- Números-chave: não há dados quantitativos; o texto é o dispositivo e os parágrafos citados (Art. 15(1)(h) GDPR e Art. 22(1)).
- Limitações declaradas: não se aplica (decisão judicial); o acórdão trata de GDPR e não de alucinação de IA generativa.
- Status: Verificado na fonte original (EUR-Lex, texto em inglês).

## 13. Diretiva (UE) 2024/2853 sobre responsabilidade por produtos defeituosos (software e sistemas de IA como "produto")
- Autores/veículo: Parlamento Europeu e Conselho da UE | Jornal Oficial L, 18/nov/2024 (diretiva de 23/out/2024; aplica-se a produtos colocados no mercado após 09/dez/2026) | Tipo: ato regulatório
- Link: https://eur-lex.europa.eu/legal-content/EN/TXT/HTML/?uri=CELEX:32024L2853 (CELEX 32024L2853)
- Fatos e consequência: art. 4(1): "'product' means all movables ... it includes electricity, digital manufacturing files, raw materials and software"; considerando: "Software, such as operating systems, firmware, computer programs, applications or AI systems ... should be clarified ... that software is a product for the purposes of applying no-fault liability"; considerando: a "destruction or corruption of data" não usada profissionalmente é indenizável; art. 9 (divulgação de provas); art. 10(2): presume-se defeito se o réu não divulga provas relevantes ou se há "obvious malfunction of the product during reasonably foreseeable use"; art. 10(4): presunção judicial quando o autor enfrenta "excessive difficulties, in particular due to technical or scientific complexity"; art. 2(1): "shall apply to products placed on the market or put into service after 9 December 2026"; art. 22: transposição até 09/dez/2026.
- Números-chave: datas acima (09/dez/2026).
- Limitações declaradas: art. 2(2): não se aplica a software livre e de código aberto fora de atividade comercial; só pessoas naturais são indenizadas (considerando sobre danos a propriedade de uso exclusivamente profissional). Data da fonte anterior ao período (publicação nov/2024), incluída por seus efeitos a partir de 2026.
- Status: Verificado na fonte original (EUR-Lex).

## 14. Regulamento (UE) 2024/1689 (AI Act): supervisão humana, exatidão e sanções
- Autores/veículo: Parlamento Europeu e Conselho da UE | Jornal Oficial L, 12/jul/2024 (regulamento de 13/jun/2024); aplicação escalonada a partir de 02/fev/2025 | Tipo: ato regulatório
- Link: https://eur-lex.europa.eu/legal-content/EN/TXT/HTML/?uri=CELEX:32024R1689 (CELEX 32024R1689)
- Fatos e consequência: art. 14(1)/(4)(b): sistemas de alto risco devem permitir supervisão por pessoas, inclusive estar "aware of the possible tendency of automatically relying or over-relying on the output produced by a high-risk AI system (automation bias)"; art. 15(1): "appropriate level of accuracy, robustness, and cybersecurity"; art. 99(3): multas por práticas proibidas "up to EUR 35 000 000 or ... up to 7 % of its total worldwide annual turnover"; art. 99(4): outras infrações de operadores "up to EUR 15 000 000 or ... up to 3 %"; art. 113: "It shall apply from 2 August 2026. However: (a) Chapters I and II shall apply from 2 February 2025; (b) Chapter III Section 4, Chapter V, Chapter VII and Chapter XII and Article 78 shall apply from 2 August 2025".
- Números-chave: acima.
- Limitações declaradas: a versão acima é a original de 2024; as datas de aplicação de obrigações de alto risco são objeto da proposta de alteração descrita na fonte 15 (status final da alteração em nov/2026 [NÃO VERIFICADO]).
- Status: Verificado na fonte original (EUR-Lex).

## 15. Proposta COM(2025) 836 (Digital Omnibus on AI) e Programa de Trabalho da Comissão 2025, COM(2025) 45 (retirada prevista da Diretiva de Responsabilidade por IA)
- Autores/veículo: Comissão Europeia | COM(2025) 45 de 11/fev/2025; COM(2025) 836 de 19/nov/2025 | Tipo: ato regulatório (propostas/comunicação)
- Link: https://eur-lex.europa.eu/legal-content/EN/TXT/HTML/?uri=CELEX:52025DC0045 e https://eur-lex.europa.eu/legal-content/EN/TXT/HTML/?uri=CELEX:52025PC0836
- Fatos e consequência: COM(2025) 45, Anexo IV (retiradas), item 32: proposta COM(2022)496 "on adapting non-contractual civil liability rules to artificial intelligence (AI Liability)": "No foreseeable agreement - the Commission will assess whether another proposal should be tabled or another type of approach should be chosen." COM(2025) 836 (Exposição de motivos): "all rules entering into application by 2 August 2027 ... most provisions – in particular those governing high-risk AI systems – will only start to apply from 2 August 2026 or 2 August 2027"; a proposta cria um mecanismo que "links the entry into application to the availability of measures in support of compliance" (normas harmonizadas, orientações), com data-limite definida.
- Números-chave: datas acima. Datas-limite específicas da proposta (ex.: dez/2027, ago/2028) não conferidas [NÃO VERIFICADO].
- Limitações declaradas: são propostas; a adoção final e o texto vigente em nov/2026 [NÃO VERIFICADO]. A retirada da AILD aparece como intenção na Comunicação, com o formal da retirada [NÃO VERIFICADO].
- Status: Verificado na fonte original (EUR-Lex) quanto ao texto das propostas.

---

Nota: as entradas 16 a 27 abaixo são casos e decisões cujas fontes primárias (tribunais, jornais, escritórios) estão em domínios bloqueados nesta sessão. Os dados vêm de resumos de busca (WebSearch) com URLs dos resultados; nenhuma página original foi aberta. Cada entrada tem o campo "Status" com o marcador.

## 16. Ayinde v London Borough of Haringey; Al-Haroun v Qatar National Bank, [2025] EWHC 1383 (Admin) (Divisional Court)
- Autores/veículo: High Court of England and Wales, Divisional Court | 06/jun/2025 | Tipo: decisão judicial
- Link: https://caselaw.nationalarchives.gov.uk/ewhc/admin/2025/1383 (URL do resultado de busca; página não aberta)
- Fatos e consequência (segundo o resumo de busca): revisão judicial contra o município de Haringey com petição que citava cinco autoridades inexistentes (Ayinde); no caso Al-Haroun, declaração de testemunha com 45 citações, 18 totalmente fictícias; o tribunal concluiu que a representante de Ayinde "either deliberately included fake citations ... or used generative AI tools and lied about it"; advertência de que ao menos a inclusão de citações falsas "is likely to result in a referral to a regulator and a wasted costs award"; frase atribuída ao acórdão: "Artificial intelligence is a tool that carries with it risks as well as opportunities". Citado depois em [2026] UKUT 81 (IAC) (https://caselaw.nationalarchives.gov.uk/ukut/iac/2026/81).
- Números-chave: 5 citações inexistentes (Ayinde); 45 citações, 18 fictícias (Al-Haroun) [NÃO VERIFICADO]
- Limitações declaradas: não aplicável (decisão judicial). O resumo de busca registra divergência entre fontes sobre contagens e sobre a citação neutra de primeira instância (EWHC 1040 (Admin)).
- Status: não aberto na origem (caselaw.nationalarchives.gov.uk bloqueado) [NÃO VERIFICADO]

## 17. Johnson v. Dunn (N.D. Ala., No. 2:21-cv-01701), ordem de sanções contra advogados do escritório Butler Snow
- Autores/veículo: U.S. District Court, N.D. Alabama (Juíza Anna Manasco) | 23/jul/2025 | Tipo: decisão judicial
- Link: https://www.docketalarm.com/cases/Alabama_Northern_District_Court/2--21-cv-01701/Johnson_v._Dunn_et_al/204 (URL do resultado de busca; não aberta); análise: https://edrm.net/2025/07/when-ai-policies-fail-the-ai-sanctions-in-johnson-v-dunn-and-what-they-mean-for-the-profession/
- Fatos e consequência (segundo o resumo de busca): caso de litígio prisional; cinco citações problemáticas em duas petições da defesa, atribuídas a IA generativa; sanções a três advogados do Butler Snow: desqualificação do caso, encaminhamento à ordem, e comunicação obrigatória a clientes e a outros tribunais; a firma havia advertido os advogados sobre LLMs desde 2023.
- Números-chave: 5 citações, 2 petições, 3 advogados sancionados [NÃO VERIFICADO]
- Limitações declaradas: o resumo de busca informa que parte da cobertura inicial citava 4 decisões fabricadas; a ordem teria 5.
- Status: não aberto na origem (docketalarm.com e edrm.net bloqueados) [NÃO VERIFICADO]

## 18. Coomer v. Lindell (D. Colo., No. 1:22-cv-01129), ordem de 07/jul/2025: multas a advogados por petição com erros de IA
- Autores/veículo: U.S. District Court, D. Colorado (Juíza Nina Y. Wang) | 07/jul/2025 | Tipo: decisão judicial
- Link: https://news.bloomberglaw.com/litigation/mike-lindell-my-pillow-lawyers-fined-ai (reportagem; não aberta); AI Incident Database: https://incidentdatabase.ai/reports/6175
- Fatos e consequência (segundo o resumo de busca): violação da Regra 11; duas multas de US$ 3.000 (Christopher Kachouroff e seu escritório, de um lado; Jennifer DeMaster, de outro), pagáveis até 4/ago; petição com "numerous errors including fake cases, misquotes", cerca de 30 erros segundo uma reportagem; Mike Lindell e a MyPillow não foram sancionados.
- Números-chave: 2 multas de US$ 3.000; ~30 erros [NÃO VERIFICADO]
- Limitações declaradas: o próprio resumo diz que a ordem não foi acessada, só cobertura de imprensa.
- Status: não aberto na origem (news.bloomberglaw.com e incidentdatabase.ai bloqueados) [NÃO VERIFICADO]

## 19. Wadsworth v. Walmart Inc. (D. Wyo., No. 2:23-cv-118-KHR), ordem de 24/fev/2025: sanções a advogados da Morgan & Morgan
- Autores/veículo: U.S. District Court, D. Wyoming | 24/fev/2025 | Tipo: decisão judicial
- Link: https://news.bloomberglaw.com/us-law-week/morgan-morgan-lawyers-fined-for-hallucinated-ai-citations (reportagem; não aberta); https://todaysgeneralcounsel.com/attorneys-sanctioned-because-of-ai-fabricated-case-citations/
- Fatos e consequência (segundo o resumo de busca): moção in limine com oito citações de casos inexistentes geradas por IA interna; advogado Rudwin Ayala teve a admissão pro hac vice revogada e multa de US$ 3.000; dois outros advogados, US$ 1.000 cada (total US$ 5.000); a firma pediu desculpas, retirou a moção, pagou honorários da parte contrária e implementou treinamento. Caso subjacente: responsabilidade por produto (hoverboard e incêndio).
- Números-chave: 8 citações inexistentes; US$ 3.000 + 2 x US$ 1.000 [NÃO VERIFICADO]
- Limitações declaradas: o resumo de busca registra divergência sobre se a firma foi penalizada.
- Status: não aberto na origem [NÃO VERIFICADO]

## 20. Noland v. Land of the Free, L.P., 114 Cal.App.5th 426 (Cal. Ct. App. 2d Dist., 12/set/2025)
- Autores/veículo: California Court of Appeal | 12/set/2025 | Tipo: decisão judicial (primeira opinião publicada na Califórnia sobre citações fabricadas por IA, segundo o resumo de busca)
- Link: https://calemploymentlawupdate.proskauer.com/2025/10/attorney-sanctioned-10000-for-citing-nonexistent-ai-generated-legal-authority/ ; https://mcguirewoods.com/client-resources/alerts/2025/9/california-appellate-court-issues-10k-sanctions-in-states-first-published-opinion-on-ai-hallucinated-case-citations (URLs de resultados de busca; não abertas). A citação "114 Cal.App.5th 426, 445 (2025)" aparece no PDF aberto da fonte 2 (arXiv:2606.21155, p. 1) como citação de Noland, o que confirma a existência da citação, não o conteúdo.
- Fatos e consequência (segundo o resumo de busca): apelação contra summary judgment; peças com citações e transcrições geradas por ferramenta de IA; sanção de US$ 10.000, encaminhamento à State Bar e envio da decisão ao cliente; apelação considerada frívola; "21 of the 23 case quotations in the opening brief were fabricated" (uma fonte); seguida por People v. Alvarez (4th Dist., Div. 1).
- Números-chave: US$ 10.000; 21 de 23 citações [NÃO VERIFICADO]
- Limitações declaradas: o resumo de busca aponta que fontes divergem sobre quais ferramentas de IA foram usadas.
- Status: não aberto na origem [NÃO VERIFICADO]

## 21. Walters v. OpenAI, L.L.C. (Gwinnett County Superior Court, Georgia, No. 23-A-04860-2): julgamento sumário a favor da OpenAI (resultado contrário à responsabilização por alucinação)
- Autores/veículo: Superior Court of Gwinnett County, Georgia (Juíza Tracie Cason) | 19/mai/2025 | Tipo: decisão judicial
- Link: https://www.clearygottlieb.com/news-and-insights/publication-listing/georgia-court-dismisses-defamation-lawsuit-against-openai-over-chatgpt-output ; https://www.covingtonblogs.com/2025/06/16/georgia-court-dismisses-defamation-suit-against-ai-developer-openai/ ; https://www.loeb.com/en/insights/publications/2025/05/walters-v-openai-llc (URLs de resultados de busca; não abertas)
- Fatos e consequência (segundo o resumo de busca): ChatGPT afirmou falsamente que o apresentador Mark Walters era acusado de desviar fundos da Second Amendment Foundation; julgamento sumário para a OpenAI em três fundamentos: (1) a saída não poderia ser razoavelmente entendida como afirmação de fato, em parte porque o usuário sabia que o ChatGPT pode fabricar e havia avisos; (2) ausência de prova de negligência (ao menos ordinária), com rejeição de responsabilidade objetiva; (3) ausência de actual malice e de dano comprovado, sem pedido de retratação exigido pela lei da Geórgia para danos punitivos. Decisão de primeira instância estadual, sem efeito vinculante em outros foros.
- Números-chave: sem valores monetários [NÃO VERIFICADO]
- Limitações declaradas: segundo o resumo de busca, comentaristas notam que é decisão de tribunal estadual de primeira instância, não precedente vinculante.
- Status: não aberto na origem [NÃO VERIFICADO]

## 22. Relatório da Deloitte para o Departamento de Emprego e Relações de Trabalho da Austrália (DEWR): reembolso parcial após citações e citação judicial inexistentes
- Autores/veículo: reportagens (The Register, 06/out/2025; Neowin; AI Incident Database) sobre relatório da Deloitte Australia ao DEWR | out/2025 | Tipo: caso real documentado
- Link: https://www.theregister.com/2025/10/06/deloitte_ai_report_australia/ ; https://incidentdatabase.ai/reports/6247 (URLs de resultados de busca; não abertas)
- Fatos e consequência (segundo o resumo de busca): contrato de AU$ 440.000 sobre o Targeted Compliance Framework (compliance automatizado de benefícios); a versão corrigida divulga uso de "Azure OpenAI GPT-4o"; erros: três referências acadêmicas inexistentes e uma citação inventada de decisão da Federal Court, apontados pelo acadêmico Christopher Rudge (Univ. de Sydney); Deloitte devolveu a última parcela do contrato (valor aproximado de US$ 291.245 / "AU$ 290 mil" segundo as fontes); o DEWR afirmou que a substância e as recomendações permaneciam.
- Números-chave: AU$ 440.000 (valor do contrato); 3 referências inexistentes; 1 citação judicial inventada; valor do reembolso divergente entre fontes [NÃO VERIFICADO]
- Limitações declaradas: o resumo de busca informa que as fontes divergem sobre o valor do reembolso (cerca de AU$ 439.000 em algumas) e que detalhes finais do reembolso seriam divulgados pelo DEWR.
- Status: não aberto na origem (theregister.com, incidentdatabase.ai bloqueados) [NÃO VERIFICADO]

## 23. Plano de Recursos Humanos em Saúde de Terra Nova e Labrador (Deloitte): citações inexistentes
- Autores/veículo: reportagens (HR Reporter; The Independent, Canadá; AI Incident Database) | nov/2025 | Tipo: caso real documentado
- Link: https://www.hrreporter.com/focus-areas/automation-ai/ai-errors-province-grapples-with-deloitte-report-marred-by-false-citations/393782 ; https://incidentdatabase.ai/reports/6706/ (URLs de resultados de busca; não abertas)
- Fatos e consequência (segundo o resumo de busca): plano de 526 páginas publicado pelo Departamento de Saúde em mai/2025; o governo pagou "$1,598,485" à Deloitte em oito parcelas; o The Independent achou ao menos quatro citações que parecem apontar para artigos inexistentes, usadas para sustentar afirmações sobre recrutamento, incentivos, cuidados virtuais e efeitos da COVID-19; Deloitte disse ter usado IA "selectively" para algumas citações e que revisava o relatório; o governo disse que Deloitte "stand[s] by the conclusions". Em 22/nov/2025 o plano seguia no site sem divulgação de uso de IA.
- Números-chave: $1,598,485; 526 páginas; no mínimo 4 citações [NÃO VERIFICADO]
- Limitações declaradas: o resumo de busca informa que não há resultados posteriores a fins de 2025; desfecho da revisão não confirmado.
- Status: não aberto na origem [NÃO VERIFICADO]

## 24. Banco "AI Hallucination Cases" (Damien Charlotin): contagem de decisões judiciais com conteúdo alucinado
- Autores/veículo: Damien Charlotin (base de dados); contagens citadas por Bloomberg Law (29/dez/2025), blog de terceiros (ago/2026), artigos de ordens de advogados | 2025-2026 | Tipo: banco de incidentes / relatório com metodologia declarada (compilação de decisões)
- Link: https://www.damiencharlotin.com/hallucinations/ (base; domínio bloqueado); Bloomberg Law: https://news.bgov.com/bloomberg-government-news/ai-faked-cases-become-core-issue-irritating-overworked-judges ; cópia do paper 2606.21155 (aberto, fonte 2) usa a base: "merged with additional data from Charlotin (2026)"
- Método e amostra: compilação contínua de decisões em que tribunais constataram conteúdo alucinado em petições (EUA e outros países); inclusão manual.
- Números-chave (segundo resumos de busca): Bloomberg Law, 29/dez/2025: "estimated 712 legal decisions written about hallucinated content in court cases around the world, with about 90% of those decisions written in 2025"; ritmo de "five or six a day" em dez/2025 (2-3/dia em set/2025); blog de terceiros em 29/ago/2026: 1.981 casos, 1.363 nos EUA; atualização de 18/jun/2026: 1.624 casos; artigo de ordem de advogados: "in 2025, out of 524 recorded instances, monetary sanctions were levied in 97 cases"; maior multa individual relatada, cerca de US$ 109.700; abril/2026: 470 advogados e 725 litigantes sem advogado [NÃO VERIFICADO]. Do paper aberto (fonte 2, p. 1): "over 1,000 filings containing fabricated citations" (verificado).
- Limitações declaradas: o resumo de busca informa que os números divergem por data e método de contagem, e que o mantenedor relatou cansaço em manter o banco (Bloomberg).
- Status: base e contagens não abertas na origem [NÃO VERIFICADO]; apenas a menção "over 1,000 filings" foi verificada em arXiv:2606.21155

## 25. Estate of Lokken v. UnitedHealth Group (D. Minn., No. 0:23-cv-03514): decisão de 13/fev/2025 sobre uso do algoritmo nH Predict em negativas de cobertura (IA preditiva)
- Autores/veículo: U.S. District Court, D. Minnesota | 13/fev/2025 (decisão sobre moção de dismissal); ordem de discovery de 08/set/2025 | Tipo: decisão judicial (ação coletiva em andamento)
- Link: https://litigationtracker.law.georgetown.edu/wp-content/uploads/2023/11/Lokken_2025.02.13_MEMORANDUM-OPINION-AND-ORDER.pdf (URL do resultado de busca; não aberta); https://www.dlapiper.com/insights/publications/ai-outlook/2025/lawsuit-over-ai-usage-by-medicare-advantage-plans-allowed-to-proceed (número do processo inferido de URL de resultado; não aberto)
- Fatos e consequência (segundo o resumo de busca): beneficiários de Medicare Advantage alegam que o nH Predict (naviHealth) foi usado para negar cobertura de cuidados pós-agudos; o tribunal manteve apenas as alegações de quebra de contrato e de violação do dever implícito de boa-fé, dispensando a maioria das demais por preempção do Medicare Act; ordem de discovery ampla em set/2025; em fev/2026 os réus resistiam a discovery sobre o desenho do nH Predict; sem sentença final nem certificação de classe encontradas.
- Números-chave: alegação de que "over 90% of claim denials are reversed on appeal and over 80% of preauthorization denials are reversed" [NÃO VERIFICADO] (o resumo de busca ressalta que "90% error rate" é uma alegação sobre reversões em recurso e não uma taxa de erro medida, e que a UHC nega usar o nH Predict).
- Limitações declaradas: o resumo de busca informa que o ponto de 90% vem de site de advocacy e é alegação dos autores.
- Status: não aberto na origem [NÃO VERIFICADO]

## 26. Wolf River Electric v. Google (AI Overviews, difamação) e decisão do tribunal de Munique contra o Google por AI Overviews
- Autores/veículo: ação em tribunal estadual de Minnesota (mar/2025), removida para tribunal federal; decisão provisória de tribunal em Munique | 2025-2026 | Tipo: caso real documentado / decisão judicial
- Link: https://minnlawyer.com/2025/06/13/wolf-river-electric-google-ai-defamation-lawsuit/ ; https://reason.com/volokh/2025/06/11/large-libel-models-small-business-sues-google-claiming-ai-overview-in-searches-hallucinated-attorney-general-lawsuit/ ; https://vibegraveyard.ai/story/google-ai-overviews-munich-court-liability/ (URLs de resultados de busca; não abertas)
- Fatos e consequência (segundo o resumo de busca): a empresa Wolf River Electric alega que o AI Overview do Google afirmou falsamente que o procurador-geral de Minnesota a processava; pede dano reportado entre US$ 110 milhões e US$ 210 milhões; o caso foi removido para a corte federal; não foram encontradas decisões de mérito de 2026; separadamente, um tribunal em Munique teria decidido, em caráter provisório, que o Google pode responder por acusações falsas em AI Overviews (Google disse que recorreria).
- Números-chave: US$ 110-210 milhões (valor pedido) [NÃO VERIFICADO]
- Limitações declaradas: o resumo de busca informa que fontes são notícias e comentários de 2025 e que não há decisão de 2026 localizada; a decisão de Munique é temporária.
- Status: não aberto na origem [NÃO VERIFICADO]

## 27. Decisões brasileiras sobre jurisprudência inexistente gerada por IA e a Resolução CNJ 615/2025
- Autores/veículo: TSE, TJSC, TST, TRF4 e CNJ, segundo notícias de Migalhas, Conjur, Lex e tribunais | 2025-2026 | Tipo: decisões judiciais e ato regulatório
- Link: https://www.migalhas.com.br/quentes/443562/tse-multa-advogado-por-usar-julgados-inexistentes-criados-com-ia ; https://www.tjsc.jus.br/web/imprensa/-/tjsc-mantem-multa-por-uso-de-jurisprudencia-ficticia-gerada-com-o-auxilio-de-ia ; https://www.conjur.com.br/?p=835917 ; https://www.sedep.com.br/?p=156466 (URLs de resultados de busca; não abertas)
- Fatos e consequência (segundo o resumo de busca): TSE, nov/2025, multa de cinco salários-mínimos a advogado por julgados inexistentes e envio à OAB/BA; TSE, fev/2025, multa de R$ 2 mil a advogada em causa própria; TJSC manteve multa por litigância de má-fé por jurisprudência fictícia (voto cita a Resolução CNJ 615/2025); Sexta Turma do TST aplicou multa de 1% sobre o valor da causa a empresa e advogado; TRF4 com multas de dez salários-mínimos ao advogado; caso de prompt injection em peça processual com multa de R$ 32,8 mil (Tecnoblog).
- Números-chave: 5 salários-mínimos (TSE, nov/2025); R$ 2 mil (TSE, fev/2025); 1% do valor da causa (TST); 10 salários-mínimos (TRF4); R$ 32,8 mil [NÃO VERIFICADO]
- Limitações declaradas: o resumo de busca informa que as fontes são notícias e artigos de divulgação, não os acórdãos, e que números de processo e inteiro teor devem ser conferidos.
- Status: não aberto na origem [NÃO VERIFICADO]

