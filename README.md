Roll call votes data for the Mexican Chamber of Deputies

Author: Eric Magar
email: emagar@gmail.com (emagar at gmail.com)
Revised: July 8, 2015

This repository in under the MIT License [http://opensource.org/licenses/MIT]. The sole condition to use the data is to cite it as follows: Francisco Cantu, Scott Desposato, and Eric Magar. 2014. "Consideraciones metodologicas para estudiantes de politica legislativa mexicana: sesgo por seleccion en votaciones nominales". Politica y Gobierno vol. 21, num. 1, pp. 25-54.

*Citation in BibTex format*
``` TeX
@article{cantuDesposatoMagar2014,
	title = {Consideraciones metodol\'ogicas para estudiantes de pol\'itica legislativa mexicana: sesgo por selecci\'on en votaciones nominales},
	author = {Cant\'u, Francisco and Desposato, Scott and Magar, Eric},
	year = 2014,
	volume = 21,
	number = 1,
	journal = {Pol\'itica y Gobierno},
	pages = {25--54}
}
```

*Description*

The main primary source is the Chamber of Deputies' web page at http://www.diputados.gob.mx/. Repository contains code, raw data, and clean roll call databases. Code included (in the code/ subdirectories) replicates data downloading from the primary source (code/getweb/); databases preparation from raw data (code/rcPrep); and descriptive analysis and ideal point estimation (code/rcAnalysis/). Raw data downloaded for the 60th (2006-2009), 61st (2009-2012), and part of the 62nd (2012-2015) Legislatures is included (in the data/fromWeb/ subdirectory). **Those interested in clean roll call votes only should direct themselves straight to the data/votesForWeb/ subdirectory**. It includes roll call votes of the 60th (1sep2006-31aug2009), 61st (1sep2009-31aug2012), and most of the 62nd (1sep2012-7oct2014) Legislatures. Data is in R (http://cran.r-project.org/) and csv formats. 

*Codebook*

The objects in each R file (zipped together in text-only files) are the following:

-dipdat: individual federal deputy information (nom=name, id=district, part=party, 
 edo=state, edon=state number, dsmd=indicates single-member district deputies, 
 dis=district number, tipo=propietario or suplente)

-votdat: vote information (favor=ayes, contra=nays, absten=abstained,
 quorum=present but not voting, ausen=no show, title=motion considered, 
 leg=legislature, yr-mo-dy=vote's date)

-rc: roll call vote information (0=was not chamber member, 1=aye,
 2=nay, 3=abstained, 4=present but did not vote, 5=no show)

-dgaceta: indicates whether or not the vote was also reported by the
 Gaceta Parlamentaria (http://gaceta.diputados.gob.mx/), as discussed 
 by Cantu, Desposato, and Magar 2014.

