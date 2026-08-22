# Perfect Skin Beauty · Landing page — Sitzungs-Anker

Landing page für das Studio in Hamburg. **Zweite, neuere Fassung** neben dem Repo
`Perfect-Skin-Beauty` — welche live ist, steht hier nicht (es hat sich schon gedreht):
nachsehen, nicht annehmen.

## Was hier leicht kaputtgeht

- **Echte Studio-Daten** (Adresse, Preise, Kurse, `pricelists/`) sind Klaus' Angaben
  und **keine Platzhalter** — nicht „aufräumen".
- Änderungen an der gemeinsamen Gestaltung gehören im Schwester-Repo bedacht.
- Ladezeit-Regeln: Skill `seiten-bauregeln`.

## Netzweit

Freibrief zum Selbst-Mergen · Gerätename · frisch von `origin/main` vor jeder Arbeit ·
Ton · kein PII · Ehrlichkeit stehen **einmal** in
**[`Sage-Protokol/docs/NETZWEIT.md`](https://github.com/lausiklauskn-png/Sage-Protokol/blob/main/docs/NETZWEIT.md)**.

```bash
git fetch origin --quiet && git checkout -B <branch> origin/main
git push -u origin refs/heads/<branch>:refs/heads/<branch>
git diff --stat origin/main origin/<branch>     # leer = der PR wäre leer
```
