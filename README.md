# Pub Svilenkovic Com

Source kod sajta ugostiteljskog objekta (meni, porudzbine, galerija, kontakt) optimizovan za brz static/PHP deploy.

## Tehnologije

- HTML/CSS/JavaScript
- PHP fallback (`default.php`, `maintenance.php`)
- SEO (`robots.txt`, `sitemap.xml`)

## Klucne stranice

- `index.html`: pocetna
- `meni.html`: ponuda
- `porudzbine.html`: porudzbine
- `o-nama.html`: o lokalu
- `galerija.html`: galerija
- `kontakt.html`: kontakt

## Lokalni pregled

```bash
php -S 127.0.0.1:8080
```

## Live Preview

- https://www.nosatipub.rs

## Operativne napomene

- Posle vecih izmena proveri sve navigacione linkove izmedju stranica.
- Odrzavaj SEO fajlove (`robots.txt`, `sitemap.xml`) u skladu sa finalnim URL-ovima.
- Ako se koriste forme/porudzbine, validiraj backend endpoint pre deploy-a.
