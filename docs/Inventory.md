# Inventar-System

## 1. Inventar

Das Inventar ist das zentrale Verwaltungssystem für alle Gegenstände, die ein Spieler besitzt. Es besteht aus fünf Hauptkategorien und einem spezialisierten Hotbar-System zur schnellen Nutzung von Items.

### Kategorien

1. **Items**  
   Beinhaltet alle grundlegenden Objekte wie:
    - Consumables (Lebensmittel, Getränke)
    - Useables (Werkzeuge, Dekorationsgegenstände, spezielle Ausrüstungsgegenstände)
2. **Kleidung**  
   Diese Kategorie umfasst Kleidung und ein spezielles Inventar-Interface für Kleidungsgegenstände, das es erlaubt, Kleidung direkt bestimmten Slots zuzuordnen (z.B. Torso, Beine), um Grafikfehler zu vermeiden.

3. **Schlüssel**  
   Speichert Fahrzeug-, Haus-, und Apartment-Schlüssel, sowie Schlüssel zu Lagerräumen und Keycards für spezielle Einrichtungen. Jeder Schlüssel zeigt seinen zugehörigen Identifier.

4. **Waffen**
    - Waffen sind einzigartig und jede Waffe hat eine Seriennummer (Ausnahme: illegale, selbstgefertigte Waffen. Diese können auf Wunsch legalisiert und bei der Polizei registriert werden).
5. **Portemonnaie**

    - Beinhaltet persönliche Dokumente wie Ausweise und Visitenkarten, sowie Bargeld und Bankkarten.

6. **Animationen**
    - Sammlung aller verfügbaren Animationen und Emotes im Spiel, einschließlich Custom-Emotes.

### Funktionen des Inventars

-   **Drag-and-Drop**: Die Hauptbedienung erfolgt per Drag-and-Drop.
-   **Kontextmenü**: Bei bestimmten Items lässt sich ein Kontextmenü per Rechtsklick öffnen, das Optionen wie Umbenennen, Löschen oder Benutzen bietet.
-   **Hotbar-Slots**: Das Inventar enthält 6 Hotbar-Slots, die schnellen Zugriff auf Items, Waffen oder Schlüssel gewähren. Per Zahlen 1-6 lassen sich Items sofort verwenden.
-   **Einzigartige Gegenstände**: Kleidungsstücke erscheinen im Tab „Kleidung“ und sind nicht stapelbar.
-   **Gewichts- und Verderb-System**:
    -   Ein Gewichtssystem begrenzt die Traglast des Inventars.
    -   Das Verderb-System sorgt dafür, dass bestimmte Items, wie etwa Fleisch, schneller ablaufen, wenn sie nicht gekühlt werden.

---

## 2. Container

Container bieten zusätzlichen Stauraum und sind wie das Inventar organisiert, jedoch ohne Hotbar und mit größerem Gewichtslimit.

### Eigenschaften der Container

-   **Kategorien**:  
    Container bieten drei Hauptkategorien:

    -   **Items**
    -   **Kleidung**
    -   **Waffen**

-   **Schloss und Sicherheit**:  
    Container lassen sich abschließen, können jedoch im Abwesenheit des Besitzers geknackt werden.

-   **Stationäre Nutzung**:  
    Container sind stationäre Einheiten und lassen sich nicht bewegen. Sie sind in bestimmten Gebäuden oder Lagerräumen platziert.

---

## 3. Kofferraum

Der Kofferraum ist ein Teil der Fahrzeuge und funktioniert ähnlich wie ein Container, bietet jedoch einzigartige Eigenschaften für mobile Nutzung.

### Eigenschaften des Kofferraums

-   **Mobiler Container**:  
    Im Gegensatz zu Containern sind Kofferräume mobil und an die Fahrzeuge gebunden.

-   **Knackbar**:  
    Auch der Kofferraum ist separat knackbar und erfordert spezielle Werkzeuge zum Öffnen.

-   **Kategorien**:  
    Die Kategorien entsprechen denjenigen des Containers (siehe oben).
