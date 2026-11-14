# Política de segurança e privacidade

## 1. Objetivo

Definir salvaguardas mínimas para testes, documentação e publicação de informações neste laboratório.

## 2. Princípios de segurança

- **Menor privilégio:** utilizar somente os acessos necessários à tarefa.
- **Finalidade específica:** limitar cada operação ao objetivo declarado.
- **Minimização de dados:** coletar e publicar apenas o conteúdo indispensável.
- **Integridade:** evitar alterações não autorizadas em dados e configurações.
- **Rastreabilidade:** manter registros suficientes para compreender o que foi feito.
- **Reversibilidade:** preferir procedimentos que permitam revisão ou recuperação.

## 3. Informações que não devem ser publicadas

Não inserir neste repositório público:

- senhas, tokens, chaves de API, cookies ou códigos de autenticação;
- dados bancários, financeiros ou identificadores de conta;
- documentos pessoais ou identificadores governamentais;
- conteúdo privado de e-mails, calendários, conversas ou arquivos;
- dados pessoais de terceiros sem fundamento e autorização adequados;
- endereços privados, informações de localização precisa ou dados de autenticação;
- capturas de tela que exponham informações restritas.

Quando uma evidência for necessária, deve-se preferir descrição técnica, dados fictícios ou versão devidamente anonimizada.

## 4. Testes em serviços externos

1. Respeitar os mecanismos oficiais de autenticação e autorização.
2. Não tentar acessar contas, arquivos ou sistemas fora do escopo autorizado.
3. Não enviar mensagens, publicar conteúdo ou alterar registros reais sem autorização específica.
4. Utilizar dados de teste não sensíveis sempre que possível.
5. Não criar operações fictícias em ambientes de produção sem avaliar o impacto.
6. Interromper o teste diante de comportamento inesperado, exposição de dados ou risco de alteração indevida.

## 5. Gestão de credenciais

Credenciais não devem ser armazenadas em arquivos do repositório, histórico de commits, exemplos de código ou documentação pública. Quando houver necessidade de autenticação, utilizar os mecanismos seguros oferecidos pela própria plataforma e limitar as permissões concedidas.

Se uma credencial for exposta acidentalmente, deve-se considerar sua revogação ou rotação imediata e remover a exposição conforme os procedimentos da plataforma, sem presumir que apagar o arquivo elimine cópias do histórico.

## 6. Incidentes e falhas

Suspeitas de exposição, acesso indevido ou alteração não autorizada devem ser tratadas com prioridade:

- interromper a atividade afetada;
- evitar novas operações que possam ampliar o impacto;
- registrar apenas os fatos necessários, sem replicar o dado exposto;
- avaliar as medidas de contenção disponíveis;
- corrigir a documentação e revisar o procedimento que originou o problema.

## 7. Dados de terceiros e propriedade intelectual

Respeitar direitos autorais, termos de uso, confidencialidade e regras aplicáveis ao tratamento de dados. Não reproduzir documentos privados ou conteúdo protegido além do necessário e permitido para a finalidade legítima do teste.

## 8. Limites desta política

Esta política é um conjunto de diretrizes operacionais do repositório. Não substitui políticas oficiais dos serviços utilizados, análise jurídica específica, avaliação formal de riscos ou programa independente de segurança.

## 9. Revisão

A política deve ser revista quando houver mudança relevante no escopo do laboratório, nos serviços utilizados ou nos riscos identificados. Toda revisão deve ser registrada no controle de versão.
