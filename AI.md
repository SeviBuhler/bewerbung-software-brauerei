# 🤖 AI.md – wie ich mit AI arbeite

> AI macht mich zehnmal schneller. Nicht zehnmal schlauer.
> Das habt ihr geschrieben. Ich unterschreibe es.

## Meine Toolbox

| Tool | Wofür |
|---|---|
| **Claude Code** | Coding-Agent direkt im Projektordner, z. B. für mein Godot-Spiel |
| **Claude (Chat)** | Specs, Architektur-Sparring, Recherche, Lernen |
| **Claude-basierter Agent** | Read-only Monitoring meines Trading-Bots auf dem Homelab |
<!-- TODO: weitere Tools ergänzen, die du wirklich nutzt (Cursor, Copilot, MCP-Server …) -->

## Meine Regeln

1. **Kein Merge ohne Verständnis.** Was ich nicht erklären kann, landet nicht im Code.
2. **Jeder Diff wird gelesen.** Auch wenn der Agent sehr selbstbewusst klingt. Gerade dann.
3. **Tests vor Vertrauen.** Der Agent darf Tests schreiben. Ob sie das Richtige prüfen, entscheide ich.
4. **Least Privilege für Agents.** Mein Monitoring-Agent sieht den Trading-Bot, kann aber nichts auslösen.
5. **Selber durchklicken.** Bevor etwas beim Kunden landet, habe ich es selbst bedient.
6. **Lernen bleibt meine Aufgabe.** Bei meiner Kalender-PWA lasse ich mich nur anleiten und schreibe den Code selbst. So weiss ich später, warum er funktioniert.

## Wo AI glänzt – und wo nicht

| ✅ Gute Idee | ⚠️ Nur mit Kontrolle | ❌ Nicht delegiert |
|---|---|---|
| Boilerplate, Scaffolding | DB-Migrationen | Security-Entscheide |
| Tests vorschlagen | Refactorings über viele Dateien | Was beim Kunden live geht |
| Fehlermeldungen erklären | Neue Libraries, die ich nicht kenne | Architektur ohne Rückfrage |
| Doku & Commit-Texte | Alles mit Rechten auf Prod oder Geld | Code, den ich nicht verstehe |

## Ein echter Fall

<!-- TODO: Hier eine echte Geschichte einsetzen. Das ist der wichtigste Teil dieser Datei. Vorlage: -->

**Kontext:** *Welches Projekt, was wolltest du erreichen?*
**Was der Agent gemacht hat:** *Was hat er vorgeschlagen oder geändert?*
**Was mir aufgefallen ist:** *Woran hast du gemerkt, dass etwas nicht stimmt? Diff, Test, Durchklicken?*
**Lösung:** *Was hast du korrigiert, und was hast du daraus für deinen Workflow mitgenommen?*

---

[← zurück zur README](README.md)
