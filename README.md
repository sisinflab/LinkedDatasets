# LinkedDatasets

## Datasets linked to Linked Open Data knowledge Graphs

The _LAST.FM_ dataset corresponds to user-artist plays on Last.fm online music system released during [HETRec 2011](http://ir.ii.uam.es/hetrec2011/) Workshop. It contains social networking, tagging, and music artists listening information from a set of 2K users. _LibraryThing_ represents books' ratings collected in the LibraryThing website\footnote{\url{https://www.librarything.com/}} community. It contains social networking, tagging and rating information on a [1..10] scale. _Yahoo Movies_ ([Yahoo! Webscope dataset ydata-ymovies-user-movie-ratings-content-v1\_0](http://research.yahoo.com/Academic\_Relations)) contains movies ratings generated on Yahoo! Movies up to November 2003. It provides content, demographic and ratings information on a [1..5] scale, and mappings to \movielens and _EachMovie_ datasets. _Facebook Movies_, _Facebook Music_ and _Facebook Books_ datasets have been released for the [Linked Open Data challenge co-located with ESWC 2015](https://2015.eswc-conferences.org/program/semwebeval.html), and they refer to movies, music and books domains respectively. Only implicit feedback is available for these datasets, but for each item a link to DBpedia is provided. In order to map items in _LAST.FM_ and _LibraryThing_ to _DBpedia_ resources, we exploited a [freely available mapping](https://github.com/sisinflab/LODrecsys-datasets). For the remaining one (_Yahoo Movies_),  we extracted all the updated items-features mappings (_Yahoo Movies_, _LibraryThing_,_LAST.FM_, _Facebook Movies_, _Facebook Music_ and _Facebook Books_).

Datasets statistics are shown in Table.

![Datasets Statistics](https://github.com/vitowalteranelli/LinkedDatasets/blob/master/imgs/datasetsStatistics.png)

## Reference
If you publish research that uses LinkedDatasets please use:
~~~
This work is currently under review
~~~
The full paper describing the overall approach WILL BE available here [PDF](link)


## Credits
This algorithm has been developed by Vito Walter Anelli and Joseph Trotta while working at [SisInf Lab](http://sisinflab.poliba.it) under the supervision of Tommaso Di Noia.  

## Contacts

   Tommaso Di Noia, tommaso [dot] dinoia [at] poliba [dot] it  
   
   Vito Walter Anelli, vitowalter [dot] anelli [at] poliba [dot] it 
   
   Joseph Trotta, joseph [dot] trotta [at] poliba [dot] it 
