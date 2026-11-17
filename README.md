# gamez85-studio.github.io

Web de desarrollador de gamez85, servida por GitHub Pages en
https://gamez85-studio.github.io. Es la "Website" de la ficha de desarrollador
en Google Play, así que AdMob lee `app-ads.txt` de aquí.

| Archivo | Para qué |
| --- | --- |
| `index.html` | Portada: juegos y contacto. Se edita aquí. |
| `app-ads.txt` | Autoriza a AdMob a vender los anuncios de las apps. |
| `simple-shooter/` | Política de privacidad, términos e icono de Simple Shooter. |

Lo de `simple-shooter/` y `app-ads.txt` **no se edita aquí**: se escribe en el
proyecto SimpleShooter (`store-assets/android/`) y se copia con
`npm run site:sync`. Después:

```
git add -A
git commit -m "Update Simple Shooter pages"
git push
```

GitHub Pages publica el cambio en uno o dos minutos. Cada juego nuevo tendrá
su propia carpeta junto a `simple-shooter/`.
