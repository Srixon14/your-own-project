
![Ironhack logo](https://i.imgur.com/1QgrNNw.png)

# Project 4

The topic of my project is the threatened/endangered animal species of all over the world.
The goal is to study and analyze how we humans are extinguishing entire species of animals that have been around for millions of years (much more than us).

-how many individuals of each theatened species are left?
-Which species are the most threatened?
-How have their number evolved during the last years?
-Which have already been extincted?
-What can we humans do to stop this extermination?
-Which endangered species have lately increased their number and why?
-Which are the countries with more threatened species?

I will try to answer not only these but also many other questions regarding this issue, and make everyone who sees my presentation aware of it.

Regarging the data, I've already found some datasets which I think I will be able to work with. There are some csv files and some APIs as well.


-hipotesis: contaminacion, poblacion, etc. afecta? hipotesis y contrastarla...

-Añadir yo a mi main bbdd las filas con los animales q no esten (sacarlos de webs de top10 animales amenazados etc)

-Añadir graph comparison de poblacion humana vs threatened species o algo asi ->> pie plot (todo humanos), en la Slide añadir dato: sumando todos los individuos de todas las especies amenazadas, el ratio es de 70,000 humanos a 1 threatened specie

-centrarme en mamíferos? o en top 10 o whatever?

-añadir tabla de STATUS scale: Critically endangered, vulnerable, etc y comentar q el termino threatened engloba CE, EN y VU

-evolucion numero de especies amenazads ultimos años por categoria (mamiferos, anfibios...)

-plot mapamundi con colores (cuanto mas oscuro mas especies amenzadas, por ejemplo)

- 1223 de las 5792 especies de mamíferos de la Tierra están amenazadas de extinción. 76 especies por lo menos se han extinguido desde 1500. No obstante, los resultados muestran también que determinadas especies que se encuentran al borde de la extinción pueden recuperarse; el 5% de los mamíferos actualmente amenazados muestran señales de recuperación en estado silvestre.

-Sources: web scrappling: IUCNredlist.org, ourendangeredworld.com, worldwildlife.org, data.worldbank.org...
          API: tried to but did not get any answer
          
-al no tener acceso a la API he tenido muchos problemas con las sources: resulta que prácticamente toda la data interesante y de valor que pude obtener estaba en formato pdf, lo cual me ha causado grandes problemas ya que lo unico q podia hacer era copy paste en un excel y trabajar a partir de ahi, pero quedaba super sucia y muy dificil de limpiar


lo que tengo en tablas (pandas): -totals de CR, EN y VU desde 2000 hasta 2019 divididos por mammals, birds, etc. (evolucion)
                                 -total species de mammals, birds, etc. vs total de threateneds
                                 -thereatened species de mammals, birds etc por pais (y total)
                                 -poblacion de cada pais
                                 -individuals left for some of the most threatened species
