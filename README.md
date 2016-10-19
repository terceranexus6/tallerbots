# taller de bots
del #miercolesgeek de la OSL, UGR

Aquí encontraréis lo necesario para crear vuestro bot de telegram, con las correcciones encontradas tras las dificultades del miércoles. En issues encontraréis el pdf de la presentación.

Receta:
Neceritaremos...
- Linux!
- github
- telegram
- herramientas de python
- google/nodejs/cloud9...
- ganas de dominar el mundo

Pasos:
- Nos descargaremos (clonaremos) el bot de pyTelegramBotAPI y/o telebot si queremos usar google appengine
- desde botrather, seguimos los pasos para crear un nuevo bot (/newbot) y guardamos el token
- si usamos googleappengine, seguir los pasos del repo de telebot
- si usamos cloud9, crear un nuevo proyecto nativo y copypastear un ejemplo de codigo de bot. 
- para más info sobre este último método (resultó mucho más fácil!) visitar el link de este issue https://github.com/terceranexus6/tallerbots/issues/2 

encontraréis varios ejemplos en repos, y hay un par de ejemplos fáciles en los issues. 
Un saludo!

ACTUALIZACIÓN DE OCTUBRE DE 2016:

Ahora resulta que Cloud 9 pide tu tarjeta de crédito. Ouch! pero no pasa nada, hay otra opción desde la terminal de telegram. Un compañero ha encontrado la solución.

Tan sólo usando la api, y con un par de comandos tenemos resuelto el problema:
git clone https://github.com/eternnoir/pyTelegramBotAPI.git

python3 nombreprograma.py
