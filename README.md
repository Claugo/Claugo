Mi chiamo Claudio Govi. Da anni mi dedico, in modo indipendente, allo studio della fattorizzazione dei semiprimi e delle sue potenzialità applicative in ambito crittografico.
Il risultato di questa ricerca è GC57, un algoritmo originale in grado di fattorizzare grandi semiprimi istantaneamente, indipendentemente dalla loro dimensione. L'algoritmo non fa uso di metodi probabilistici, euristici o computazionalmente intensivi.

GC57 sfrutta proprietà numeriche che ho individuato attraverso un approccio logico-sperimentale e non basato sulla letteratura accademica. I fattori dei semiprimi vengono determinati con rapidità, permettendo di generare chiavi crittografiche in modo controllato.

Su questa base, ho sviluppato un sistema a chiave simmetrica indipendente dalla chiave di cifratura, che utilizza:

    la generazione controllata di semiprimi molto grandi (fino a decine di migliaia di bit);

    l'estrazione immediata dei fattori, da cui viene derivata la chiave di cifratura;

    la cifratura e decifratura di file e messaggi;

    la possibilità di includere dati accessori (es. allegati) all’interno del file cifrato.

L’implementazione è realizzata in Python, con particolare attenzione alla gestione di grandi numeri interi, all'uso controllato di hash crittografici e alla semplicità operativa.
    

Nota importante: Il metodo GC57 non si fonda su approcci accademici tradizionali, bensì su un modello logico originale, sviluppato e testato empiricamente. 
I programmi di crittografia da me realizzati non hanno finalità commerciali, ma servono esclusivamente come strumenti dimostrativi per evidenziare, in modo pratico,
l’efficacia di questo metodo di fattorizzazione.


Per approfondire:

Potete visitare il sito informativo:

🔹 https://claugo.github.io/GC57PrimeCrypt/

oppure

🔹 https://www.gc57crypto.net

L’intero saggio sul sistema GC57, articolato in tre documenti distinti, è disponibile su Zenodo:

📄 Documento introduttivo: https://zenodo.org/records/15640331

📄 Approfondimento tecnico: https://zenodo.org/records/15742011

📄 Estensione ai contenitori modulari: https://zenodo.org/records/15809129

Autore ORCID: https://orcid.org/0009-0005-9020-0691
