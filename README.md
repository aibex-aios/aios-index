# aios-index

Index der Pakete des Hubs `aibex-aios` für AIbex AIOS. `aios --library [<suchwort>]` liest `index.yaml` und sucht darin in Namen und Beschreibungen; die Versionen eines Pakets kommen aus den Tags seines Repos (`aios --library <paket>`).

```yaml
schema: 1
packages:
  - name: <paket>
    type: skill | assistant | knowledge | app | tutorial | distribution
    description: <ein Satz>
```

Der Index dient nur der Suche. Ein Paket, das hier fehlt, lässt sich mit seinem Namen trotzdem holen (`aios --fetch <paket>`). Neue Pakete kommen als Pull Request.
