

Projekti omanik

tiim TARTU

Tiim TARTU liikmed

| Nimi | github kasutaja |
| --- | --- |
| Airika Vettik | AirikaVettik |
| Ilja Akulenko | akulenkoilja |
| Ingri Jufkin | IngridJufkin |
| Kevin-Anders Kalamees | Kevinanders0 |
| Ragne Samson | ragne989 |
| Vaire Riiet | Vaire444 |


## Iseseiseva töö kirjeldus

1. Luua andmebaas mongo atlas lehel (Võib ka mujal või ise hostida)
2. Mõtle välja andmebaasi schema (struktuur) mongoose schema kujul (näiteks: https://github.com/erlendprikss/expressmongoosedemo/blob/main/src/models/users.model.js). Andmebaas võiks miinimum sisaldada kolme tabelit – Products, Orders, Users.
3. Loo järgnevad api endpointid nodejs keskkonnas:
   - Kasutaja loomine
   - Uue toote loomine 
   - Kõigi toodete kätte saamine
   - Kindla toote või toodete filtreerimine sisend parameetritega (nt nimi vms)
   - Ühe toote kuvamine _id järgi
   - Ühe toote muutmine _id järgi
   - Ühe toote kustutamine _id järgi
   - Luba sisestada tooteid ainult ühel kindlal Users tabelis oleval kasutajal
   - Lisa uus tellimus (Tellimus schema võiks sisaldada tootedete id-sid millega nad seotud on, tellimuse numbri genereerimine javascript abiga. Võib olla lihtsalt 1,2,3 jne)
   - Kõigi tellimuste kätte saamine
   - Kindla tellimuse või tellimuste filtreerimine sisend parameetritega (nt kasutaja)
   - Ühe tellimuse kuvamine _id järgi (Vastus peaks sisaldama ka kogu seotud toodete infot)
   - Ühe tellimuse muutmine _id järgi
   - Ühe tellimuse staatuse muutmine
     -  näiteks nagu: ``` OFFER, WAITING_FOR_PAYMENT, IN_MAIL, DONE ```
