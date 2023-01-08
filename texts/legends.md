---
title: Louisiana Legends about Treasure
nav_exclude: true
---

## Introduction

For those not interested in reading all 27 text files on GitHub, I have made a single document out of them. You will note that each text is one big blob of text. That's my doing. When I first set up this collection, I deleted all the line returns because I had not yet mastered how to remove them when I was working with them in code. I now know how to do that, and I am in the process of adding back the line breaks, which were, by and large, by clause. So, the second text would look like this:

I went to meet an old man in Marrero,
and he told me a story.
He went to look for a treasure with some other men.
And there was a controller who had brought a Bible to control the spirits.
And when they arrived at the site,
they saw a big horse coming through the woods with a man riding it,
and when he dismounted,
it was no longer a man on the horse.
It was a dog.
And he said the dog came and rubbed itself against his legs.
He said it was growling.
He said he knew the dog was touching him,
but he didn't feel anything.
It was like there was just a wind.
And he said they all took off running.
He lost his hat and his glasses
and he tore all his clothes.
And even the controller ran off
and he never saw his Bible again after that.

To assemble all the texts into a single file, I used a command line utility called **`tail`** which displays the contents of a file with regard to line numbers. In the case of the command below, I told it to start with the first line, a rather long tail:

    tail -n +1 *.txt > ../all.txt

I tell it to take all the text files, `*.txt` in the current directory and write the output to a new file, `all.txt` in the next level up directory -- in this case it was my desktop.

The advantage of using `tail` over `cat` -- a utility which con**cat**enates files -- is that tail automatically separates the compiled files with the name of the file from which the content was drawn. In the case of the file above, that looked like this:

    ==> anc-089.txt <==

Because I wanted things to look nicer for you, I decided to convert the file names into markdown-style headers so that I could use markdown to convert the files to HTML. To do that, I first chopped off the part of the file name I didn't need plus the right-hand side of the division marker: `.txt <==` and replaced it with ` ##`, which is the other side of the Heading 2 markup in markdown, but it could just as well have been nothing.

Having done that, I replaced the lefthand part of the divider, `==>` with the beginning of the markdown indicator for a second level heading, `##`. Again, a Replace All in a text editor and we are done. Then we run the completed document through a markdown implementation, converting it to HTML, and apply a cascading style sheet we already have lying around and *presto!*

What follows are 27 folk narratives collected by Barry Ancelet (ANC), myself (LAU), Lindahl, Owens, and Harvison (LOH), and a number of my students (ULS).

## The Legends ##

### anc-088 ###

In Charenton, north of Lake Charenton, there was an old Indian named Jim. And they asked old Jim where might be a certain marked oak tree north of the lake. And old Jim said he knew. So they went. They started digging. And as soon as they had dug a ways, there was a great big bull that came through the woods with flames coming out of his nose. So it passed. And it just touched the shovel of the man who was digging, and all of them got away. So as soon as the man looked, all the others were gone. So he left, too. And the man told the Indian, "Well," he said, ''I'll have to go back to town for a spirit controller." So he said, ''I'll be back." So some time later, he came back but it was during the time of the vigilantes, you know, the Ku Klux Klan. And his wife thought they were the ones who wanted to talk to him. So his wife didn't want him to go with them. So the spirit controller said to the Indian, "Will you give us your share?" And the Indian said, "Yes, go ahead, you all can have it." So they went. So some time later, the Indian said to my late father- He was going through the woods not far from there. So he decided he would go north of the lake to see, you know. The hole was there, and the chest, and the markings of dollars were on the wood that they have broken off of the chest. So they had found it. The spirit controller had done it. It must be that he controlled the bull, the fire-breathing bull. But they said the flame was coming out of its nose and they could hear it coming through the woods. They heard the wood cracking, you know, when he jumped. The louder it cracked, the closer he came, until he was right next to them.

### anc-089 ###

I went to meet an old man in Marrero, and he told me a story. He went to look for a treasure with some other men. And there was a controller who had brought a Bible to control the spirits. And when they arrived at the site, they saw a big horse coming through the woods with a man riding it, and when he dismounted, it was no longer a man on the horse. It was a dog. And he said the dog came and rubbed itself against his legs. He said it was growling. He said he knew the dog was touching him, but he didn't feel anything. It was like there was just a wind. And he said they all took off running. He lost his hat and his glasses and he tore all his clothes. And even the controller ran off and he never saw his Bible again after that.

