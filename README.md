Dependance qui ne marche pas et c'est pas grave : libjpeg62-turbo-dev

Installer les dépendances :
```
  sudo apt install -y g++ make libsdl2-dev liba52-dev libmpeg2-4-dev libogg-dev libvorbis-dev libflac-dev libmad0-dev libpng-dev libtheora-dev libfaad-dev libfluidsynth-dev libfreetype6-dev zlib1g-dev libunity-dev checkinstall libsdl-image1.2-dev libsdl-dev
```

Compiler
```
git clone https://github.com/scummvm/scummvm.git
cd scummvm
./configure
make clean
make
sudo checkinstall
```
Tapez "3" et changez le version number par "2.2.0-svn+#DATE" durant le procédé, quand on voit le tableau d'info apparaître, dire oui si demandé de créer un fichier manquant.




Compiler residualvm
```
git clone https://github.com/residualvm/residualvm.git
cd residualvm
./configure
make clean
make
sudo checkinstall
```
Tapez "3" et changez le version number par "2.2.0-svn+#DATE" durant le procédé, quand on voit le tableau d'info apparaître, dire oui si demandé de créer un fichier manquant.




Compiler residualvmmouse
```
git clone https://github.com/B4rabbas/grim_mouse.git
cd grim_mouse
./configure
make clean
make
sudo checkinstall
```
Tapez "3" et changez le version number par "2.2.0-svn+#DATE" durant le procédé, quand on voit le tableau d'info apparaître, dire oui si demandé de créer un fichier manquant.

