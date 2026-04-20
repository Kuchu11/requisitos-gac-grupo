# requisitos-gac-grupo

# GAC – Gestão de Ativos do CCT

## 👥 Equipe do Projeto

* **Wesley**
* **Emily**
* **Suyane**
* **Salua**

**Orientador:** Prof. Marcelo Bezerra

---

## 1. Problema e Oportunidade

O controle de empréstimo de projetores, chaves e outros ativos do CCT é feito de forma manual ou descentralizada, gerando dificuldade de rastreio e perdas. A solução proposta é uma plataforma digital integrada a identificadores físicos (NFC/QR Code) para maior eficiência e transparência.

## 2. Identificação de Stakeholders

* **Professores:** Solicitam e devolvem equipamentos.
* **Equipe do CCT:** Operacionaliza o sistema e verifica o estado dos bens.
* **TI da Unifor:** Apoio em infraestrutura e autenticação.
* **Coordenação/Direção:** Acompanham indicadores de uso.

## 3. Requisitos Principais

* **RF01:** Cadastro de ativos com status.
* **RF07:** Leitura de QR Code/NFC para identificação rápida.
* **RNF01:** Disponibilidade do sistema de 99%.
* **RNF06:** Interface simples e responsiva (máximo 3 cliques).

## 4. Regras de Negócio (RN)

| ID             | Descrição                                                       |
| :------------- | :---------------------------------------------------------------- |
| **RN01** | Um professor não pode retirar mais de 3 ativos simultaneamente.  |
| **RN02** | O prazo máximo de empréstimo é de 7 dias (renovável uma vez). |
| **RN04** | Atraso gera pendência que impede novas retiradas.                |
| **RN05** | Itens em manutenção não podem ser emprestados.                 |

## 5. Backlog Priorizado (MoSCoW)

* **🟢 Must Have:** Cadastro, Empréstimo, Devolução, Login e Regras de limite.
* **🟡 Should Have:** Leitura QR Code/NFC e Relatórios básicos.
* **🔵 Could Have:** Reserva futura e Dashboards.
