Générez des codes QR et/ ou des codes Barres personnalisés dans vos projets laravel. 

Etape 1: Créer un projet laravel

Etape 2: Configurer la base de données dans le fichier .env

Etape 3: Installer le package de générateur de code QR: --composer require simplesoftwareio/simple-qrcode

Etape 4: Configurer le package dans config/app.php (ajouter le providers & l'aliases)

Etape 5: Créer un controller et une vue (si c'est pas encore fait) pour l'affichage des codes

Etape 6: Afficher le code QR : {!! QrCode::size(300)->backgroundColor(255,90,0)->generate('NomQr') !!}


Fin
