Mi chiamo Claudio Govi. Da anni mi dedico, in modo indipendente, allo studio della fattorizzazione dei semiprimi e delle sue potenzialità applicative in ambito crittografico.
Il risultato di questa ricerca è GC57, un algoritmo originale in grado di fattorizzare grandi semiprimi istantaneamente, indipendentemente dalla loro dimensione. L'algoritmo non fa uso di metodi probabilistici, euristici o computazionalmente intensivi.

GC57 sfrutta proprietà numeriche che ho individuato attraverso un approccio logico-sperimentale e non basato sulla letteratura accademica. I fattori dei semiprimi vengono determinati con rapidità, permettendo di generare chiavi crittografiche in modo controllato.

Su questa base, ho sviluppato un sistema di cifratura simmetrica che utilizza:

    la generazione controllata di semiprimi molto grandi (fino a decine di migliaia di bit);

    l'estrazione immediata dei fattori, da cui viene derivata la chiave simmetrica;

    la cifratura e decifratura di file e messaggi;

    la possibilità di includere dati accessori (es. allegati) all’interno del file cifrato.

L’implementazione è realizzata in Python, con particolare attenzione alla gestione di grandi numeri interi, all'uso controllato di hash crittografici e alla semplicità operativa.

    Nota importante: GC57 non si basa su metodi accademici consolidati, ma su un modello logico personale sperimentato empiricamente.
    
Se volete saperne di più visitate https://claugo.github.io/GC57PrimeCrypt/ OPPURE  www.gc57crypto.net

