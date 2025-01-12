# TCC-AWS-project-in-team
# Projeto de Arquitetura de Segurança na AWS  

## Visão Geral  
Este projeto foi desenvolvido como parte do TCC do curso **AWS re/Start** na Escola da Nuvem, com o objetivo de criar uma **arquitetura de segurança robusta e escalável** para a startup de e-commerce **Nova Tech**. A solução proposta combina as melhores práticas da AWS para garantir proteção de dados, alta disponibilidade, conformidade regulatória e resiliência operacional.  

## Objetivos do Projeto  
1. **Proteção de Dados:**  
   - Assegurar a confidencialidade, integridade e disponibilidade das informações sensíveis, como dados bancários e pessoais dos clientes.  
2. **Conformidade Regulatória:**  
   - Alinhar a arquitetura às normas LGPD, GDPR e PCI DSS.  
3. **Mitigação de Ameaças:**  
   - Detectar, prevenir e mitigar fraudes e ataques cibernéticos.  
4. **Resiliência Operacional:**  
   - Garantir a continuidade das operações em cenários de falhas ou incidentes de segurança.  

## Arquitetura Proposta  
### Principais Componentes  
1. **Fronte de Distribuição:**  
   - **Route 53 e CloudFront:** Gerenciamento de DNS e entrega de conteúdo com baixa latência e segurança.  
   - **AWS WAF:** Proteção contra ameaças como SQL Injection e ataques DDoS.  
2. **Rede Virtual e Infraestrutura Segura:**  
   - **VPC com Subnets Públicas e Privadas:** Isolamento de rede e controle de tráfego.  
   - **Security Groups e NACLs:** Regras específicas para proteção de tráfego de entrada e saída.  
3. **Gerenciamento de Dados:**  
   - **RDS e DynamoDB:** Bancos de dados seguros e altamente disponíveis.  
   - **S3 e KMS:** Armazenamento seguro com criptografia gerenciada.  
4. **Monitoramento e Conformidade:**  
   - **CloudTrail e AWS Config:** Auditoria e conformidade contínuas.  
   - **Amazon Inspector:** Identificação de vulnerabilidades em tempo real.  
5. **Recuperação e Continuidade:**  
   - **AWS Backup:** Automação de backups e recuperação de desastres.  
   - **Multi-AZ Deployments:** Alta disponibilidade para serviços críticos.  

### Ferramentas e Tecnologias Utilizadas  
- **IAM:** Gerenciamento de identidades e acessos.  
- **AWS Shield Standard:** Mitigação de ataques DDoS.  
- **CloudWatch:** Monitoramento de desempenho e alertas em tempo real.  
- **AWS Lambda:** Automação de respostas a incidentes.  

## Metodologia e Etapas do Projeto  
1. **Planejamento:**  
   - Análise de requisitos e mapeamento de ativos críticos, como bancos de dados e APIs.  
   - Avaliação de riscos, incluindo ameaças externas e internas.  
2. **Implementação:**  
   - Configuração de infraestrutura AWS na região de Norte da Virgínia na AWS é us-east-1, com foco em segurança e baixa latência.  
   - Implementação de controles de acesso, criptografia de dados e políticas de segurança.  
3. **Testes e Validação:**  
   - Testes de penetração e simulações de falhas para avaliar a eficácia das soluções.  
   - Ajustes baseados em resultados de auditorias de conformidade.  
4. **Capacitação e Treinamento:**  
   - Treinamento da equipe da Nova Tech para gerenciar e monitorar a arquitetura de forma eficiente.  
5. **Monitoramento Contínuo:**  
   - Revisões periódicas e melhorias na arquitetura para acompanhar a evolução de ameaças.  

## Resultados Esperados  
- **Segurança Reforçada:** Mitigação de vulnerabilidades e proteção contra ataques.  
- **Eficiência Operacional:** Continuidade de negócios mesmo em situações de falha.  
- **Conformidade Garantida:** Alinhamento com normas regulatórias e boas práticas de mercado.  

## Equipe de Desenvolvimento  
- **Maria Castro:** Gerente de Projeto e Treinamento.  
- **Italo Fernandes:** Especialista em Segurança de Dados.  
- **Rafael Rocha:** Arquiteto de Redes e Infraestrutura.  
- **Gevair Junior:** Especialista em Continuidade e Recuperação de Desastres.  

## Links Importantes  
- [Diagrama da Arquitetura](https://github.com/MariaCastro03/TCC-AWS-project-in-team/blob/main/AQR7.drawio.svg)  
- [Documentação Detalhada](https://drive.google.com/file/d/1V9pqEbD9S0z1WK7PivTz_YHFEmm4Harz/view?usp=sharing)  
 
## Conclusão  
Este projeto exemplifica como uma arquitetura de segurança bem estruturada pode atender às demandas de uma empresa de e-commerce em crescimento, garantindo proteção, conformidade e sustentabilidade.  
