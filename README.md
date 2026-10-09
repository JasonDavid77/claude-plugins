# Jason Lau-Christen: Plugins für Claude Code

**Deutsch** | [English](#english)

Werkzeuge, die beim Lernen und Arbeiten mit KI im Beruf helfen, gebaut für Menschen ohne Technikwissen. Jedes Plugin hat sein eigenes Repository mit Anleitung, Changelog und Issues.

## Plugins

| Plugin | Was es tut |
|---|---|
| [Der Weise](https://github.com/JasonDavid77/der-weise) (`weise`) | Ein Lernpartner, der Ihnen ein Werkzeug oder Fachgebiet an Ihrem echten Projekt beibringt: Erklärung von Grund auf, mitwachsender Lernpfad, Abfrage-Karten. Ihre Dateien bleiben lokal. |

## Wissenspakete für den Weisen

Ein Wissenspaket ist fertiges Lernmaterial zu einem Thema. Es enthält nur Texte, keine Befehle. Die Pakete selbst liegen im Katalog [weise-pakete](https://github.com/JasonDavid77/weise-pakete); hier steht nur die Liste. So nutzen Sie eines: in den Einstellungen unter „Plugins“ beim Paket auf das Plus, dann `/weise:paket` aufrufen. Eigene Pakete reichen Sie im Katalog `weise-pakete` ein.

| Paket | Inhalt | Stand |
|---|---|---|
| `weise-agentische-kanzlei` | Agentische Kanzlei: acht Rechercheberichte zu agentischer KI in der Rechtsberatung (Deutsch) | 2026-10-01 |

## Installation

Voraussetzung: Claude Code (Desktop-App, Reiter „Code“, oder Terminal) und Git.

1. Katalog hinzufügen:

   ```
   /plugin marketplace add JasonDavid77/claude-plugins
   ```

2. Plugin installieren, zum Beispiel den Weisen:

   ```
   /plugin install weise@jason-lau-christen
   ```

Automatische Updates für diesen Katalog schalten Sie einmal ein: `/plugin` eingeben, „Marketplaces“, `jason-lau-christen`, „Enable auto-update“. Alles Weitere steht in der Anleitung des jeweiligen Plugins.

## Lizenz

[MIT](LICENSE), Copyright (c) 2026 Jason Lau-Christen.

---

## English

Tools that help you learn and work with AI on the job, built for people without a technical background. Each plugin has its own repository with guide, changelog and issues.

| Plugin | What it does |
|---|---|
| [Der Weise](https://github.com/JasonDavid77/der-weise) (`weise`) | A learning partner that teaches you a tool or field on your real project: explanations from scratch, a growing learning path, recall cards. Your files stay local. |

**Knowledge packs for Der Weise:** ready-made learning material, text only, no commands. The packs live in the [weise-pakete](https://github.com/JasonDavid77/weise-pakete) catalog; this catalog only lists them. To use one, install it from the plugin list, then run `/weise:paket`.

| Pack | Content | As of |
|---|---|---|
| `weise-agentische-kanzlei` | Agentic law firm: eight research reports on agentic AI in legal services (German) | 2026-10-01 |

**Install** (requires Claude Code and Git):

```
/plugin marketplace add JasonDavid77/claude-plugins
/plugin install weise@jason-lau-christen
```

To turn on automatic updates for this catalog once: type `/plugin`, choose "Marketplaces", `jason-lau-christen`, "Enable auto-update".

License: [MIT](LICENSE).