### anc-090 ###

Mom said that they used to dig a lot for money. Lots and lots of money was taken out of the ground like that. And she said that her little brother had gone in the woods to get the cows. And he stayed longer than he was supposed to stay. So his mother spoke to him, and she wanted to know where he had been. So he said he had seen a little tomb in the woods. And he said there was a pile of leaves on the grave. And he had cleaned the tomb and he had danced on it. So he had had fun on this little tomb in the woods. "Well," she said, "if you did this, come and show me where it is." He went, but they were never able to find the place.

### anc-091 ###

I know them well. There was Jesse Venable. That was their father. Oh yeah, they saw that often there. There were two buckets. One each end of the chain, you see. When you raised one, the other one went down. You could get water that way. Well, they went all by themselves there. Water flew out and splashed against the side of the big well, a square well. Oh yeah. There are some who claim that there was gas in the ground, but no. That wasn't it because they saw other things. Heard huge echoes as though the earth had split. They would go outside and there was nothing to see. There wasn't money buried there? Supposedly. That's what they said. The oak tree had been transplanted to indicate the place, mark the place. Where the money was. Many went to look for it. They looked often, but they couldn't find it, but they saw things. Oh yeah. This was true. I lived nearby for years, maybe twenty years, right next to that place.

### lau-013 ###

One day ... my family was kind of weird. Because they would always try to dig for money. So one day ... I was young, about twelve I guess. So my mother ... couldn’t leave me home, had to take me out there. So we went out there, to a place called the country, some property we had out there, about an acre of land. So they said form a circle. And this is ... my eyes seen this myself. We formed this circle, man. My brother, my brother was preaching. He was digging in the middle. We were all around him and he was digging in the middle. Man, he took that shovel. I guess from the way it looked it must have been a shovel deep, about like this. Something went yanga yanga yanga yang. And then went boom. And when you looked again, they had a fucking coffin, man. Solid gold. Open it up, nothing but coins in there. And then a bull appeared, just appeared out of nowhere. The bull had fire coming out his nose and his eye was red red red. And you hadn’t supposed to talk, because it would break the chain of everything. That’s just how it was. That bull started charging. I was trying to get out of there. I’m young. I don’t know what’s going on. My mother telling me just don’t move. There ain’t nothing, ain’t nothing. You just seeing things. And that sucker come up from me to like where I’m sitting to you and disappeared. Now you know that scared the shit out of me. I was damn near shitting in my clothes. My uncle come up in the car. And when he drove in the yard that shit exploded. And when I looked again it didn’t look like anyone had dug in the ground at all. Everything disappeared.

### lau-014 ###

Like I said my family was weird, they liked to dig for money and stuff. Said my grandfather had left us some money, and they was digging for it So one day we went, and I was at work, so I can see, we at a country spot, like our property. So I can see a lot of people dressed in white. So I’m curious me. I said well shit what the hell is everybody doing out there dressed in white? I wanna see. So I goes out there. So they tell me you’re working right now, just go home come back. You know, come back after work. So I goes back, man, after work. So, they all in the house. We all praying man, everyone’s on their knees praying. They got an excavator in the back yard, digging. You understand? Find this money, I guess. We’re on our knees, man, we’re praying. It’s like in the pit of the summer like here. No wind nothing. They had a wind come through the house. That wind was so strong: my aunt was holding onto the door like that and both her legs was in the air. That’s how strong the wind was. In the house. So they said — they picked me, my nephew, the one I was telling you that talk all that shit, and my little niece to go bring some water to the workers in back, the one that was doing the work. So we got to walking. We passed on the side of the house to bring them. So my nephew said, say man you see that guy in the tree? I said man fuck I don’t see nobody in no tree. He said yeah man he be right there sitting on that limb. I said I don’t see nobody man. I’m getting scared now. Man I don’t see nobody. But he’s seeing this, you know. So he said — I said how he look? It’s a guy, he said, it’s a guy dressed in a pirate suit, man. He said he got a pirate hat on. He got a pirate jacket. And he started talking to him. The guy in the tree started talking to him while he’s telling me this. But the guy in the tree is tell him shut up don’t tell me that. So he telling me, man, look he right there. You can’t see him? Look he right there on that branch. He say he want something more to drink You know, because what they had did: they’d put a bowl in the back yard, under this tree, with some alcohol in it. You understand? And I don’t know if it was the sun that would dissolve it, but it would be gone. Okay, so he say he say man he want another drink. So I said fuck man don’t tell me that. I wanna get back in the house. I said I don’t see nobody up there. So we kept on walking. We went out there. We brung them some water. So on our way back. Look at him. He say, see you, you son of a bitch. He say you don’t wanna give me another drink, huh? He say you gonna be just like me. He say you see this here peg leg? He say you going to be just like me. He say for this out here y’all are going to have to lose something. So, man, it got kind of scared. We started walking fast. By the time we got to the house, I broke out a run. A shovel, man, come from the back of the house. I mean full force. That shovel stuck in that tree so deep we had to dig it out with an axe. It stuck — you know with a shovel, it’s hard to stick a shovel into anything. That shovel went inside the tree halfway.

