# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

**Data:** 02 de março de 2026  
**Empresa:** Abstergo Industries  
**Responsável:** Armando de Lima  

---

## Introdução

Este relatório apresenta o processo de implementação de ferramentas na empresa **Abstergo Industries**, realizado por Armando de Lima.

O objetivo do projeto foi elencar três serviços da **Amazon Web Services (AWS)** com a finalidade de promover a diminuição imediata de custos operacionais, bem como melhorar a escalabilidade, disponibilidade e eficiência da infraestrutura tecnológica da organização.

---

## Descrição do Projeto

O projeto de implementação foi dividido em três etapas, cada uma com objetivos específicos voltados à otimização de recursos e modernização da arquitetura de sistemas.

---

## Etapa 1 – Amazon EC2 Auto Scaling

**Foco:** Ajuste automático de capacidade computacional conforme a demanda.

### Caso de Uso

O Amazon EC2 Auto Scaling permite aumentar ou reduzir automaticamente a quantidade de instâncias do Amazon EC2 em execução, de acordo com métricas de utilização previamente definidas.

- Em períodos de alta demanda, novas instâncias são provisionadas automaticamente.
- Quando a demanda diminui, instâncias excedentes são encerradas.
- Redução de desperdício de recursos.
- Otimização de custos operacionais.

Essa abordagem elimina a necessidade de manter servidores ociosos permanentemente ativos.

---

##  Etapa 2 – Elastic Load Balancing

**Foco:** Distribuição inteligente de tráfego e alta disponibilidade.

### Caso de Uso

O Elastic Load Balancing distribui automaticamente o tráfego de entrada entre múltiplas instâncias EC2, garantindo melhor aproveitamento dos recursos disponíveis.

- Distribuição equilibrada de requisições.
- Verificação de integridade (Health Checks).
- Redirecionamento automático em caso de falha.
- Maior disponibilidade da aplicação.

Com isso, a empresa reduz riscos de indisponibilidade, melhora a experiência do usuário e evita sobrecarga em servidores específicos.

---

##  Etapa 3 – Amazon SQS

**Foco:** Comunicação desacoplada entre microserviços e organização de requisições.

###  Caso de Uso

O Amazon SQS é um serviço de mensageria baseado em filas que permite a comunicação assíncrona entre componentes da aplicação.

###  Arquitetura do Modelo

- **Produtor** → Envia a mensagem  
- **Fila** → Armazena temporariamente  
- **Consumidor** → Processa a mensagem  

### Benefícios

- Processamento organizado de requisições  
- Redução de sobrecarga imediata  
- Aumento da escalabilidade  
- Desacoplamento entre microserviços  
- Arquitetura mais resiliente  

---

## Conclusão

A implementação das ferramentas na empresa **Abstergo Industries** tem como resultado esperado:

- Redução imediata de custos com infraestrutura  
- Aumento da disponibilidade dos sistemas  
- Maior eficiência operacional  
- Arquitetura escalável e resiliente  

O uso conjunto do Amazon EC2 Auto Scaling, Elastic Load Balancing e Amazon SQS proporciona uma estrutura alinhada às boas práticas de computação em nuvem.

Recomenda-se a continuidade da utilização das ferramentas implementadas e a avaliação constante de novas tecnologias para aprimoramento dos processos internos.


## Assinatura do Responsável

**Armando de Lima**
