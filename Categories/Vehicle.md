## Fahrzeug-System

-   **Funktionalität**

    -   Fahrzeuge sind der wertvollste Besitz des Spielers und werden dementsprechend behandelt.
    -   Zerstörte Fahrzeuge, die nicht versichert sind (z.B. durch Explosion), sind nicht länger in der Garage verfügbar und gelten als unwiederbringlich verloren.

-   **Versicherungssystem**

    -   Ähnlich wie im echten Leben gibt es für Fahrzeuge eine Vollkaskoversicherung.
    -   Wird ein versichertes Fahrzeug zerstört, kann es gegen eine steigende Versicherungsgebühr wieder ausgeparkt werden.
    -   Jeder Spieler startet mit einem niedrigen Versicherungs-Score, der mit jedem Unfall und jeder Zerstörung steigt. Dieser Score beeinflusst die Versicherungsgebühren und -bedingungen.

-   **Fahrzeugkapazitäten**

    -   Fahrzeuge haben Kofferräume mit individueller Kapazität, die je nach Fahrzeugtyp unterschiedlich groß ist.
    -   LKWs bieten ohne Anhänger kaum Platz für Items. Anhänger können optional gekauft und ebenfalls versichert werden. Bei Verlust werden versicherte Anhänger automatisch ersetzt.

-   **Persistente Fahrzeugpositionen**

    -   Fahrzeugpositionen werden in der Datenbank gespeichert und zur Laufzeit im Cache (Redis) verwaltet, sodass jedes Fahrzeug immer an seiner letzten Position verbleibt.

-   **Sichere Parkzonen**

    -   Es gibt bestimmte sichere Parkzonen wie große Parkplätze oder Parkhäuser. Fahrzeuge, die in diesen Zonen durch Fremdverschulden zerstört werden, können kostenlos ersetzt werden, ohne dass die Versicherungskosten steigen.
    -   Diese Parkzonen gelten jedoch nicht als reguläre „Safe Zones“ im Spiel, sodass keine Roleplay-Einschränkungen greifen.

-   **Fahrzeugstatus-Speicherung**

    -   Tuning und Schadensstatus jedes Fahrzeugs werden persistiert, damit das Fahrzeug stets im aktuellen Zustand verbleibt.

-   **Erweiterbarer Kofferraum**

    -   Gegen einen höheren Preis kann zusätzliches Tuning für mehr Stauraum im Fahrzeug oder Anhänger erworben werden, um einen ausgewogenen Spielverlauf zu gewährleisten.

-   **Beschlagnahme**

    -   Fahrzeuge können im Zuge von Gesetzesverstößen beschlagnahmt werden. Ein beschlagnahmtes Fahrzeug gilt als zerstört, bis ein Staatsbeamter es freigibt.

-   **Jobfahrzeuge**

    -   Jobfahrzeuge werden wie private Fahrzeuge behandelt. Sie sind über den Arbeitgeber versichert und gelten als dessen Eigentum.

-   **Parkdauer und Abschleppdienst**
    -   Fahrzeuge, die die maximale Parkdauer überschreiten, werden vom Abschleppdienst (ACSA) abgeschleppt.
    -   Wiederholte Verstöße führen zu einer steigenden Gebühr, um das Fahrzeug auszulösen und den Missbrauch von Parkplätzen zu verhindern.
