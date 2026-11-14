# Mapa de atores — seguro-desemprego: do Caixa Cidadão à proposta Canal GOV

Aluno: Lucimar Oliveira do Nascimento. Base documental: B_relatorio_assistente_v3.md. Base decisória: 13 rodadas reais de C_grill_transcript.md, encerradas com confirmação do aluno, e uma 14ª rodada de esclarecimento nominal. Síntese e desenho: Codex.

## Serviço, finalidade e fronteira

Nota de cronologia: o mapa foi decidido com a pesquisa v3 do ciclo anterior, preservada no commit f3e6086498687939dd21f295ffed356e0d711664. O novo ciclo ampliou a pesquisa documental posteriormente; os sete papéis e as escolhas do aluno permanecem iguais. Não foram acrescentados como decisões suas atores ou relações descobertos após a entrevista.

O caso concreto é a busca de informação sobre parcelas do seguro-desemprego pelo atendimento telefônico Caixa Cidadão, referido no exercício como URA da Caixa. A finalidade escolhida é reduzir o tempo gasto pelo trabalhador repetindo contatos quando sua dúvida não é resolvida. A fronteira vai da tentativa de consulta até uma orientação útil, sem análise completa da concessão (rodadas 1–3).

A entrevista produziu uma proposta de melhoria: **Canal GOV**, plataforma comum de atendimento, com direcionamento automático, tratamento pelas equipes competentes e retorno ao cidadão no mesmo ambiente (rodadas 7–10). É nome e desenho propostos pelo aluno. Não afirmamos que exista essa plataforma nem que corresponda à conta ou infraestrutura atual gov.br. Atender todas as demandas de governo é uma visão; este exercício detalha apenas o caso do seguro-desemprego.

## Atendimento documentado e desenho proposto

| Base atual da pesquisa v3 | Limite da evidência | Escolha da entrevista |
|---|---|---|
| Caixa divulga consulta telefônica de parcelas e oferta eletrônica/humana | Menus, acesso efetivo ao humano por demanda e arquitetura não observados | Automação primeiro; humano quando o cidadão disser que a resposta não resolveu — rodadas 4–5 |
| Caixa se apresenta como agente pagador; MTE responde pelo serviço federal de solicitação | Integração de dados, ligação e protocolo não comprovada | Equipes Caixa e MTE atuam no ambiente comum, mantidas suas competências — rodadas 8–10 |
| SAC e Ouvidoria são canais institucionais | Seu percurso pela plataforma proposta não foi demonstrado | Discutidos na rodada 9, sem aprovação de sequência obrigatória |
| Nenhuma unidade gestora ou operadora de plataforma conjunta foi identificada | Autoridade, fornecedor, contrato e viabilidade desconhecidos | Coordenação conjunta proposta; papel técnico apresentado para discutir riscos — rodadas 11–12 |

Fontes e limitações estão na v3: F1/F2/F4/F5 foram recuperadas por busca em domínio oficial, sem abertura integral bem-sucedida; F3/F6 tiveram leitura direta. As auditorias do Gemini são pareceres críticos textuais; não comprovam verificação externa independente.

## Sete atores ou papéis distintos

São pessoas, organizações e funções diferenciadas no desenho, não sete instituições independentes. Canal GOV, automação e roteamento são componentes e não entram na contagem.

| ID | Ator/papel | Tipo e camada | Papel no desenho desejado | Rastreabilidade e condição |
|---|---|---|---|---|
| A1 | Trabalhador ou beneficiário | Pessoa usuária; centro do serviço | Apresenta dúvida, informa que a resposta não resolveu e recebe orientação no mesmo ambiente | Rodadas 1–5; necessidade escolhida, sem pesquisa de campo com usuários |
| A2 | Caixa Econômica Federal | Organização; responsabilidade institucional | Responde por suas atribuições e participa da coordenação do atendimento comum | Rodadas 6, 8, 10–11; agente pagador em F5 |
| A3 | Equipe humana da Caixa / Caixa Cidadão | Papel operacional interno à Caixa | Trata demandas de sua competência após insuficiência da resposta automática e retorna pelo ambiente comum | Rodadas 4–5 e 8–10; atuação no Canal GOV é proposta |
| A4 | Ministério do Trabalho e Emprego (MTE) | Órgão público; responsabilidade administrativa | Mantém atribuições do serviço federal e participa da coordenação | Rodadas 7–11; responsabilidade pelo serviço em F3 |
| A5 | Equipe de atendimento do MTE | Papel operacional interno ao MTE | Recebe e trata assuntos de sua competência dentro do ambiente comum | Equipes discutidas nas rodadas 8 e 10 e papel confirmado nominalmente na rodada 14; unidade e vínculo não identificados; função do desenho proposto |
| A6 | Coordenação do Canal GOV, com participação da Caixa e do MTE | Governança proposta | Acompanha demandas sem solução e encaminhamentos errados; coordena o percurso conjunto | Rodada 11, reiterada na 12 e síntese na 13; não presumida autoridade existente |
| A7 | Equipe técnica do Canal GOV | Suporte técnico proposto | Manutenção da plataforma; suporte à investigação e correção técnica de roteamento é recomendação de implementação do Codex | Mencionada na rodada 12; aluno priorizou encaminhamento errado; atribuições detalhadas, composição e fornecedor abertos |

