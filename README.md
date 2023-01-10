# vaccine covid19


id	user_name	user_location	user_description	user_created	user_followers	user_friends	user_favourites	user_verified	date	text	hashtags	source	retweets	favorites	is_retweet
0	1340539111971516416	Rachel Roh	La Crescenta-Montrose, CA	Aggregator of Asian American news; scanning di...	2009-04-08 17:52:46	405	1692	3247	False	2020-12-20 06:06:44	Same folks said daikon paste could treat a cyt...	['PfizerBioNTech']	Twitter for Android	0	0	False
1	1338158543359250433	Albert Fong	San Francisco, CA	Marketing dude, tech geek, heavy metal & '80s ...	2009-09-21 15:27:30	834	666	178	False	2020-12-13 16:27:13	While the world has been on the wrong side of ...	NaN	Twitter Web App	1	1	False
2	1337858199140118533	eli🇱🇹🇪🇺👌	Your Bed	heil, hydra 🖐☺	2020-06-25 23:30:28	10	88	155	False	2020-12-12 20:33:45	#coronavirus #SputnikV #AstraZeneca #PfizerBio...	['coronavirus', 'SputnikV', 'AstraZeneca', 'Pf...	Twitter for Android	0	0	False
3	1337855739918835717	Charles Adler	Vancouver, BC - Canada	Hosting "CharlesAdlerTonight" Global News Radi...	2008-09-10 11:28:53	49165	3933	21853	True	2020-12-12 20:23:59	Facts are immutable, Senator, even when you're...	NaN	Twitter Web App	446	2129	False
4	1337854064604966912	Citizen News Channel	NaN	Citizen News Channel bringing you an alternati...	2020-04-23 17:58:42	152	580	1473	False	2020-12-12 20:17:19	Explain to me again why we need a vaccine @Bor...	['whereareallthesickpeople', 'PfizerBioNTech']	Twitter for iPhone	0	0	False
5	1337852648389832708	Dee	Birmingham, England	Gastroenterology trainee, Clinical Research Fe...	2020-01-26 21:43:12	105	108	106	False	2020-12-12 20:11:42	Does anyone have any useful advice/guidance fo...	NaN	Twitter for iPhone	0	0	False
6	1337851215875608579	Gunther Fehlinger	Austria, Ukraine and Kosovo	End North Stream 2 now - the pipeline of corru...	2013-06-10 17:49:22	2731	5001	69344	False	2020-12-12 20:06:00	it is a bit sad to claim the fame for success ...	['vaccination']	Twitter Web App	0	4	False
7	1337850832256176136	Dr.Krutika Kuppalli	NaN	ID, Global Health, VHF, Pandemic Prep, Emergin...	2019-03-25 04:14:29	21924	593	7815	True	2020-12-12 20:04:29	There have not been many bright days in 2020 b...	['BidenHarris', 'Election2020']	Twitter for iPhone	2	22	Fals


![image](https://user-images.githubusercontent.com/104040980/211676978-7650911a-e8c6-4624-9993-e6f8d96797ed.png)



Model: "sequential_4"
_________________________________________________________________
 Layer (type)                Output Shape              Param #   
=================================================================
 embedding_4 (Embedding)     (None, 200, 120)          1200000   
                                                                 
 bidirectional_8 (Bidirectio  (None, 200, 128)         94720     
 nal)                                                            
                                                                 
 dropout_2 (Dropout)         (None, 200, 128)          0         
                                                                 
 bidirectional_9 (Bidirectio  (None, 64)               41216     
 nal)                                                            
                                                                 
 dense_2 (Dense)             (None, 1)                 65        
                                                                 
=================================================================
Total params: 1,336,001
Trainable params: 1,336,001
Non-trainable params: 0
_________________________________________________________________

![image](https://user-images.githubusercontent.com/104040980/211676728-8fc903e0-e38a-4113-aa1c-b9f883bd33cf.png)
