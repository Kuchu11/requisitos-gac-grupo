# Diagramas UML - Projeto GAC

## Diagrama de Casos de Uso (Mermaid)

```mermaid
useCaseDiagram
    Professor --> (Solicitar Ativo)
    Professor --> (Transferir para Colega)
    (Solicitar Ativo) ..> (Identificar via QR/NFC) : include
    Atendente --> (Registrar Devolução)
    Atendente --> (Validar Estado do Bem)
    Atendente --> (Gerar Relatório de Pendência)