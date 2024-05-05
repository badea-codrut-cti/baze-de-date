Se consideră chemele relaţionale:

```
ALBUM (id_album, id_formatie, gen, nume, data_l, pret)
FORMATIE (id_formatie, nume, data_lansare, data_retragere , website, tara_prov)
PREMIU (id_premiu, concurs, sectiune, frecventa, tara_prov)
CASTIGA (id_premiu, id_formatie, data_d, loc_ocupat, recompensa)
```

### Exercitiul 1

Pentru formaţiile care au participat la concursuri desfăşurate anual, se cere numele, website-ul, împreună cu albumele lansate (nume, pret) care au avut preţul de vânzare mai mare de 30. (3 p)

### Exercitiul 2

Pentru fiecare premiu câştigat de o formaţie să se afişeze numele, locul ocupat, precum şiultimul album lansat (id_album, nume) înainte de decernare. (2 p)

### Exercitiul 3

Se cer numele, data lansării, numărul de albume lansate, pentru formaţiile care au câştigat doar premii bianuale. (2 p)

### Exercitiul 4

Creaţi o vizualizare care să conţină detalii despre formaţiile care au lansat albume pop şi nu au câştigat premii. Inseraţi o linie prin intermediul acestei vizualizări. (2 p)