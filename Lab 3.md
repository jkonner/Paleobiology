Paleobiology lab 3
Joshua Konner
2/8/16

> 16.6/20

1)	There are 704 collections associated with the paper.
2)	The reference ID is 24429.

1)	The significance of the citation is that is the name of the person who named the species and first described it by its scientific name.  The date is the year in which that occurred.
2)	Class: Strophomenata, Order: Strophomenida, family: Strophomenidae, genus: Strophomena, species: planumbona
3)	The data was collected in Union County.
4)	The data comes from the Ordovician period.
5)	The data comes from the Liberty formation.

1) The different colors signify different time ranges.  The orange dots are older than the yellow ones, unless the yellow is referring to the Cenozoic, which encompasses both.  Orange refers to the paleogene and yellow refers to the neogene.  This gets more specific for different shades of each breaking down to the epochs and stages.

2) Abra occurs in the Ypresian stage in the United States of America, United Kingdom, and Belgium

3) Cincinnati has the most occurrences of Ambonychia.

4) Most Ambonychia occurrences are in the Ordovician period.

1) In the Ordovician period, most occurences of <strike>the</strike> Ambonychia were arrayed parallel to the equator.
2) The Ambonychia belongs to the Myalinida order.

1) https://paleobiodb.org/data1.2/occs/list.json?datainfo&rowcount&base_name=Ambonychia&strat=Lexington Limestone
2) https://paleobiodb.org/data1.2/occs/list.csv?datainfo&rowcount&base_name=Mammalia&interval=Paleocene,Oligocene
3) https://paleobiodb.org/data1.2/taxa/opinions.csv?datainfo&rowcount&base_name=Testudines&interval=Mesozoic
4) https://paleobiodb.org/data1.2/colls/list.csv?datainfo&rowcount&base_name=Aves, Marsupialia, Sirenia&cc=US
5) <strike>https://paleobiodb.org/data1.2/occs/list.csv?datainfo&rowcount&base_name=Ficus&taxon_reso=genus&cc=US</strike> 

> https://paleobiodb.org/data1.2/occs/list.csv?datainfo&rowcount&base_name=Gastropoda:Ficus&taxon_reso=genus&cc=US, -1 points

1)	The Gastrocopta genus is in the Gastrocoptidae family.
2)	The Isoetes in Portugal is from the Aptian age, ~113–~125 Ma.
3)	The oldest Gastrocopta comes from the Bridgerian age, 50.3 - 46.2 Ma
4)	The Tiktaalik was found in present day Nunavut, Canada, which was <strike>locatred</strike> located in the tropics in the Devonian period.
5)	The Namacalathus occurences are from the Kotodzha formation and Raiga formation.


1)
````R
URL<-"https://paleobiodb.org/data1.2/colls/list.csv?base_name=Mammut&interval=Pliocene"
Data<-read.csv(URL,row.names=1)
````

2)
```R
dim(Data)
[1] 39 12
````

> -1 points because you did nnot answer

3) The above call used collections.

4) The genus being called is Mammut, which is colloquially known as the Mastodon.  The age was limited to the Pliocene.  

5) 
````R
URL<-"https://paleobiodb.org/data1.2/colls/list.csv?base_name=Mammut&interval=Miocene,Pleistocene"
````

> -1 points because you did not answer

6) 

````R
URL<-"https://paleobiodb.org/data1.2/colls/list.csv?base_name=Mammut&interval=Miocene,Pleistocene&show=paleoloc"
````

> -1 points because you did not answer

1)	In the PaleoDB, you can look at morphology of the species.  This shows mean shell width, height, and diameter- the statistics given about the ammonite samples from lab two.  Standard deviations are also given.  Using this, you can look at what species falls under which morphologic data.

> I was looking for something in depth, but I suppose the instructions were not sufficiently explicit. 

2)	This species was named by Brayard and Bucher in 2008.  The name of the article is: “Smithian (Early Triassic) ammonoid faunas from northwestern Guangxi (South China)”

3)	Speciemens 8,20, and 21 appear to be of the speices Xenoceltites variocostatus

> Based on what criteria? It would really help if you explain your answers, otherwise it's impossible to give partial credit.

-2 points
