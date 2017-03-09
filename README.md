# Explanation of solution
Here is the solution
Input:
https://www.reddit.com/r/all/

Output:
[
	{
		"url": "https://i.imgflip.com/1kzbwx.jpg",
		"commentsUrl": "https://www.reddit.com/r/AdviceAnimals/comments/5y54am/my_uncle_is_an_awesome_boss/",
		"topComments": [
    "The cashier is a young woman from Guatemala (legally immigrated here 4 years ago) (17, I think), she looked genuinely scared       lifeless. My uncle drove her home to make sure that jackass didn't try anything and worked her shift.",
    "My uncle has a saying: A whipped horse will run, a loved horse will jump.",
    "That girl will work her ass off for that man. He's gotten something he couldn't buy. Actual loyalty.",
    "People like your uncle, the world needs more of them.",
    "What a dumb show to get your username from.",
    "If we forget about the politics of the situation, it's a customer threatening an employee. That's something that should not be tolerated.",
    "Champions",
    "What is your uncle's view on spurs?",
    "I like pancakes.",
    "Emoposer is a reference to goth episode of South Park."
    ],
		"topKeywords": [
			"cashier","Guatemala","horse","jump","work","loyalty","uncle world needs","South park","pancakes","emoposer"
		]
	}]
.
Explanation:
1)Top comments are selected based on the points using pandas.
2)top 10 words are selected based on three algorithms i appliied.a)bag of words b)Tf-idf c)word_tokenize and their parts of speech.

Solution is for only one url mentioned above.
