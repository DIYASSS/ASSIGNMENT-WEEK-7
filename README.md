USER@DESKTOP-37EBJTN MINGW64 ~
$ mkdir DIYAS

USER@DESKTOP-37EBJTN MINGW64 ~
$ dir
3D\ Objects        IntelGraphicsProfiles  ntuser.dat.LOG2                                                                               Pictures
AppData            Links                  NTUSER.DAT{53b39e87-18c4-11ea-a811-000d3aa4692b}.TxR.0.regtrans-ms                            Postman
Application\ Data  Local\ Settings        NTUSER.DAT{53b39e87-18c4-11ea-a811-000d3aa4692b}.TxR.1.regtrans-ms                            PrintHood
Contacts           main.py                NTUSER.DAT{53b39e87-18c4-11ea-a811-000d3aa4692b}.TxR.2.regtrans-ms                            Recent
Cookies            MicrosoftEdgeBackups   NTUSER.DAT{53b39e87-18c4-11ea-a811-000d3aa4692b}.TxR.blf                                      Saved\ Games
Desktop            Music                  NTUSER.DAT{53b39e88-18c4-11ea-a811-000d3aa4692b}.TM.blf                                       Searches
DIYAS              My\ Documents          NTUSER.DAT{53b39e88-18c4-11ea-a811-000d3aa4692b}.TMContainer00000000000000000001.regtrans-ms  SendTo
Documents          NetHood                NTUSER.DAT{53b39e88-18c4-11ea-a811-000d3aa4692b}.TMContainer00000000000000000002.regtrans-ms  Start\ Menu
Downloads          NTUSER.DAT             ntuser.ini                                                                                    Templates
Favorites          ntuser.dat.LOG1        OneDrive                                                                                      Videos

USER@DESKTOP-37EBJTN MINGW64 ~
$ cd DIYAS

USER@DESKTOP-37EBJTN MINGW64 ~/DIYAS
$ mkdir sekolah

USER@DESKTOP-37EBJTN MINGW64 ~/DIYAS
$ mkdir kerja

USER@DESKTOP-37EBJTN MINGW64 ~/DIYAS
$ dir
kerja  sekolah

USER@DESKTOP-37EBJTN MINGW64 ~/DIYAS
$ cd sekolah

USER@DESKTOP-37EBJTN MINGW64 ~/DIYAS/sekolah
$ touch ijazah.txt

USER@DESKTOP-37EBJTN MINGW64 ~/DIYAS/sekolah
$ cat ijazah.txt
Perkenalkan namaku DIYAS
Aku berasal dari AJIBARANG
Salam Kenal :D
USER@DESKTOP-37EBJTN MINGW64 ~/DIYAS/sekolah
$ touch portfolio.txt

USER@DESKTOP-37EBJTN MINGW64 ~/DIYAS/sekolah
$ cat portfolio.txt
Saya pernah bekerja pada beberapa perusahaan salah satu
diantaranya ialah

- DIYASTATION
- SAYID CORP
- SIC
USER@DESKTOP-37EBJTN MINGW64 ~/DIYAS/sekolah
$ cd ..

USER@DESKTOP-37EBJTN MINGW64 ~/DIYAS
$ dir
kerja  sekolah

USER@DESKTOP-37EBJTN MINGW64 ~/DIYAS
$ cd kerja

USER@DESKTOP-37EBJTN MINGW64 ~/DIYAS/kerja
$ touch cv.txt

USER@DESKTOP-37EBJTN MINGW64 ~/DIYAS/kerja
$ cat cv.txt
Salam,

Perkenalkan namaku DIYAS, saya memiliki kegemaran
- GAME
- RENANG
- MEMBACA
USER@DESKTOP-37EBJTN MINGW64 ~/DIYAS/kerja
$ ls -al
total 1
drwxr-xr-x 1 USER 197121  0 Sep 27 13:31 ./
drwxr-xr-x 1 USER 197121  0 Sep 27 13:22 ../
-rw-r--r-- 1 USER 197121 88 Sep 27 13:32 cv.txt

USER@DESKTOP-37EBJTN MINGW64 ~/DIYAS/kerja
$ cd ..

USER@DESKTOP-37EBJTN MINGW64 ~/DIYAS
$ ls -a
./  ../  kerja/  sekolah/

USER@DESKTOP-37EBJTN MINGW64 ~/DIYAS
$ cd sekolah

USER@DESKTOP-37EBJTN MINGW64 ~/DIYAS/sekolah
$ mv portfolio.txt kerja

USER@DESKTOP-37EBJTN MINGW64 ~/DIYAS/sekolah
$ ls -a
./  ../  ijazah.txt  kerja

USER@DESKTOP-37EBJTN MINGW64 ~/DIYAS/sekolah
$ cd kerja
bash: cd: kerja: Not a directory

USER@DESKTOP-37EBJTN MINGW64 ~/DIYAS/sekolah
$ cd ..

USER@DESKTOP-37EBJTN MINGW64 ~/DIYAS
$ cd kerja

USER@DESKTOP-37EBJTN MINGW64 ~/DIYAS/kerja
$ ls -a
./  ../  cv.txt

USER@DESKTOP-37EBJTN MINGW64 ~/DIYAS/kerja
$ ls sekolah
ls: cannot access 'sekolah': No such file or directory

USER@DESKTOP-37EBJTN MINGW64 ~/DIYAS/kerja
$ mv kerja portfolio.txt
mv: cannot stat 'kerja': No such file or directory

USER@DESKTOP-37EBJTN MINGW64 ~/DIYAS/kerja
$ ls -a
./  ../  cv.txt

