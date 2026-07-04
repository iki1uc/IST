# IST – Public State Layer

## Öffentlicher Zweck
IST bildet die öffentliche Zustands‑Ebene der Trinity‑Struktur.  
Es dient als sichtbare Komponente zur Darstellung von aktuellen Zuständen, Status‑Werten und öffentlich freigegebenen State‑Bezügen innerhalb der Public‑Umgebung.

## Argumenteria‑Rahmen
IST folgt dem Argumenteria‑Prinzip:
1. Klarheit – eindeutige Zustands‑Ebene.
2. Struktur – geordnete Darstellung von State‑Bezügen.
3. Neutralität – keine internen Mechanismen oder Systemdetails.
4. Nachvollziehbarkeit – klarer Zweck und klare Funktion.
5. Integrität – konsistente Außendarstellung.

## 7SINN‑Relevanz
IST erfüllt die 7SINN‑Kriterien:
1. Verständlichkeit – IST zeigt Zustände klar und nachvollziehbar.
2. Orientierung – dient als öffentliche State‑Ebene.
3. Nutzen – erleichtert die Zuordnung öffentlicher Status‑Items.
4. Struktur – ordnet State‑Elemente und Lage‑Bezüge.
5. Neutralität – bleibt frei von Systeminternas.
6. Integrität – wahrt die Logik der Public‑Ebene.
7. Nachvollziehbarkeit – klare, stabile Darstellung.

## Modulbeschreibung
Dieses Repository stellt die öffentliche IST‑Ebene dar.  
Es dokumentiert Zustands‑Bezüge und öffentlich freigegebene State‑Items innerhalb der Trinity‑Public‑Struktur, ohne interne Abläufe offenzulegen.

## IST‑Struktur (Public‑Version)
IST nutzt eine neutrale Public‑Struktur, um Zustands‑Informationen sichtbar zu machen.  
Diese Darstellung zeigt ausschließlich öffentlich freigegebene Felder.

### Beispiel einer IST‑Public‑Struktur

```json
{
  "id": "IST1",
  "info": {},
  "meta": {
    "layer": "state",
    "public": true
  },
  "state": {
    "value": null,
    "active": false
  },
  "item": {
    "name": "Public-State-Item",
    "version": "1.0",
    "active": false
  }
}

