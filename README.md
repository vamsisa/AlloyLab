# Alloy Lab

Labben kommer bestå av att sätta upp ett CI/CD flöde (Continious Integration/Continious Deployment) för en färdig applikation med moment som kräver PowerShell för driftsättningen.

I labben kommer vi att använda Github för källkodshantering. En tjänst som heter AppVeyor som Continious Integration server (byggserver) och Octopus Deploy för Continious Deployment server. Dessa program/tjänster är mycket vanliga ute på företagen men det finns naturligtvis andra som gör ungefär samma sak. Koncepten är dock desamma.

Din utmaning blir att lösa ett antal steg i den automatiserade driftsättningsprocessen med PowerShell-skript.

## Förberedelser
Även om PowerShell idag är open source och finns på fler plattformar kommer vi uteslutande att arbeta med Windows under labbarna med PowerShell. 

1) Du behöver en VM med Windows 10 eller Windows Server 2016 (med GUI). Windows behöver inte vara aktiverat så du borde klarar dig med en trial utan skarp licens. Vi kommer inte att jobba med virtualisering och skapa upp nya maskiner så du kan behålla *nix som host om du vill på labbdatorn. Labben går ut på att automatisera installationen av en webbapplikation på din labbdator.

2) Du behöver skapa ett konto på Github om du inte redan har ett konto. Acceptera inbjudan till organisationen Nackademin-DEVOPS17 genom att klicka på inbjudningslänken som du har fått i ett separat mejl. Lägg in ditt riktiga namn och bild i profilen på Github.

3) Skapa ett trial konto på Appveyor (14 day free trial)

4) Skapa ett trial konto på Octopus Deploy Cloud. Skapa en instans av servern som heter t.ex. ”Nackademin-FH”.
