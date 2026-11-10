# lost-inventory

Fundseite für die QR-Labels aus der App „LXKsound Inventory“.
Wer ein Gerät findet und den QR-Code scannt, landet auf `https://lost.lxksound.com/<Inventarnummer>`
und sieht den Kontakt. Es stehen **keine Inventardaten** in diesem Repo.

- `index.html` und `404.html` sind identisch: GitHub Pages liefert für jede Nummer im Pfad die 404-Seite aus,
  das Skript liest die Nummer aus der Adresse.
- `CNAME`: eigene Domain `lost.lxksound.com` (DNS bei united-domains: CNAME `lost` → `lxksound.github.io`).
- Hosting: GitHub Pages (Branch `main`, Ordner `/`), HTTPS erzwingen.
