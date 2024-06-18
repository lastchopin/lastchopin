# Projekte aus meinem Cyber Security Studium

Dieses Repository dient zur Sammlung und Dokumentation von verschiedenen Projekten, die ich während meines Studiums im Bereich Cyber Security entwickle. Jedes Projekt hier zeigt eine praktische Anwendung und Umsetzung von verschiedenen Konzepten, Techniken und Algorithmen aus dem Bereich der Cybersicherheit.

## Projekt 1: DSA Implementierung in Python

Dieses Projekt implementiert den Digital Signature Algorithm (DSA) in Python. Der DSA ist ein asymmetrisches Verschlüsselungsverfahren, das für die Erstellung und Verifikation digitaler Signaturen verwendet wird. Es umfasst die folgenden Funktionen:

- **Schlüsselgenerierung**: Erzeugt DSA-Schlüssel gemäß den Spezifikationen in [FIPS 186-4](https://nvlpubs.nist.gov/nistpubs/fips/nist.fips.186-4.pdf).
- **Signierung**: Signiert Nachrichten mit dem DSA-Signaturalgorithmus und der SHA-256 Hashfunktion.
- **Verifikation**: Verifiziert die Korrektheit von Signaturen.
- **Kompromittierung des privaten Schlüssels**: Demonstriert potenzielle Schwachstellen bei der Wiederverwendung von Zufallszahlen.

## Projekt 2: RSA Signatur und Fälschung in Python

Dieses Projekt behandelt die RSA-Signatur und demonstriert die universelle Fälschung von RSA-Signaturen. RSA (Rivest-Shamir-Adleman) ist ebenfalls ein asymmetrisches Verschlüsselungsverfahren und wird für digitale Signaturen sowie Verschlüsselung verwendet. Die Implementierung umfasst:

- **RSA-Schlüsselgenerierung**: Generiert einen RSA-Schlüssel mit einem Modulus von mindestens 3000 Bit.
- **Signierung**: Signiert Nachrichten mit RSA und der SHA-256 Hashfunktion.
- **Verifikation**: Verifiziert die Korrektheit von RSA-Signaturen.
- **Universelle Fälschung**: Zeigt einen Angriff, bei dem ein Angreifer eine beliebige Nachricht signieren kann, ohne den privaten RSA-Schlüssel zu kennen.
