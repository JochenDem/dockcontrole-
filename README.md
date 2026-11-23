# dockcontrole

Twee losse pagina's, zonder bibliotheken, voor de dockcontrole. Beide gebruiken de tabel `dock_routes` in het Supabase-project **work-sap** (TU als sleutel) en dezelfde work-sap-login.

## `index.html` — Dock input
- Gegevens uit de SAP-export plakken, per HU de controlecode aflezen.
- Dock en TU invullen (de dock is aanpasbaar).
- **Naar controle sturen** zet de route klaar voor de controle.

## `controle.html` — Dockcontrole
- Een klaargezette route kiezen en afvinken wat er op het dok staat.
- Per HU maar één keuze: 6m, 6.5m of `?` (niet gevonden, de rij wordt oranje).
- S0-labels toewijzen aan een S1 van dezelfde klant.
- De dock is aanpasbaar; alles wordt automatisch teruggeschreven.
- **Controle afgerond** zet de route op afgewerkt (met tijdstip en e-mailadres) en maakt daarna de velden leeg.

Zet GitHub Pages aan op de branch `main`, map `/ (root)`.
