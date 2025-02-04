# Relatório de Implementação de Medidas de Segurança

**Data:** 04/02/2025  
**Empresa:** Abstergo Industries  
**Responsável:** Cauê

## Introdução

Este relatório apresenta o processo de implementação de ferramentas de segurança na empresa Abstergo Industries, realizado por João Silva. O objetivo do projeto foi implementar 3 medidas de segurança utilizando serviços da AWS, com a finalidade de aumentar a segurança e proteger dados sensíveis da empresa.

## Descrição do Projeto

O projeto de implementação de ferramentas foi dividido em 3 medidas de segurança. A seguir, são descritas as etapas da implementação:

### Medida 1: Implementação de Criptografia de Dados com AWS KMS (Key Management Service)

A criptografia é uma das principais medidas para proteger dados sensíveis. O AWS KMS foi utilizado para criar e gerenciar chaves de criptografia de forma centralizada. A partir dessa implementação, todos os dados sensíveis da empresa, como informações de clientes e transações financeiras, estão criptografados tanto em repouso quanto em trânsito.

**Caso de Uso:**  
A empresa usou o KMS para criptografar bancos de dados no Amazon RDS e arquivos armazenados no Amazon S3. Isso assegura que os dados permaneçam protegidos mesmo em caso de acesso não autorizado.

### Medida 2: Implementação de Controle de Acesso com AWS IAM (Identity and Access Management)

A AWS IAM foi configurada para garantir que apenas usuários e serviços com permissão adequada possam acessar os recursos da AWS. As políticas de IAM foram rigorosamente definidas para conceder permissões mínimas necessárias para cada função ou serviço. Além disso, o uso de autenticação multifatorial (MFA) foi habilitado para aumentar a segurança dos acessos administrativos.

**Caso de Uso:**  
A empresa configurou perfis de acesso detalhados para usuários e sistemas, aplicando o princípio de "menor privilégio". O MFA foi implementado para todas as contas de acesso administrativo, protegendo contra acessos não autorizados.

### Medida 3: Implementação de Monitoramento e Auditoria com AWS CloudTrail e AWS CloudWatch

O monitoramento contínuo das atividades na AWS é essencial para garantir a segurança e detectar comportamentos anômalos. O AWS CloudTrail foi ativado para registrar todas as chamadas de API feitas na conta da AWS, enquanto o AWS CloudWatch foi configurado para monitorar logs e métricas de serviços críticos.

**Caso de Uso:**  
A empresa configurou o CloudTrail para registrar todas as ações de usuários e serviços em tempo real. O CloudWatch foi usado para criar alertas sobre atividades suspeitas e gerar relatórios sobre o desempenho e integridade dos recursos.

## Conclusão

A implementação de ferramentas de segurança na empresa Abstergo Industries tem como resultado uma melhoria significativa na proteção dos dados e na gestão do acesso aos recursos da AWS. A utilização das ferramentas descritas garante um ambiente mais seguro, prevenindo acessos não autorizados e permitindo uma auditoria eficaz das atividades. Recomenda-se a continuidade da utilização das ferramentas implementadas e a busca por novas tecnologias que possam melhorar ainda mais os processos de segurança da empresa.

## Anexos

- [Manual de Implementação de KMS](#)
- [Política de IAM](#)
- [Relatórios de Monitoramento - AWS CloudWatch](#)

---

**Assinatura do Responsável pelo Projeto:**  
Cauê
