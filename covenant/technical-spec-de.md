# Technische Spezifikation für Deposit, Nachweis und Trigger-Auslösung

## für das Set-OutlookSignatures Benefactor Circle Add-on

**Stand:** 2. Juni 2026

## 1. Zweck

Diese technische Spezifikation konkretisiert die öffentliche Software-Fallback- und Projekt-Treuhand-Erklärung für das **Set-OutlookSignatures Benefactor Circle Add-on**.

Sie beschreibt insbesondere:

- das technische Deposit-Modell;
- das öffentliche Nachweis-Modell;
- das Einsichts- und Vorführungsrecht;
- die Integration der Proof-Unterlagen in den Build-Prozess;
- sowie den praktischen Ablauf im Trigger-Fall.

## 2. Repositorien

### 2.1 Kanonisches Projekt-Repository

Das kanonische öffentliche Projekt-Repository ist:

`https://github.com/Set-OutlookSignatures/Set-OutlookSignatures`

### 2.2 Geheimes Repository

Das Set-OutlookSignatures Benefactor Circle Add-on wird in einem nicht öffentlichen, von ExplicIT Consulting GmbH kontrollierten Repository geführt.

### 2.3 Nachweis-Repositorium

Das öffentliche Nachweis-Repositorium lautet:

`https://github.com/Set-OutlookSignatures/benefactor-circle-add-on-proof-of-escrow`

Es dient ausschließlich der Veröffentlichung von:

- Covenant-Fassungen;
- technischer Spezifikation;
- Nachweis-Manifests;
- Hash-Dateien;
- Trigger-Mitteilungen;
- Nachfolger-Erklärungen;
- und sonstigen Governance-Dokumenten.

Es dient **nicht** der Vorab-Offenlegung des Quellcodes.

## 3. Deposit-Modell

### 3.1 Inhalt des Deposit-Pakets

Das Deposit-Paket umfasst die in der Covenant-Erklärung definierten Bestandteile der Kategorien A und B und schließt Kategorie C aus.

### 3.2 Form

Das Deposit-Paket wird als komprimiertes Archiv erstellt, beispielsweise ZIP.

### 3.3 Versionierung

Für jedes Produktions-Release wird ein eigenes Deposit-Paket erzeugt.

### 3.4 Speicherung

Das Deposit-Paket verbleibt bis zum Eintritt eines Triggers in einem nicht öffentlichen Speicherbereich unter Kontrolle von ExplicIT Consulting GmbH.

## 4. Öffentlicher Existenznachweis

### 4.1 Frist

Innerhalb von zehn (10) Geschäftstagen nach jedem Produktions-Release wird ein öffentlicher Nachweis im Nachweis-Repositorium veröffentlicht.

### 4.2 Mindestinhalt

Jeder Nachweis enthält mindestens:

- Produktname;
- Version oder Build-Kennung;
- UTC-Datum der Erstellung;
- Dateiname des Deposit-Pakets;
- SHA-256-Hashwert;
- Hinweis auf den Umfang;
- Hinweis auf ausgeschlossene Kategorien;
- Verweis auf die aktuelle Covenant-Fassung.

### 4.3 Verzeichnisstruktur

Empfohlene Struktur im Nachweis-Repositorium:

`/proof/vX.Y.Z/`

mit mindestens:

- `deposit-manifest.json`
- `SHA256SUMS.txt`
- `README.md`

### 4.4 Zusatzveröffentlichung

Die Dokumente sollen zusätzlich auf `set-outlooksignatures.com` veröffentlicht oder von dort verlinkt werden.

## 5. Einsichts- und Vorführungsrecht

### 5.1 Turnus

Die Projektadministratoren haben Anspruch auf Vorführung:

- nach jedem Update des geheimen Repositorys;
- mindestens jedoch einmal pro Kalenderquartal.

### 5.2 Gegenstand der Vorführung

Die Vorführung muss zeigen:

