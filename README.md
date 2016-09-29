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
--- Hiermee plak je paths aan elkaar. In dit geval een nieuw bestand.
- Wordt de return-waarde van `Directory.CreateDirectory(...)` steeds opgevangen? (TIP: gebruik `CTRL-SHIFT-F`)
--- Ja
- Wat is de return-waarde van `Directory.CreateDirectory(...)`?
--- Het returnt een boolean
- Wanneer is het nuttig om de return-waarde van `Directory.CreateDirectory(...)` op te vangen?
--- Om te zien of de method werkt

i.v.m. duidelijkheid/geschiedenis van de code:

- Lukken de testen in de commit 3ffe2c86? Waarom (niet)?
--- nee, Expect en assert zijn omgewisseld
- Wat lost commit d0320b6a op?
--- Oplossing van de problemen van vorige commit. 
- Wat is het probleem met de files in commit 9d184949?
--- Niet genoeg uitgewerkt.
- Wat doet commit 9b3e4065? Maakt dit de code makkelijker leesbaar? Makkelijker uitbreidbaar?
--- Verduidelijking van de code. Maakt het dus duidelijker en makkelijker leesbaar.



