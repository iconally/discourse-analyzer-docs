# discourse-analyzer-docs

Dokumentų saugykla **atskirai** nuo Streamlit aplikacijos ([discourse-analyzer](https://github.com/iconally/discourse-analyzer)).

## Struktūra (siūloma)

- `corpus/` — šaltinio tekstai (.txt, .docx)
- `policy/` — politiniai / norminiai dokumentai
- `terms/` — žodynų CSV ir watchlist failai
- `exports/` — analizės išvestys (CSV, ataskaitos)

## Įkėlimas

Naršyklėje: **Add file** → **Upload files**, arba kelias su aplanku, pvz. `policy/2021-06-Data-Security-Law_CN.txt`.

Šis repozitorijus **nepaleidžia** Streamlit app — tik saugo failus.
