# LatvianPeriodicals_OCR
Experiments with periodicals published on the territory on modern Latvia in various languages (Latvian, Russian, Latgalian, German)

# Periodicals in Latgalian

Largely based on (http://data.lnb.lv/digitala_biblioteka/laikraksti/index3.htm):

* Gaisma, 1905-1906

* Sākla, 1906

* Auseklis, 1906-1907

[Available issues] (http://periodika.lv/#periodicalMeta:1539;-1](http://data.lnb.lv/nba01/Auseklis/1906/)

* Drywa, 1908-1917

[Available issues] (http://periodika.lv/#periodicalMeta:1539;-1]()
	
* Drywa : Gorīgajs pīlykums, 1912-1913

[Available issues] (http://periodika.lv/#periodicalItem:1660)
	
* Drywa : Ziniskajs pīlykums, 1912-1913
	
* Drywa : Pielikums Gorīga Maize, 1914-1917 
	
* Drywa : Pielikums Orōjs, 1914-1915
	
* Jaunas Zinias, 1912-1914
  
* Liaužu Bolss, 1917

* Jaunō Drywa, 1918
	
* Jaunō Letgola, 1918
	
* Latgalīts, 1920 - 1926
	
* Jaunō Straume 1921-1934
	
* Zemnīka Bolss, 1924-1926
   
* Zemnīka Ziņas, 1926-1931

* Latgalīts, 1920-1926

* Jaunais Wōrds, 1931-1940

* Latgolas Wōrds, 1920-1940

* Latgolas Dorbs, 1924-1934

* Latgolas Socialdemokrats, 1928


# Periodicals in Russian

## Russian Empire

* Курляндские губернские ведомости = Kurländische Gouvernements Zeitung, 1852-1915

[Available issues] (http://periodika.lv/#periodicalMeta:1539;-1)

NB: incorrectly chosen models for later issues (German instead of Russian)

* Rīgas Pilsētas Policijas Avīze = Ведомости Рижской Городской полиции, 1889-1902 (not all years available)

Trilingual; good Latvian and German OCR, poor Russian OCR (in modern orthography, many errors)

[Available issues](http://periodika.lv/#periodicalMeta:358;-1)

* Лифляндские губернские ведомости = Livländische Gouvernements-Zeitung = Vidzemes Guberņas Avīze

Poor quality OCR recognition; multilingual texts

[Available issues](https://dea.digar.ee/cgi-bin/dea?a=cl&cl=CL1&sp=livzeitung&l=en)

[Issues published in 1905](http://datatest.lnb.lv/digitala_biblioteka/laikraksti/VidzGubAvize/index.htm)


* Рижское Обозрѣніе, 1915-1917

OCR layer with old orthography symbols available 

[Available issues (the main corpus)](http://periodika.lv/#periodicalMeta:1683;-1)

[Available issues (8 more)](http://periodika.lv/#periodical;id=26633521346598475474666534128088861199)


* Рижский Вестник, 1869-1917

OCR layer with old orthography symbols available 

[Available issues] (http://periodika.lv/#periodicalMeta:1728;-1)

[Available issues](http://datatest.lnb.lv/digitala_biblioteka/laikraksti/RizskijVestnik/index.htm)

* Рижское утро, 1915-1917

OCR layer with old orthography symbols available 

[Available issues](http://periodika.lv/#periodicalMeta:1685;-1)

## Independent Latvia (interwar)

* Вера и жизнь, 1923-1940

[Available issues](http://periodika.lv/#periodicalItem:1734)

* Вечернее время

OCR layer with old orthography symbols available 

[Available issues](http://periodika.lv/#periodicalItem:1686)

* Для вас

NB: poor Russian OCR (in modern orthography, many errors)

[Available issues](http://periodika.lv/#periodicalItem:673)

* Голос народа : вестник Русской крестьянской фракции Сейма

[Available issues](http://periodika.lv/#periodicalMeta:276;-1)

* Сегодня, 1919-1940

[Available issues](http://periodika.lv/#periodicalItem:276)

# Useful tools/libraries

Tesseract, OCRopus (add links)

https://github.com/KBNLresearch/ochre - postprocessing (NB: prepare GT data first)

https://github.com/ktodorov/eval-historical-texts - postprocessing (using BERT embeddings)

https://github.com/TurkuNLP/ocr-correction (poorly documented)

https://github.com/kak-to-tak/Google_rusngram_spellcheck - a spellchecker for old Russian orthography (based on n-grams)

https://github.com/dhhse/prereform2modern - a converter for old Russian orthography

https://github.com/tberg12/ocular - Ocular, a state-of-the-art (at least in the past) system for historical OCR

https://github.com/cisocrgroup/OCR-Workshop - materials from the workshop "OCR and postcorrection of early printings for digital humanities"

http://cistern.cis.lmu.de/ocrocis/ - a wrapper for OCRopus


