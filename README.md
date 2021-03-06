# LMS-Feeder API Documentation

## v.01 - 5-27-2015

###JSON: 

URL: /rest/views/site_feeds.json

```
   {  
      "id":"629",
      "uuid":"9b07823f-6607-492a-8029-68bd76abf46b",
      "type":"Article",
      "title":"Ex Odio Torqueo",
      "dek":"Appellatio caecus defui duis quis vereor. Amet blandit commoveo euismod sino typicus. Odio quidem ulciscor. Amet dolor te.",
      "body":"Brevitas mos pala pertineo praesent uxor. Laoreet mos refoveo. Cogo dignissim genitus modo pneum tego ullamcorper usitas. Commodo neque nibh probo quae saluto. 
Diam lenis loquor nulla quadrum wisi. Ea iusto neo ratis turpis. Abdo autem commoveo iustum nostrud quibus. Blandit elit exerci ille neque tincidunt voco.\n\nDignissim eros eu 
facilisi huic rusticus usitas. Abdo abluo bene lenis nulla nunc scisco sit ulciscor vicis. Aptent distineo facilisi lobortis nibh quis sit vindico. Defui imputo jugis patria 
qui quis valetudo. Dignissim haero meus minim. Damnum iriure lucidus rusticus valetudo ymo. Hos lenis quis virtus voco.\n\nAdipiscing causa cui diam dolor eum pneum ulciscor. 
Causa exputo iriure ludus proprius refero sudo. Abbas persto vulputate. Abigo defui duis lenis nutus usitas volutpat.\n\nAbluo eligo probo validus. Cogo cui eu haero imputo 
interdico jus odio venio. Facilisi praemitto sagaciter uxor. Abico cogo dignissim exerci nibh pala paratus sed te vereor. Cogo eu inhibeo patria populus quidem. Diam esca 
ludus vel verto. Elit exputo iustum mauris neo paratus patria persto populus sagaciter. Acsi brevitas euismod exputo gemino nulla premo turpis. Abluo distineo esca imputo 
typicus valde vereor.\n\nEu feugiat iaceo luctus. Aliquip defui in metuo nibh refoveo suscipere utinam. Euismod fere roto. Commoveo dignissim pneum secundum tation ulciscor 
utrum.\n\nDiam facilisi imputo praemitto qui. Capto enim facilisi utinam. Aptent bene ea immitto iustum laoreet qui quis tamen te. Amet camur elit inhibeo mauris sudo. Acsi 
antehabeo camur diam esca esse hos humo lobortis sudo. Acsi diam eros suscipit. Acsi facilisis loquor voco. Neque suscipit volutpat vulpes.\n\nComis nimis vulpes. Amet bene 
iriure lucidus magna mos tamen velit venio. Esca immitto paulatim sit te velit. Abdo esca hos mos obruo refoveo roto typicus ulciscor. Amet in luptatum nobis probo quidne 
saluto si valde vulpes.\n\nEnim iaceo letalis nibh nulla persto. Antehabeo capto consectetuer in ratis. Adipiscing camur feugiat gemino plaga rusticus secundum sed ut 
valetudo. Cui hos iriure olim rusticus. Bene letalis valetudo virtus.\n\nBene cui ibidem jugis pertineo refero singularis utrum veniam venio. Exputo illum loquor neque ratis 
suscipit valetudo. Caecus genitus magna paulatim praemitto sino. Acsi ad causa consectetuer cui modo os sed valde.\n\n",
      "category":"Health",
      "updated":"2015-05-19  15:42:40",
      "created":"2015-05-19  05:32:07"
   }
```

###XML:

URL: /rest/views/site_feeds.xml

```
<item>
	<id>628</id>
	<uuid>de254bdb-42dd-49a1-83c5-bd5bd490ab00</uuid>
	<type>Article</type>
	<title>Laoreet Saepius</title>
	<dek>
	Consequat interdico jus. Adipiscing enim fere ludus populus quae qui. Antehabeo brevitas esse magna neo patria quibus virtus vulpes. Aptent duis facilisis gilvus 
	letalis 
	patria quae sudo turpis. Aliquam antehabeo augue exerci illum jumentum olim plaga pop
	</dek>
	<body>
	<p>Abdo antehabeo autem gravis nulla pecus plaga premo saluto vindico. Ad feugiat probo suscipit validus velit vero. Augue esse facilisi jumentum natu veniam. At eros 
	esca genitus meus nulla tamen ulciscor verto.</p> <p>Ad dolus jumentum sed valde ymo. Cogo laoreet nulla persto praesent refoveo. Facilisi paulatim quidne suscipit vel. 
	Macto quis si. Adipiscing cogo commodo facilisi humo luptatum molior refoveo suscipere. Immitto lenis letalis. Abigo blandit dignissim iustum meus utrum.</p> <p>Antehabeo autem 
	camur dignissim metuo quidne valetudo. Abdo accumsan aptent enim genitus oppeto scisco sed tincidunt. Antehabeo at defui neo nobis nutus suscipit tincidunt ut. Nisl qui vereor. Hos 
	occuro quis sagaciter. Aptent eu gilvus importunus patria quadrum quae vero. Abbas antehabeo pala rusticus similis velit. Dignissim enim jugis quibus ratis rusticus 
	valde.</p> 
	<p>Appellatio importunus minim nunc nutus olim paratus suscipere vindico. Abdo importunus jus modo natu paulatim quae. Abluo exerci facilisi jumentum obruo quibus sino 
	vereor vicis. Aliquip antehabeo facilisi ibidem incassum obruo sagaciter. Augue enim fere.</p>
	</body>
	<category>Fitness</category>
	<updated>2015-05-19 15:42:40</updated>
	<created>2015-05-19 13:39:41</created>
</item>
```

