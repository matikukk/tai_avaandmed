# tai_avaandmed
PoC avaandmete laadimiseks TAI avaandmete keskkonnast
Kasutame Google Colabi ja DuckDBd selleks, et andmeid kättesaada (loader) ja näidata.
Kogu rakendus on 2 Yupiter notebooki

# /loader
**proovitoo.ipynb**
Käivitamiseks teita oma draivi Colab_TAI_Andmed kataloog või eemalda viide failile 
engine = create_engine(f'duckdb:///{db_path}') asemel engine = create_engine() siis on täiesti stateless in-memory lahendus.

vajuta nuppu ja sa saaks mängida sellega 
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/matikukk/tai_avaandmed/blob/main/loader/proovitoo.ipynb)

# /client
**tai_avaandmete_päringud.ipynb**
vajuta nuppu ja sa saaks mängida sellega
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/matikukk/tai_avaandmed/blob/main/client/tai_avaandmete_päringud.ipynb)

# /data
Siin kataloogis on on TAI veebist alla laetud columnar andmed parquet vormingus
