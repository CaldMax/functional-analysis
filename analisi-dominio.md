# Analisi di dominio

## ER diagrams
    
```mermaid
erDiagram
    Verbale ||--|| Contante : "has fixed number of"
    Contante ||--|| ImportoRiferimento : "defined by"
    Contante ||--|| QuantitaContante : has
    Verbale ||--|{ Varie : has
    Varie ||--|| ID : "defined by"
    Varie ||--|| QuantitaVarie : has
    Verbale ||--|| Stampa : has
```

### Legenda significati relazione
```mermaid
erDiagram
    A |o..o| B : Zero or more
```
```mermaid
erDiagram
    A |o..o| B : Exactly 1
```
```mermaid
erDiagram
    A }o..o{ B : Zero or more (no upper limit)
```
```mermaid
erDiagram
    A }|..|{ B : One or more (no upper limit)
```

## Lettura giacenze di cassa

## Entità

## Vocabolario




