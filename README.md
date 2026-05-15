Obiectivul principal al proiectului este utilizarea instrumentelor de analiza spatiala (GIS) pentru a localiza zonele cu un deficit critic de locuri in invatamantul liceal.

In cadrul acestui studiu am efectuat mai multe procese si analize asupra datelor.
Pentru a ajunge la rezultatul dorit, acela fiind identificarea judetelor cu nevoi educationale, am efectuat un flux de procesare, un model:

<img width="959" height="438" alt="image" src="https://github.com/user-attachments/assets/fad62a76-b328-4dc5-a36f-f4c8959cdfde" />
In prima etapa a studiului, s-a stabilit capacitatea medie a unitatilor de invatamant prin raportarea numarului total de elevi din anul anterior la numarul de licee existente in fiecare judet. Aceasta metrica reflecta dimensiunea medie a unui liceu in functie de densitatea elevilor; de exemplu, Municipiul Bucuresti prezinta cea mai ridicata densitate, cu o medie de aproximativ 600 de elevi per unitate scolara.

Ulterior, s-a estimat volumul actual al populatiei scolare de nivel liceal prin raportarea indicelui demografic la totalul populatiei judetene. Rezultatele confirma concentrarea cererii in Capitala, unde se aproximeaza peste 48.000 de liceeni.

Pentru identificarea zonelor cu necesar de infrastructura, analiza a fost filtrata pentru a evidentia judetele in care cererea actuala depaseste capacitatea din anul anterior. In urma acestei filtrari, au fost identificate 16 judete aflate intr-o situatie de suprasolicitare a retelei scolare.

Se calculeaza apoi deficitul elevilor, prin scaderea totalului de elevi actuali la cei din anul precedent, pentru a determina totalul elevilor ce nu au loc in liceele actuale, urmand apoi sa fie impartiti la capacitatea unui liceu (math.ceil(!deficit_elevi! / !Pondere_elevi! )) pentru a determina numarul exact de licee ce ar trebui sa fie construite astfel incat sa aiba loc si acesti elevi.

Dupa procesele efectuate in model, rezulatul va fi urmatorul:

<img width="1500" height="502" alt="image" src="https://github.com/user-attachments/assets/2f07cadb-bb66-48ef-8d61-e4cb06b2d7ea" />
In urma procesarii datelor, se observa o necesitate critica de infrastructura in regiunea de sud a tarii, unde judete precum Teleorman, Giurgiu si Calarasi prezinta un necesar estimat de 5-7 unitati scolare noi. O situatie similara se regaseste si in judetul Ilfov, a carui dinamica este strans legata de expansiunea urbana a Capitalei.

Rezultatele obtinute sustin ipoteza conform careia deficitul de unitati de invatamant din judetele vecine genereaza un flux masiv de migratie scolara catre Municipiul Bucuresti sau alte judete mari. Din cauza lipsei de locuri si a infrastructurii subdimensionate la nivel local, elevii sunt adesea nevoiti sa isi continue studiile in Capitala. Aceasta alegere nu este influentata doar de necesitate, ci si de cautarea unor oportunitati de dezvoltare superioare, fapt ce explica presiunea ridicata identificata anterior asupra liceelor bucurestene (cu o medie de 600 de elevi per unitate).

Am realizat in cadrul acestui studiu si alte analize, precum ponderea specializarilor, cat si cea a programelor de intensiv.

<img width="716" height="506" alt="image" src="https://github.com/user-attachments/assets/cbb1e0af-d33f-4c6f-a00e-ed2ec7046bb1" /><img width="279" height="329" alt="image" src="https://github.com/user-attachments/assets/07abde95-625c-4acb-93b9-185eefb87add" />

Asadar, printre cele mai populare programe de intensiv se numara engleza si informatica, iar ca specializari avem tehnic, real si umanist.

<img width="1509" height="598" alt="image" src="https://github.com/user-attachments/assets/0d39337b-3820-45be-a18c-7a9964faaa81" />

