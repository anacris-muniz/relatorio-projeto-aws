# Relatório de Implementação de Serviços AWS – Redução de Custos 📂

**Data:** 15/03/2026  
**Empresa:** Abstergo Industries  
**Responsável:** Ana Muniz  

---

## Introdução

Este repositório apresenta o relatório do processo de implementação de serviços em nuvem utilizando recursos da **AWS (Amazon Web Services)** na empresa Abstergo Industries.

O projeto teve como objetivo identificar e implementar serviços capazes de:

- Reduzir custos operacionais da infraestrutura em nuvem  
- Otimizar o uso de recursos computacionais  
- Melhorar a eficiência e escalabilidade do ambiente  

A estratégia adotada concentrou-se em três pilares principais:

- Monitoramento de custos
- Otimização automática de recursos
- Armazenamento inteligente de baixo custo

---

## Descrição do Projeto

A implementação foi dividida em **três etapas**, cada uma focada em um serviço da AWS voltado para **otimização de custos e eficiência operacional**.

---

## Etapa 1 – Monitoramento de Custos

**Ferramenta:** AWS Cost Explorer  

**Foco da ferramenta:**  
Análise e visualização detalhada dos custos e uso de recursos na AWS.

### Caso de Uso

O Cost Explorer foi implementado para permitir o acompanhamento detalhado dos gastos com serviços AWS.

Com essa ferramenta é possível:

- Identificar serviços com maior consumo financeiro  
- Analisar tendências de custo ao longo do tempo  
- Detectar desperdícios ou recursos subutilizados  

Essas informações permitem que a equipe técnica tome decisões baseadas em dados para **reduzir despesas desnecessárias**.

---

## Etapa 2 – Otimização Automática de Recursos

**Ferramenta:** AWS Compute Optimizer  

**Foco da ferramenta:**  
Recomendações automáticas para otimização de instâncias e recursos computacionais.

### Caso de Uso

O Compute Optimizer foi utilizado para analisar métricas de desempenho de recursos como:

- Instâncias EC2  
- Volumes EBS  
- Funções Lambda  

A ferramenta gera recomendações como:

- Redimensionamento de instâncias superdimensionadas  
- Substituição por tipos de instâncias mais econômicos  
- Ajuste de configurações de recursos  

Essas recomendações permitem **reduzir custos mantendo desempenho e disponibilidade dos sistemas**.

---

## Etapa 3 – Armazenamento Inteligente de Baixo Custo

**Ferramenta:** Amazon S3 Intelligent-Tiering  

**Foco da ferramenta:**  
Otimização automática de custos de armazenamento de dados.

### Caso de Uso

Foi implementada a classe de armazenamento **S3 Intelligent-Tiering**, que move automaticamente os dados entre camadas de armazenamento conforme a frequência de acesso.

### Benefícios da solução

- Redução automática de custos para dados pouco acessados  
- Manutenção da disponibilidade imediata dos arquivos  
- Eliminação da necessidade de gerenciamento manual de camadas de armazenamento  

Essa solução garante **economia contínua no armazenamento de dados corporativos**.

---

## Conclusão

A implementação das ferramentas AWS na empresa Abstergo Industries proporcionou maior controle sobre os custos da infraestrutura em nuvem e uma utilização mais eficiente dos recursos disponíveis.

### Principais benefícios obtidos

- Redução de desperdício de recursos computacionais  
- Melhor visibilidade e controle sobre gastos na nuvem  
- Otimização automática de armazenamento e processamento  
- Maior eficiência operacional  

Recomenda-se a continuidade do uso dessas ferramentas, bem como a adoção de práticas de **FinOps**, com avaliações periódicas de novos serviços e estratégias de otimização financeira na infraestrutura.

---

## Responsável pelo Projeto

**Ana Muniz**  
Projeto desenvolvido para a **DIO (Digital Innovation One)**.
