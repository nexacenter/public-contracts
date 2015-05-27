<ol type="1">

<li><b>Quali dati avete usato?</b></li>
<p>Quelli esposti dalle pubbliche amministrazioni italiane secondo quanto prescritto dalla "Legge Anticorruzione", (L. 190/2012), che disciplina, tra l’altro, gli obblighi di trasparenza, pubblicità e diffusione delle informazioni riguardanti i bandi di gara ed i contratti pubblici. In particolare, le modalità di pubblicazione dei dati - in formato XML - sono strettamente regolamentate dall'ANAC (Autorità Nazionale Anti Corruzione), il che ha favorito il rilascio, dal 2012, di grandi quantità informazioni in formato standard ed aperto.<a href=”http://dati.anticorruzione.it/L190.html”>portale Open Data dell’ANAC</a>.</p>

<li><b>Quale tecnologia avete usato?</b></li>
<p>Linked open data! Usando ontologie standard, abbiamo convertito gli <a href=”http://it.wikipedia.org/wiki/XML”>XML</a> originari in <a href=”http://it.wikipedia.org/wiki/Resource_Description_Framework”RDF</a>, un formalismo del web dei dati. Ora i dati sono interrogabili mediante un end-point <a href=”http://it.wikipedia.org/wiki/SPARQL”>SPARQL</a>.</p>

<li><b>Ho fatto una ricerca, e per un dato ente il totale degli importi aggiudicati e il totale degli importi percepiti non coincidono. Come mai?</b></li>
<p>Se il primo è più alto del secondo, è possibile che l’orizzonte temporale del contratto vada oltre il 2014, e che quindi non sia ancora stato erogato l’intero importo, oppure che la PA abbia pubblicato dati incompleti per gli anni precedenti. Se il secondo è più alto del primo, è possibile che, in corso d’opera, l’ammontare dell’erogazione sia cresciuta, ad esempio per un aumento dei costi. Naturalmente, si tratta di esempi che non rendono conto di tutte le fattispecie possibili, che andrebbero comunque valutate caso per caso.</p>

<li><b>Ho fatto una ricerca e non ho trovato un certo ente. Come mai?</b></li>
<p>Non tutti gli organismi pubblici hanno esposto correttamente i dati ex “Decreto Trasparenza” sui contratti pubblici. Inoltre, al 21/05/2015, circa il 30% dei link di file xml presenti sul <a href=”http://dati.anticorruzione.it/L190.html”>portale Open Data dell’ANAC</a> sono errati o non restituiscono file validi, e circa 5000 PA sono completamente assenti sul  portale Open Data ANAC.   Ti consigliamo di segnalare il problema alla PA mancante, affinché possa colmare la lacuna.</p>

<li><b>Perché certi soggetti compaiono sia come stazioni appaltanti, sia come aggiudicatari di contratti?</b></li>
<p>Si tratta per la gran parte di organismi pubblici, i quali possono essere stazione appaltante, e in altri casi, aggiudicatari di un bando promosso da un altro ente pubblico.</p>

<li><b>Ci sono limitazioni all’uso dei dati?</b></li>
<p>Questi dati sono rilasciati con licenza creative commons attribution share-alike 4.0 in ragione della compatibilità con la licenza IODL 1.0 con la quale sonon rilasciati i dataset originali.</p>

<li><b>Quali ontologie sono state usate per generare i linked data?</b></li>
<p>
pc:         http://purl.org/procurement/public-contracts#
dcterms:     http://purl.org/dc/terms#
gr:         http://purl.org/goodrelations/v1#
dbpedia-owl:    http://dbpedia.org/ontology/
pay:         http://reference.data.gov.uk/def/payment#
time:        http://www.w3.org/2006/time#
org:        http://www.w3.org/ns/org#
foaf:        http://xmlns.com/foaf/0.1#
Sono state usate properties custom per esprimere il ruolo di un'azienda in un raggruppamento e per esprimere i tipi di procedura. 
</p>

</ol>
