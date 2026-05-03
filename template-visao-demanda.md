# Visão da Demanda (VD)

## Histórico de Versões

| Data | Versão | Descrição | Autor |
| --- | --- | --- | --- |
| 03/05/2026 | 1.0 | Elaboração inicial do documento de visão da demanda para o sistema de locação de projetores | Emily da Silva Freitas; Salua Rayane Melo; Suyane Pereira Costa; Wesley Amorim Campêlo |
|  |  |  |  |

---

## Autores

- Emily da Silva Freitas  
- Salua Rayane Melo  
- Suyane Pereira Costa  
- Wesley Amorim Campêlo  

---

## 1. Objetivo

Este documento tem como objetivo apresentar a visão da demanda para o desenvolvimento de um sistema informatizado de controle e locação de projetores e equipamentos audiovisuais, visando otimizar processos operacionais, aumentar a rastreabilidade dos ativos e melhorar a eficiência no atendimento aos usuários.

---

## 2. Proposta de Valor

A implementação da solução proposta permitirá a substituição do controle manual atualmente realizado por meio de registros físicos, promovendo maior agilidade no atendimento e redução significativa de filas em horários de pico.

Adicionalmente, o sistema proporcionará maior controle e transparência no uso dos equipamentos, garantindo rastreabilidade completa dos ativos, segurança na transferência de responsabilidade entre usuários e suporte à tomada de decisão por meio de relatórios e indicadores de uso.

---

## 3. Descrição da Demanda

Atualmente, o processo de empréstimo de projetores é realizado por meio de um único caderno físico, o que ocasiona filas, especialmente em períodos de troca de turno. Além disso, a prática informal de repasse de equipamentos entre professores compromete a rastreabilidade, uma vez que a responsabilidade permanece vinculada ao primeiro usuário registrado.

Diante desse cenário, propõe-se o desenvolvimento de um sistema no domínio de locação de equipamentos, com as seguintes funcionalidades principais:

- Cadastro e gerenciamento de ativos (projetores e cabos)  
- Registro e controle de empréstimos  
- Verificação de disponibilidade em tempo real  
- Solicitação e agendamento de uso  
- Repasse digital de responsabilidade entre usuários  
- Registro de histórico de manutenção  
- Geração de relatórios gerenciais e estatísticos  

O sistema deverá atender diferentes perfis de usuários, contemplando funcionalidades específicas para cada papel envolvido no processo.

---

## 4. Partes Interessadas

| Nome | Papel | Responsabilidades | Representante |
| -------------------- | --------------- | ----------------------------------- | ---------------- |
| Professores | Usuários finais | Solicitar, utilizar e transferir equipamentos | - |
| Equipe do CCT | Operacional | Gerenciar empréstimos, validar condições dos equipamentos | - |
| Diretor do CCT | Cliente | Validar a solução e acompanhar indicadores de desempenho | Prof. Jackson |
| DTEC | Suporte técnico | Garantir infraestrutura, manutenção e integração tecnológica | - |
| Coordenadores | Stakeholders | Assegurar a disponibilidade de recursos para as atividades acadêmicas | - |

---

## 5. Personas

### 5.1. Professor

- **Descrição:** Docente que depende do uso de recursos audiovisuais para execução de suas atividades acadêmicas.  
- **Objetivo:** Realizar a solicitação de equipamentos de forma ágil, confiável e com garantia de disponibilidade, além de possibilitar a transferência de responsabilidade quando necessário.  

### 5.2. Atendente do CCT

- **Descrição:** Profissional responsável pela gestão operacional dos equipamentos e atendimento aos usuários.  
- **Objetivo:** Controlar empréstimos com eficiência, reduzir filas e assegurar a integridade e rastreabilidade dos ativos.  

---

## 6. Necessidades e Funcionalidades

### Necessidade 1: Controle de acesso ao sistema

#### F1.1 Autenticação de usuários

- **Descrição:** Permitir a autenticação de usuários por meio de credenciais válidas, garantindo segurança no acesso ao sistema.  
- **Incluída**  
- **Atores:** Funcionário, Professor  
- **Frequência:** Alta  
- **Valor:** Alto  

---

### Necessidade 2: Gestão de ativos

#### F2.1 Cadastro de equipamentos

- **Descrição:** Permitir o registro de projetores e cabos com identificação patrimonial.  
- **Incluída**  
- **Atores:** Funcionário  
- **Frequência:** Média  
- **Valor:** Alto  

#### F2.2 Atualização e remoção de ativos

- **Descrição:** Permitir a atualização de informações e remoção de equipamentos do sistema.  
- **Incluída**  
- **Atores:** Funcionário  
- **Frequência:** Média  
- **Valor:** Médio  

