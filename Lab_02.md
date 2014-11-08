[Laboratorium2](http://wbzyl.inf.ug.edu.pl/sp/labs02)

1\. Wyświetl na ekran 2 pierwsze wiersze pliku program.c. (head)
```sh
  head -2 program.c
```

2\. Wyświetl na ekran 4 ostatnie wiersze pliku program.c. (head, tail)
```sh
  tail -4 program.c
```

3\. W pliku program.c znajdź wszystkie wiersze z wystąpieniem słowa „main”. (grep)
```sh
  grep main program.c
```
4\. Plikowi program.c nadaj następujące uprawnienia: właściciel – czytanie, pisanie, grupa – czytanie, pozostali użytkownicy: brak uprawnień. (chmod)
```sh
chmod u=wr,g=r program.c
```

5\.Będąc w katalogu temp przenieś katalog wazne-sprawy do katalogu praca.

```sh
mv dom/wazne-sprawy/ praca/
```
6\. Zarchiwizuj cały katalog temp. (zip i tar)
```sh
tar -czf archiwum1.tar.gz temp
tar -czf archiwum1.tar.gz temp
```
7\. Usuń katalog temp.
```sh
rm -r temp
```

8\. Odtwórz z archiwum katalog temp. (unzip i tar)
```sh
tar -xzf archiwum1.tar.gz
unzip archiwum2.zip
```

9\. Posprzątaj na swoim koncie.

```sh
rm temp.tar
rmdir -r temp/
```
