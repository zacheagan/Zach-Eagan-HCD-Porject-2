# Zach-Eagan-HCD-Project-2

HYPOTHESIS:

My hypothesis for this project is Perspective will score the toxicity of a group of letters used in common swear words higher than letters not used in common swear words. Perspective will faslely deem these letters toxic, as a single letter or three should not be toxic. My prediction is the letter f will have the highest toxicity score, despite the letter e being in more overall words. 

My threshold for perspective toxicity score of the comments is 0.1. This seems very low, but I am looking at a letter that can be used in numerous words, but will still come up toxic compared to others. The labels I will be using is obscene, threat, and insult. These three column labels in my opinion will give us the best yield in terms of the swear words and the letters we are testing.

TESTING:

As a disclamer, the words that I am alluding to are offensive swear words. I do not in any way condone the use of these words. I am only theorizing how perspective views these swear words, and how toxic the program deems the letters are in these words.

In my testing I have two seperate groups, a control group of letters and words, and a group of letters that I deemed to be common in swear words. The seperate groups will allow us to compare what I hypothesis as toxic and not toxic and see the difference in scores. The difference in scores between the groups will prove or disprove the hypothesis. In each group there are 10 comments of different length, and each comment has a counterpart in the other group with the same character length.

RESULTS:

The results of my testing were not very surprising. In our control group, perspective rated each of the control group data points properly. None of them were supposed to be positive, and none of them were positive. On the other hands, the swear group had 5 data points be positive, and 5 show up negative. Looking at which data points were positive, and which were negative shows a slight trend. If the data point is a singular letter, more than likely perspecitive will score this not toxic. The exception is the letter f, which scored just above the threshold at 0.11. If the comment was expected to be toxic, and if the comment is more than one singular letter the program will deem it toxic.


ANALYSIS:

After conducting testing I can conclude my hypothesis is wrong. This does not mean all of my hypothesis was wrong, only parts. Looking at the results will illustrate why. Seeing the trend that a singular letter, even if I predicted perscpective would call it toxic, will most likely be not toxic forces me to say my hypothesis is wrong. On the other hand, if the comment was predicted to be toxic, and is more than two letters, more than likely the program will call the comment toxic.

Based off the testing results, the only data point I do not agree with is "cr". I believe the program would not deem the swear word "Crap" to be very toxic, but I believe 'cr' should still fit the low given threshold. The other data point that surprised me, but I agree with Perspective, is 'Who'. I wanted to see how the program would react to these letters. On its own 'who' is a word that is not toxic. I believed the program would still see 'who' as toxic as it is very close to the swear word we were looking with this data point.

I have a theory on why the program may predict toxic scores, based off of a few letters of a word. I believe that the way the machine learning algorithm can look at these letters and determine the most common uses of the words. In terms of general toxicity scores, these scores are not very toxic. Given the context of the experiment, I was determining how well perspective could predict toxicity of merely a few letters out of a whole swear word. I believe that perspective is used to determine the toxicity of a comment, and these comments contain a lot of vulgar language. Therefore, the program has learned that these specific sets of letters I predicted to be toxic are the beginning of other toxic words it has already learned. The program is filling in the rest of the word after the letters and that is where the prediction comes from. 

Conclusion:

Overall, I believe given the context perspective was able to determine the toxicity of the given values well. I predicted that the program would be able to determine the greater toxicity in letters of common swear words, and it generally did that well. 
