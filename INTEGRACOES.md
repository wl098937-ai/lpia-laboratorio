# Matriz de integrações

**Data-base:** 14/11/2026

Esta matriz resume o estado observado na sessão avaliada. “Identificado” não significa “conectado”; “disponível” não significa “testado”.

| Serviço | Status | Evidência observada | Limite atual |
|---|---|---|---|
| Gmail | 🟢 VERDE | Consulta e recuperação do corpo integral HTML de mensagem; rascunho criado em teste anterior | Envio/resposta não testados |
| Google Calendar | 🟢 VERDE | Consulta e criação/exclusão de evento temporário privado, sem notificações | Edição de evento preexistente não testada |
| Canva | 🟢 VERDE / 🟡 AMARELO | Leitura de texto/páginas e transação aberta/cancelada | Salvamento de edição não testado |
| GitHub | 🟢 VERDE | Leitura, criação de oito arquivos e atualização de dois documentos, com releitura | Outras modalidades de escrita/gestão não testadas |
| Automações | 🟢 VERDE / 🟡 AMARELO | Consulta de registros e instruções | Execução e alterações não testadas |
| Files — PDF | 🟢 VERDE | Extração/leitura de conteúdo de PDF | Escopo limitado aos arquivos examinados |
| Files — Excel | 🟢 VERDE | Leitura de planilha com seis abas | Edição não testada |
| Files — Word | 🔵 AZUL | Não havia DOCX disponível para teste | Requer arquivo de teste |
| Geração DOCX/XLSX/PDF | 🟡 AMARELO | Tentativa bloqueada por indisponibilidade da ferramenta de análise de dados | Repetir quando disponível |
| Microsoft Teams | 🔵 AZUL | Catálogo consultado; `installed: false` | Conexão/autenticação pendentes |
| SharePoint | 🔵 AZUL | Catálogo consultado; `installed: false` | Conexão/autenticação pendentes |
| Outlook E-mail | 🔵 AZUL | Catálogo consultado; `installed: false` | Conexão/autenticação pendentes |
| Outlook Calendar | 🔵 AZUL | Catálogo consultado; `installed: false` | Conexão/autenticação pendentes |
| Power BI | 🔵 AZUL | Catálogo consultado; `installed: false` | Conexão e operação não comprovadas |
| Word / Excel / PowerPoint | 🔴 VERMELHO* | Integração direta não confirmada nesta sessão | Não confundir com geração local de arquivos |
| OneDrive | 🔴 VERMELHO* | Integração direta não confirmada nesta sessão | Conexão não comprovada |
| Microsoft Edge local | 🔴 VERMELHO | Controle local não identificado | Web pública não equivale a controle do navegador |

* O indicador vermelho significa ausência de integração operacional comprovada neste diagnóstico, não uma afirmação de que o produto jamais ofereça essa capacidade em outros ambientes.

## Legenda

- 🟢 VERDE: teste prático aprovado.
- 🟡 AMARELO: parcial ou pendente.
- 🔴 VERMELHO: indisponível/não identificado operacionalmente neste ambiente.
- 🔵 AZUL: identificado, ainda não testado.

## Regra de atualização

Atualizar o status somente após teste datado e evidência verificável. Em avaliações futuras, registrar tendência ↑, → ou ↓ apenas quando houver comparação objetiva com o resultado anterior.
