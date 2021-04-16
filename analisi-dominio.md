---
layout: default
title: Analisi di dominio
nav_order: 5
---

# Analisi di dominio

## Definizione entities e value objects

- Entities
  - verbale
  - taglio contante
  - taglio varie
  - cassa
- Value Objects
  - fatto amministrativo
  - mastro contabile
  - stampa verbale
  - giacenza di cassa
  - parametri di dominio cassa
  - sessione

## ER diagrams
![ER](./Images/ER01.png)

## Interazioni

|**Da**|**interazione**|**A**|
|---|---|---|
|verbale| chiede la giacenza|cassa|
|verbale| chiede i codici di voci varie | parametri di dominio cassa|
|verbale| comunica la giacenza | taglio contante / varie|
|verbale| legge la giacenza dichiarata | taglio contante / varie|
|verbale| aggiorna la giacenza | cassa|
|verbale| chiede l'utente attivo | sessione|
|verbale| verifica autorizzazioni per l'utente attivo | contabilità|

## ettura giacenze di cassa

## Entità

## Vocabolario




