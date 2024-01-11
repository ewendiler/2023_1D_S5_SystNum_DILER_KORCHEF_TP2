Commandes AT :

    Tester si la liaison avec le micro-controleur est bien active : AT
    Verifier la version du software embarqué dans le module : AT+VERSION\r\n
    Remettre le périphérique à sa configuration par défaut : AT+ORGL
    Changer le nom du module bluetooth (très important pour différencier tous les modules dans la salle) : AT+NAME=<NAME>\r\n
    Mettre le module en mode Master : AT+ROLE=Param1 
    Changer le mot de passe d'accès au bluetooth : AT+PWD=<Password>\r\n 
    Changer le baudrate de la liaison à 38400 baud/s : AT+UART=38400,1,2,\r\n