USER@DESKTOP-37EBJTN MINGW64 ~/DIYAS/kerja
$ cd ..

USER@DESKTOP-37EBJTN MINGW64 ~/DIYAS
$ cd sekolah

USER@DESKTOP-37EBJTN MINGW64 ~/DIYAS/sekolah
$ mv kerja portfolio.txt

USER@DESKTOP-37EBJTN MINGW64 ~/DIYAS/sekolah
$ ls -a
./  ../  ijazah.txt  portfolio.txt

USER@DESKTOP-37EBJTN MINGW64 ~/DIYAS/sekolah
$ cd ..

USER@DESKTOP-37EBJTN MINGW64 ~/DIYAS
$ dir
kerja  sekolah

USER@DESKTOP-37EBJTN MINGW64 ~/DIYAS
$ mv portfolio.txt kerja
mv: cannot stat 'portfolio.txt': No such file or directory

USER@DESKTOP-37EBJTN MINGW64 ~/DIYAS
$ cd sekolah

USER@DESKTOP-37EBJTN MINGW64 ~/DIYAS/sekolah
$ dir
ijazah.txt  portfolio.txt

USER@DESKTOP-37EBJTN MINGW64 ~/DIYAS/sekolah
$ mv portfolio /kerja
mv: cannot stat 'portfolio': No such file or directory

USER@DESKTOP-37EBJTN MINGW64 ~/DIYAS/sekolah
$ mv portfolio.txt /kerja
mv: cannot move 'portfolio.txt' to '/kerja': Permission denied

USER@DESKTOP-37EBJTN MINGW64 ~/DIYAS/sekolah
$ mv portfolio.txt kerja

USER@DESKTOP-37EBJTN MINGW64 ~/DIYAS/sekolah
$ dir
ijazah.txt  kerja

USER@DESKTOP-37EBJTN MINGW64 ~/DIYAS/sekolah
$ mv kerja portfolio.txt

USER@DESKTOP-37EBJTN MINGW64 ~/DIYAS/sekolah
$ mv portfolio.txt kerja/DIYAS
mv: cannot move 'portfolio.txt' to 'kerja/DIYAS': No such file or directory

USER@DESKTOP-37EBJTN MINGW64 ~/DIYAS/sekolah
$ ls
ijazah.txt  portfolio.txt

USER@DESKTOP-37EBJTN MINGW64 ~/DIYAS/sekolah
$ ls -a
./  ../  ijazah.txt  portfolio.txt

USER@DESKTOP-37EBJTN MINGW64 ~/DIYAS/sekolah
$ mv portfolio.txt DIYAS/kerja
mv: cannot move 'portfolio.txt' to 'DIYAS/kerja': No such file or directory

USER@DESKTOP-37EBJTN MINGW64 ~/DIYAS/sekolah
$ cd ..

USER@DESKTOP-37EBJTN MINGW64 ~/DIYAS
$ mv portfolio.txt DIYAS/kerja
mv: cannot stat 'portfolio.txt': No such file or directory

USER@DESKTOP-37EBJTN MINGW64 ~/DIYAS
$ ls sekolah
ijazah.txt  portfolio.txt

USER@DESKTOP-37EBJTN MINGW64 ~/DIYAS
$ mv DIYAS/sekolah/portfolio.txt DIYAS/kerja/
mv: cannot stat 'DIYAS/sekolah/portfolio.txt': No such file or directory

USER@DESKTOP-37EBJTN MINGW64 ~/DIYAS
$ cd sekolah

USER@DESKTOP-37EBJTN MINGW64 ~/DIYAS/sekolah
$ ls -a
./  ../  ijazah.txt  portfolio.txt

USER@DESKTOP-37EBJTN MINGW64 ~/DIYAS/sekolah
$ mv portfolio.txt kerja/
mv: cannot move 'portfolio.txt' to 'kerja/': No such file or directory

USER@DESKTOP-37EBJTN MINGW64 ~/DIYAS/sekolah
$ mv portfolio.txt
ijazah.txt     portfolio.txt

USER@DESKTOP-37EBJTN MINGW64 ~/DIYAS/sekolah
$ mv portfolio.txt
ijazah.txt     portfolio.txt

USER@DESKTOP-37EBJTN MINGW64 ~/DIYAS/sekolah
$ mv portfolio.txt
ijazah.txt     portfolio.txt

USER@DESKTOP-37EBJTN MINGW64 ~/DIYAS/sekolah
$ mv portfolio.txt
mv: missing destination file operand after 'portfolio.txt'
Try 'mv --help' for more information.

USER@DESKTOP-37EBJTN MINGW64 ~/DIYAS/sekolah
$ cd ..

USER@DESKTOP-37EBJTN MINGW64 ~/DIYAS
$ mv portfolio.txt kerja
mv: cannot stat 'portfolio.txt': No such file or directory

USER@DESKTOP-37EBJTN MINGW64 ~/DIYAS
$ cd sekolah

USER@DESKTOP-37EBJTN MINGW64 ~/DIYAS/sekolah
$ mv portfolio.txt ../kerja

USER@DESKTOP-37EBJTN MINGW64 ~/DIYAS/sekolah
$ dir
ijazah.txt

USER@DESKTOP-37EBJTN MINGW64 ~/DIYAS/sekolah
$ cd ..

USER@DESKTOP-37EBJTN MINGW64 ~/DIYAS
$ cd kerja

USER@DESKTOP-37EBJTN MINGW64 ~/DIYAS/kerja
$ ls
cv.txt  portfolio.txt

USER@DESKTOP-37EBJTN MINGW64 ~/DIYAS/kerja
$
