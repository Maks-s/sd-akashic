# Let's talk Seed editing! (by richservo#8465)
The numbers in the brackets are the random number seeds assigned to each image in a stack

![seed example](https://media.discordapp.net/attachments/1005540397910597734/1007064438580449360/unknown.png)

The way the LD model works is it starts with a noise pattern that uses that value.
Then it resolves that noise to the image you selected.
The really cool part is.
When you use the same prompt and seed you end up with the same image.

For example :

`!dream "film still of John Cena as Nada in Bank scene in They Live 1988" -W 704 -S 1225724671`

Will produce this image. Try it. 

![john cena](https://media.discordapp.net/attachments/1005540397910597734/1007064828722036756/film_still_of_John_Cena_as_Nada_in_Bank_scene_in_They_Live_1988_-W_704_-n_9_-i_-S_3136365759_ts-1660010873_idx-5.png?width=512&height=372)

Now, it's close, but what's he doing? He's not in the scene. He needs a shotgun and sunglasses!

`!dream "film still of John Cena as Nada wearing sunglasses and holding a shotgun with a bandolier in Bank scene in They Live 1988" -W 704 -i -S 1225724671`

So by editing the prompt to add sunglasses and a shotgun we get: 

![john cena, shotgun and glasses](https://media.discordapp.net/attachments/1005540397910597734/1007065115364970516/film_still_of_John_Cena_as_Nada_wearing_sunglasses_and_holding_a_shotgun_with_a_bandolier_in_Bank_scene_in_They_Live_1988_-W_704_-i_-S_1225724671_ts-1660011647_idx-0.png?width=512&height=372)

But in the movie he's wearing a flannel shirt, not a t-shirt<br>
So we can add that to the prompt

`!dream "film still of John Cena as Nada wearing a flannel shirt and sunglasses and holding a shotgun with a bandolier in Bank scene in They Live 1988" -W 704 -i -S 1225724671`

And we get :

![john cena, shotgun, glasses, bandolier](https://media.discordapp.net/attachments/1005540397910597734/1007065327844200529/film_still_of_John_Cena_as_Nada_wearing_a_flannel_shirt_and_sunglasses_and_holding_a_shotgun_with_a_bandolier_in_Bank_scene_in_They_Live_1988_-W_704_-i_-S_1225724671_ts-1660011726_idx-0.png?width=512&height=372)

We successful put John Cena into They Live! But wait, What if I want Dwayne Johnson...he's also a modern wrestler.<br>
Just edit the prompt again:

`!dream "film still of Dwayne Johnson as Nada wearing a flannel shirt and sunglasses and holding a shotgun with a bandolier in Bank scene in They Live 1988" -W 704 -i -S 1225724671`

![The Rock, shotgun, glasses, bandolier](https://media.discordapp.net/attachments/1005540397910597734/1007065561802477678/film_still_of_Dwayne_Johnson_as_Nada_wearing_a_flannel_shirt_and_sunglasses_and_holding_a_shotgun_with_a_bandolier_in_Bank_scene_in_They_Live_1988_-W_704_-i_-S_1225724671_ts-1660065476_idx-0.png?width=512&height=372)

And maybe Dave Bautista:

![Dave Bautista, shotgun, glasses, bandolier](https://media.discordapp.net/attachments/1005540397910597734/1007065613245612062/film_still_of_Dave_Bautista_as_Nada_wearing_a_flannel_shirt_and_sunglasses_and_holding_a_shotgun_with_a_bandolier_in_Bank_scene_in_They_Live_1988_-W_704_-i_-S_1225724671_ts-1660065724_idx-0.png?width=512&height=372)

or Randy Macho Man Savage:

![Randy Savage, shotgun, glasses, bandolier](https://media.discordapp.net/attachments/1005540397910597734/1007065660645458001/film_still_of_Randy_Savage_as_Nada_wearing_a_flannel_shirt_and_sunglasses_and_holding_a_shotgun_with_a_bandolier_in_Bank_scene_in_They_Live_1988_-W_704_-i_-S_1225724671_ts-1660064888_idx-0.png?width=512&height=372)

who said it has to be real people, how about Kratos?

![Kratos, shotgun, glasses, bandolier](https://media.discordapp.net/attachments/1005540397910597734/1007065744422482061/film_still_of_Kratos_as_Nada_wearing_a_flannel_shirt_and_sunglasses_and_holding_a_shotgun_with_a_bandolier_in_Bank_scene_in_They_Live_1988_-W_704_-i_-S_1225724671_ts-1660065893_idx-0.png?width=512&height=372)

You can do a LOT with seed editing.