### loh-157 ###

The man whose story I'm going to tell you as far as I know actually lived, because I played around his grave a lot. He was buried, still buried, where we lived. He was buried in the yard where I lived. They had built a cypress picket fence around it. By the time I was old enough to know anything, the picket fence was falling apart. But it was still intact, partially. This was a guy by the name of Fisher, which is obviously not a Cajun name. Supposedly Fisher and his wife and Fisher's wife's son, whose name was Billy, came to live in that house. Where they came from, nobody knows. The story is, and this is rumor and speculation, that he was a bank robber. He had moved into that house to sort of disappear. He was a drunk. Every time he'd go to town, he'd get drunk. This would have been Church Point, the closest town. He'd go on horseback and go to town and come back drunk and beat up on Billy. One afternoon he came back drunk and Billy shot him. Killed him. His wife and Billy buried him right there. That night as it was dark, they left in the buggy, supposedly with a lot of gold. They came up to Jean Jannise Jr.'s house. This is not the loup garou, this is his son, who was living --and the house is still there, not the house but the place. When they got there, she looked upon Jean Jr. as a reliable man. She stopped there right after dark. It's always after dark! He told her, "If you try to cross this forest at night, you're going to be robbed. Why don't you stay here tonight and tomorrow you can go." Supposedly she was returning to Mississippi. That night, supposedly, she buried her money on the other side of Jean Jr.'s house, a lot of gold. Tremendous amount of gold. She never returned so the gold is still there. I had a friend of mine who told me that was true because all drunks have a lot of money to bury! And that's my reaction to that story.

### loh-158 ###

There was so much Lafitte activity here, then legend glorified it. Then Texas picked up on it at Galveston. There's a lot of stories. In the little town of Duson over near Lafayette, on Highway Ninety near Lafayette, you'll notice there's a little Catholic church on the left side of the road when you're coming this way, just a little out of town. There's a man named Judice who was very active in public affairs. He had a man plowing his field and the plow hit something. They opened it up and it was a big chest full of jewels and gold coins. All of them had early dates, and there were French coins and early American coins. They were buried there. They said it was Lafitte. They don't know who it was. But this negro man who found this built the Catholic church and the school there with part of the money. Seven years later, I guess jealousy, it burned down. He rebuilt it. Seven years later, it burned down again. He rebuilt it again. How much he had left I don't know. That's one case, and there's well-established fact on it.

### loh-159 ###

Where Hodges Gardens now is, my Dad was hauling pine knots. They used to fire these locomotives, these trains. The locomotives would pull the log engines. They fired them with pine knots. He was hauling that stuff and selling to the railroads. He was working oxen. He stopped at a little branch to water his oxen, saw something glittering in the water, went to pick it up and it was a gold brick. A gold brick. Now, that was a bullion. These Mexicans would mine it (gold) and make it into little bricks. Now, the way he described it. I was too young to remember it. I was a baby at the time. He described it, like, it would have been like a small Hershey bar the way he described it. Well, him and his brother, they went down the little branch digging and hunting to see if there was any more. But they never could find any more. He put it over the door facing, and he'd show it to everybody that came in. One day, he went to show it to someone and it was gone. Somebody had put it in their pocket while he wasn't looking, and he lost it. Now, he [his father] had a cousin that found a gold . . . It was not a bar; it was some kind of medallion. They said it was hexagon shaped and had Spanish writing on it. He did about the same thing. Some guy was gonna send it off and see what it was worth, and that was the end of it. That's why I'm not a rich man today; my relatives didn't hang on to their money!

