# Boris Borroni

Studente di Ingegneria Matematica al Politecnico di Torino.

Ogni progetto parte da una domanda precisa e riporta il risultato così com'è, anche quando è negativo.

## Progetti

| Progetto | Domanda | Risultato in breve |
|---|---|---|
| [volatility-surface](https://github.com/BorisBorroni/volatility-surface) | Vendere opzioni su SPY e coprirle in delta dà un vantaggio? | Superficie SVI senza arbitraggi evidenti sui dati; il premio della volatilità implicita sulla singola opzione ATM non è distinguibile da zero, quindi nessun vantaggio dimostrato. |
| [yield-curve-relative-value](https://github.com/BorisBorroni/yield-curve-relative-value) | Gli scostamenti dei Treasury dalla curva di Nelson-Siegel sono un segnale sfruttabile? | Formule verificate contro la curva della Fed; scambiando il giorno dopo il segnale e con costi di pochi decimi di punto base il guadagno sparisce. |
| [markov-regime-allocation](https://github.com/BorisBorroni/markov-regime-allocation) | Una catena di Markov sui regimi di volatilità migliora l'allocazione di portafoglio? | Drawdown molto più basso del mercato, ma nessun valore aggiunto rispetto a un semplice vol targeting. |
| [risk-managed-momentum](https://github.com/BorisBorroni/risk-managed-momentum) | La gestione della volatilità del momentum (Barroso e Santa-Clara 2015) funziona anche dopo il periodo del paper? | Crolli e drawdown molto più bassi fuori campione; miglioramento dello Sharpe al limite della significatività e non distinguibile da zero con i costi. |

## Come lavoro

- Solo dati gratuiti, con le fonti e i limiti dichiarati.
- Python, test automatici con pytest e integrazione continua su GitHub Actions.
- Dove possibile, prima un controllo su un caso noto (mondo sintetico, curva della Fed, replica di un paper), poi i dati veri.
- Dove possibile, criteri del verdetto fissati prima del test fuori campione.
