# Pokemon Analytics
This repository hosts two projects, a Singles Battle Predictor notebook and a Market Basket Analysis notebook that objectively resolves the debate around which Pokemon are "broken" or "too powerful" to use in competitive play.
<br>
### Pokemon-Battle-Guesser
This notebook explores Pokemon from Gen I to Gen VII, the generations I grew up with, and predicts the winner of a singles (1v1) battle. <br> <br> The notebook uses data from Weedle's dojo which has Pokemon base stats for Gen I to Gen VI. I scrapped and added the Gen VII pokemon stats. The format of Gen VIII, the most recent generation, removes mega evolutions and essentially set itself apart from the other generations so I decided to exclude it. Gen VII does not introduce mega evolutions of Pokemon whose base form first appeared in Gen VII. <br> <br> The purpose of this model and notebook is not to make Pokemon Showdown matches trivial given the accuracy of the model but instead, introduce players to the intuitive process behind competitve play. Similarly, the model is not as robust as one may dream for since if it were perfect, it would be cheating. Likewise, singles is not a popular format as Pokemon team combinations make every game unique and often more enjoyable. However, the flagship series games focus primarily on the singles battle format which means that this notebook lends to the transition from singles to the metagame. Ultimately, the model serves as a way to start team building which in my experience is the barrier of entry into this scene.
