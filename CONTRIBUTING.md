# Bijdragen tot Routinier 

Alle bijdrages aan Routinier zijn welkom. Als je iets wilt vragen of voorstellen. Maar dan alsjeblieft eerst een issue aan.
En als je een bug wilt verhelpen. Of een feature wilt implementeren kan je altijd een pull request aanmaken. 

## Pull Requests 

De volgende richtlijnen zijn van kracht op pull requests. 

- Alle code volgt de [PSR-2](https://www.php-fig.org/psr/psr-2/) & [PSR-12](https://www.php-fig.org/psr/psr-12/) coderings standaarden.
- Alle bug fixes of feature implementaties moeten bijgestaan worden door unit tests. 
- Hou het `README.md` bestand en de documentatie ten alle tijden up-to-date met de wijzigingen
- We volgen [Semantic versioning](https://semver.org) voor het releasen van nieuwe versies. Gebruik dus ook de versie als indicatie. 
- Update het `CHANGELOG.md` bestand met alle updates en volg de [changelog standaarden](https://keepachangelog.com/nl/1.0.0/)

## Running tests

Je kan de unit tests uitvoeren met het volgende commando: 

```
$ vendor/bin/phpunit
```