### loh-160 ###

I was in Leesville one day, in the grocery store, and a man told me, said, "You ought to talk to my dad. He's got a very interesting story he can tell you." I said, "I want to talk to him, by all means." So I went to see him, and he is a man by the name of Smith. They own the Piggly Wiggly store in Leesville. There's two of the brothers. I don't know if it was John, who is a state representative, John Smith, or if it was his brother. One of them told me about it. One of them told me to go see their dad. So Mr. Smith told me, he said that his grandfather, a man by the name of Brock, originally lived in Marthaville, Louisiana, in Natchitoches Parish. He had moved to the Rio Grande valley and was a farmer. This was along about 1912. There was a bandit by the name of Pancho Villa. He would come across the river and raid farms in Texas. Finally, well, for years they were trying to get the federal government to do something about it. They were pretty slow to react to it. He finally went up to Columbus, New Mexico. Killed a lot of people up there and done a lot of damage. They sent General Pershing. Later on, he was a famous World War I general over in Europe. He never did catch Pancho Villa, but he got close enough for Pancho Villa to decide he better stay out of the United States. Run him back across the river. But back to my story, he raided a farm next to Mr. Brock's. I suppose he probably killed some people, took what valuables they had, gold or stock. Scared Mr. Brock up pretty bad, and he decided he'd just leave. Get out of there if that's the way it was gonna be. So he was packing up to come back to Marthaville, and there was an old Mexican on his place. Come to him and says, "Mr. Brock, I'm gonna give you a map where you can dig up some money when you get back to Louisiana." Well, I stopped Mr. Smith right there and I said, "Now, look, why didn't the Mexican go dig it up?" He said, "Well, he was an alien. He was not an American citizen. In those days, a law officer would just shoot one down." Mr. Brock came on back. In the spring of the year, he was making a crop. He had two grown boys to help him. They were after the old man, "Let's go dig up the money. Let's go dig up the money." He was afraid they wouldn't get the crop in. But after the crop was laid by in the summertime, he said, "Alright boys, we'll go see about it." So they went straight and dug up. There was a little cave. They dug the money up. It was twenty thousand dollars in silver. No gold. Mr. Smith told me, "I took my grandfather back there several times. He wanted to go see where this money was dug up, so I took him there several times." I asked him, "Well, would you take me and show me where it was?" He said, "Well, I'll try. It's been a long time." Understand that they have straightened that road out. It used to have terrible curves. So we got over there. We went up there. It got pretty close to the place, and he said, "It's somewhere. I know it's over here somewhere." We went about a mile or two and he said, "We went too far." We never could locate just where it was, but he said, "It's right in here on this ridge." He said that these two uncles came in later and used dynamite, hoping to find some more. But they didn't find any more. There was an outlaw by the name of West. I believe, the best I remember, he might have rode with Murrell. He might have been in Murrell's gang when he was young. I think he was a Civil War veteran. I think he fought in the war. But he built him up a good little gang. But they were terrible as far as being heartless. Throw people in wells! Just let 'em starve to death! Killing babies, all kinds of stuff. West was the outlaw that did that (buried the money), according to the Mexican. He was with West and remembered it well enough to draw that map

### loh-161 ###

I'll tell another little story. A friend of mine told me this story. She was raised down here on Toro Creek, just off of one-seventy-one Highway. She said that, I knew that there was an old stage coach route that came through where Hodges Gardens is now, just west of this Toro Church we were talking about. I didn't know that they had an old stage station over there. Nobody ever told me that. If they did, I'd forgotten it. But she said there was an old stage station right close to where they lived. It was just off the road going to Toro Church. She went to church there when she was a girl. She said one day, one Sunday, they were going to church. There was a bunch of guys in a car, stopped over there, had shovels with them and everything. They stopped and asked them if they had trouble and could they help them. "What are you doing in the country, on a country road?" They told them that no, they had car trouble, but they had it fixed. So they went on to church. When they came back after church, the kids went out to the old stage station. It was close to the road. That's where they had stopped. Said it was a big rock. I asked her, "Was the rock part of the foundation of the building?" She said, "I think it was more foundation for the chimney." She said that rock had been turned over, and there was a neat, little vault about eight inches square and maybe eight inches deep. There it was, a neat little vault with nothing in it. She figured they'd gotten gold or money out of it. That happened in the thirties.

