# SearXNG-Web-Exstension (search.stefan-schmieder.net)
**SearXNG** ist eine kostenlose Internet-Metasuchmaschine, die Ergebnisse aus verschiedenen Suchdiensten und Datenbanken aggregiert. Benutzer werden nicht getrackt oder profiliert.

[**SearXNG**](https://github.com/searxng/searxng) is a fork of [**SearX**](https://github.com/searx/searx).

[**Original SearXNG repository on GitHub**](https://github.com/searxng/searxng)

# Wie funktioniert es?
Diese Erweiterung bedient sich `manifest.json`, um Ihre Standardsuchmaschine zu ändern.

Beispiel:

(**Standardeinstellungen**)
```json
{
  "chrome_settings_overrides": {
    "search_provider": {
      "search_url": "https://example.com/search?q={searchTerms}"
    }
  }
}
```

(**Mit addon**)
```json
{
  "chrome_settings_overrides": {
    "search_provider": {
      "search_url": "https://search.stefan-schmieder.net/search?q={searchTerms}"
    }
  }
}
```

Dies bedeutet, dass Ihr Browser beginnt, den zweiten Link zu verwenden, wenn Sie eine Suchanfrage stellen.

Wenn Sie **SearXNG** als neue Standardsuchmaschine verwenden möchten, tun Sie dies:
- fügen Sie dieses Addon zu Ihrem Browser hinzu
- zustimmen, wenn der Browser "Diese Erweiterung hinzufügen?"
- widersprechen, wenn der Browser "Möchten Sie Ihre Suchmaschine ändern?"
- Verwenden Sie Schlüsselwörter wie `@searxng, @searx, @sx`, wenn Sie **SearXNG** verwenden möchten, wenn Sie eine Anfrage stellen

# Contributors
[**Rodion Borisov**](https://github.com/vintprox) - found `"suggestion_url"` and etc.  
[**Ivan Muzyka**](https://github.com/SeryiBaran) - found icons and etc.