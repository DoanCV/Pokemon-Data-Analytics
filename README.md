# Pokemon Analytics 
This repository hosts three projects, a singles battle predictor notebook, a market basket analysis notebook and a Pokemon affinity notebook that objectively resolves the debate around which Pokemon are "broken" or "too powerful" to use in competitive play.
<br>
### Pokemon Singles Battle Predictor (Currently deploying as Flask application)
##### Introduction
This notebook explores Pokemon from Gen I to Gen VII, the generations I grew up with, and predicts the winner of a singles (1v1) battle. <br> <br> The notebook uses data from Weedle's dojo which has Pokemon base stats for Gen I to Gen VI. I scraped and added the Gen VII pokemon stats. The format of Gen VIII, the most recent generation, removes mega evolutions and essentially set itself apart from the other generations so I decided to exclude it. Gen VII does not introduce mega evolutions of Pokemon whose base form first appeared in Gen VII. <br> <br> The purpose of this model and notebook is not to make Pokemon Showdown matches trivial given the accuracy of the model but instead, introduce players to the intuitive process behind competitve play. Similarly, the model is not as robust as one may dream for since if it were perfect, it would be cheating. Likewise, singles is not a popular format as Pokemon team combinations make every game unique and often more enjoyable. However, the flagship series games focus primarily on the singles battle format which means that this notebook lends to the transition from singles to the metagame. Ultimately, the model serves as a way to start team building which in my experience is the barrier of entry into this scene.

####### Note: combats.csv has battles that I simulated on custom mode and the 1v1 mode to account for battles among the new generation pokemon as well as against the older generations. I could not simulate as much as I wanted to but I used the same setup to verify battles from the predictor.

### Type Guesser (In Progress)
##### Introduction
Given the stats of a Pokemon, one can guess the correct type (at least one). The model from this notebook serves as a tool to determine the correct type.

### Competitive Pokemon Affinity Tool (Planned)
##### Introduction
Unlike Ash Ketchum, the popular protagonist of the main series animated show, I do not have the benefits of "plot armor", making my team development difficult since it does not revolve around selecting the less developed Pokemon when there are objectively better options. Granted, there are formats that restrict players to the pool of underdeveloped Pokemon. However, the formats that I enjoy the most on Pokemon Showdown are OU, AG, Uber, VGC20XX, BH, Mix & Mega, Monotype and Battle Factory, in no particular order. Only the first four formats truly raise the bar for the strength of team composition. In my experience, given that half of my list requires more developed Pokemon to be competitive, this notebook would be useful for targeting which Pokemon to chose from to not only develop a strong team but also create a novel strategy to win with this team. 
