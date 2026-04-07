# Local development (Jekyll + GitHub Pages)

## Setup iniziale

Dalla root del repository:

```bash
bundle install
```

Se necessario (tema remoto):

```bash
bundle add jekyll-remote-theme
```

---

## Avvio server locale

```bash
bundle exec jekyll serve --livereload
```

Apri nel browser:

```
http://localhost:4000
```

---

## Workflow corretto

- Modifica i file localmente
- Visualizza le modifiche su `localhost:4000`
- Il sito si aggiorna automaticamente (livereload)

Quando sei soddisfatto:

```bash
git add .
git commit -m "update"
git push
```

---

## Note importanti

- Non usare `http://localhost:4000` nel terminale → va aperto nel browser
- `bundle exec` usa le dipendenze locali del progetto
- Se ci sono errori → controlla `Gemfile` e `_config.yml`

---

## Problemi comuni

Errore:

```
cannot load such file -- jekyll-remote-theme
```

Soluzione: aggiungere nel `Gemfile`:

```ruby
gem "jekyll-remote-theme"
```

poi:

```bash
bundle install
```