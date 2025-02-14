# **Github-ohjeet**
![github](https://github.com/Panomies87/Github-ohjeet/blob/main/github-logo-git-hub-icon-with-text-on-white-and-black-background-free-vector.jpg)

### Lyhyet ohjeet GitHubin käyttöön



GitHub-repositorion luominen

Kirjaudu sisään GitHubiin.

Luo uusi repositorio valitsemalla "New".


Anna repositoriolle nimi ja valitse, onko se julkinen vai yksityinen.

Halutessasi lisää README.md, .gitignore tai lisenssi.

Klikkaa "Create repository".

### Repositorion yhdistäminen paikalliseen koneeseen

Jos ei ole olemassa olevaa Git-repoa:

Siirry terminalissa haluamaasi kansioon.

Alusta Git-repo komennolla git init.

Lisää GitHub-repositorio etäkohteeksi: git remote add origin https://github.com/kayttaja/repo-nimi.git

Luo README.md tiedosto ja tee ensimmäinen commit:

echo "# Repo nimi" >> README.md

git add README.md

git commit -m "Initial commit"

Lähetä muutokset GitHubiin:

git branch -M main

git push -u origin main

### Jos olet kloonaamassa olemassa olevan repositorion:

Kloonaa repositorio komennolla git clone https://github.com/kayttaja/repo-nimi.git.

Siirry kloonattuun kansioon komennolla cd repo-nimi.

### Peruskomennot: Git pull ja push

Pull

Varmista, että olet oikeassa branchissa komennolla git branch.

Hae ja yhdistä muutokset etäkohteesta komennolla git pull origin main.

Push

Lisää muutokset komennolla git add ..

Tee commit viestillä komennolla git commit -m "Kuvaus muutoksista".

Lähetä muutokset etäkohteeseen komennolla git push origin main.

### Etäkohteiden hallinta

Näytä etäkohteet: git remote -v

Lisää etäkohde: git remote add origin https://github.com/kayttaja/repo-nimi.git

Poista etäkohde: git remote remove origin

### Yleisiä huomioita

Päivitä paikallinen kopio ennen työskentelyä komennolla git pull origin main.

Tarkista repositorion tila komennolla git status.

Ratkaise mahdolliset merge-konfliktit, lisää muutokset ja jatka työskentelyä:

git add .

git commit

git push
