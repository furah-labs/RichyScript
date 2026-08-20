# RichyScript

          RICHYSCRIPT LANGUAGE SUPPORT FOR VSCODE

L'extension officielle VSCode pour RichyScript 
Le 1er langage de programmation educatif 100% Africain.

Cree par : FURAH LABS
Site : www.richyscript.com
Email : contact@furahlabs.com

                     1. FONCTIONNALITES

[OK] Coloration Syntaxique : keywords, strings, comments, numbers
[OK] Snippets Intelligents : 10 raccourcis pour coder plus vite
[OK] Bouton "Run" : Execute ton code .richy en 1 clic
[OK] Theme "RichyScript Dark" : Theme sombre bleu-nuit
[OK] Auto-completion : Pour RichBerry, QtDarks, OpenAI

                      2. INSTALLATION

Option A : Marketplace VSCode
1. Ouvre VSCode
2. Ctrl+Shift+X pour aller dans Extensions  
3. Cherche "RichyScript"
4. Clique sur "Installer"

Option B : Fichier .VSIX
1. Telecharge le .vsix dans Releases Github
2. Ctrl+Shift+P -> "Extensions: Install from VSIX"

                       3. UTILISATION

1. Cree un fichier avec l'extension .richy
   Exemple : bonjour.richy

2. Utilise les snippets : tape "say" + Tab

3. Clique sur le bouton PLAY ▶️ en haut a droite pour executer

EXEMPLE DE CODE :

# Mon premier programme RichyScript
module "richberry.richy"

say "Bonjour Kinshasa !"

set nom = ask "C'est quoi ton nom ?"
say "Enchante " + nom

set led = RichBerry.pin(17)
led.on()


                      4. LISTE DES SNIPPETS

say       -> say "Hello World"
set       -> set variable = valeur
if        -> if condition then ... end
for       -> for i = 1 to 10 ... end
module    -> module "nom.richy"
ask       -> set reponse = ask "Question:"
RichBerry -> Controle Arduino/Raspberry
QtDark    -> Fenetre popup
OpenAI    -> Appeler ChatGPT
function  -> function nom() ... end

                       5. THEME

Pour activer le theme : Ctrl+K puis Ctrl+T -> "RichyScript Dark"

                     6. DEVELOPPEMENT

Pour lancer en mode dev :
1. git clone https://github.com/FURAH-LABS/vscode-richyscript
2. npm install
3. Appuie sur F5 pour tester

                      7. LICENCE & SUPPORT

Licence : MIT © 2026 FURAH LABS

Support :
Site Web : www.richyscript.com
Email : contact@furahlabs.com
WhatsApp : Rejoindre la communaute

Fait avec amour a Kinshasa, RDC
Apprendre a coder. Construire l'Afrique.
