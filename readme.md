# Kuidas teha repositooriumi ja muudatusi selles:

## 1.Samm - git init

git init 
```
Kasutad seda ainult esimene kord kui repository oled just teinud
```
## 2.Samm - git add			
git add README.md 
```
lisab faili, mida hakkad committima
```
## 3.Samm - git commit
git commit -m "first commit" 
```
saad tehtud muudatusi kommenteerida, first commiti kasutad ainult esimene kord
```
## 4.Samm - git remote add origin
git remote add origin https://github.com/evaliisaedela/Saanselgeks.git 
```
et teaks kuhu muudatusi saata
```
## 5.Samm - git push 
git push -u origin master 
```
saadab muudatused repositooriumisse teele
```