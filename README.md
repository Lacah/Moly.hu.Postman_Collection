# Moly.hu.Postman_Collection

Minden API-t tartalmaz a Moly.hu dokumentációból (2023 augusztus 8-i állas szerint):

## https://moly.hu/api

Használatához szükség van egy egyedi API kulcs-ra, amit a fenti oldalon igényelhetsz regisztrációt és a használati feltételek elfogadását követően.
Másold be a kulcsot a collection 'personalKey' változójába, majd mentsd el. Innentől kezdve minden API kérésednek része lesz az egyedi kulcsod.

A Könyvadatok, Kiadások, Értékelések és az Idézetek API mind egy köynvazonosítót használ, amit én a 'bookId' változóval helyettesítettem. Ennek értélét szintén a Collection változói közt tudod módosítani, illetve testszés szerint átírhatod egyedileg az endpoint-okban is.

Ugyenezen logika szerint müködik a Szerzőadatok API is, ahol pdig az 'authorId' változót használtam, mely szintén a Collection változói között módosítható.
