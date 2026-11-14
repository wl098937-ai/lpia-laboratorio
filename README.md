# LPIA — Laboratório de Pesquisa e Integração Aplicada

![Auditoria](https://img.shields.io/badge/auditoria-multiplataforma-blue)
![Documentação](https://img.shields.io/badge/documentação-pública-brightgreen)
![Evidências](https://img.shields.io/badge/critério-evidência%20verificável-informational)

> Laboratório independente dedicado à pesquisa, experimentação controlada e documentação de capacidades de ferramentas digitais e inteligência artificial, com foco em melhorar a organização pessoal, os estudos, as atividades profissionais, a pesquisa, a produção de relatórios e a gestão de projetos.

## Por que esta auditoria foi iniciada?

A iniciativa busca responder a uma questão prática: **como diferentes mecanismos de inteligência artificial podem trabalhar, cada qual dentro de suas capacidades comprovadas, para reduzir tarefas manuais, otimizar o tempo e apoiar a rotina?**

O trabalho considera necessidades como organização pessoal e agenda, planejamento de atividades, estudos jurídicos e revisão técnica de temas, pesquisa, preparação de documentos e relatórios, acompanhamento de economia e mercado financeiro/B3, organização de ideias e difusão de conteúdo.

A auditoria não pretende apenas listar funcionalidades. Procura identificar qual ferramenta atende melhor a cada necessidade, quais operações foram efetivamente testadas, quais dependem de conexão ou autorização e quais ainda não foram comprovadas.

## Relatório principal

1. **[Relatório Geral Consolidado — Auditoria Multiplataforma](RELATORIO_GERAL_AUDITORIA.md)** — finalidade, motivação, escopo, plataformas, evidências, resultados, limitações e próximos passos.

## Relatórios técnicos e documentos de apoio

### Avaliação técnica e histórico
2. [Relatório técnico das ferramentas e integrações examinadas](RELATORIO_TECNICO.md)
3. [Matriz de integrações e indicadores](INTEGRACOES.md)
4. [Testes pendentes e prioridades](TESTES_PENDENTES.md)
5. [Histórico de avaliações](HISTORICO_AVALIACOES.md)
6. [Auditoria específica do Microsoft Edge](docs/auditoria-edge-relatorio-consolidado-2026-11-14.md)

### Identidade e governança
7. [Identidade institucional](IDENTIDADE_INSTITUCIONAL.md)
8. [Governança do laboratório](GOVERNANCA.md)
9. [Política de segurança e privacidade](POLITICA_DE_SEGURANCA.md)

## Plataformas contempladas

- **ChatGPT/OpenAI:** coordenação, organização de demandas, síntese e uso das ferramentas efetivamente conectadas.
- **Google Gemini:** pesquisa e análise complementar — incluído no escopo estratégico; teste funcional específico ainda não documentado.
- **Microsoft Copilot:** produtividade no ecossistema Microsoft — incluído no escopo estratégico; teste funcional específico ainda não documentado.
- **Microsoft Edge:** navegação e eventual interação local — controle do navegador não comprovado na avaliação.
- **GitHub:** documentação, versionamento e histórico do laboratório.
- **Serviços e conectores:** Gmail, Google Calendar, Canva, Automações, Files e serviços Microsoft consultados.

A arquitetura de colaboração entre plataformas é uma proposta de trabalho. Não se presume comunicação automática entre IAs ou controle irrestrito de aplicativos.

## Painel resumido de evidências — 14/11/2026

| Área | Resultado registrado |
|---|---|
| ChatGPT e ferramentas da sessão | 🟢 Operações específicas aprovadas; avaliação parcial por serviço |
| Gmail | 🟢 Consulta e leitura de corpo integral HTML; envio não testado |
| Google Calendar | 🟢 Consulta e criação/exclusão de evento temporário |
| Canva | 🟢 Leitura e abertura/cancelamento de transação; salvamento não testado |
| GitHub | 🟢 Leitura, criação de oito arquivos e atualização de dois documentos |
| Automações | 🟢 Consulta de registros; execução e alterações não testadas |
| Files — PDF e Excel | 🟢 Leitura aprovada |
| Google Gemini | 🔵 Incluído no escopo; sem teste funcional comprovado nos registros consultados |
| Microsoft Copilot | 🔵 Incluído no escopo; sem teste funcional comprovado nos registros consultados |
| Outlook, Teams, SharePoint e Power BI | 🔵 Catálogo consultado; conectores não instalados nesta sessão |
| Microsoft Edge local | 🔴 Controle local não identificado |
| Geração de DOCX/XLSX/PDF | 🟡 Tentativa bloqueada por indisponibilidade temporária da ferramenta |

### Legenda

- 🟢 **VERDE — Aprovado:** operação específica testada e confirmada.
- 🟡 **AMARELO — Parcial/Pendente:** operação incompleta ou dependente de conexão, autorização, insumo ou disponibilidade.
- 🔴 **VERMELHO — Não identificado:** capacidade operacional não demonstrada no ambiente examinado.
- 🔵 **AZUL — Em observação:** recurso incluído no escopo, mas sem teste funcional concluído.

Os indicadores qualificam operações específicas, não a plataforma inteira. A ausência de evidência nesta sessão não prova impossibilidade técnica em outros ambientes.

## Metodologia e integridade

A auditoria distingue consulta/leitura, criação, edição, exclusão, publicação e configuração. Nenhum teste é considerado aprovado apenas porque a ferramenta aparece no catálogo. Ações com efeitos externos exigem autorização compatível e confirmação do estado final.

O repositório é público. Não publicar credenciais, tokens, conteúdo privado, dados pessoais ou financeiros, documentos particulares ou identificadores sensíveis.

## Natureza dos documentos

Os registros são avaliações funcionais e documentais pontuais. Não constituem certificação, auditoria independente de segurança, parecer de conformidade ou garantia de disponibilidade futura de serviços de terceiros.

**Data-base da consolidação geral:** 14 de novembro de 2026.
