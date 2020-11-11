# TV Show Schema

- ID (string, series/{num})
- Names (array)
    - language (string, some ISO code)
    - name (string)
    - kind (enum, primary/alternate)
- OriginalCountry (string, some ISO code)
- OriginalLanguage (string, some ISO code)
- Characters (array of character schema)
- Artworks (array of artwork schema)
- Seasons (array of season schema)

