Roll call votes data for the Mexican Chamber of Deputies

Author: Eric Magar
email: emagar@gmail.com
Revised: July 8, 2015

This repository in under the MIT License [http://opensource.org/licenses/MIT]. If you use the data, please cite as follows: Francisco Cantu, Scott Desposato, and Eric Magar. 2014. "Consideraciones metodologicas para estudiantes de politica legislativa mexicana: sesgo por seleccion en votaciones nominales". Politica y Gobierno vol. 21, num. 1, pp. 25-54.

Citation in BibTex format
@article{cantuDesposatoMagar2014,
	title = {Consideraciones metodol\'ogicas para estudiantes de pol\'itica legislativa mexicana: sesgo por selecci\'on en votaciones nominales},
	author = {Cant\'u, Francisco and Desposato, Scott and Magar, Eric},
	year = 2014,
	volume = 21,
	number = 1,
	journal = {Pol\'itica y Gobierno},
	pages = {25--54}
}

The main primary source is the Chamber of Deputies' web page at [http://www.diputados.gob.mx/]. Repository contains code, raw data, and clean roll call databases. Code included in the code/ subdirectories allows to download data from the primary source (code/getweb/); prepare databases from raw data (code/rcPrep); and do descriptive analysis and ideal point estimation (code/rcAnalysis/). Raw data downloaded for the 60th (2006-2009), 61st (2009-2012), and part of the 62nd (2012-2015) Legislatures is included in data/fromWeb/ subdirectory. Those interested in clean roll call votes only should direct themselves straight to the data/votesForWeb/ subdirectory. It includes roll call votes of the 60th (2006-2009), 61st (2009-2012), and most of the 62nd (2012-2015) Legislatures in R format and in comma separated characters. 

*Need to add codebook here*.
