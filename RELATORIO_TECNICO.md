# Relatório técnico de avaliação

## 1. Identificação

- **Data da avaliação:** 14 de novembro de 2026
- **Objeto:** capacidades, integrações e ferramentas disponibilizadas em uma sessão do ChatGPT
- **Natureza:** avaliação funcional, com testes de consulta, leitura e simulação
- **Finalidade:** documentar o que foi efetivamente observado, distinguindo recursos aprovados, parciais, indisponíveis e ainda não testados.

## 2. Metodologia e critérios

A avaliação considerou respostas efetivas das ferramentas, inspeção de recursos disponíveis e execução de operações de baixo risco. Não se considerou uma funcionalidade aprovada apenas porque seu nome apareceu no catálogo.

### Escala de status

| Indicador | Significado |
|---|---|
| 🟢 VERDE | Teste prático concluído com resposta satisfatória |
| 🟡 AMARELO | Parcial, dependente de autorização, conexão ou disponibilidade, ou ainda sem teste conclusivo |
| 🔴 VERMELHO | Recurso não disponível ou não identificado como operacional no ambiente examinado |
| 🔵 AZUL | Recurso identificado, mas não testado funcionalmente |

As setas de tendência (↑, →, ↓) ficam reservadas à comparação entre avaliações datadas. Não se presume evolução sem uma linha de base comparável.

## 3. Resultados por serviço

### 3.1 Gmail — 🟢 Consulta e rascunho aprovados

Foram consultadas etiquetas e informações de mensagens. Em teste complementar, uma mensagem autorizada foi recuperada em formato integral HTML, com corpo disponibilizado pela ferramenta. A recuperação retornou HTML (não texto simples) e não havia anexos. Também permanece registrado o teste anterior de criação de rascunho sem destinatário e sem envio.

**Limites:** envio, resposta e encaminhamento de e-mails não foram testados.

### 3.2 Google Calendar — 🟢 Consulta; 🟡 criação pendente

Foram consultados calendários e eventos; a consulta realizada retornou zero eventos, resultado que não permite concluir que a agenda esteja vazia. Em seguida, foi criado um evento temporário, privado, sem convidados e sem notificações, na agenda principal. A ferramenta confirmou a criação; o evento foi imediatamente excluído, com retorno de status cancelado.

**Resultado:** 🟢 consulta, criação e exclusão de evento temporário aprovadas. Nenhum evento de teste permaneceu na agenda.

### 3.3 Canva — 🟢 leitura e estrutura de edição; 🟡 salvamento pendente

Foi localizada a apresentação existente “Aula 14 - Rescisão Indireta do Contrato de Trabalho”, com 19 páginas. A integração recuperou texto de páginas, miniaturas e estrutura editável. Uma nova transação de edição foi aberta e imediatamente cancelada, sem aplicação de alterações.

**Resultado:** 🟢 leitura de conteúdo/páginas e abertura/cancelamento de transação aprovadas; 🟡 salvamento de edição não testado. Nenhum design foi alterado ou publicado.

### 3.4 GitHub — 🟢 leitura aprovada; 🟡 escrita pendente na avaliação anterior

Foram confirmadas consultas de repositórios, metadados, branch padrão, estrutura de diretórios e conteúdo de arquivo. Em etapa posterior autorizada, foram criados oito arquivos documentais e, em seguida, o README e o histórico foram atualizados. Os arquivos e as duas atualizações foram relidos para conferência.

**Resultado:** 🟢 leitura, criação de arquivos e atualização de documentos aprovadas no repositório público do laboratório. Não se trata de aprovação geral de todas as operações GitHub.

### 3.5 Automações — 🟢 consulta; 🟡 alterações pendentes

Foi realizada nova consulta somente de leitura aos registros de automações e às instruções salvas. A resposta confirmou a recuperação dos registros. Nenhuma automação foi executada, criada, excluída, pausada ou modificada.

**Resultado:** 🟢 consulta de registros e instruções; 🟡 execução e alteração permanecem sem teste.

### 3.6 Arquivos — 🟢 PDF e Excel; 🔵 Word; 🟡 geração

A leitura de PDF foi testada em páginas do documento. A leitura de uma planilha Excel confirmou seis abas e recuperação de conteúdo textual.

Não foi localizado arquivo DOCX para teste de leitura. A tentativa de gerar documentos Word, Excel e PDF foi bloqueada pela indisponibilidade temporária da ferramenta de análise de dados. Não há comprovação de arquivos gerados nessa tentativa.

## 4. Integrações Microsoft e navegador

Foram localizadas opções de conexão para Microsoft Teams, SharePoint e Outlook (e-mail e calendário), além de referência ao Power BI em pesquisa de catálogo. Não foi comprovada instalação ou autenticação desses serviços nesta sessão.

Não foi identificada integração operacional com Word, Excel, PowerPoint ou OneDrive. Isso não prova incapacidade universal do produto; registra apenas a ausência de comprovação no ambiente examinado.

O controle direto do Microsoft Edge local não foi identificado. Não houve comprovação de acesso às abas, histórico, favoritos, cookies, sessões autenticadas ou controle de mouse e teclado. A pesquisa e leitura de páginas públicas pela web são capacidades distintas do controle do navegador local.

## 5. Inventário de ferramentas

Foram identificados grupos de ferramentas para Gmail (21), Google Calendar (10), GitHub (89), Canva (43), Plugin Management (6), Automações (7), Files (6), Skills (2) e configurações do usuário (2).

Essas quantidades representam ferramentas listadas no ambiente examinado, não número de operações testadas nem garantia de acesso irrestrito.

## 6. Segurança, integridade e limites

- As consultas e simulações descritas não devem ser confundidas com autorização genérica para operações futuras.
- Envio de mensagens, publicação de conteúdo, criação ou exclusão de dados externos e alterações em contas exigem autorização compatível com a operação.
- Nenhum sucesso deve ser declarado sem resposta confirmatória da ferramenta.
- A disponibilidade pode variar conforme plano, permissões, autenticação, configuração e estado dos serviços externos.
- Este documento não contém credenciais, tokens, dados privados de mensagens ou identificadores internos de contas.

## 7. Conclusão

A bateria complementar ampliou a comprovação: Gmail recuperou corpo integral HTML; Google Calendar permitiu criar e excluir um evento temporário; Canva recuperou conteúdo e páginas e abriu/cancelou uma transação; GitHub confirmou criação e atualização documental. A consulta de automações também foi repetida com sucesso. Permanecem pendentes o envio de e-mail, o salvamento de edição no Canva, a execução de automações, leitura de DOCX e geração de arquivos enquanto a ferramenta estiver indisponível. As integrações Microsoft seguem sem conexão comprovada e o controle local do Edge não foi identificado.

A avaliação é, portanto, **positiva para determinadas operações de leitura e consulta, mas parcial quanto à execução de alterações e à integração Microsoft**. Cada recurso deve manter seu próprio status até que haja evidência de teste específico.

## 8. Natureza do documento

Este relatório é um registro de avaliação funcional pontual. Não constitui auditoria independente de segurança, certificação, parecer de conformidade ou garantia de disponibilidade futura.
