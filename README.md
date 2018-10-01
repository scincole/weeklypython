# Nem monthy python, nem monthly python, hanem weekly python

A cégnél minden héten összejövünk egy kicsit másfél órára, hogy kimozduljunk a komfortzónánkból, programozási feladatokat oldjunk meg, és közben tanuljuk a problémamegoldás szépségeit és a python rejtelmeit. 

Ebben a repóban található leckékhez a következőket kell installálni, letölteni, ilyesmik:

## GIT
https://git-scm.com/downloads

Verziókezelő rendszer, a legnyitottabb, a legelérhetőbb, a legelterjedtebb

A leckéket aztán le lehet tölteni vele parancssorból:

```git clone https://github.com/keszegrobert/weeklypython.git```

## Python
https://www.python.org/downloads/

A gyakorlatok anyagai python3 alatt íródtak, viszont nem vetjük meg a python 2-t, még nagyon sok hasznos lib-et nem írtak át python3 alá, nem látom értelmét, hogy küzdjünk a szélmalmokkal.

## Jupyter 
https://jupyter.org/

### Install
```
$pip install jupyter
```

Tanításra, kód részletek újrafuttatására nagyon jó kis eszköz, sok python-os videóban láttam használni, sok-sok előnye van a parancssorral szemben, főleg a grafikai és interaktív lehetőségeit emelném ki. Láttam és készítettem már jupyter notebookban táblázatokat, grafikonokat, képeket, 3d-s interaktív grafikákat, térképet, további infók itt: https://jupyter.org/widgets

### Indítás
```
jupyter notebook
```

Ilyenkor elindul egy lokális szerver, ami értelmezi és végrehajtja az egyes cellákban lévő kódot, és a kód futásának eredményét kirakja az éppen lefuttatott cella alá (több nyelvhez létezik jupyter-es interpreter, nem csak pythonhoz). 
Ahhoz tehát, hogy elindítsunk egy tetszőleges kódrészletet, elég a böngészőbe beírni a kódunkat, és lefuttatni egy Shift+Enter lenyomásával, majd várni pár ezredmásodpercet, hogy visszajöjjön a szervertől az eredmény. Nincs kontextusváltás tehát, nem kell az ablakok között váltogatnunk, és látjuk azonnal a kódunk alatt az eredményt. Sőt, az interpreter megjegyzi az adott notebook-on belül inicializált változóinkat is, aminek az egyik cellában értéket adunk, azt a másik cellában használhatjuk.

A jupyter ismeri a github-on is használt Markdown language-et, amivel szöveget tudunk formázni. A kódunkhoz tehát írhatunk értelmes kommenteket, akár grafikákat is beültethetünk, valamint táblázatokkal és linkekkel is elkápráztathatjuk notebookjaink későbbi csodálóit. Továbbiak itt: https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet


## Egyéb
A python nyelvnek vannak furcsaságai is, lásd: https://github.com/satwikkansal/wtfpython