### loh-162 ###

Years ago, when the Perkins started over into this area from Mississippi, this family pooled all their money. They had it in a flour barrel. John Reed's great grandmother had it in her family and had a cloth over it. One of the kin folks' children come over there one cold morning and didn't have any shoes. She took him aside about where his shoes were and all, and he said, "I just don't have any." She said, "Well, I'm gonna stop that." She went in to the pantry where this flour barrel was. John Reed's grandmother went with her. She was just a little girl then. She said her grandmother, John Reed's great grandmother, threw this cloth back and reached in there and got a piece of money and gave it to this little kid. Told him, "Now you tell your mother to buy you some shoes." Well, while she was doin' this, John's grandmother, she couldn't see into the barrel, but she reached over it and she could feel this money. There was that much money in there in this flour barrel. They had pooled all their money and put it together. So later on, one of 'em, I don't know which one, was charged (given the responsibility) with taking this money and what was it? A couple of slaves. He headed west to buy land for the whole family. He was supposed to buy land. But he got down to where they call Big Woods, and he sickened and died. Now, the slaves told the story that this money is buried in there. By the time they made their way back to Mississippi, they couldn't remember where it was. They had buried all this money he had. What it was in then, I don't know. It was probably in boxes. Evidently, this money was supposed to be buried there. That money, as far as anybody knows, has never been discovered. But that whole area has been dug up!

### loh-162b ###

Her (his wife, Maggie) father one time, when he was a boy, there used to be a store just west of here, Field's. It's still there. He was playing there on the porch, and he had a nugget. One of what they call a drummer, a salesman, come by and said, "Let me see that, son." He looked at it and it was supposedly silver. He gave him fifty cents. Told him, "I'll pay you more if you take me" -- now, there's a little creek out there, Windham Creek -- "If you take me back and show me where you found this." He said he was just about eight or nine years old, playing along this creek. He was sure he could find it, so he took this fellow up there to show him where it was. He never could find the place where he found it. One time out east of town here, a guy found a stump full of money. A hollow tree. Come to find out, it was slot machines stolen from the old Pines nightclub. All these nickels and stuff was hidden in this stump, in this hollow tree.

### loh-163 ###

One of the most famous stories here is after the War of 1812. Jean Lafitte, the pirate, was still active here. He helped the United States in the Battle of New Orleans when Jackson defeated the British. They let him go, and he went to Galveston. The city of Galveston was founded by Jean Lafitte. He moved, supposedly, all his operations and headquarters outside the jurisdiction of the United States. But his biggest market, of course, was New Orleans. He would ply his piracy and his trade there. At night, they knew all these swamps and innerland that the U.S. didn't know, the Coast Guard didn't know. And he would slip his stuff in through Barataria Bay and peddle it to New Orleans. One time one of his sloops or ships was apprehended, almost apprehended, by the U.S. Coast Guard. When they got to what they thought was waters outside of the United States, they turned into Sabine Lake. But it wasn't at that time outside of the United States. The Coast Guard was so close behind them that they scuttled their ship and sank it. There's always been a claim that they buried whatever they had somewhere in that area. People still look for the money there.

### loh-164 ###

