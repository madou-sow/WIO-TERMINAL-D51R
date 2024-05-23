## WIO TERMINAL (D51R) - Terminal Wio : ATSAMD51 Core avec Realtek RTL8720DN BLE 5.0,  Wi-Fi 2.4G/5G et carte de développement
Wio Terminal est un microcontrôleur basé sur ATSAMD51 avec une connectivité sans fil Bluetooth
et Wi-Fi alimenté par Realtek RTL8720DN, compatible avec Arduino et MicroPython.
Actuellement, la connectivité sans fil n'est prise en charge que par Arduino. Plus qu'un simple
module fonctionnel intégré, le Wio Terminal lui-même est intégré à un écran LCD de 2,4", une IMU
intégrée (LIS3DHTR), un microphone, un buzzer, un emplacement pour carte microSD, un capteur
de lumière, un émetteur infrarouge (IR 940nm). En plus de cela, il dispose également de deux ports
Grove multifonctionnels pour l'écosystème Grove et d'un GPIO à 40 broches compatibles
Raspberry pi pour plus d'add-ons. Tous ces modules complémentaires pratiques sont soigneusement
logés dans un boîtier compact, ce qui en fait un produit efficace et prêt à l'emploi. Équipé d'un
GPIO Raspberry Pi 40 broches, il peut être monté sur un Raspberry Pi en tant qu'appareil esclave.


  <img alt="WIOT" src="https://github.com/madou-sow/WIO-TERMINAL-D51R/blob/main/images/fig-wio.png" width=50% height=50%  title="WIOT"/>

### Principales caractéristiques

- Microcontrôleur puissant : Microchip ATSAMD51P19 avec cœur ARM Cortex-M4F
fonctionnant à 120 MHz
- Connectivité sans fil fiable : équipé de Realtek RTL8720DN, Wi-Fi bi-bande 2,4 Ghz/5 Ghz.
- Système complet équipé d'un écran + carte de développement + interface d'entrée/sortie +
boîtier
- Conception hautement intégrée : écran LCD 2,4 pouces, MCU, IMU, WIFI, BT et d'autres
modules complémentaires pratiques logés dans un boîtier compact avec des aimants intégrés
et des trous de montage vous permettent de configurer facilement votre projet IoT
- Le GPIO compatible Raspberry Pi 40 broches permet l'installation en tant que périphérique
sur le Raspberry Pi
- Ports Grove externes multifonctionnels intégrés : Compatible avec plus de 300 modules
Plug&Play Grove à explorer avec l'IoT
- Prise en charge USB OTG : peut agir comme un hôte USB (lit les données ou les signaux
d'une souris, d'un clavier, d'un périphérique MIDI, d'une imprimante 3D, etc.) ou d'un client
USB (émule une souris, un clavier ou un périphérique MIDI vers un PC hôte).
- Prend en charge Arduino, CircuitPython, Micropython, ArduPy, AT Firmware, Visual Studio
Code
- Appareil certifié Azure : détecter et baliser les données du monde réel et visualiser-les via
Azure IoT Central

**C'est quoi Grove ?** Grove est un ensemble d'outils modulés et prêts à l'emploi. Il faut une
approche modulaire pour assembler l'électronique. Par rapport à la méthode d'apprentissage
traditionnelle et compliquée consistant à utiliser une planche à pain et divers composants
électroniques pour assembler un projet, Grove simplifie considérablement le processus
d'apprentissage. Le système Grove se compose d'un blindage de base et de divers modules
avec des connecteurs standardisés. Le blindage de base permet une connexion facile de
n'importe quelle entrée ou sortie de microprocesseur des modules Grove, et chaque module
Grove adresse une seule fonction, comme un simple bouton ou un capteur plus complexe.
Chacun est accompagné d'une documentation claire et d'un code de démonstration pour vous
aider à démarrer rapidement.

**Fonctionnement de Grove :** Un projet basé sur Grove nécessite quatre éléments pour
démarrer : une carte de plate-forme, une carte de dérivation, un module Grove et un câble.
Une fois que vous les avez tous sous la main, vous pouvez commencer tout de suite.

**Tableau de bord :** Si vous souhaitez connecter Grove à votre plate-forme, vous aurez
besoin d'un Breakout Board. Une carte Breakout est une carte d'extension Grove qui
achemine toutes les broches de votre microcontrôleur (par exemple Arduino) vers des prises
Grove riches pour des connexions instantanées, simples et sans soudure. Il existe déjà de
nombreuses cartes Breakout pour différentes plates-formes, notamment Arduino Uno,
Raspberry Pi, Beaglebone, etc.

