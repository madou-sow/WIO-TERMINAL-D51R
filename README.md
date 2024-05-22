## WIO TERMINAL (D51R) - Terminal Wio : ATSAMD51 Core avec Realtek RTL8720DN BLE 5.0 et carte de développement Wi-Fi 2.4G/5G

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


  <img alt="WIOT" src="https://github.com/madou-sow/WIO-TERMINAL-D51R/blob/main/images/fig-wio.png" width=70% height=70%  title="WIOT"/>

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

 <img alt="WIOT" src="https://github.com/madou-sow/WIO-TERMINAL-D51R/blob/main/images/descrip-wio.png" width=70% height=70%  title="WIOT"/>


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

