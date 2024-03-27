# GWAS - PMC10602383

## Tvoj tim sakuplja podatke o varijantama nađenim u GWAS radovima. Tebi su dali zadatak da pogledaš PMC10602383. Rešiti dole izlistane zadatke.

1. Na koje pojmove treba da obratimo pažnju kad tražimo kvalitetan GWAS?
```text
Rešenje:
    
```
2. Pročitati rad i napisati sažetak rada. Neka sažetak ima do 5 rečenica. 
```text
Rešenje:
    
```
3. Koje varijante se nalaze, a koje se ne nalaze u fajlu "***previously_studied_variants.txt***"?
```text
Rešenje:
    
```
4. Popuniti JSON fajl podacima varijanti. Fajl nazvati "***PMC10602383_variants.json***".

    Bitni podaci: SNP, Effect Allele, Frequency, Effect Size, Gene, P-value u naucnom zapisu (baza + eksponent, npr. 1.23e-10).

```text
Primer JSON fajla:
[
    {
        "snp": "rs27032024",
        "allele": "G",
        "frequency": 0.85,
        "effectSize": 0.0219,
        "gene": "NFU1P2",
        "statisticalSignificance": {
            "base": 1.57,
            "exponent": -10
        }
    },
    ...
]
```
5. Ažurirati "***previously_studied_variants.txt***" novim varijantama.
5. Da li se ovaj proces može potpuno ili semi automatizovati? Ako je odgovor "da", ponuditi rešenje. Rešenje ne mora biti nužno tačno i potpuno.
```text
Resenje:

```

## Materijali:
- [PubMed Central - PMC10602383](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC10602383/)  
- [PDF - PMC10602383.pdf](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC10602383/pdf/pgen.1010977.pdf)
- [previously_studied_variants.txt](https://raw.githubusercontent.com/NovakPersida/GWAS_Testing_Task/main/previously_studied_variants.txt)

## Rad i predaja:
- Tekstualna rešenja zadataka napisati u ovaj fajl.
- Sve korišćene i rezultujuće fajlove upakovati u ZIP fajl, pa poslati na mejl (nevena.vucinic@persida-bio.com)
- Rok za predaju je sreda, 27.03.2024. do 15:00.