# Efikasno pretraživanje proizvoda uz pomoć Bloom filtera

U okviru ovog projekta implementirana je Bloom filter struktura podataka u programskom jeziku Python, s ciljem analize efikasnosti pretraživanja u domenu e-commerce sistema. Korišten je javno dostupan skup podataka koji sadrži opise proizvoda, nad kojim je izvršeno eksperimentalno testiranje vremena pretrage. Mjereno je vrijeme pristupa pri različitom broju hash funkcija (k), te je analiziran uticaj tog parametra na brzinu i tačnost pretrage. Pokazano je da Bloom filter ostvaruje značajno kraće vrijeme pretrage u odnosu na linearnu pretragu nad listom, dok u odnosu na hash strukturu (set) pokazuje nešto manju brzinu, ali veću memorijsku efikasnost.

---

# Tehnologije i okruženje

- Python 3.12.12
- Google Colab

# Skup podataka

Za eksperimentalni dio projekta korišten je [E-commerce Data](https://www.kaggle.com/datasets/carrie1/ecommerce-data) dataset, preuzet sa platforme Kaggle.

## Korištena literatura

1. Broder, A., & Mitzenmacher, M. *Network Applications of Bloom Filters: A Survey*.  
2. Blustein, J., & El-Maazawi, A. *Bloom Filters: A Tutorial, Analysis, and Survey*.  
3. Rottenstreich, O., & Keslassy, I. *The Bloom Paradox: When Not to Use a Bloom Filter?*.  
4. Luo, L., Guo, D., Ma, R. T. B., Rottenstreich, O., & Luo, X. *Optimizing Bloom Filter: Challenges, Solutions, and Comparisons*.


---

# Autori

| Ime i prezime | GitHub profil | Email |
|----------------|---------------|--------|
| **Nađa Kovačević** | [nkovacevic3](https://github.com/nkovacevic3) | nkovacevic3@etf.unsa.ba |
| **Una Hodžić** | [unahodzic1](https://github.com/unahodzic1) | uhodzic1@etf.unsa.ba |


Elektrotehnički fakultet Univerziteta u Sarajevu

Akademska godina: 2025/2026


