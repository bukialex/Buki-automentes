# Buki Autómentés 0-24

Statikus weboldal (fekete–sárga dizájn).

## Struktúra
```
.
├─ index.html
└─ assets/
   ├─ gallery1.jpg
   ├─ gallery2.jpg
   ├─ gallery3.jpg
   └─ gallery4.jpg
```

## Használat
Nyisd meg a `index.html` fájlt böngészőben.

## Deploy Netlify-ra (GitHub-ról)
1. Push-old ezt a repót GitHub-ra (pl. `buki-automentes-site`).
2. Netlify: **Add new site → Import from GitHub**.
3. Válaszd ki a repót.
4. Build command: *nincs* (hagyj üresen).
5. Publish directory: `/` (gyökér).
6. Domain management: add hozzá a saját domainedet, `www`-re CNAME a Netlify app domainre, rootra A rekordok (75.2.60.5, 99.83.190.102).
