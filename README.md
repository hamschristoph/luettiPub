# Dublin im Hundi

Live-Tracker für das Ziel **10 Liter Bier in 24 Stunden** für Tim, Lütti, Jan, Jannik, Christoph, Robin und Carsten.

**App:** https://claude.ai/artifact/MbekUuWpJCdUTyhoQjaYtv

Die App läuft als Claude-Artefakt mit gemeinsamem Live-Speicher. Alle, die eingeladen sind, sehen jeden Eintrag sofort.

## Bedienung

- **Gesamtstand Do–So:** Tabelle mit allen Getränken vom 19. bis 22. November pro Person und Tag (ein Tag geht bis 6 Uhr früh), unabhängig von der 24-h-Runde.
- **Neue Runde:** Wenn eine Runde vorbei ist, startet „Neue Runde starten“ (zweimal tippen) die nächste. Alte Einträge bleiben erhalten.
- **Rangliste:** Die Türen sind nach Litern sortiert, wer am meisten hat, steht oben.
- **Tür antippen:** Getränk für diese Person eintragen (Pint 0,568 · Halbe 0,5 · Dose 0,44 · Flasche 0,33 · ½ Pint 0,284 · Maß 1,0 oder eigene Menge).
- **Whiskey:** im Eintragefenster unten „Whiskey ★“. Jeder Whiskey gibt einen Stern neben dem Namen und zählt nicht als Bier.
- **„+“ rechts an der Tür:** wiederholt das letzte Getränk dieser Person mit einem Tipp.
- **Rückgängig:** nach jedem Eintrag ein paar Sekunden lang im Hinweis unten.
- **Verlauf:** falsche Einträge mit × löschen (mit Rückfrage, ebenfalls rückgängig machbar).
- **Uhr:** startet automatisch mit dem ersten Getränk. Unter „Uhr & Regeln“ lassen sich Startzeit und **Endzeit** (z. B. Sperrstunde) festlegen. Ohne Endzeit gelten 24 Stunden.

## Regeln

- Es zählen nur Getränke zwischen Start und Ende (2 Minuten Kulanz für Handy-Uhren). Ziel bleibt 10 Liter, das Soll verteilt sich auf die gewählte Dauer.
- Status pro Person: *Im Soll*, *hinter Soll*, *Geschafft*, dazu das nötige Tempo („1 Pint alle … min“).

## Dateien

- `dublin-im-hundi.html` – Quelltext der App (so wie er als Artefakt veröffentlicht ist).
- `index.html` – leitet auf die App weiter.
- `backup/stand.json` – Sicherung des Stands vom 19.11.2026 (63 Einträge, Start- und Endzeit).
