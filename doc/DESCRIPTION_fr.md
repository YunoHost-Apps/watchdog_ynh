Un service de surveillance *watchdog* s'assure que votre serveur tourne toujours, et le redémarre si nécessaire.  
Il tournera préférentiellement (uniquement?) si votre serveur est équipé d'un [*watchdog*](https://fr.wikipedia.org/wiki/Chien_de_garde_(informatique)) matériel.

Le service inclut ira régulièrement écrire dans `/dev/watchdog`. S'il s'arrête, le plantage est alors détecté et résolu par un redémarrage du système.

Cette application n'a été testée que sur Raspberry Pi.
