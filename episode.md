# Episode Schema

- ID (string, series/<num>/season/<num>/episode/<num>)
- Numbers (array of object)
    - kind (enum, absolute/tv/disk)
    - number (int)}
- Names (array of object)
    - language (string, some ISO code) 
    - name (string)
    - kind (enum, primary/alternate)
- Runtime (int, minutes)
- Aired (datetime, YYYY-MM-DD HH:MM:SS)
- Characters (array of character schema)
- Artworks (array of artwork schema)

