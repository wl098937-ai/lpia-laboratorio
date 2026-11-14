# Governança do laboratório

## 1. Objetivo

Estabelecer critérios para planejar, executar, documentar e revisar atividades técnicas realizadas no âmbito deste repositório.

## 2. Papéis e responsabilidades

- **Responsável pelo projeto:** define objetivos, prioridades e limites de autorização.
- **Executor do teste:** realiza a operação dentro do escopo autorizado e registra o resultado.
- **Revisor documental:** verifica coerência, clareza, evidências e ausência de dados indevidos antes da publicação.

Uma mesma pessoa pode exercer mais de um papel, sem afastar a necessidade de registrar limites e resultados com precisão.

## 3. Classificação dos testes

Cada atividade deve ser classificada, sempre que aplicável, em uma das seguintes categorias:

- **Consulta/leitura:** obtenção de informações sem alteração intencional do sistema externo.
- **Criação:** inclusão de novo conteúdo ou registro.
- **Edição:** modificação de conteúdo existente.
- **Exclusão/cancelamento:** remoção ou interrupção de conteúdo ou operação.
- **Publicação/compartilhamento:** disponibilização de conteúdo a terceiros.
- **Configuração/permissão:** alteração de parâmetros, acessos ou autorizações.

A classificação deve indicar o sistema envolvido e o impacto potencial.

## 4. Autorização e limites

1. A autorização deve ser compatível com a ação concreta pretendida.
2. A autorização para consultar não implica autorização para editar, excluir ou publicar.
3. Ações externas com efeitos relevantes ou difíceis de reverter exigem autorização específica.
4. Em caso de dúvida sobre escopo, conta, destinatário ou impacto, a execução deve ser suspensa até esclarecimento.
5. Não se deve contornar controles de acesso, autenticação ou políticas da plataforma.

## 5. Integridade e controle de alterações

- Consultar o estado atual antes de modificar arquivo existente.
- Preferir a criação de novos arquivos quando isso atender ao objetivo.
- Não sobrescrever ou excluir conteúdo sem necessidade demonstrada e autorização.
- Usar mensagens de commit objetivas e descritivas.
- Após alterações, reler os arquivos ou consultar o estado resultante para verificar a publicação.
- Registrar falhas, respostas incompletas e operações canceladas, sem classificá-las como sucesso.

## 6. Registro mínimo de avaliação

Cada avaliação deve conter, quando disponíveis:

- data e ambiente;
- objetivo e escopo;
- serviço ou ferramenta;
- operação executada;
- resultado observado;
- evidência verificável;
- limitações e pendências;
- status atribuído;
- comparação com avaliações anteriores, se houver.

## 7. Indicadores

- 🟢 **VERDE:** operação testada e aprovada.
- 🟡 **AMARELO:** resultado parcial, dependente ou inconclusivo.
- 🔴 **VERMELHO:** recurso indisponível ou não identificado como operacional no ambiente examinado.
- 🔵 **AZUL:** recurso identificado, mas ainda não testado.

Tendências ↑, → e ↓ só devem ser usadas quando existirem avaliações comparáveis.

## 8. Revisão e correção

Documentos podem ser corrigidos quando surgirem evidências novas, erros materiais ou alterações de escopo. A correção deve preservar o histórico de versões e explicar, quando relevante, a razão da mudança.