### Description
La plateforme Wio (Wireless Input and Output) (Wio Link, Wio Nodes, etc.) a été présentée pour la
première fois au monde fin 2015 par Seeed.

Wio Terminal est compatible avec Arduino et Micropython, construit avec un microcontrôleur
ATSAMD51 avec une connectivité sans fil prise en charge par Realtek RTL8720DN. Sa vitesse de
processeur tourne à 120 MHz (Boost jusqu'à 200 MHz). La puce Realtek RTL8720DN prend en
charge à la fois le Bluetooth et le Wi-Fi, fournissant l'épine dorsale des projets IoT. Le terminal Wio
est hautement intégré avec un écran LCD de 2,4 pouces, il y a une IMU intégrée (LIS3DHTR), un
microphone, un buzzer, un emplacement pour une carte microSD, un capteur de lumière et un
émetteur infrarouge (IR 940nm).

Il y a des aimants intégrés et deux trous de montage sur le boîtier bien conçu, vous permettant de
configurer votre projet IoT sans tracas.

En plus de cela, il dispose également de deux ports Grove multifonctionnels pour se connecter à
plus de 300 modules et d'un GPIO compatible Raspberry Pi 40 broches pour des tonnes de modules
complémentaires Pi HAT, ce qui signifie qu'il existe une infinité de possibilités IoT que vous
pouvez créer avec ce petit appareil !

Avec Wio Terminal, vous pouvez :
- Détecter et étiqueter les données du monde réel avec plus de 300 bosquets créés par
Seeed et visualiser via Azure IoT Central Platform pour créer un projet IoT de bout en
bout
- Utiliser du matériel 100 % open-source de manière pythonique
- Construiser votre interpréteur de programme à partir de 90 % avec un écran LCD et un
boîtier compact
- Créer une interface graphique intégrée avec des éléments graphiques faciles à utiliser et
de superbes outils d'édition visualisés.

 <img alt="WIOT" src="https://github.com/madou-sow/WIO-TERMINAL-D51R/blob/main/images/descrip-wio.png" width=50% height=50%  title="WIOT"/>


 Le système complet Wio Terminal est idéal pour la réalisation de projets multimédias, ludiques et
connectés nécessitant un affichage graphique.
- Fonctionnalités : Ce module est une solution rapide et pratique pour la réalisation d'une
interface graphique connectée en Bluetooth ou en WiFi.
Le Wio Terminal intègre un accéléromètre, un capteur de luminosité, 3 boutons
configurables, un émetteur IR, un joystick, un micro et un buzzer.
- Connectique : Ce petit afficheur comprend 2 ports compatibles avec le système Grove de
Seeedstudio. Ces deux connecteurs permettent l'utilisation de modules ou capteurs
compatibles (voir liste de compatibilité).
Un connecteur GPIO permet d'enficher ce module sur une carte Raspberry Pi. Ce connecteur
permet l'utilisation de l'afficheur, des différents capteurs intégrés et de la connectique Grove
sur Raspberry Pi.
- Programmation : Le Wio Terminal est compatible Arduino, MicroPython et ArduPy.
Seeedstudio met à disposition un guide d'utilisation en anglais.
ArduPy est une combinaison d'Arduino et de MicroPython. Le code MicroPython utilise les API Arduino pour piloter le matériel.
- Exemples d'applications : Terminal Python portable, lecteur portable multimédia, console
de jeux rétro, module IoT avec capteurs Grove ou encore module esclave raccordé à une
carte Raspberry Pi.

**Caractéristiques techniques :**

- Alimentation : 5 Vcc via le port USB Type-C
- Microcontrôleur: ARM Cortex-M4 à 120 MHz (ATSAMD51P19)
- Mémoire FLASH: 4 MB
- Mémoire RAM: 192 KB
- Contrôleur Realtek RTL8720DN
  -- WiFi: 2,4 et 5 GHz - 802.11 a/b/g/n
  -- Bluetooth: BLE 5.0
- Afficheur: 2,4" - 320 x 240 pixels
- Accéléromètre LIS3DHTR: ±2 g, ±4 g, ±8 g et ±16 g
- Connecteur GPIO 40 broches compatible Raspberry Pi
- Compatible USB OTG : hôte et client USB
- Interfaces Grove : digitale, analogique, I2C et PWM
- Buzzer (niveau sonore: ≥78 dB)
- Micro intégré (sensibilité: -42 dB)
- Capteur de lumière : 400-1050 nm
- Emetteur IR: 940 nm
- Connecteur FPC 20 broches
- Support pour carte micro-SD: 16 Go maxi
- Température de service: -40 à 85 °C
- Dimensions: 72 x 57 x 12 mm
- Matériaux: ABS et polycarbonate
- Livré avec cordon USB Type-C (environ 20 cm)

  <img alt="WIOT schema" src="https://github.com/madou-sow/WIO-TERMINAL-D51R/blob/main/images/present-mat-wio.png" width=70% height=70%  title="WIOT schema"/>

### Schéma du brochage

 <img alt="WIOT broche" src="https://github.com/madou-sow/WIO-TERMINAL-D51R/blob/main/images/schema-broche.png" width=50% height=50%  title="WIOT broche"/>

### Installation et Utilisation
#### Matériel
- Matériaux nécessaires
- Borne Wio
- Ordinateur
- Câble USB Type-C

   <img alt="WIOT branche" src="https://github.com/madou-sow/WIO-TERMINAL-D51R/blob/main/images/connex-wio.png" width=50% height=50%  title="WIOT branche"/>

Connecter le terminal Wio à votre ordinateur via un câble USB. La LED bleue à l'arrière doit
s'allumer. Un nouveau port devrait apparaître avec la commande :
```
root@port-lipn12:~# ls -l /dev/tty*
crw--w---- 1 root tty 4, 8 déc. 29 09:09 /dev/tty8
crw--w---- 1 root tty 4, 9 déc. 29 09:09 /dev/tty9
crw-rw---- 1 root dialout 166, 0 déc. 29 09:09 /dev/ttyACM0
crw------- 1 root root 5, 3 déc. 29 09:09 /dev/ttyprintk
crw-rw---- 1 root dialout 4, 64 déc. 29 09:09 /dev/ttyS0
crw-rw---- 1 root dialout 4, 65 déc. 29 09:09 /dev/ttyS1

```
En général, il s’agit du port /dev/ttyACM0. Avant de téléverser un programme dans la carte, il vous
faudra probablement modifier les droits d’accès au port USB (message Error opening serial port...).
La raison est que le propriétaire du fichier /dev/ttyACM0 fait partie du groupe dialout :

```
crw-rw---- 1 root dialout 166,0 déc. 29 09:09 /dev/ttyACM0
```
Il faut donc ajouter l’utilisateur à ce groupe :
```
root@port-lipn12:~# usermod -a -G dialout mamadou
```

#### Logiciel
- 1. Installer un logiciel Arduino
<!--
<img alt="https://www.arduino.cc/en/software" src="https://github.com/madou-sow/WIO-TERMINAL-D51R/blob/main/images/download-arduino1.png" width=30% height=30%  title="[WIOT]"/>
-->

[!['download'](https://github.com/madou-sow/WIO-TERMINAL-D51R/blob/main/images/download-arduino1.png)](https://www.arduino.cc/en/software)

  
Double-cliquez sur l'application Arduino IDE que vous avez précédemment téléchargée et procéder à l’installation de l’application.
- 2. Ouvrir l'exemple Blink
Ouvrez l'exemple d'esquisse de clignotement de LED : **Fichier > Exemples > 01.Basics > Blink**.
- 3. Ajouter le fichier de carte requis pour le terminal Wio ou Ajouter la bibliothèque Wio Terminal Board
Dans le menu supérieur Arduino, allez dans **Fichier -> Préférences et copiez/collez**
**https://files.seeedstudio.com/arduino/package_seeeduino_boards_index.json** dans la zone URL
supplémentaires du gestionnaire de cartes :

   <img alt="WIOT ref" src="https://github.com/madou-sow/WIO-TERMINAL-D51R/blob/main/images/rajout-pref.png" width=70% height=70%  title="WIOT ref"/>

- 4. Cliquer sur **Outils -> Tableau -> Gestionnaire de Carte et recherchez Wio Terminal**

  <img alt="WIOT module" src="https://github.com/madou-sow/WIO-TERMINAL-D51R/blob/main/images/insaller-wio-module.png" width=70% height=70%  title="WIOT module"/>

- 5. Sélectionner votre carte et votre port
Vous devrez sélectionner l'entrée dans le menu **Outils > Carte** qui correspond à votre Arduino
Sélection du **Seeeduino Wio Terminal**. Vous devrez ensuite sélectionner l'entrée dans le menu **Outils > Port**, le port **/dev/ttyACM0 pour la carte Seeeduino Wio Terminal**

  <img alt="WIOT port" src="https://github.com/madou-sow/WIO-TERMINAL-D51R/blob/main/images/portacm-seeed.png" width=70% height=70%  title="WIOT port"/>

- 6. Téléverser le programme Blink
L'exemple d'esquisse de clignotement de LED : **Fichier > Exemples > 01.Basics > Blink**.
Maintenant, cliquez simplement sur le bouton Téléverser dans l'environnement. Attendez quelques
secondes et si le téléversement est réussi, le message « téléversement terminé ». apparaîtra dans la
barre d'état. Télécharger le code Quelques secondes après la fin du téléchargement, vous devriez
voir le voyant au bas du terminal Wio commencer à clignoter. Si c'est le cas, félicitations ! Votre
Wio Terminal est opérationnel.

  <img alt="WIOT port" src="https://github.com/madou-sow/WIO-TERMINAL-D51R/blob/main/images/televerser-blink-seeed.png" width=70% height=70%  title="WIOT port"/>

#### Exemple de code
Cet exemple initialise l'écran LCD TFT sur le terminal Wio et remplit l'écran de couleur rouge sketch_lcd-red.ino
```
#include"TFT_eSPI.h"
TFT_eSPI tft;
void setup() {
          tft.begin();
          tft.setRotation(3);
          tft.fillScreen(TFT_RED); // fills entire the screen with colour red
          // tft.fillScreen(TFT_GREEN); // fills entire the screen with colour GREEN
}
void loop() {
}
```

 <img alt="WIOT rouge" src="https://github.com/madou-sow/WIO-TERMINAL-D51R/blob/main/images/lcd_wio_rouge.jpg" width=70% height=70%  title="WIOT rouge"/>

 ```
#include"TFT_eSPI.h"
TFT_eSPI tft;
void setup() {
          tft.begin();
          tft.setRotation(3);
          //tft.fillScreen(TFT_RED); // fills entire the screen with colour red
          tft.fillScreen(TFT_GREEN); // fills entire the screen with colour GREEN
}
void loop() {
}
```

  <img alt="WIOT vert" src="https://github.com/madou-sow/WIO-TERMINAL-D51R/blob/main/images/lcd_wio_vert.jpg" width=70% height=70%  title="WIOT vert"/>

  Vous pouvez rencontrer un problème d’affichage à l’écran lié à un conflit entre les librairies LCD,
en effet les librairies LCD sont incluses dans la bibliothèque de la borne Wio. Dans ce cas la
résolution est simple il faut supprimer les répertoires de ses libraires de votre répertoire de travail.
```
mamadou@port-lipn12:~/Arduino/libraries$ rm -rdf TFT*
```

#### Fonctions graphiques de base

Ce référentiel décrit certaines des fonctions graphiques de base de la bibliothèque LCD TFT sur
Wio Terminal. Vous pouvez utiliser ces fonctions pour créer vos propres fonctions de dessin !

```
#include"TFT_eSPI.h"
TFT_eSPI tft;
void setup() {
            tft.begin();
            tft.setRotation(3);
            tft.fillScreen(TFT_RED); // fills entire the screen with colour red
            tft.drawPixel(4,7,TFT_BLACK); //drawing a black pixel at (4,7)
            tft.drawFastHLine(0,120,320,TFT_BLACK); //A black horizontal line starting
            from (0, 120)
            tft.drawFastVLine(160,0,240,TFT_BLACK); // A black vertical line starting
            from (160, 0)
            tft.drawRect(110,70,100,100,TFT_BLACK); //A 100x100 black rectangle
            starting from (110, 70)
            tft.drawCircle(160,120,50,TFT_BLACK); //A black circle origin at (160, 120)
            tft.drawEllipse(160,120,50,100,TFT_BLACK);//A black ellipse origin at (160,
            120) with horizontal radius of 50, and vertical radius of 100
            tft.drawTriangle(160,70,60,170,260,170,TFT_BLACK); //A triangle with points
            at (160, 70), (60, 170) and (260, 170)
            tft.drawRoundRect(110,70,100,100,10,TFT_BLACK);
}
void loop() {
}
```
