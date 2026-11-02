# meine-skills

Claude-Plugin-Marktplatz mit Spiegeln von Skills, die selbst keinen Marktplatz haben.

| Plugin | Quelle | Aktualisierung |
|---|---|---|
| be-ambitious | [robonuggets/be-ambitious](https://github.com/robonuggets/be-ambitious) | GitHub Action, täglich 04:17 UTC |
| humanizer-de | [marmbiz/humanizer-de](https://github.com/marmbiz/humanizer-de) | GitHub Action, täglich 04:17 UTC |

## Einrichtung in claude.ai

1. claude.ai → **Anpassen** → **Plugins** → **Hinzufügen** → **Marktplatz hinzufügen** → `mblmg/skill-store-i-make-media`
2. Beim Marktplatz **Automatisch synchronisieren** einschalten.
3. Plugin `be-ambitious` installieren.

## Weitere Skills spiegeln

Neuen Ordner unter `plugins/<name>/` anlegen (mit `.claude-plugin/plugin.json` und `skills/<name>/SKILL.md`),
in `.claude-plugin/marketplace.json` eintragen und im Workflow einen weiteren Job ergänzen.

## Lizenz

Die gespiegelten Skills behalten ihre Original-Lizenz (siehe jeweilige `LICENSE`).
