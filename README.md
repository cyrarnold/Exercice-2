L'application présentée dans ce livrable sera codée en php.


Une fois INGITE installez, on installera PHP Thin Client en tant que package Composer à l'aide de la commande ci-dessous :

composer require apache/apache-ignite-client.

Pour utiliser le client dans l'application, on doit inclure le fichier vendor/autoload.php, généré par Composer, dans le code source

Avant de se connecter à Ignite à partir du client Thin PHP, vous devez démarrer au moins un nœud de cluster Ignite.

Sur Windows : 

1 cd {IGNITE_HOME}\bin\

2 ignite.bat ..\examples\config\example-ignite.xml

Ouvrez un autre onglet à partir de votre shell de commande et exécutez à nouveau la même commande.

Décompressez le fichier compressé.

Installez le projet dans un répertoire bien connu.

Puis faites les tests 

