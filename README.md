# Lab5
Rozwiązanie do zadania z laboratorium 5

# Uruchomienie
docker build --build-arg VERSION=2.0.0 -t lab5 . <br>
docker run -p 8080:80 lab5

# Opis
Działanie kontenera można sprawdzić komendą <i>"docker ps"</i>, natomiast do sprawdzenia poprawności funkcjonowania aplikacji można użyć polecenia <i>"docker inspect lab5"</i> lub <i>"curl http://localhost:8080"</i>.
