# Analyseer

Bekijk de volledige commit-geschiedenis om te bestuderen hoe dit project tot stand gekomen is.

Probeer volgende vragen te beantwoorden:

i.v.m. MSTest:

- Welke Assert-methods worden naast `Assert.AreEqual` nog allemaal gebruikt?
--- Assert.isTrue, Assert.isFalse
- Waarom heeft `TestDirectories` een `Initialize`- en `CleanUp`-method?
--- Om een speciale test directory aant te maken om daarin te werken. Die wordt ook weer verwijderd.
- Zijn de attributen `[TestMethod]`, `[TestClass]`, ... noodzakelijk? (Test uit!)
--- Ja
- Wat is de shortcut om alle tests uit te voeren in VS?
--- Ctrl + r, Ctrl + a

i.v.m. Files en Directories:

- Wat is het voordeel van `Path.Combine` i.v.m. strings aan elkaar plakken?
- Wordt de return-waarde van `Directory.CreateDirectory(...)` steeds opgevangen? (TIP: gebruik `CTRL-SHIFT-F`)
- Wat is de return-waarde van `Directory.CreateDirectory(...)`?
- Wanneer is het nuttig om de return-waarde van `Directory.CreateDirectory(...)` op te vangen?

i.v.m. duidelijkheid/geschiedenis van de code:

- Lukken de testen in de commit 3ffe2c86? Waarom (niet)?
- Wat lost commit d0320b6a op?
- Wat is het probleem met de files in commit 9d184949?
- Wat doet commit 9b3e4065? Maakt dit de code makkelijker leesbaar? Makkelijker uitbreidbaar?


