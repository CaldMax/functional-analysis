# Analisi extra dominio

# Interazioni
## Impianti organizzativi

|**Obiettivo**|**Input**|**Output**|
|---|---|---|
| elenco delle filiali della banca e relativa denominazione | nessuno | elenco di coppie (filiale(numero), denominazione(stringa)) |

## Contabilità

|**Obiettivo**|**Input**|**Output**|
|---|---|---|
|lettura del mastro di contabilità associato ad una cassa cassa|numero di cassa|mastro contabile associato alla cassa|
|lettura del mastro di contabilità associato agli ammanchi di cassa|codice identificativo "ammanchi di cassa"|mastro contabile associato |
|lettura del mastro di contabilità associato alle eccedenze di cassa|codice identificativo "eccedenze di cassa"|mastro contabile associato |
|lettura del saldo di contabilità di un mastro contabile|mastro contabile + filiale + data|saldo contabile|
|esecuzione di una scrittura contabile|codice servizio + mastro contabile + importo + segno + valuta + filiale|tipo + anno + numero|


