## 1. Requisitos Funcionais (RF)

* **RF01 - Cadastro de Ativos:** O sistema deve permitir o registro de projetores (por patrimônio) e cabos (HDMI/VGA/USB numerados de 1 a 25).
* **RF02 - Registro de Empréstimo:** O sistema deve vincular um ativo a um professor, registrando Matrícula, Centro de Origem, Bloco, Sala e Turno.
* **RF08 - Repasse Digital (Novo):** O sistema deve permitir que um professor transfira a responsabilidade de um item para outro colega via confirmação mútua (QR Code), resolvendo o problema do repasse informal.
* **RF09 - Histórico de Manutenção:** O sistema deve registrar quando um item vai para conserto e alertar sobre o fim da garantia (3 meses).

## 2. Regras de Negócio (RN)

* **RN01:** Um professor não pode retirar novos ativos se tiver pendências de devolução.
* **RN07:** Todo item deve ser devolvido no mesmo dia (até às 22:40), independentemente do bloco.
* **RN08:** No caso de troca de item por defeito, o sistema deve dar baixa no item antigo e abrir um novo registro automaticamente para o professor não perder tempo.