- dass das geheime Repository tatsächlich existiert;
- dass der aktuelle Stand des Repositorys technisch zugänglich ist;
- dass das vorhandene Build-Skript ausführbar ist;
- und dass damit eine voll funktionsfähige Version des Set-OutlookSignatures Benefactor Circle Add-on erstellt werden kann.

### 5.3 Formen der Vorführung

Zulässige Formen sind insbesondere:

- Live-Bildschirmfreigabe;
- Live-Build-Demonstration;
- protokollierte Demonstration mit nachvollziehbarem Ablauf;
- oder gleichwertige technische Nachweisformen.

### 5.4 Schutz vertraulicher Inhalte

ExplicIT Consulting GmbH darf während der Vorführung sensible Inhalte unkenntlich machen oder anderweitig schützen, soweit der Kernnachweis dadurch nicht vereitelt wird.

### 5.5 Dokumentation

Über jede Vorführung soll ein kurzes Protokoll erstellt werden, zumindest mit:

- Datum und Uhrzeit;
- teilnehmenden Personen;
- gezeigter Version / Commit-Referenz;
- Ergebnis der Vorführung;
- allfälligen Einschränkungen oder Vorbehalten.

## 6. Trigger-Prozess

### 6.1 Ausdrückliche Einstellung

Im Fall einer ausdrücklichen Einstellungserklärung durch ExplicIT Consulting GmbH wird die Trigger-Mitteilung unverzüglich im Nachweis-Repositorium dokumentiert.

### 6.2 Sonstige Trigger

In allen anderen Trigger-Fällen veröffentlichen die Projektadministratoren eine `trigger-notice.md` im Nachweis-Repositorium.

### 6.3 Beschluss

Soweit eine Entscheidung der Projektadministratoren erforderlich ist, bedarf es einer Zwei-Drittel-Mehrheit.

### 6.4 Wartefrist

Sofern die Covenant-Erklärung keine sofortige Wirkung vorsieht, gilt eine Wartefrist von 90 Kalendertagen.

## 7. Übergabe im Trigger-Fall

### 7.1 Herausgabe

Nach Wirksamwerden des Triggers übergibt ExplicIT Consulting GmbH das aktuelle Deposit-Paket an die Projektadministratoren.

### 7.2 Erstübernahme

Die technische Erstübernahme erfolgt in einem separaten Repository.

### 7.3 Vertraulichkeit bis Veröffentlichungsbeschluss

Bis zu einem Veröffentlichungsbeschluss der Projektadministratoren ist das Deposit-Paket vertraulich zu behandeln.

### 7.4 Spätere Veröffentlichung

Über eine spätere Veröffentlichung und die anzuwendende Open-Source-Lizenz entscheiden die Projektadministratoren mit Zwei-Drittel-Mehrheit.

## 8. Empfohlene Ordnerstruktur des Nachweis-Repositoriums

```text
/covenant
  covenant-de.md
  covenant-en.md
  technical-spec-de.md
  technical-spec-en.md

/proof
  /vX.Y.Z
    deposit-manifest.json
    SHA256SUMS.txt
    README.md

/notices
  trigger-notice-template.md
  successor-assumption-template.md
```

## 9. Signatur und Publikation

1. Die offizielle Fassung der Covenant-Erklärung soll zusätzlich als PDF veröffentlicht werden.
2. Die offizielle veröffentlichte Fassung kann entweder als digital signiertes PDF oder als Scan eines manuell unterschriebenen Ausdrucks veröffentlicht werden.
3. Die Arbeitsfassungen in Markdown dienen der Transparenz, Nachvollziehbarkeit und Versionsverwaltung.

## 10. Praktischer Minimalprozess

1. Produktions-Release intern abschließen.
2. Deposit-Paket erstellen.
3. SHA-256 berechnen.
4. Manifest erzeugen.
5. Unterlagen strukturieren.
6. Öffentlichen Nachweis in das Nachweis-Repositorium publizieren.
7. Bei Repo-Update bzw. mindestens quartalsweise Vorführung für die Projektadministratoren durchführen.
8. Dokumentation der Vorführung ablegen.
