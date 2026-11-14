# Testes pendentes e prioridades

**Data de referência:** 14/11/2026

Os itens abaixo representam oportunidades de validação posterior. Nenhum deles deve ser considerado aprovado antes da execução e confirmação do resultado.

| Prioridade | Teste | Status | Condição de conclusão |
|---|---|---|---|
| Alta | Leitura integral de e-mail no Gmail | 🟡 Pendente | Recuperar corpo integral de mensagem autorizada e confirmar conteúdo |
| Alta | Criar evento de demonstração no Calendar | 🟡 Pendente | Autorização específica, criação e conferência do evento; depois avaliar remoção apenas se autorizada |
| Alta | Leitura de arquivo Word | 🔵 Aguardando insumo | Disponibilizar DOCX não sensível e confirmar extração |
| Alta | Gerar DOCX, XLSX e PDF | 🟡 Bloqueado | Ferramenta de análise de dados disponível e arquivos demonstrativos validados |
| Média | Salvar edição de teste no Canva | 🟡 Pendente | Usar design de demonstração e autorização específica |
| Média | Criar arquivo/commit de teste no GitHub | 🟡 Pendente | Utilizar arquivo isolado e registrar commit e URL; evitar sobrescrever conteúdo |
| Média | Executar automação de teste | 🟡 Pendente | Identificar automação segura e obter autorização para execução |
| Média | Conectar Teams/SharePoint/Outlook | 🔵 Aguardando conexão | Usuário concluir conexão/autenticação e ferramenta confirmar acesso |
| Média | Verificar Power BI | 🔵 Aguardando conexão | Confirmar existência do conector e testar consulta autorizada |
| Baixa | Reavaliar controle do Edge/desktop | 🔴 Não identificado | Verificar disponibilidade de recurso específico em sessão compatível |

## Protocolo para testes futuros

1. Definir o objetivo e o escopo do teste.
2. Identificar se a operação é somente leitura ou se altera dados externos.
3. Obter autorização específica para qualquer gravação, envio, publicação ou exclusão.
4. Preferir ambiente de demonstração e dados fictícios.
5. Executar uma operação por vez quando houver risco de conflito.
6. Registrar resposta da ferramenta, data, resultado e limitações.
7. Conferir o estado final no serviço de destino.
8. Atualizar o painel e o histórico somente após confirmação.

## Critério de aprovação

Uma funcionalidade somente recebe 🟢 VERDE quando a operação correspondente for executada com sucesso e houver evidência suficiente. A existência de uma ferramenta ou permissão técnica, isoladamente, não satisfaz esse critério.
