# Pesquisa v3 final revisada — consulta sobre seguro-desemprego pelo Caixa Cidadão

Pesquisador: Codex, família OpenAI. Fechamento do ciclo revisado em 14/11/2026 após a segunda auditoria do Gemini enviada pelo aluno. A v1 original e as versões anteriormente submetidas com 90/100 foram preservadas. Esta revisão documental é posterior à entrevista: não foi alterada a cronologia das decisões do aluno nem atribuída a ele análise das novas fontes.

## Mudanças da v2 para a v3, motivadas pela segunda auditoria

| Gatilho | Alteração concreta na v3 | Resultado e limite |
|---|---|---|
| AV2-01 — camada da chamada fora da matriz | Criada uma matriz própria de componentes e lacunas, logo após o inventário de atores, diferenciando interface telefônica, operador desconhecido e retaguarda do benefício | A Dataprev não representa toda a tecnologia do serviço. Componentes e papel técnico não identificado não entram na contagem de organizações confirmadas. |
| AV2-02 — fontes incompletas na linha Caixa | Separada, na célula probatória da Caixa, a fonte do agente pagador (F5/F7) das fontes da oferta telefônica (F1/F2/F4) | Cada papel tem seu conjunto de fontes explícito e seu nível de acesso preservado. Não se afirma leitura integral das páginas Caixa. |
| Item 3.3 do parecer — síntese ampla sobre competências | Explicitada a diferença entre processamento/cálculo técnico e autoridade administrativa para decidir o direito | A auditoria resumiu a v2 como exclusão de competência para “calcular”. A v2 não sustentava essa proibição técnica geral; mantemos a fronteira sem adotar essa ampliação. |
| Declaração de acesso do auditor | Acrescentada nota de proveniência sobre a verificação dos PDFs | O Codex leu e inspecionou páginas na etapa de revisão; o Gemini declara não ter aberto os PDFs. A concordância do auditor não constitui uma segunda leitura independente. |

Os dois achados AV2 são refinamentos de modelagem e rastreabilidade, não erros factuais demonstrados. Foram acolhidos por melhorarem a clareza do artefato. A auditoria v1 revisada identificou omissões substantivas tratadas por ACH-02/ACH-04/ACH-05; não se convertem os refinamentos da segunda auditoria em supostas falhas factuais para obter pontuação.

## 1. Escopo e método de verificação

O serviço concreto continua sendo a busca de informação sobre parcelas do seguro-desemprego no atendimento telefônico Caixa Cidadão. O contexto necessário ao mapa inclui responsáveis administrativos e tecnológicos que influenciam a informação, ainda que não atendam a ligação. Não se pretende descrever todo o programa nem afirmar que cada ator esteja presente em cada chamada.

A auditoria recebida contém cinco achados ACH-01 a ACH-05, cinco limitações e três oportunidades. Seu texto integral permanece em B_relatorio_auditoria_v1.md. A declaração do Gemini de consulta indexada não foi transformada em prova de leitura direta. O Codex reconferiu páginas e baixou documentos oficiais: Resolução CODEFAT nº 957/2022, contrato MTE–Dataprev nº 20/2024 e o anexo PNCP citado no parecer. As páginas pertinentes foram extraídas e inspecionadas visualmente. As fontes têm épocas e escopos diferentes; não se pressupõe vigência contratual atual nem arquitetura da URA a partir de um documento de sistemas do benefício.

## 2. Tratamento consolidado dos achados da primeira auditoria

