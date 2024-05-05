Schemele relaţionale ale modelului folosit sunt:

```
STUDENT (cod_student, nume, prenume, data_nasterii, nr_matricol, grupa, an, cnp, sectie)
PROFESOR (cod_profesor, nume, prenume, data_nasterii, data_angajarii, titlu, salariu)
CURS (cod_curs, denumire, nr_credite, cod_profesor)
NOTE (cod_student, cod_curs, nota, data_examinare)
```

### Exercitiul 1

Afişaţi numele şi prenumele profesorilor, împreună cu numele şi prenumele studenţilor, născuţi în aceeaşi lună cu profesorii, care au urmat cel puţin un curs al acestora. (2p)

### Exercitiul 2

Numele şi prenumele studenţilor care au avut restanţe la cel puţin aceleaşi cursuri ca şi studentul care are codul 1. (2.5p)

### Exercitiul 3

Pentru fiecare profesor şi pentru fiecare curs ţinut de aceştia afişaţi numărul total de studenţi care au promovat. (2p)

### Exercitiul 4

Creaţi tabelul credite care să conţină codul, cnp-ul şi numărul total de credite pe care le deţine fiecare student. Adăugaţi o constrângere de tip not null şi o constrângere de tip foreign key. (2.5p)