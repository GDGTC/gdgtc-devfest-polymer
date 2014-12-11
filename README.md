GDGDCsite
=========

Builds index.html
vulcanize -o index.html --strip prebuild-index.html

Builds main-scaffold.html
vulcanize -o main-scaffold.html --strip prebuild-main-scaffold.html

Builds devfest14.html
vulcanize -o ./pages/devfest14.html --strip ./pages/prebuild-devfest14.html

Builds aboutgdg.html
vulcanize -o ./pages/aboutgdg.html --strip ./pages/prebuild-aboutgdg.html

Builds codehack.html
vulcanize -o ./pages/codehack.html --strip ./pages/prebuild-codehack.html