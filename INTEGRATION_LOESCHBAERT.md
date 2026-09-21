# Integration Löschbärt – öffentliche Verkaufsseite

Branch: `claude/integration-loeschbaert` (aufgesetzt auf `codex/verkaufsplattform-foehr`)

Der vollständige Bericht über alle drei Projekte steht in
`loeschmeier-abo/INTEGRATION_LOESCHBAERT.md`.

## Übernommen aus der Codex-Fassung

- Leck vollständig entfernt
- manuelle PayPal-Zahlung mit Zahlungsbeleg per E-Mail abgeschafft; die
  Bestellung läuft nur noch über den abgesicherten zentralen Ablauf
- Gemeindeversion als individuelle Anfrage statt als kaufbares Produkt
- Kündigung und Widerruf dauerhaft in Kopf- und Fußzeile verlinkt
- Datenschutzerklärung um Konto, Vertrag, Zahlung, E-Mail-Versand,
  Drittlandübermittlung und Speicherdauer ergänzt

## Zusätzlich korrigiert

- Preis überall als Gesamtpreis: „Gesamtpreis 12,00 € pro Jahr" mit Hinweis
  auf § 19 UStG und darauf, dass keine weiteren Preisbestandteile anfallen
- Seitentitel und Überschrift „Löschbärt Föhr" statt „Einzelabo"
- AGB zusätzlich verlinkt
- Offline-Aussage präzisiert: nutzbar, solange der Zugang besteht
- Hinweis ergänzt, dass die Karte eine ergänzende Arbeitshilfe ist und keine
  amtliche Auskunft ersetzt
- sichtbare Fokusmarkierung, Hinweistext von 11 auf 12 Pixel

## Geprüft

- Darstellung bei 360 und 1280 Pixeln ohne Querscrollen, keine Skriptfehler
- Farbkontraste Stufe AA, geringster Wert 6,7:1
- alle Verweise lösen auf, auch die auf `test.roewise.com`
- keine externen Skripte, Schriften oder Zähldienste eingebunden; deshalb ist
  kein Einwilligungsbanner erforderlich
- keine Verweise mehr auf Leck, Löschmeier oder Löschberg

## Offen

- Der Verkauf verweist auf `test.roewise.com`. Vor einem echten Verkaufsstart
  ist die endgültige Adresse festzulegen und hier sowie in der
  Worker-Variablen `OEFFENTLICHE_BASIS_URL` einzutragen.
- Impressum und Datenschutzerklärung stehen unter dem Vorbehalt der
  anwaltlichen Prüfung. Offene Betreiberangaben siehe Hauptbericht.
