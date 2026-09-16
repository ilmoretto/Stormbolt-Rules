# Política de Privacidade do Stormbolt

**Última atualização:** 16/09/2026

Esta Política de Privacidade explica como o Stormbolt ("Bot") coleta, utiliza, armazena e compartilha dados durante a vinculação de CPF entre o Discord e um servidor SA-MP.

## 1. Responsável pelo tratamento

- **Controlador ou responsável:** Alencar Morete
- **Contato de privacidade:** morete.alencar@gmail.com
- **Servidor relacionado:** Storm City

## 2. Dados tratados

De acordo com os comandos utilizados e o schema integrado, o Bot pode tratar:

- CPF informado pelo usuário;
- ID do usuário Discord;
- ID e nome da conta correspondente em `players`;
- estado da verificação;
- data e hora da verificação;
- prazo, motivo e responsável por bloqueios;
- registros de histórico das ações `VERIFY`, `UNVERIFY` e `BLOCK`;
- informações técnicas necessárias para segurança, diagnóstico e logs do serviço.

O Bot não precisa armazenar o token do usuário Discord nem acessar mensagens privadas para executar a verificação.

No Storm City, o CPF associado é utilizado como uma credencial operacional do servidor para localizar e vincular a conta do jogador. Essa finalidade não significa que o Bot esteja emitindo ou validando um documento civil. Ainda assim, quando o CPF puder ser relacionado a uma pessoa natural, ele será tratado com as salvaguardas aplicáveis a dados pessoais.

## 3. Fontes dos dados

Os dados são obtidos do usuário, do Discord, do banco de dados do servidor SA-MP e de membros autorizados da Staff.

## 4. Finalidades

Os dados são tratados para localizar a conta correspondente ao CPF, manter a vinculação entre jogador e Discord, informar o estado da verificação, invalidar a verificação quando o membro sair, aplicar bloqueios administrativos, manter histórico e proteger o serviço contra fraude.

A integração ocorre exclusivamente por MySQL. O Bot não realiza comunicação direta com o processo do SA-MP.

## 5. Compartilhamento e acesso

O acesso é limitado a operadores autorizados, membros da Staff com permissão, infraestrutura necessária ao funcionamento, prestadores técnicos autorizados e autoridades quando houver obrigação legal válida.

O Bot não deve publicar CPF completo em canais públicos. Consultas da Staff devem ser privadas e, quando possível, utilizar CPF mascarado.

## 6. Segurança

O operador deve utilizar variáveis de ambiente para credenciais, queries parametrizadas, permissões mínimas no MySQL, controle de cargos da Staff, logs sem CPF completo e acesso administrativo restrito.

## 7. Retenção

Os registros permanecem enquanto forem necessários para manter a verificação, aplicar as regras do servidor, realizar auditoria, prevenir fraude e resolver disputas. Após o término da necessidade, os dados deverão ser eliminados ou anonimizados, salvo obrigação legal ou necessidade legítima de preservação.

## 8. Direitos do titular

Conforme a legislação aplicável, o titular poderá solicitar informações sobre o tratamento, correção de dados, confirmação de existência, eliminação quando cabível, oposição, portabilidade ou outros direitos previstos.

Solicitações devem ser enviadas para **morete.alencar@gmail.com**. O responsável poderá solicitar confirmação de identidade antes de atender a solicitação e deverá responder dentro dos prazos legais aplicáveis.

## 9. Crianças e adolescentes

O Bot não deve ser utilizado para coletar dados pessoais de crianças ou adolescentes em desconformidade com a legislação aplicável. O responsável pelo servidor deve definir requisitos de idade e autorização quando necessários.

## 10. Transferências internacionais

Discord, serviços de hospedagem, provedores de banco de dados ou outros fornecedores podem processar dados fora do país do usuário. O responsável deve avaliar os fornecedores utilizados e adotar as salvaguardas exigidas pela legislação aplicável.

## 11. Alterações e contato

Esta Política poderá ser atualizada para refletir mudanças no Bot, no banco de dados, nas regras do servidor ou na legislação.

- **Contato:** morete.alencar@gmail.com
- **Responsável:** Alencar Morete

> Este documento é um modelo operacional e não substitui revisão jurídica. Confirme a base legal, os critérios de retenção, o controlador e os fornecedores utilizados antes da publicação.
