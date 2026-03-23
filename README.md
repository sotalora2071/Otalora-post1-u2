# Sistema de Notificaciones - Patrones Creacionales

Este proyecto implementa los patrones Singleton y Factory Method en Java.

## Singleton
Se utiliza para manejar un registro único de logs de notificaciones.
Se implementa con enum para garantizar una sola instancia.

## Factory Method
Permite crear diferentes tipos de notificadores (Email, SMS, Push)
sin depender de clases concretas.

## Ejecución
```bash
mvn compile
mvn exec:java -Dexec.mainClass="com.patrones.u2.Main"