| ID | Decisão | Alteração, evidência e limite |
|---|---|---|
| ACH-01 | Esclarecer; aceitar melhoria de identificação e defender a separação já existente | F1 usa a expressão atendimento ao cidadão para 0800 726 0207; padronizamos aqui Caixa Cidadão. Não é o SAC 0800 726 0101. Ouvidoria: 0800 725 7474, conforme F2/F4. A v1 já distinguia canais; não havia troca de números demonstrada. Omissão de horários é aprofundamento, não erro factual por si só. |
| ACH-02 | Corrigir a subespecificação institucional, com correção também da auditoria | A Caixa é agente pagador, e não apenas publicadora de orientações. F7, art. 64, § 1º, página 20, sustenta o papel. O parecer citou art. 1º, § 1º, incorretamente. Essa regra não prova, sozinha, exclusividade das funções do canal nem toda a lista de competências negativas atribuída à Caixa pelo Gemini. |
| ACH-03 | Defender a ressalva da v1 e tornar a terminologia ainda mais explícita | O tutorial foi fornecido no exercício e a v1 declarou arquitetura não confirmada. Mantemos “atendimento eletrônico publicado” como evidência; “URA” é a denominação didática do recorte. As fontes não demonstram quais demandas do seguro-desemprego são resolvidas eletronicamente, menus, teclado, reconhecimento de fala ou IA. |
| ACH-04 | Aceitar omissão relevante na pesquisa de influências, com fonte mais precisa e limites | Incluída a Dataprev como participante tecnológico do ecossistema do benefício, não operadora presumida da URA. F8, contrato 20/2024, páginas 14, 18 e 125, documenta serviços de TIC e envio de lotes de pagamento à Caixa. O link genérico de artigos da auditoria é insuficiente como localizador. Não afirmamos que toda ausência de parcela decorra de batimento na Dataprev nem que esse contrato demonstre a operação atual da central. |
| ACH-05 | Acrescentar contexto e distinguir organizações, rede e instrumento financeiro | F5 situa SRTE e SINE entre locais de solicitação. F3 oferece meios de agendamento e 158; não confirma, sozinha, todos os atos atribuídos à rede no parecer. CODEFAT é ator normativo em F6/F7; FAT é fundo, não outro órgão deliberativo. Nenhum deles é convertido em atendente ou etapa obrigatória da ligação. |

A lacuna substantiva mais bem sustentada é ACH-04: uma pesquisa voltada a influências sobre a informação de parcelas não examinou a participação de uma organização tecnológica documentada no processamento do benefício. A v1 reconhecia não ter demonstrado comunicação entre bases; isso não equivale a ter identificado e delimitado a Dataprev. A inclusão agora tem evidência específica. Não sustentamos o achado alegando que uma hipótese da v1 já fosse falsa.

## 3. Canal e fronteira de responsabilidades

Caixa Cidadão, SAC e Ouvidoria são ofertas distintas. A nomenclatura genérica da FAQ não deve fazer o leitor confundir o número consultivo com o SAC. F4 publica funcionamento eletrônico contínuo e janelas de atendimento humano; esses horários de oferta geral não comprovam acesso humano para cada demanda específica. Não foram observados menus, autenticação, espera, transbordo ou transferência de ligações.

A função de agente pagador da Caixa está documentada em F7. F3 situa o serviço federal de solicitação no MTE. Atendimento informativo, atividade tecnológica e decisão administrativa não são a mesma função. A participação da Dataprev em processamento não lhe atribui, por si só, autoridade administrativa para rever o direito do trabalhador. Isso não exclui processamento ou cálculo técnico executado por sistemas: competência decisória e execução tecnológica devem ser distinguidas. Não se afirma uma proibição geral de calcular dados a partir do papel de agente pagador ou prestador de TIC. Tampouco a norma de pagamento demonstra que o telefone da Caixa trate exclusivamente de parcelas já liberadas.

## 4. Inventário ampliado para análise, sem substituir o mapa decidido

