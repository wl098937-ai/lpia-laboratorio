# Relatório Geral Consolidado — Auditoria de Ferramentas, Plataformas e Fluxos de Trabalho com Inteligência Artificial

**Projeto:** LPIA — Laboratório de Pesquisa e Integração Aplicada  
**Data-base da consolidação:** 14 de novembro de 2026  
**Repositório:** `wl098937-ai/lpia-laboratorio`  
**Natureza:** avaliação funcional e documental preliminar, com registro de evidências, limitações e oportunidades de integração.

## 1. Apresentação e motivo da auditoria

Esta auditoria nasceu de uma necessidade prática: avaliar como ferramentas de inteligência artificial, serviços digitais e mecanismos de integração podem atuar de forma coordenada para melhorar a organização da rotina, reduzir tarefas manuais, otimizar o tempo e apoiar atividades pessoais, profissionais e de estudo.

O propósito não é testar tecnologia por curiosidade isolada, nem declarar uma plataforma vencedora em abstrato. A finalidade é compreender **qual mecanismo atende melhor a cada necessidade concreta**, quais tarefas podem ser apoiadas ou executadas com segurança, quais dependem de conexão/autorização e onde ainda existem limitações.

O laboratório procura construir um fluxo de trabalho assistido por IA no qual as ferramentas contribuam, conforme suas capacidades comprovadas, para:

- organização pessoal, agenda, compromissos, lembretes e acompanhamento de tarefas;
- planejamento e organização de atividades profissionais e administrativas;
- estudos jurídicos, pesquisa, revisão técnica de temas, legislação e jurisprudência;
- preparação de materiais, sínteses, documentos e relatórios;
- acompanhamento de economia, mercado financeiro e B3, com boletins e relatórios técnicos;
- organização de ideias, estruturação de projetos e difusão de conteúdo;
- documentação, versionamento e acompanhamento de projetos no GitHub;
- interoperabilidade entre plataformas, evitando duplicidade de trabalho e reduzindo etapas manuais.

A auditoria também procura melhorar o desempenho do assistente de IA utilizado como camada de coordenação: organizar demandas, estruturar ideias, selecionar ferramentas adequadas, preparar instruções e conteúdos, acompanhar resultados e encaminhar tarefas aos serviços conectados quando houver capacidade técnica e autorização. Essa função de coordenação não significa que exista controle irrestrito ou conexão automática com todas as plataformas.

## 2. Objetivo geral

Identificar, testar e documentar as capacidades efetivamente disponíveis em cada plataforma e integração, para estabelecer uma matriz prática de adequação entre ferramenta e necessidade de trabalho.

### Objetivos específicos

1. Mapear ferramentas, conectores e permissões disponíveis no ambiente examinado.
2. Testar operações de consulta, leitura, criação, edição, exclusão e publicação, sempre distinguindo cada modalidade.
3. Identificar quais tarefas podem ser realizadas diretamente, quais exigem intervenção do usuário e quais permanecem indisponíveis ou não comprovadas.
4. Avaliar possibilidades de colaboração entre ChatGPT/OpenAI, Google Gemini, Microsoft Copilot, Microsoft Edge e demais serviços relevantes.
5. Reduzir riscos de duplicidade, perda de informação, alteração indevida e exposição de dados.
6. Criar documentação verificável e um histórico que permita comparar avaliações futuras.

## 3. Escopo das plataformas e status das evidências

A presença de uma plataforma no escopo não significa que ela tenha sido conectada ou aprovada. A classificação abaixo separa testes funcionais comprovados, análises documentais e avaliações ainda não demonstradas.

