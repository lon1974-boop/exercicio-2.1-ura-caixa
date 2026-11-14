# Pesquisa v2 — atendimento ao seguro-desemprego pela URA da Caixa

Pesquisador: Codex (família OpenAI). Revisão: 14/11/2026. Auditor independente: Gemini, modo Flash-Lite, resposta preservada em B_relatorio_auditoria_v1.md. Esta revisão responde aos quatro pontos do auditor e registra discordâncias fundamentadas. O serviço permanece o atendimento telefônico; não é uma descrição observada da operação da central.

## Resposta à auditoria v1

| ID | Decisão e alteração | Fundamentação e pendência |
|---|---|---|
| A1 | Defender a distinção já existente e separar visualmente atores e componentes nesta versão | A v1 chamou expressamente a URA de componente mediador, distinguindo-a de organização e papel. A crítica não demonstra que tenha sido contada como ator. A separação abaixo reduz ambiguidade de apresentação. |
| A2 | Defender o texto original e manter a lacuna aberta | A v1 dizia “Categoria de investigação” e “Lacuna”; não atribuía irregularidade à instituição. Não há prova de terceirização. Busca pública e eventual pedido de informação são caminhos de pesquisa; não é demonstrado que ofício ou auditoria presencial sejam obrigatórios. |
| A3 | Aprimorar a fronteira institucional, com fonte adicional | A página institucional F5 identifica a Caixa como agente pagador. F3 identifica o MTE como responsável pelo serviço federal de solicitação. Consulta de parcelas e decisão sobre requerimento são operações distintas. Não atribuímos a um atendente poder de conceder benefício. |
| A4 | Aceitar a necessidade de qualificar evidência e manter acesso integral pendente | Em 14/11 foram refeitas buscas e tentativas de abertura: páginas Caixa continuaram com redirecionamento na ferramenta; F3 foi aberta. Resultado indexado não garante atualização integral. Não diagnosticamos WAF nem exigimos captura assinada: o auditor não demonstrou a causa técnica ou essa exigência. |

O Gemini informou não ter realizado consultas externas. A sua alegação de uma diretriz de restrição à web não veio do nosso prompt. Referências genéricas a TOGAF, normas e possíveis causas técnicas na auditoria não substituem verificação documental. O parecer contribui para revisão crítica, sem adquirir valor de prova por ter sido emitido por outra IA.

## Método e evidências

A v1, de 13/11, foi preservada. A v2 acrescenta a reconferência de 14/11 e novas fontes; não retrodata descobertas. F1, F2, F4, F5 e F6 foram recuperadas por resultados de busca em páginas institucionais. Esse modo de acesso é limitado: não constitui leitura integral, confirmação por ligação nem validação dos menus. F3 teve leitura direta. Não houve uso de aplicativo, entrevista de atendente, obtenção de contrato ou observação telefônica.

F1 aponta o Caixa Cidadão, 0800 726 0207, como opção para consulta da parcela. F4 publica atendimento eletrônico e humano desse canal; não comprova as opções disponíveis para cada demanda. F2 apresenta SAC e Ouvidoria como canais distintos. F3 informa meios de requerimento e acompanhamento e atribui responsabilidade pelo serviço ao MTE. F5 descreve a Caixa como agente pagador. Estas informações sustentam uma fronteira funcional, sem demonstrar intercâmbio de bases, transferência telefônica ou protocolo único.

## Atores: núcleo, interfaces e ambiente

1. Trabalhador ou beneficiário: procura informação. Sua necessidade e dificuldade concreta serão exploradas na entrevista, sem pressupor que todos tenham a mesma experiência.
2. Caixa Econômica Federal: organização que oferece o canal e atua como agente pagador, conforme F1/F5.
3. Equipe humana Caixa Cidadão: função operacional interna identificada pela oferta F4; autonomia, vínculo e acesso específico ao seguro-desemprego permanecem abertos.
4. MTE: responsável pelo serviço federal de solicitação, F3. É interface institucional para requerimento e questões do benefício; não se presume participação em cada ligação.
5. Equipe SAC Caixa: função interna de manifestações, F2. Camada de exceção; não etapa obrigatória.
6. Equipe Ouvidoria Caixa: função interna para reclamações não solucionadas, F2. Não se presume transferência direta a partir da URA.
7. Empregador que fornece o requerimento: participante anterior à consulta, previsto na etapa de solicitação F3. Sua inclusão é contextual e não significa participação na ligação.
8. CODEFAT: conselho que edita resoluções sobre o programa, identificado no portal oficial F6. Pertence ao ambiente normativo, sem evidência de comando operacional sobre uma chamada específica.

Caixa e suas equipes são níveis de análise distintos, explicitamente identificados para evitar dupla contagem da organização como se fossem instituições independentes. O mapa final dependerá das escolhas justificadas na entrevista.

## Componentes, relações e questões abertas

A URA é componente de interface telefônica. Telefone, menus e sistemas não contam como pessoas ou organizações. Um eventual fornecedor ou operador técnico permanece uma lacuna fora da lista de atores confirmados; não foi demonstrada contratação nem sua identidade.

A relação trabalhador–Caixa é de busca/oferta de informação. Empregador–trabalhador é interface anterior documentada pela entrega do requerimento. SAC e Ouvidoria são possibilidades de manifestação. MTE e CODEFAT compõem a fronteira administrativa e normativa. A existência desses papéis não prova um fluxo sequencial entre todos eles.

Continuam desconhecidos: opções e autenticação da URA, acesso efetivo ao humano para a demanda, supervisão, fontes de dados usadas na chamada, contratos, indicadores de espera e integração entre protocolos. Não existe nesta pesquisa evidência específica de reconhecimento de voz, chatbot ou modelo de linguagem no canal. Automação telefônica e IA não serão equiparadas.

## Referências e localizadores

- F1: [FAQ Caixa — seguro-desemprego](https://www.caixa.gov.br/beneficios-trabalhador/seguro-desemprego/perguntas-frequentes/Paginas/default.aspx), seção sobre consulta de liberação. Busca; acesso integral pendente.
- F2: [Atendimento Caixa](https://www.caixa.gov.br/atendimento/Paginas/default.aspx), seções SAC e Ouvidoria. Busca; acesso integral pendente.
- F3: [Solicitar seguro-desemprego — MTE](https://www.gov.br/pt-br/servicos/solicitar-o-seguro-desemprego), etapas e outras informações. Leitura direta em 14/11/2026.
- F4: [Telefones e aplicativos Caixa](https://www.caixa.gov.br/atendimento/telefones-app/Paginas/default.aspx), Caixa Cidadão. Busca; acesso integral pendente.
- F5: [Seguro-desemprego — Caixa](https://www.caixa.gov.br/beneficios-trabalhador/seguro-desemprego/Paginas/default.aspx?source=post_page---------------------------), apresentação da instituição como agente pagador. Resultado de busca consultado em 14/11/2026; não leitura integral.
- F6: [Portal FAT — resoluções sobre seguro-desemprego](https://portalfat.trabalho.gov.br/resolucoes-2/resolucoes-por-assunto/seguro-desemprego/), identificação de resoluções CODEFAT. Resultado de busca em 14/11/2026. Não foi feita consolidação jurídica da legislação vigente nem reconstrução do histórico normativo.
