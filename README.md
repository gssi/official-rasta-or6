# Itineraries and Point of Interests of the Abruzzo National Park (OR6)

## Local installation
To add itineraries and Point of Interests related to the Abruzzo National Park, run the `pna-data.sql` sql script file in the `rastapms` database.
You can use a terminal or `phpmyadmin` if installed.

**As a prerequisite, you must follow the installation instructions for the Rasta PMS (https://github.com/gssi/official-rasta-pms/blob/main/Install.md)**

## Docker installation

### System Requirements
Docker has to be installed to your machine

### Add itineraries and Point of Interests
Open a terminal in the directory where you downloaded the source code and type the following command:

    ```
    docker exec -it mysql-db mysql -u root -prootpassword rastapms < ./pna-data.sql
    ```

If you are using Windows you should use the following command:

    ```
    type .\pna-data.sql | docker exec -i mysql-db mysql -u rastapms -prastapms rastapms
    ```

## License
Rasta PMS is Open Source software released under the [Apache 2.0 license](/LICENSE.md).

## Gran Sasso Science Institute Team
- Sadia Azam
- Maria Giovanna Brandano
- Gianlorenzo D'Angelo
- Martina De Sanctis
- Amleto Di Salle
- Paola Inverardi
- Ludovico Iovino
- Rickson Pereira
- Claudio Pompilio
- Franco Raimondi