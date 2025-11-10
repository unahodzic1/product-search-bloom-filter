# Efikasno pretraživanje proizvoda uz pomoć Bloom filtera

U okviru ovog rada implementirana je Bloom filter struktura podataka u programskom jeziku Python, s ciljem analize efikasnosti pretraživanja u domenu e-commerce sistema. Korišten je javno dostupan skup podataka koji sadrži opise proizvoda, nad kojim je izvršeno eksperimentalno testiranje vremena pretrage. Mjereno je vrijeme pristupa pri različitom broju hash funkcija (k), te je analiziran uticaj tog parametra na brzinu i tačnost pretrage. Pokazano je da Bloom filter ostvaruje značajno kraće vrijeme pretrage u odnosu na linearnu pretragu nad listom, dok u odnosu na hash strukturu (set) pokazuje nešto manju brzinu, ali veću memorijsku efikasnost.

---

# Tehnologije i okruženje
- Python 3.12.12
- Google Colab
