# moj-pierwszy-projekt# Skopiuj repozytorium na komputer (klon)
git clone https://github.com/TwojaNazwaUzytkownika/moj-pierwszy-projekt.git

# Przejdź do folderu projektu
cd moj-pierwszy-projekt

# Dodaj nowy plik
echo "Hello GitHub!" > hello.txt

# Dodaj plik do „listy zmian”
git add hello.txt

# Zatwierdź zmiany
git commit -m "Dodano plik hello.txt"

# Wyślij zmiany do GitHuba
git push
