La procedura verrà eseguita quando il giocatore utilizzerà il trigger del portale su un blocco.

La procedura dovrebbe restituire un risultato di azione di tipo SUCCESS/CONSUME se il trigger ha interagito con il blocco, FAIL se l'interazione non è riuscita e PASS se non c'è stata alcuna interazione. Se il trigger ha creato correttamente un portale o se la procedura non restituisce alcun valore, il tipo di risultato dell'azione sarà SUCCESS.