| Plataforma/serviço | Papel considerado no fluxo | Evidência registrada nesta auditoria | Status |
|---|---|---|---|
| ChatGPT / OpenAI | Coordenação das demandas, organização de ideias, pesquisa, síntese, preparação de documentos e orquestração de ferramentas disponíveis | Sessão examinada; ferramentas e conectores disponíveis foram inspecionados e operações específicas foram testadas, conforme matriz abaixo | 🟢 Parcialmente comprovado |
| Google Gemini | Pesquisa e análise complementar; segunda perspectiva para comparação e revisão | Foi considerado na arquitetura de colaboração, mas não há, nos registros consultados, evidência de teste funcional executado nesta bateria | 🔵 Não testado / previsto |
| Microsoft Copilot | Apoio à produtividade no ecossistema Microsoft e atividades documentais | Foi considerado como ferramenta potencial de produtividade; não há evidência registrada de teste funcional específico do Copilot nesta bateria | 🔵 Não testado / previsto |
| Microsoft Edge | Navegação e eventual interação com páginas e sessões do navegador | Diagnóstico documental específico; controle de instância local, abas e interface não foi comprovado | 🔴 Controle local não identificado |
| GitHub | Repositório, documentação, versionamento e acompanhamento de projetos | Consulta/leitura, criação de oito arquivos e atualização de dois documentos no repositório do laboratório, com releitura confirmatória | 🟢 Operações documentais comprovadas |
| Gmail | Consulta e recuperação de mensagens; apoio à preparação de comunicações | Consulta e recuperação de corpo integral HTML; rascunho criado em teste anterior; envio não testado | 🟢 Leitura / 🟡 envio pendente |
| Google Calendar | Consulta e organização de agenda | Consulta realizada; evento temporário privado criado e imediatamente excluído, sem convidados ou notificações | 🟢 Consulta e operação temporária comprovadas |
| Canva | Leitura e preparação de materiais visuais | Conteúdo e páginas de apresentação recuperados; transação de edição aberta e cancelada sem salvar | 🟢 Leitura / 🟡 salvamento pendente |
| Automações | Rotinas programadas e acompanhamento de tarefas | Consulta de registros e instruções; três rotinas habilitadas identificadas, mas nenhuma executada ou modificada | 🟢 Consulta / 🟡 execução pendente |
| Files — PDF e Excel | Leitura e análise de documentos | Leitura de PDF e planilha Excel com seis abas | 🟢 Leitura comprovada |
| Files — Word | Leitura de documentos DOCX | Não havia DOCX disponível para teste | 🔵 Aguardando insumo |
| Microsoft Outlook, Calendar, Teams, SharePoint e Power BI | Produtividade e gestão no ecossistema Microsoft | Consulta ao catálogo; os conectores consultados retornaram `installed: false` nesta sessão | 🔵 Conexão não comprovada |
| OneDrive, Word, Excel e PowerPoint | Arquivos e produtividade Microsoft | Integração direta não comprovada nesta sessão | 🔵 Não comprovada |

**Nota sobre Gemini e Copilot:** são partes expressas do escopo estratégico do laboratório e da arquitetura pretendida. Contudo, os registros consultados não demonstram testes funcionais dessas duas plataformas. Por rigor metodológico, não se atribuem resultados, notas de desempenho ou aprovação sem evidência.

## 4. Resultados funcionais comprovados no ambiente ChatGPT

### 4.1 Gmail
- Consulta de metadados e recuperação de mensagem.
- Recuperação do corpo integral em HTML, em teste complementar.
- Criação de rascunho sem envio em etapa anterior.
- **Não testado:** envio, resposta e encaminhamento.

### 4.2 Google Calendar
- Consulta de calendários e eventos.
- Criação de evento temporário, privado, sem convidados e sem notificações.
- Exclusão imediata do evento de teste, com confirmação de cancelamento.
- A consulta que retornou zero eventos não permite concluir que a agenda estivesse vazia.

### 4.3 Canva
- Localização de apresentação com 19 páginas.
- Recuperação de texto, páginas e miniaturas.
- Abertura e cancelamento de transação de edição, sem salvar alterações.
- **Não testado:** salvamento ou publicação de design.

### 4.4 GitHub
- Consulta de repositórios, metadados, branch e arquivos.
- Criação de oito arquivos documentais no repositório público do laboratório.
- Atualização do painel principal e do histórico.
- Releitura dos documentos para conferência.
- **Limite:** isso comprova apenas as operações específicas realizadas, não todas as modalidades de administração do GitHub nem a execução do GitHub Copilot.

### 4.5 Automações
- Consulta de registros e instruções.
- Identificação de três rotinas habilitadas.
- Nenhuma rotina foi executada, criada, excluída, pausada ou modificada, pois a execução poderia produzir efeitos externos fora do escopo autorizado.

### 4.6 Arquivos
- Leitura de PDF e Excel confirmada; planilha com seis abas.
- Não havia DOCX disponível para teste.
- Tentativa de geração de DOCX, XLSX e PDF bloqueada por indisponibilidade temporária da ferramenta de análise de dados.

## 5. Papel pretendido de cada camada no fluxo de trabalho

A arquitetura é funcional, não uma afirmação de integração automática já concluída:

- **ChatGPT/OpenAI — coordenação e consolidação:** receber demandas, organizar ideias, estruturar planos, preparar relatórios, sintetizar resultados e acionar ferramentas efetivamente conectadas.
- **Google Gemini — pesquisa e análise complementar:** oferecer uma perspectiva adicional para pesquisa, comparação e revisão, quando houver acesso e teste próprios.
- **Microsoft Copilot — produtividade no ecossistema Microsoft:** apoiar tarefas em aplicativos e serviços Microsoft, condicionado à licença, conexão, permissões e capacidades efetivamente disponíveis.
- **Microsoft Edge — camada de navegação:** eventual acesso ou automação do navegador, se existir mecanismo específico habilitado; não foi comprovado controle local nesta sessão.
- **GitHub — memória técnica do projeto:** guardar documentação, histórico, versões e resultados verificáveis.
- **Serviços conectados — execução especializada:** Gmail, Calendar, Canva, Files e Automações podem atender operações delimitadas, conforme os testes e permissões descritos.

