# Tesi-Tecniche-di-Machine-Learning-per-la-Selezione-della-Terapia-nei-casi-di-Malaria-Severa
Tesi-Tecniche di Machine Learning per la Selezione della Terapia nei casi di Malaria Severa

In questa tesi vengono presentate alcune tra le più famose tecniche di Machine Learning e la loro applicazione per la selezione della terapia nei casi di malaria severa. Il dataset è stato fornito dell'Istituto Lazzaro Spallanzani di Roma, e consiste in una lista dei principali parametri clinici di 259 pazienti, dei quali 119 con malaria severa.

Dopo aver descritto brevemente il funzionamento dei classificatori Support Vector Machine e Random Forest, si sono costruiti due modelli che facessero corrispondere ad ogni paziente, la terapia più adatta tra due possibili scelte (si tratta quindi di un problema di classificazione binaria).

Per individuare le caratteristiche del paziente più rilevanti nel compiere tale decisione, sono stati utilizzati due strumenti di feature selection. I risultati ottenuti hanno confermato l'importanza degli attuali criteri della World Health Organization, ma hanno sottolineato anche il contributo di alcuni valori ematici. Queste informazioni sono state sfruttare per migliorare le performance dei classificatori precedenti, arrivando a buoni livelli di accuratezza.

Come ultima fase, sono stati implementati due algoritmi di Clustering, al fine di determinare delle naturali suddivisioni del dataset. In particolare, sono stati individuati due gruppi, ognuno dei quali con una prevalenza di pazienti con una determinata terapia. Una nuova feature selection su questi gruppi ha aggiunto alle feature rilevanti, quella relativa ai trattamenti di chemioprofilassi.