| Participante ou elemento | Camada e natureza | Participação sustentada e limite |
|---|---|---|
| Trabalhador/beneficiário | Usuário do serviço | Busca informação; sem experiência universal presumida. F1/F3. |
| Caixa Econômica Federal | Organização, pagamento e atendimento | Agente pagador: F5/F7. Oferta do canal: F1/F2/F4. Nenhuma decisão administrativa é atribuída ao atendente por essas fontes. |
| Equipe humana Caixa Cidadão | Papel operacional | Oferta publicada, atribuição específica para cada demanda ainda a verificar. F4. |
| Ministério do Trabalho e Emprego | Órgão responsável pelo serviço federal | Solicitação, acompanhamento e canal de dúvidas em F3. |
| Equipe SAC Caixa | Manifestações, função interna | Canal publicado, sem sequência ou transferência presumida. F2. |
| Equipe Ouvidoria Caixa | Manifestações não solucionadas, função interna | Participação eventual; sem roteiro obrigatório. F2. |
| Dataprev | Organização tecnológica do ecossistema | Serviços de TIC e interface de lotes com Caixa documentados no contrato de 2024. Não fornecedor da URA identificado. F8. |
| SRTE | Rede/unidades públicas, interface presencial | Locais de solicitação mencionados em F5; unidades concretas e alcance para o caso dependem de confirmação. |
| SINE | Rede de atendimento, interface presencial | Não é uma instituição única nem participa de toda chamada. F5. |
| CODEFAT | Conselho, contexto normativo | Edição de normas do programa; sem gestão de menus comprovada. F6/F7. |
| Empregador | Contexto antecedente | Fornece requerimento na etapa anterior, conforme F3. |

### Matriz de componentes e lacunas técnicas — resposta a AV2-01

| Elemento | Camada | Evidência e estado | Relação com os atores |
|---|---|---|---|
| Atendimento eletrônico publicado; URA como denominação didática | Interface da chamada | F2/F4 publicam oferta eletrônica. Serviços específicos, menus, entrada por teclado/fala e arquitetura não verificados | Canal da Caixa, não organização autônoma nem IA comprovada |
| Operador ou fornecedor técnico da central | Papel técnico a identificar | Lacuna mantida: nenhum contrato apresentado demonstra quem opera a URA deste canal | Não identificado como Dataprev por associação; não listado como fornecedor confirmado |
| Sistemas e troca de lotes do seguro-desemprego | Retaguarda do benefício | F8 documenta suporte tecnológico e indicador contratual; F9 contém propostas históricas de leiaute, sem comprovação da arquitetura atual | Dataprev, MTE e Caixa têm participação contextual documentada; isso não descreve a consulta telefônica em tempo real |
| Interface entre chamada e dados da parcela | Integração a investigar | Não foram observados a ligação, a autenticação nem a base consultada | Não há vínculo técnico específico estabelecido entre a URA e os sistemas mencionados no contrato |

FAT é o instrumento financeiro identificado na norma, fora da contagem de organizações. Atendimento eletrônico e sistemas de processamento são componentes. Um fornecedor da central ou operador técnico da URA continua não identificado. O mapa já confirmado pelo aluno trata de uma plataforma futura chamada Canal GOV, com papéis propostos distintos deste inventário documental. Nenhum novo ator será inserido naquele mapa como decisão do aluno sem discussão real na entrevista.

## 5. Relações tecnológicas e limites temporais

F8 sustenta uma relação documentada MTE–Dataprev–Caixa no contexto contratual de serviços do benefício. Sua seção 14.1, na página 125 do PDF, estabelece um indicador de envio de lotes à Caixa. Isso acrescenta uma relação de retaguarda relevante, sem descrever a base consultada em tempo real durante uma ligação. Não foi feita consolidação dos aditivos e da vigência do contrato em 2026.

O anexo PNCP F9 tem cabeçalho interno de 2020. A página 13 do PDF contém proposta de leiaute de retorno diário à Dataprev para modalidades do seguro-desemprego. A página 26 menciona remessa recebida da Dataprev no segmento pescador artesanal. A presença em um endereço de contratação de 2026 não atualiza automaticamente o conteúdo de 2020 nem permite generalizar a modalidade ou a frequência de um trecho para todo o programa. F9 não será usado como prova isolada da arquitetura atual.

## 6. Limitações e oportunidades da auditoria

LIM-01 a LIM-05 são mantidas como limitações já reconhecidas: acesso indireto às páginas Caixa; ausência de observação telefônica; operador da central desconhecido; IA e métricas não demonstradas; e protocolos/transferências entre canais não confirmados. A nova documentação de lotes não elimina essas limitações.

