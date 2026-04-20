# Especificação de Requisitos e Regras de Negócio

## 1. Requisitos Funcionais (RF)

* **RF01 - Cadastro de Ativos:** O sistema deve permitir o registro de novos bens com categoria e status.
* **RF02 - Registro de Empréstimo:** O sistema deve vincular um ativo a um professor solicitante.
* **RF03 - Registro de Devolução:** O sistema deve registrar o retorno do bem e seu estado físico.
* **RF04 - Autenticação:** O sistema deve permitir login seguro para equipe e professores.
* **RF07 - Integração Física:** O sistema deve permitir leitura de QR Code ou NFC para identificação rápida.

## 2. Requisitos Não Funcionais (RNF)

* **RNF01 - Disponibilidade:** O sistema deve estar disponível 99% do tempo.
* **RNF03 - Desempenho:** O tempo de resposta para buscas deve ser inferior a 2 segundos.
* **RNF06 - Usabilidade:** Interface responsiva e simples (máximo de 3 cliques para ações principais).

## 3. Regras de Negócio (RN)

* **RN01:** Um professor não pode retirar mais de 3 ativos simultaneamente.
* **RN02:** O prazo máximo de empréstimo é de 7 dias (renovável uma vez).
* **RN04:** Atrasos geram pendências que impedem novas retiradas.
* **RN05:** Itens em manutenção não podem ser emprestados.



## 4. Regras de Negócio (RN)

*As leis que regem o funcionamento do sistema GAC.*

| ID             | Descrição                                                             |
| :------------- | :---------------------------------------------------------------------- |
| **RN01** | Um professor não pode retirar mais de 3 ativos simultaneamente.        |
| **RN02** | O prazo máximo de empréstimo é de 7 dias (renovável uma vez).       |
| **RN03** | Somente a equipe do CCT pode cadastrar/editar ativos e registrar danos. |
| **RN04** | Atraso na devolução gera pendência que impede novas retiradas.       |
| **RN05** | Itens com status "em manutenção" não podem ser emprestados.          |
| **RN06** | O estado do bem na devolução é obrigatório e validado pelo CCT.     |

## 5. Backlog Priorizado (MoSCoW)

*Priorização das entregas para a gestão do projeto.*

* **Must Have (Obrigatório):** Cadastro de ativos, Empréstimo, Devolução, Login e Regras de limite/pendência (RF01, RF02, RF03, RF06, RN01, RN02, RN04).
* **Should Have (Importante):** Leitura de QR Code/NFC e Relatórios básicos (RF07, RF08).
* **Could Have (Desejável):** Dashboard de indicadores para a coordenação.
