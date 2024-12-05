# test-MO
link gita:
https://github.com/Mopacak/test-MO.git


Upit: 
SELECT z.ime_prezime, SUM(e.broj_sati) AS ukupno_sati
FROM evidencija e
JOIN zaposlenik z ON e.zaposlenik = z.id
WHERE z.id = 1  
GROUP BY z.ime_prezime;



