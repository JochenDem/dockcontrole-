# dockcontrole

Pagina om de klaargezette routes aan het dok af te vinken. Eén bestand, `index.html`, zonder bibliotheken.

- De routes komen uit de tabel `dock_routes` in het Supabase-project **work-sap** (TU als sleutel). Inloggen met dezelfde work-sap-login als de andere pagina's.
- Per HU maar één keuze: 6m, 6.5m of `?` (niet gevonden, de rij wordt oranje).
- S0-labels toewijzen aan een S1 van dezelfde klant.
- De dock is aanpasbaar; alles wat je aanduidt wordt automatisch teruggeschreven.
- **Controle afgerond** waarschuwt als er nog HU's zonder keuze zijn, zet de route op afgewerkt (met tijdstip en e-mailadres) en maakt daarna de velden leeg.
- De kolom `volledig_gekeurd` in `dock_routes` wordt `true` zodra elke HU een keuze heeft (6m, 6.5m, ?, gezien of paletten/dozen).

Zet GitHub Pages aan op de branch `main`, map `/ (root)`.