Have you all heard anything about hunting money? Well, that's the thing I'm gonna get involved with here. I went on a hunting expedition. And people don't know what actually goes on. I was invited to go on this trip, and they explained to me what it was. I'd never heard of it before. That was news to me. Okay, people a long time ago (pause) they claimed they buried their money. That was back when they had the slaves and all that there. And they, this old slave owner, he'd have a lot of money to bury. Well, he'd take his most-trusted slave he had. His old slave. And he'd take him with him. Well, he'd go out and he'd pick him out a spot where he wanted it. And he'd tell the old slave, "Now, I want you to dig right here." And he'd put it about four or five foot deep. Well, the old slave'd be down there digging. When he thought it was deep enough, the old slave owner'd tell him, "Now, look. I want you to promise me something. That you'll guard this money as long as you can." And the old slave'd say, "Yeah, I'll do that, boss." Well, then he would, he'd shoot him. Kill him. Well, then the owner'd cover the hole up. He was the only man that knew where it was. That slave down in there, the belief was, that the slave, his spirit, would continue to guard that money. Well, these people decided how to get around that. Well, I went off on this trip with 'em. I saw things I thought I'd never see again. They told me when they went, they said, "You gotta be pure." Now, these are grown men. These ain't little boys. They said, "You can't have any dealings with your wife for a week, at least seven days before this hunt." Well, these guys hired a man from the other side of Houma to come over here. He was supposed to be a professional finder. Well, he done it for a fee. They had to pay him, his expenses, to come over here. He brought a guy with him, and the two of 'em drove from Houma over here. He had a forked rod. And that's the thing he used to hunt the money with there. They could find it. Well, we went way out in the country to an old plantation deal there. They told us, they said, "Now, y'all stay here. And if that money's within a mile of here, we can find it." And he said, "We'll come back and get y'all." So he told 'em all that. Well, we sat there in the dark, and he told us, "Now don't talk loud. Y'all can just whisper." So it was weird. I mean I was sitting there, and I didn't know what was going on. Well, in a little while, they come back. And the guy said, "We've located it." He said, "Now, this is what I want y'all to do. When we start out to get it, they can't nobody say another word." So, we trailed along behind 'em back through the woods. And it was dark. We was stumbling over roots and everything else. And we finally got to the point, the place there, and they had an old lantern. It was the only light we had, and they had it up in front. We was all in the back. And they got up there and sure enough, there was that forked piece of metal sticking in the ground where they'd located it. Well, they told us, and everybody, wasn't nobody saying a word. They was motioning, stand back and all that there. Well, all at once, this guy come out with a little old box. This was the part that was weird to me. He got that box and he went in there and he had some white powder. I know it was flour. That's what it looked like. He went and made a big circle around the whole thing. That was to keep that spirit in there. In other words, to keep that spirit from getting that money and running with it. It was their belief that once you got that powder around it, he couldn't cross that powder. Well, they got there and they got that old powder'd up. Then they started digging. And I mean they was going at it fast. Nobody wasn't saying a word, it was just strictly just everybody was working. I didn't know nothing about it. I did get in there and dig just a little bit, but I was [pause] more or less [pause] wanting to watch than anything else. Well, they dug a hole , I bet you, it was seven-foot deep. You could've buried a car in it. There was some of them fellers there, they wouldn't work in a pie factory. But boy they was at it with that digging. Well, they was going at it and all at once, one of them fellers got a coughing spell. Well when he did, this guy that was supposed to be the professional, he just got up and said, "Boys, it's all over with." He said, "It's gone now." He said, "I told you, you can't make no noise of no kind!" He said, "Now you can dig all day and they ain't no money there now." And that wound the money hunting up. Since then, I've heard other people talk about going on trips, and they always blame it on something! Even one time, they got so mad with one of the guys, they thought he'd lied [inaudible]. They thought he was lying. I never heard of nobody finding the money. But they're right close to it. Now, there's people right today that's still doing it. Here a while back, I heard a man down below his house there, he went to work one morning and there was a hole there the side of the field. He said he don't know when they dug that! It was some time during the night!

### loh-165 ###

