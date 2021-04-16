# Analisi di dominio

## ER diagrams
@startmermaid
erDiagram
    Verbale ||..|| Contante : "has fixed number of"
    Contante ||--|| ImportoRiferimento : "defined by"
    Contante ||--|| QuantitaContante : has
    Verbale ||--|{ Varie : has
    Varie ||--|| ID : "defined by"
    Varie ||--|| QuantitaVarie : has
    Verbale ||--|| Stampa : has
@endmermaid

### Legenda significati relazione
@startmermaid
erDiagram
    A |o..o| B : Zero or more
@endmermaid
@startmermaid
erDiagram
    A |o..o| B : Exactly 1
@endmermaid
@startmermaid
erDiagram
    A }o..o{ B : Zero or more (no upper limit)
@endmermaid
@startmermaid
erDiagram
    A }|..|{ B : One or more (no upper limit)
@endmermaid

## Lettura giacenze di cassa

## Entità

## Vocabolario




