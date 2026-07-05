# ShopAF

## Beschreibung

Dieses Projekt zeigt ein einfaches Beispiel für das **LabVIEW Actor Framework**.

Es gibt zwei Actors:

- **Customer A** (Kunde)
- **ShopAssistant** (Verkäufer)

Der Kunde fragt nach dem Preis eines Teddybären. Der Verkäufer antwortet mit dem Preis.

## Projektaufbau

- **Launcher.vi** – Startet das Programm.
- **Customer A.lvlib** – Enthält den Kunden und seine Nachrichten.
- **ShopAssistant.lvlib** – Enthält den Verkäufer und seine Nachrichten.

## Ablauf

1. `Launcher.vi` starten.
2. Die Checkbox **"Bear Price?"** auswählen.
3. Der Kunde sendet eine Nachricht an den Verkäufer.
4. Der Verkäufer berechnet den Preis (3,50 $).
5. Der Verkäufer sendet die Antwort zurück.
6. Der Kunde zeigt die Antwort in einem Meldungsfenster an.

## Was zeigt dieses Projekt?

- Wie zwei Actors miteinander kommunizieren.
- Wie Nachrichten über Queues gesendet werden.
- Dass die Actors unabhängig voneinander arbeiten.

## Ziel

Dieses Projekt ist ein einfaches Beispiel, um das **LabVIEW Actor Framework** und die Kommunikation zwischen Actors zu verstehen.