A3 pertence a A2; A5 pertence a A4. A6 não absorve as competências desses órgãos. A7 não decide o direito ao benefício. A gestão do Caixa Cidadão, aceita na rodada 6, é a responsabilidade local da Caixa; a rodada 11 acrescenta a coordenação conjunta para o desenho ampliado.

## Diagrama de relações do desenho desejado

**Legenda:** todas as relações de integração abaixo são propostas, não observações da operação atual. Setas contínuas: jornada desejada. Pontilhadas: responsabilidade institucional, governança e suporte. A tecnologia de classificação não foi escolhida; não se presume IA generativa.

```mermaid
flowchart LR
    U["A1 — Trabalhador / beneficiário"]
    P["Canal GOV — plataforma proposta"]
    AU["Automação — primeira resposta"]
    RT["Direcionamento automático por competência"]
    EC["A3 — Equipe humana da Caixa"]
    EM["A5 — Equipe de atendimento do MTE"]
    CX["A2 — Caixa Econômica Federal"]
    MT["A4 — Ministério do Trabalho e Emprego"]
    CO["A6 — Coordenação do Canal GOV"]
    TE["A7 — Equipe técnica do Canal GOV"]
    U -->|"apresenta demanda"| P
    P --> AU
    AU -->|"primeira resposta"| U
    U -->|"diz que não resolveu"| RT
    RT -->|"competência da Caixa"| EC
    RT -->|"competência do MTE"| EM
    EC -->|"resposta no ambiente comum"| P
    EM -->|"resposta no ambiente comum"| P
    P -->|"retorno e acompanhamento"| U
    CX -.->|"responsabilidade institucional"| EC
    MT -.->|"responsabilidade institucional"| EM
    CX -.->|"participa"| CO
    MT -.->|"participa"| CO
    CO -.->|"acompanha resolução e direcionamento"| P
    TE -.->|"suporte técnico proposto"| P
```

O encaminhamento incorreto não deve forçar a pessoa a sair da plataforma ou repetir sua história. O acompanhamento decorre das rodadas 8, 11 e 12; mecanismos de protocolo, histórico e prazo ainda precisam de projeto. Não foram inventados tempos de espera, indicadores, contratos, menus ou unidades administrativas.

## Influência e interesses a validar

Esta análise é uma hipótese do Codex para implementação, não resultado medido ou fala do aluno. Caixa e MTE têm competências institucionais relevantes e precisam participar das decisões. A coordenação precisaria de mandato e mecanismos para resolver impasses; a entrevista não cria essa autoridade. As equipes operacionais podem contribuir com conhecimento sobre as demandas e devem ser consultadas. O cidadão tem interesse direto na resolução, mas menor controle institucional: sua declaração de que a resposta não resolveu deve produzir consequência no percurso. A equipe técnica influencia viabilidade e estabilidade, sem decidir conteúdo administrativo do benefício.

Possíveis tensões incluem divisão de responsabilidades, capacidade das equipes e critérios de roteamento. Não se atribui resistência real a nenhum órgão sem evidência. A prioridade expressa é evitar encaminhamento errado. Como verificação futura, propõe-se medir redirecionamentos e necessidade de novos contatos; não existe linha de base nem meta numérica definida.

## Decisões, exclusões e pendências

- Rodadas 4–5: automação antes do humano; critério aprovado é o cidadão dizer que a resposta não resolveu. Outros critérios de acesso humano precisam de avaliação posterior.
- Rodadas 9–10: plataforma comum para tratamento, além de uma entrada com links. A substituição dos sistemas internos de pagamento ou concessão não foi decidida.
- SAC e Ouvidoria foram discutidos nominalmente na rodada 9, mas a concordância parcial não definiu seu fluxo. Permanecem interfaces a detalhar, fora dos sete papéis centrais.
- Empregador e CODEFAT são contexto da pesquisa, não atores discutidos nominalmente na entrevista. Não são nós do mapa decidido.
- Coordenação e equipe técnica são funções propostas, com estatuto de evidência diferente dos órgãos existentes. Não se afirma que a governança ou uma equipe técnica tenham sido instituídas.
- Integração, acesso a dados, critérios de classificação, acessibilidade, contingência e viabilidade ficam pendentes de projeto. A proposta não demonstra viabilidade de um canal único para todos os serviços governamentais.

O mapa consolida a proposta confirmada pelo aluno e preserva a fronteira entre evidência documental, decisão de desenho e recomendação de implementação.
