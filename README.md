# tuGerenteQA


1.- Es necesario crear un entorno virtual (venv) en python dentro de la carpeta raiz de este proyecto en cualquier consola (powershell, gitbash, terminal de Visual Studio) usando el comando: 

python -m venv venv 

2.- una vez creada la carpeta del entorno virtual, activaremos el enterno virutal para instalar las dependencias desde el venv creado con el siguiente comando: 

source venv/Scripts/activate

3.- una vez creado el entorno virtual y estando situado en el procederemos a instalar las dependencias y plugins de pytest y playwright con los siguientes comandos: 

pip install playwright (esperar unos segundos y una vez terminda la descarga proceder con la siguiente descarga)
pip install pytest-playwright (esperar unos segundos y una vez terminda la descarga proceder con la siguiente descarga)
playwright install (suele tardar más porque instalar en el venv los navegadores) 

4.- para comprobar que las dependencias hayan sido instaladas usar el comando:

pip freeze


5.- abrir archivo requeriments.txt y comparar las versiones instaladas para que coicidan 

ejecutar dentro del enterno virtual el comando

python ModuloVentas4_ClienteNuevo.py