You know, some people believe in haints and some don't. Ghosts or whatever they call them. But it's something. Something that I couldn't explain now. I've seen things, heard things. A lot of people don't believe it. But I have seen things happen on different occasions, living in the country. It's unexplainable. I don't know why or what it was, but I've seen things that I just couldn't explain what it was. I was trying to remember the time that three fellows came up and asked me to go with them and show them where I had seen, what they said, the haints, spirits. I actually seen it, and they said wherever you see something like that, well usually treasure, money buried around. These three fellows came up and asked me would I show them where I seen this spirit or whatever it was. I'm getting ahead. What I really seen, must've been about nine, ten years old. About first dark one night, I was on my way home. First I heard something that sounded like singing, moaning a song or something. I stopped to see what it was, and then when I did see it, it looked almost like them clouds out there. But it wasn't as big as that cloud, it was just like a vapor like. But it was just floating through the air. I couldn't make out what it was, and when I realized it wasn't real, when it passed by the chicken house, the chickens started cuttin' up. And it came in front of me, and went out in the [inaudible] and just settled down. But it was still like it was singing. By that time, I done got up enough nerve in my feet to run. And I taken off to the house. Run in there and told my dad about it. And so he said, "Oh, it's just somebody out there trying to scare you." And he got up, got the shotgun, went outside. I told him, I went out to the porch and showed him where the last time I seen it was. So he went on out that aways. I come on back in the house, waiting to hear the gun to go off. Few minutes, still hadn't heard the gun go off, I heard him coming back running! He said when he got out there, when he raised that gun up to where I had told him that thing was, said something got all over him and that gun. Man, he come back in that house. Said something was out there. After that, these two men came along must've been about twenty-five, thirty years later, wanting to know where did I see this at. And I told them. They asked me could they go back there. Well, the house had been torn down and all growed up out there now. So anyway, I'm taking them out there, and these fellows had one of these treasure things, like you hunt buried treasure with. He had one of those, and one of them had some other kind of little gimmick. Another had a little Testament, a New Testament. I got to the place we was supposed to go. So this fellow with the little Bible, he went out and sat down on a log and started reading. Fellow with this treasure deal, he started moving it around on the ground. Finally this thing started making some kind of whining noise. Getting louder and louder. And so he said, "Something down here." We got a shovel and dug down in there. Kept in and dug a little more. Finally didn't did no more. We taking it out the hole, and that's where they found it. When we did find it, a fifty cents piece. Search and search, couldn't find nothing else. I said, "Well, this ain't where I seen the haint at. It's over here between these two cedar trees. We went over there. He got in between them trees, and I said, "It's closer to the one on the right." And so he went over that way, and that thing started making this whining noise and going on. At this time, a great big, I say a blackbird. Looked like a blackbird to me, but it was real black. It looked like it was blue. But it had a real yellow beak, and two big orange eyes, and he lit up in that cedar tree and he starts making croaking noise like a crow. Then another one, then another one. The more we searched, the more them big old birds get in that tree. Finally, them birds, got so many got in that tree it look like it was just leaning backwards and forwards. This man told me, said, "I tell you what, something has been here. But somebody done found it now." Said, "We better go!" He packed up his junk, we left. But I honestly believe they went back out after I had helped them locate where I thought. I didn't know what was there, but I believe they located something and they went back after they got rid of me. Keep from dividing with me. If there was anything there, keep from dividing with me. It was near night, so they carried me back home, and I wasn't about to go back there by myself! But anyway, that's what happened that particular night.

### uls-001 ###

A relative of ours lived in the country near the woods of Morse and Crowley when she was a little girl. She lived in an house that was stilts so that when a flood came their house would be okay. When she was a child, our relative would play with the other kids under the house during the summer to stay out of the heat. The story goes that our relative, along with the rest of the children, saw a man sitting on a wooden chest beneath the house. This apparition did nothing to the children, although it did frighten them for a time. Strangely, only our relative and the children could see it. Not the adults.

### uls-002 ###

The same relative had a husband who went out into the wooded region in that area. Along with his brother, they went looking for cypress moss for cushioning their pillows and blankets. This was way back in the day. As they were searching, they noticed a stone slab on the ground beneath a tree. It was odd because the husband and his brother weren't able to move the slab of stone. It seemed to be stuck in the ground. Then, they got this weird feeling. Something wasn't quite right with the stone. The two men freaked out, and they climbed the tree in fear. When they looked down, the slab of stone disappeared. They jumped down from the tree and ran home.

### uls-003 ###

Later that same day, after my grandmother had told me these stories, I heard almost the exact same story told by a friend of mine. This story seems to be a common legend in southern Louisiana. He said that two relatives of his went hunting out in the woods one night. When and where exactly, I don't know. They too saw the stone slab. Upon returning to the woods again to find it, it had disappeared. My friend said that the mysterious stone slab never stays in the same place. And if one sees it, you're supposed to dig in front of it to find buried treasure. My friend also mentioned how some people see a tombstone instead of stone slab. Some people also see a man standing next to or is sitting on the stone.

### uls-004 ###

Upon hearing this, I couldn't help but think of pirates who buried their treasure in southern Louisiana. I learned in history this semester that pirates would bury their treasure on land and ask one of the crewmen to protect it. The one to protect the treasure was shot dead, so that his soul would guard the treasure forever. Perhaps these two stories are connected in some way.

### uls-005 ###