#### F2.3 Consulta de disponibilidade

- **Descrição:** Disponibilizar informações em tempo real sobre a disponibilidade dos equipamentos.  
- **Incluída**  
- **Atores:** Funcionário, Professor  
- **Frequência:** Alta  
- **Valor:** Alto  

---

### Necessidade 3: Processo de locação

#### F3.1 Solicitação de equipamentos

- **Descrição:** Permitir que usuários realizem solicitações de empréstimo.  
- **Incluída**  
- **Atores:** Professor  
- **Frequência:** Alta  
- **Valor:** Alto  

#### F3.2 Aprovação de solicitações

- **Descrição:** Permitir que funcionários aprovem ou rejeitem solicitações.  
- **Incluída**  
- **Atores:** Funcionário  
- **Frequência:** Alta  
- **Valor:** Alto  

#### F3.3 Agendamento de uso

- **Descrição:** Permitir o agendamento prévio de equipamentos para datas e horários específicos.  
- **Incluída**  
- **Atores:** Professor  
- **Frequência:** Alta  
- **Valor:** Alto  

---

### Necessidade 4: Transferência de responsabilidade

#### F4.1 Repasse digital de equipamentos

- **Descrição:** Permitir a transferência de responsabilidade entre usuários por meio de confirmação mútua, garantindo rastreabilidade.  
- **Incluída**  
- **Atores:** Professor  
- **Frequência:** Média  
- **Valor:** Alto  

---

### Necessidade 5: Monitoramento e controle

#### F5.1 Relatórios gerenciais

- **Descrição:** Gerar relatórios que identifiquem padrões de uso, incluindo equipamentos mais e menos utilizados.  
- **Incluída**  
- **Atores:** Funcionário, Diretor  
- **Frequência:** Média  
- **Valor:** Alto  

#### F5.2 Histórico de manutenção

- **Descrição:** Registrar manutenções realizadas e alertar sobre prazos de garantia.  
- **Incluída**  
- **Atores:** Funcionário  
- **Frequência:** Baixa  
- **Valor:** Médio  

---

## 7. Arquitetura da Demanda

A solução será estruturada com base no domínio de locação de equipamentos, contemplando os seguintes módulos:

- Módulo de autenticação e controle de acesso  
- Módulo de gestão de ativos  
- Módulo de locação e agendamento  
- Módulo de relatórios e monitoramento  

Adicionalmente, devem ser considerados os seguintes requisitos não funcionais:

- Usabilidade: interface simples e intuitiva  
- Desempenho: respostas rápidas às operações do usuário  
- Segurança: proteção de dados e autenticação confiável  
- Disponibilidade: acesso contínuo ao sistema  

---

## 8. Regras de Negócio

- **RN01:** Usuários não poderão realizar novas solicitações enquanto houver pendências de devolução.  
- **RN07:** Todos os equipamentos devem ser devolvidos no mesmo dia de retirada.  
- **RN08:** Em caso de defeito, o sistema deverá automatizar a substituição do equipamento, registrando a ocorrência.  

---

## 9. Priorização (MoSCoW)

### Must Have (Obrigatórios)
- Autenticação de usuários  
- Cadastro e gestão de equipamentos  
- Solicitação e aprovação de empréstimos  
- Controle de disponibilidade  

### Should Have (Importantes)
- Agendamento de equipamentos  
- Relatórios de uso  
- Histórico de manutenção  

### Could Have (Desejáveis)
- Indicadores avançados de desempenho  
- Melhorias de interface e experiência do usuário  

### Won’t Have (Não contemplados neste momento)
- Funcionalidades de baixa prioridade ou fora do escopo inicial  

---

## 10. Validação e Verificação

O documento deverá passar por processo de revisão em grupo, assegurando conformidade com o padrão estabelecido e qualidade das informações descritas.

Eventuais divergências deverão ser discutidas e registradas em ata, com identificação dos responsáveis pelas decisões, priorizando impacto e urgência.

---

## 11. Pré-Validação

A versão final do documento será submetida à validação junto aos stakeholders, garantindo alinhamento com as necessidades reais do cliente e viabilidade da solução proposta.

---

## Checklist de Validação do Documento de Visão

- [x] Objetivo claramente definido  
- [x] Proposta de valor consistente e relevante  
- [x] Stakeholders identificados  
- [x] Personas descritas  
- [x] Funcionalidades associadas a atores  
- [x] Valor e frequência definidos  
- [x] Arquitetura descrita  
- [x] Linguagem formal, clara e objetivaa  