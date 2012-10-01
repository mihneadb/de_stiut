# Concepte de bază din Computer Science

## Structuri de date

### Liste

Implementare simplă în C. Simplu sau dublu înlănțuită. Cu santinelă sau fără santinelă.

Probleme:

* implementarea unei stive
* implementarea unei cozi
* implementarea unei cozi folosind două stive
	* se folosește o stivă pentru inserări și una pentru eliminări; când una dintre stive este vidă, se (re)normalizează
* verificarea dacă o listă simplu înlănțuită conține cicluri
	* se folosesc doi pointeri ce avansează cu viteze diferite; dacă cel mai rapid ajunge peste cel mai lent, există un ciclu


### Arbori binari

Implementare simplă, cu pointeri, în C: celulă cu date, pointeri pt fiu stânga și fiu dreapta.

Probleme:

* parcurgeri: SRD, RSD, SDR
* implementarea unui arbore binar de căutare
* funcție care verifică dacă un arbore binar este echilibrat
	* nicio pereche de frunze să nu aibă diferența de nivel mai mare decât 1
* căutare într-un prefix tree (trie)


### Vectori

Cu dimensiune fixată sau cu realocare dinamică.

Probleme:

* implementarea unui vector cu realocare dinamică; analiză complexitate
* funcție care inversează un string (sub formă de vector de caractere) in-place


### Tabele asociative (Maps)

Implementare cu funcție de hash și vector vs implementare cu arbori. Cost pentru căutare, memorie ocupată. Păstrarea elementelor în ordine.

Probleme:

* număr de apariții / elemente unice într-un string
* implementarea unui hash table simplist
	* vector de liste, indicele în vector calculat cu o funcție comodă