So, they had this old man, this is like the slave era in Louisiana. Well, not necessarily slave but, you had this era where they had kind of like Jim Crow laws, you know? They weren't born slaves anymore, but they still worked in a kind of indentured servitude, in a kind of fashion. And, he had, this old man he had a couple of "slaves", and what he would do, (he was very cruel, a cruel man, a cruel master. He's very superstitious though) so what he would do if a slave did something wrong, in order to guard his fortune, he would either bury them alive while holding his money, his money or something valuable, and even it would get morbid, like, they had old whiskey barrels, and he would put glass and nails on them and then roll them downhills. He was just cruel. Well, the day that he died they said that he spontaneously combusted and that, nothing else burnt. The only thing that was left of him was a giant suit mark on the bed, where he was. He died in his bed.

### uls-006 ###

Me and my brothers would hear this story a lot from one of our neighbor’s parents, she said she was a fortune teller. Supposedly, there was treasure buried by a stump and only a child could find it. The treasure would rise up out of the ground and appear to the children. The only time a child could find it is if they were playing by the stump, but if they left to go get help to get the treasure, when they came back for it, it was gone. It had disappeared. It didn’t pay for a grown up to go look for it because they wouldn’t find it.

### uls-007 ###

I had a cousin, he's dead now, he served during Vietnam as a navy seal, and when he came back­. In the same woods, there's like a legend saying that (it's an old Indian legend) that if you find this kind of like plate... it looks kind of like, some sort of like Indian, like native american...writing, or just mosaics like that, so, if you find this plate, according to the legend, where that plate sits, right underneath is a great treasure. Well, my cousin Glen was in the woods one day, he might have been hunting or something, he finds this kind of plate, and he remembered that legend, so what he did was he tried to make a trail on the way back, like scratching trees, like carving certain stuff in trees, to make sure that he could make his way back, he didn't have shovels or anything. So he comes back, I think with someone else, maybe a friend, to come and dig it up, and where the plate was, was gone, and according to another little part of that legend, the reason why it shows up is the spirits are trying to kind of play a trick on you, to get you lost in the woods, 'cause he's like "oh, yeah, I wanna come back and" … he was just smart and scratching his way, like marking his way back.

### uls-008 ###

The legend goes the person-  
it was like a umm, a farm  
that people had lived on that farm  
And the white people killed somebody and buried some money under them to say to protect their money  
And during that time  
That’s how- I guess- that’s how things had work at the time  
But we found out  
And we went try to get it  
And we could never get it because something was always running around  
You could dig but the change  
-You could hear the change falling deeper and deeper and deeper  
The more you dig  
The deeper it get  
So we never had a chance to get to it.  
And I guess no one will get to it.

### uls-009 ###

The thing is-  
Like he said, like Gator said  
The thing is back then  
A man asked a worker  
-must’ve been a worker  
If he would’ve watch his money  
And the worker- one of the workers said “no”  
And he asked this other worker if he wanted to watch his money  
The worker said “yea” he would’ve watch his money  
So what they did-  
They kill him  
Bury him underground  
And the money  
And now you watching it  
So the one that say he was watching the money  
They kill him  
And they buried him  
Now he watching the money  
He said he was gonna watch it  
Yep.

### uls-010 ###

That's it over there.  
They use to have a house in there.  
Right there where the trees is they use to have a house in there.  
Probably got the mark where the house is now.  
We used to go in there.  
We couldn’t go ... we use to ... we use to travel.  
We use to hear they had gold there.  
We’ll go try to dig it, couldn’t dig, couldn’t dig.  
Me, Dexter, Kenneth, your daddy.  
Just about all of us, I think Roland too.  
We all tried.  
Couldn’t, you couldn’t even get the shovel in the ground.  
It’s a certain time you could’ve get it in.  
But you wasn’t finding nothing.  
And you would hear noise in there.  
You hear ... you hear strange noise.  
There in the trees.  
Yeah they had some stuff in there.  
A spirit.



### uls-011 ###

Nah I ain’t scared to go over there.  
I don’t think it’s none to be scared of.  
But, but it’s still strange to hear.  
I think them old people say that spirit will not let you dig to get to the gold, whatever’s down there.  
That’s what them old people used to say.  
Its not going let ya ...
and it’s kinda strange they clean all that.  
They clean all the distance,
but they never clean that spot there.
