# TuotekuvastoApp

TuotekuvastoApp on ASP.NET Core MVC -verkkoalusta, joka näyttää tuotekuvaston.

## Ominaisuudet
- **HomeController**: Hallitsee tuotekuvaston logiikkaa.
- **products.json**: Tallentaa tuotteiden tiedot JSON-muodossa.
- **Product.cshtml**: Näyttää tuotekuvaston Razor-näkymän avulla.
- **JavaScript ja CSS**: Parantaa käyttöliittymää dynaamisella tekstillä ja tyylittelyllä.

## Miten sovellus toimii
1. **HomeController** lukee `products.json`-tiedoston `wwwroot`-hakemistosta.
2. JSON-data deserialisoidaan `Product`-olioiden listaksi.
3. **Product.cshtml** renderöi listan responsiiviseksi tuoteruudukoksi.

## Käyttöönotto
1. Kloonaa repository:
   ```bash
   git clone https://github.com/<Mlein95>/TuotekuvastoApp.git
