# FuelMe Terensko

## Struktura repozitorija

```text
.
├── README.md
├── .gitattributes
├── dokumentacija/
│   ├── 1_FuelMe_Opis_projekta.docx
│   ├── 2_FuelMe_UML_in_scenariji.docx
│   └── 3_FuelMe_Arhitektura_baze_CRUD.docx
└── prototip/
    └── index.html
```

## Predvidene mape za implementacijo

```text
.
├── aplikacija/                 # Skupni projekt Flutter za Android in splet
│   ├── lib/                    # Zasloni, modeli in odjemalec API-ja
│   ├── android/
│   ├── web/
│   └── test/
├── api/                        # PHP REST API
│   ├── public/                 # Javna vstopna točka API-ja
│   └── src/                    # Prijava, zaloga in prodaja
└── podatkovna-baza/
    └── migracije/              # SQL za strukturo baze MariaDB
```
