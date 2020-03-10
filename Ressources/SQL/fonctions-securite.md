# Fonctions : sécurité

## [MySQL](https://dev.mysql.com/doc/)

> Algorithmes disponibles : MD5, SHA-2 (224, 256, 384, 512)

|NOM|DESCRIPTION|USAGE|
|:--|:--|:--|
|**AES_ENCRYPT()**|Chiffrement AES à l'aide d'une clé|`AES_ENCRYPT(str, key)`|
|**AES_DECRYPT()**|Déchiffrement AES à l'aide d'une clé|`AES_ENCRYPT(crypt_data, key)`|
|**MD5()**|Génération d'un hash MD5 (128 bits)|`MD5(str)`|
|**SHA()**|Génération d'un hash SHA-1 (160 bits)|`SHA(str)`|
|**SHA1**|_Alias de sha()_|`SHA1(str)`|
|**SHA2()**|Génération d'un hash SHA-2 (256 bits par défaut)|`SHA2(str, length)`|

## [Oracle Database](https://docs.oracle.com/cd/B19306_01/index.htm)

> Algorithmes disponibles : MD5, SHA1, SHA256, SHA384, SHA512 

|NOM|DESCRIPTION|USAGE|
|:--|:--|:--|
|**STANDARD_HASH()**|Génération d'un hash (SHA1 par défaut)|`STANDARD_HASH(str, algorithm)`|

## [PostgreSQL](https://docs.postgresql.fr/)

> Algorithmes disponibles : md5, sha1, sha224, sha256, sha384, sha512

|NOM|DESCRIPTION|USAGE|
|:--|:--|:--|
|**DIGEST()**|Génération d'un hash (via le module **pgcrypto**)|`digest(str, algorithm)`|
|**MD5()**|Génération d'un hash MD5|`md5(str)`|

## [SQLite](https://sqlite.org/docs.html)

+ _Aucune fonction de sécurité disponible (à vous de les définir)_

## [SQL Server (Microsoft)](https://docs.microsoft.com/fr-fr/sql)

> Algorithmes disponibles : MD2, MD4, MD5, SHA, SHA1, SHA2_256, SHA2_512  

|NOM|DESCRIPTION|USAGE|
|:--|:--|:--|
|**HASHBYTES()**|Génération d'un hash|`HASHBYTES(algorithm, str)`|