OPT-01: incorporada a identificação inequívoca dos canais. Horários e prazo de disponibilidade de parcela não são necessários para este mapa e exigem contexto temporal e de modalidade; não serão reproduzidos como instrução individual ao cidadão. OPT-02: consultados documentos públicos e identificado suporte tecnológico do benefício, sem confundi-lo com contratação da URA. OPT-03: mantida a separação entre consulta/pagamento, manifestações e questões administrativas do benefício; não foi inventado roteamento existente.

## 7. Fontes e localizadores verificados

- F1 — [FAQ Caixa, consulta de liberação](https://www.caixa.gov.br/beneficios-trabalhador/seguro-desemprego/perguntas-frequentes/Paginas/default.aspx). Conteúdo indexado; acesso integral direto continuou limitado.
- F2 — [Atendimento Caixa](https://www.caixa.gov.br/atendimento/Paginas/default.aspx). Seções dos três canais; recuperação indexada.
- F3 — [MTE, Solicitar seguro-desemprego](https://www.gov.br/pt-br/servicos/solicitar-o-seguro-desemprego). Leitura direta: etapas, meios de agendamento e órgão responsável.
- F4 — [Telefones e aplicativos Caixa](https://www.caixa.gov.br/atendimento/telefones-app/Paginas/default.aspx). Oferta geral Caixa Cidadão; recuperação indexada.
- F5 — [Seguro-desemprego, Caixa](https://www.caixa.gov.br/beneficios-trabalhador/seguro-desemprego/Paginas/default.aspx). Resultado indexado sobre agente pagador e locais de solicitação. Não leitura integral direta.
- F6 — [Portal FAT, resoluções sobre seguro-desemprego](https://portalfat.trabalho.gov.br/resolucoes-2/resolucoes-por-assunto/seguro-desemprego/). Contexto normativo; não norma de menu.
- F7 — [Resolução CODEFAT nº 957/2022, cópia oficial](https://portalfat.trabalho.gov.br/wp-content/uploads/2026/09/Resolucao-no-957-de-21-de-setembro-de-2022-Revisao-do-SD.pdf). PDF baixado, texto e página 20 inspecionados: art. 64, § 1º, e art. 65. Não foi consolidada toda a legislação posterior.
- F8 — [MTE, contrato nº 20/2024 com Dataprev e anexos](https://www.gov.br/trabalho-e-emprego/pt-br/acesso-a-informacao/licitacoes-e-contratos/contratos/pdf/202024completo.pdf). PDF de 312 páginas: partes na página 1; objeto no termo de referência, página 14; sistemas na página 18; indicador específico no item 14.1, página 125, repetido na 243. Texto pertinente e página 125 inspecionados.
- F9 — [Anexo PNCP citado pelo Gemini](https://pncp.gov.br/pncp-api/v1/orgaos/23612685000122/compras/2026/7/arquivos/4). Download é PDF, apesar do tipo genérico enviado pelo servidor; 35 páginas. Cabeçalho interno de 2020; localizadores 1, 13 e 26. Proposta de leiaute não equivale a comprovação de uso atual.

## 8. Proveniência, relação com a entrevista e estado do ciclo

O Gemini afirma ter lido os relatórios e usado resultados indexados da rodada anterior, mas declara não ter aberto nem inspecionado os PDFs F7/F8/F9. A conferência direta e visual dessas páginas foi realizada pelo Codex na etapa de preparação da v2; sua concordância não substitui triangulação independente por outro leitor dos documentos.

A entrevista e o mapa de sete papéis refletem decisões reais sobre a proposta Canal GOV. A ampliação documental não é uma nova fala do aluno. Participantes do contexto de processamento, normatização e atendimento presencial não foram inseridos como novos nós decididos sem entrevista. A proposta de plataforma comum continua distinta do atendimento existente; integração e viabilidade não foram demonstradas.

Este ciclo documental revisado está concluído: v1 preservada → nova auditoria v1 do Gemini → v2 com tratamento ACH-01 a ACH-05 → nova auditoria v2 → v3 com respostas AV2-01 e AV2-02 e ressalvas de precisão. Os pareceres integrais e o histórico anterior permanecem preservados. A nota anteriormente gravada permanece 90/100 até eventual nova submissão autorizada; concluir arquivos e obter uma prévia não altera aquela nota.
