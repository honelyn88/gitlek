[200~# UC-11: Hindra andra från att ansluta

**Use case ID:** UC-11  
**Aktör:** System  
**Syfte:** Hindrar personer som inte är behöriga från att gå med i matchen.  

## Förutsättningar
- Ett privat parti har skapats.
- En okänd/obehörig spelare försöker ansluta via länken.

**Trigger:** En okänd spelare trycker på länken för att ansluta.

## Huvudflöde
1. En okänd spelare försöker ansluta till en länk.
2. Systemet kontrollerar länken och matchens status.
3. Systemet kontrollerar om anslutningen är giltig (t.ex. inom angivet antal timmar).
4. Om anslutningen är giltig, tillåter systemet personen att ansluta.
5. Om anslutningen inte är giltig nekar systemet personen som vill ansluta.
6. Systemet visar ett meddelande om att personen inte kan ansluta.

## Postconditions
- Endast behöriga spelare har tillåtits att ansluta till matchen.
- Obehöriga personer kan inte ansluta.

## Testbar avslutning
En person som inte har tillgång eller behörighet till spelet/matchen kan inte ansluta.
git push
git add .
E0F
