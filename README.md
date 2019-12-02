Z61. Na poprzednich laboratoriach budowaliśmy i uruchamialiśmy kontenery z serwerem
Apache, PHP. W tym zadaniu należy zbudować prosty plik docker-compose.yml, który
pozwoli na uruchomienie znanej z innych zajęć, uslugi LAMP. Usługa ta składa się z trzech
usług składowych:
- serwera Apacje (można wykorzystać np. obraz serwera httpd na bazie alpine)
- serwera PHP (można wykorzystać np. oficjalny obraz latest)
- bazy danych MySQL (można wykorzystać oficjalny obraz latest)

Założenia dla uslugi:
- serwery są budowane zgodnie z dokumentacją obrazów bazowych dostępnych na
DockerHub i umieszczonych tam plików Dockerfile (nie korzysta się z gotowych obrazów),
- serwery PHP i MySQL są przyłączone do sieci backend a Apache do backend oraz
frontend. Apache ma wystawiony na świat zewnętrzy port 6666.
- podać zawartość plików Dockerfile dla każdej usługi cząstkowej,
- podać zawartość innych, niezbędnych plików,
- podać zawartość pliku docker-compose.yml,
- utworzyć i podać zawartość pliku README.md opisujący stworzony projekt

Opcjonalnie: sprawdzić czy jest możliwe wygenerowanie reprezentacji graficznej dla
utworzonego pliku docker-compose.yml i jeśli tak, to umieścić go w sprawozdaniu.
Cały projekt może być też umieszczony w repozytorium na GitHub-ie. W takim przypadku
proszę w sprawozdaniu podać link do tego repozytorium. 