### Fields

Fields  | Type | Description
-------------|---| -------------
id  | int | Unique id of the piece of content - URL /node/<id>
uuid  | String | Universally Unique ID
type  | String | Content Type
title  | String| Title of the piece of content
dek  | String| Short brief or teaser for the piece of content
body  | String/HTML| Body field of piece of content - HTML
category  | Object| Tag or category that relates the content.  Can have multiple categories.
updated  | String| Timestamp of the last edit to the piece of content*
created  | String| Timestamp of the initial creation of the piece of content*

* This will change to POSIX time ie. 1432419028


## v.02 - 5-29-2015

## JSON:

URL format: <domain>/api/<version>/service/<feed_uuid>.<format>

URL: /api/1/service/83d87723-760b-4808-84eb-4e6c37ca230e.json

```
  {  
      "id":"628",
      "lid":"2342",
      "uuid":"de254bdb-42dd-49a1-83c5-bd5bd490ab00",
      "type":"article",
      "created":"1432057181",
      "changed":"1432064560",
      "title":"Laoreet Saepius",
      "dek":"Consequat interdico jus. Adipiscing enim fere ludus populus quae qui. Antehabeo brevitas esse magna neo patria quibus virtus vulpes. Aptent duis facilisis gilvus letalis patria quae sudo turpis. Aliquam antehabeo augue exerci illum jumentum olim plaga pop",
      "body":"Abdo antehabeo autem gravis nulla pecus plaga premo saluto vindico. Ad feugiat probo suscipit validus velit vero. Augue esse facilisi jumentum natu veniam. At eros esca genitus meus nulla tamen ulciscor verto.\n\nAd dolus jumentum sed valde ymo. Cogo laoreet nulla persto praesent refoveo. Facilisi paulatim quidne suscipit vel. Macto quis si. Adipiscing cogo commodo facilisi humo luptatum molior refoveo suscipere. Immitto lenis letalis. Abigo blandit dignissim iustum meus utrum.\n\nAntehabeo autem camur dignissim metuo quidne valetudo. Abdo accumsan aptent enim genitus oppeto scisco sed tincidunt. Antehabeo at defui neo nobis nutus suscipit tincidunt ut. Nisl qui vereor. Hos occuro quis sagaciter. Aptent eu gilvus importunus patria quadrum quae vero. Abbas antehabeo pala rusticus similis velit. Dignissim enim jugis quibus ratis rusticus valde.\n\nAppellatio importunus minim nunc nutus olim paratus suscipere vindico. Abdo importunus jus modo natu paulatim quae. Abluo exerci facilisi jumentum obruo quibus sino vereor vicis. Aliquip antehabeo facilisi ibidem incassum obruo sagaciter. Augue enim fere.\n\n",
      "category":{  
         "article_category":"Fitness",
         "condition":"Asthma",
         "risk_level":"High"
      }
  }
```

###XML:

URL: /api/1/service/83d87723-760b-4808-84eb-4e6c37ca230e.xml

```
<item>
	<id>628</id>
	<lid>2342</lid>
	<uuid>de254bdb-42dd-49a1-83c5-bd5bd490ab00</uuid>
	<type>article</type>
	<created>1432057181</created>
	<changed>1432064560</changed>
	<title>Laoreet Saepius</title>
	<dek>Consequat interdico jus. Adipiscing enim fere ludus populus quae qui. Antehabeo brevitas esse magna neo patria quibus virtus vulpes. Aptent duis facilisis gilvus letalis patria quae sudo turpis. Aliquam antehabeo augue exerci illum jumentum olim plaga pop</dek>
	<body>Abdo antehabeo autem gravis nulla pecus plaga premo saluto vindico. Ad feugiat probo suscipit validus velit vero. Augue esse facilisi jumentum natu veniam. At eros esca genitus meus nulla tamen ulciscor verto.

	Ad dolus jumentum sed valde ymo. Cogo laoreet nulla persto praesent refoveo. Facilisi paulatim quidne suscipit vel. Macto quis si. Adipiscing cogo commodo facilisi humo luptatum molior refoveo suscipere. Immitto lenis letalis. Abigo blandit dignissim iustum meus utrum.

	Antehabeo autem camur dignissim metuo quidne valetudo. Abdo accumsan aptent enim genitus oppeto scisco sed tincidunt. Antehabeo at defui neo nobis nutus suscipit tincidunt ut. Nisl qui vereor. Hos occuro quis sagaciter. Aptent eu gilvus importunus patria quadrum quae vero. Abbas antehabeo pala rusticus similis velit. Dignissim enim jugis quibus ratis rusticus valde.

	Appellatio importunus minim nunc nutus olim paratus suscipere vindico. Abdo importunus jus modo natu paulatim quae. Abluo exerci facilisi jumentum obruo quibus sino vereor vicis. Aliquip antehabeo facilisi ibidem incassum obruo sagaciter. Augue enim fere.

	</body>
	<category>
		<article_category>Fitness</article_category>
		<condition>Asthma</condition>
		<risk_level>High</risk_level>
	</category>
</item>
```

### Fields

Fields  | Type | Description
-------------|---|-------------
id  | int | Unique id of the piece of content - URL /node/<id>
lid | int | Unique id of the piece of content from legecy site - for linking purposes
uuid  | String | Universally Unique ID
type  | String | Content Type
title  | String | Title of the piece of content
dek  | String | Short brief or teaser for the piece of content
body  | String/HTML | Body field of piece of content - HTML
category  | Object | Tag or category that relates the content.  Can have multiple categories - see table below.
updated  | String | POSIX time
created  | String | POSIX time

### Content Type 

Type | Field | Key
-----|-------|------
article | category | article_category, condition, risk_level


