# Proyecto_github1  :smiley:

## Pasos realizados: 
1) Me ubico en donde quiero crear el proyecto y creo la carpeta con el comando : mkdir "proy_github2
2) Iniciamos la carpeta del proyecto con git usando el comando git.init 
3) Creo la  conexion con github utilizando : git remote add origin https://github.com/ArieHassan/Proyecto_github1.git
4) Creo 2 archivos: text1.txt y text2.txt en la carpeta utilizando :touch nombre archivo
5) Agrego a git los 2 archivos utilizando git add nombre archivo 
6) Commiteo los 2 archivos utilizando:  git commit -am "mensaje"
7) Subo los archivos remotamente con:  git push -u origin master
8) Creo la nueva branch rama2 utilizando : git checkout -b rama2
9) Me ubico en la rama2 y edito text1 lo suficiente como para que me genere conflico cuando vaya a hacer el merge, estaba vacio asi que tendre que editar el mismo archivo de la rama master para q me genere conflicto.
10) Commiteo text1, para ello: git commit -am "mensaje" 
11) Me ubico en la rama master y edito text1, para cambiar a la rama master utilizo: git checkout master
12) Edito text1 para generar conflicto al hacer el merge ya que el documento estaba vacio.
13) Commiteo text1, para ello: git commit -am "mensaje" 
14) Hacemos merge, para ello nos ubicamos en la rama master y escribimos "git merge rama2", es decir, estando dentro de la rama master la fusionamos con la rama 2, y evidentemente nos da un conflicto.
15) Abrimos el archivo de text1.txt y lo editamos para resolver el conflicto.
16) Hacemos un commit de text1.txt ajustado sin conflicto 
17) Hago push de la rama master a github para ello: git push origin master
18) Hago push de la rama rama2 a github para ello: git push origin rama2

### Network
![alt text](https://github.com/ArieHassan/Proyecto_github1/blob/master/Network.png)
