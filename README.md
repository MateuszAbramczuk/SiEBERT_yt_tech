# SiEBERT_yt_tech

The purpous of this model is to evaluate binary sentiment of comments published under the videos of top 5 tech content creators (Marques Brownlee; Unbox Therapy; LinusTechTips; 
MrWhoseTheBoss; Austin Evans). 

The data used for fine-tuning consisted of 4 main elements, for each of them there was a special token assigned which purpose was enabling fine-tuned model to distinguish between them.
[COMMENT] after which the whole comment was given
[TITLE] was placed before title of the video under which selected comment was published
[CHANNEL] signified by which content creator given video was uploaded
[WHY] which was followed by 
