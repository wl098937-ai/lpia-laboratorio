# Matriz de integrações

**Data-base:** 14/11/2026

Esta matriz resume o estado observado na sessão avaliada. “Identificado” não significa “conectado”; “disponível” não significa “testado”.

| Serviço | Status | Evidência observada | Limite atual |
|---|---|---|---|
| Gmail | 🟢 VERDE | Consulta de etiquetas/metadados/trecho e criação de rascunho | Envio e leitura integral não testados |
| Google Calendar | 🟢 VERDE | Consulta de calendários e eventos respondeu | Criação/edição/cancelamento não testados |
| Canva | 🟢 VERDE | Listagem, leitura de design e abertura/cancelamento de transação | Salvamento e publicação não testados |
| GitHub | 🟢 VERDE | Leitura de repositório, metadados, diretórios e arquivo | Escrita não testada na avaliação anterior |
| Automações | 🟢 VERDE | Consulta de registros e histórico | Criação, alteração e execução não testadas |
| Files — PDF | 🟢 VERDE | Extração/leitura de conteúdo de PDF | Escopo limitado aos arquivos examinados |
| Files — Excel | 🟢 VERDE | Leitura de planilha com seis abas | Edição não testada |
| Files — Word | 🔵 AZUL | Não havia DOCX disponível para teste | Requer arquivo de teste |
| Geração DOCX/XLSX/PDF | 🟡 AMARELO | Tentativa bloqueada por indisponibilidade da ferramenta de análise de dados | Repetir quando disponível |
| Microsoft Teams | 🔵 AZUL | Opção encontrada no catálogo | Instalação e autenticação não confirmadas |
| SharePoint | 🔵 AZUL | Opção encontrada no catálogo | Instalação e autenticação não confirmadas |
| Outlook E-mail | 🔵 AZUL | Opção encontrada no catálogo | Instalação e autenticação não confirmadas |
| Outlook Calendar | 🔵 AZUL | Opção encontrada no catálogo | Instalação e autenticação não confirmadas |
| Power BI | 🔵 AZUL | Referência localizada em pesquisa de catálogo | Conexão e operação não comprovadas |
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