A colaboração entre plataformas pode ocorrer inicialmente por documentos, relatórios e instruções preparados e revisados. Não se deve presumir comunicação direta entre IAs, compartilhamento automático de contexto ou execução em cadeia sem comprovação técnica.

## 6. Indicadores e critérios de avaliação

- 🟢 **VERDE — Aprovado:** operação específica executada e confirmada.
- 🟡 **AMARELO — Parcial/Pendente:** resultado parcial, dependente de conexão, autorização, insumo ou disponibilidade.
- 🔴 **VERMELHO — Não identificado/indisponível no ambiente:** a capacidade operacional não foi demonstrada no ambiente examinado.
- 🔵 **AZUL — Em observação/não testado:** plataforma ou recurso identificado, mas sem teste funcional concluído.

As classificações se aplicam à operação descrita, não à plataforma inteira. Uma ferramenta pode estar verde para leitura e amarela para edição. Tendências (↑, →, ↓) somente serão atribuídas após avaliações comparáveis em datas diferentes.

## 7. Limitações e pontos ainda não comprovados

1. Não há evidência registrada de teste funcional específico do Google Gemini ou do Microsoft Copilot nesta bateria.
2. Não foi comprovado controle direto do Microsoft Edge local.
3. Os conectores Microsoft consultados não estavam instalados/conectados nesta sessão.
4. Envio de e-mail, salvamento de edição no Canva, execução de automações e geração de arquivos permanecem pendentes conforme os respectivos registros.
5. A existência de uma ferramenta no catálogo não comprova autenticação, permissão ou disponibilidade de todas as operações.
6. A pesquisa na internet não equivale a controlar o navegador local.
7. A arquitetura de colaboração entre IAs é uma proposta de trabalho e não deve ser descrita como integração automática já implementada.

## 8. Privacidade, segurança e integridade

A avaliação deve observar menor privilégio, finalidade específica, minimização de dados, autorização compatível com cada ação e conferência do estado final. Consultar não autoriza editar; editar não autoriza publicar; e uma autorização para uma operação não se estende automaticamente a outras.

O repositório é público. Portanto, devem ser publicados somente resultados técnicos necessários, dados fictícios ou informações devidamente anonimizadas. Não devem ser incluídos credenciais, tokens, conteúdo privado de mensagens, dados financeiros pessoais, documentos particulares ou identificadores sensíveis.

## 9. Conclusão geral

A auditoria demonstra que o ambiente examinado do ChatGPT dispõe de capacidades úteis para determinadas operações de consulta, leitura, documentação e gestão delimitada de serviços conectados. Foram confirmadas operações específicas em Gmail, Google Calendar, Canva, GitHub, Automações e leitura de arquivos PDF/Excel.

Ao mesmo tempo, a auditoria identifica limites relevantes: não há comprovação de controle local do Edge; os conectores Microsoft consultados não estavam instalados; e não há registro de testes funcionais do Gemini ou do Copilot nesta bateria. Esses pontos não devem ser ocultados nem convertidos em conclusões universais sobre as plataformas.

O resultado mais importante é estabelecer uma base honesta para decidir **qual ferramenta utilizar em cada atividade**, onde a integração pode reduzir tempo e trabalho repetitivo e quais testes precisam ser feitos antes de confiar uma tarefa a determinado mecanismo.

O LPIA busca, assim, transformar o uso cotidiano de inteligência artificial em um fluxo de trabalho mais organizado, verificável, seguro e eficiente — com foco na melhoria da rotina, dos estudos, das atividades profissionais, da pesquisa e do acompanhamento de informações e projetos.

## 10. Próximas etapas recomendadas

1. Manter o relatório geral como documento principal de apresentação da auditoria.
2. Preservar relatórios específicos — como o diagnóstico do Microsoft Edge — como anexos técnicos de cada frente.
3. Planejar testes funcionais próprios para Gemini e Copilot, sem antecipar resultados.
4. Avaliar conexões Microsoft mediante autenticação e autorização explícitas.
5. Priorizar testes que tenham benefício prático claro: agenda, documentos, estudos, pesquisa e relatórios.
6. Atualizar a matriz somente com evidência datada e confirmação do resultado no serviço de destino.

---

*Documento de consolidação técnica e documental. Não constitui certificação, auditoria independente de segurança, parecer jurídico ou garantia de disponibilidade futura de serviços de terceiros.*
