
# CRÉER UN DÉPÔT NU (BARE REPOSITORY)

Source : [Installation de Git sur un serveur][installation-de-git-sur-un-serveur]

    # Exporter un dépôt existant dans un nouveau dépôt nu
    cd ..
    git clone --bare bare-repo bare-repo.git

    # Copie du dépôt nu sur un serveur
    scp -r bare-repo.git ouilogique@ssh-ouilogique.alwaysdata.net:/home/ouilogique

    # Clonage du dépôt
    git clone ouilogique@ssh-ouilogique.alwaysdata.net:/home/ouilogique/bare-repo.git









[installation-de-git-sur-un-serveur]:https://git-scm.com/book/fr/v2/Git-sur-le-serveur-Installation-de-Git-sur-un-serveur