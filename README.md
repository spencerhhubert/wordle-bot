# wordle-bot

i am bot to play popular twitter game [wordle](https://www.powerlanguage.co.uk/wordle/)

this has a somewhat flawed strategy I realize now. the program goes through the entire word list (which is stolen from the javascript of the wordle website) and weights each letter in the alphabet based on how many times it occurs among every word in the word bank. it then sums the weights of each word with those values and picks the word with the highest sum as the optimal word because presumably this will tell the player the most about the word of the day. the user than inputs the results from the wordle site and it cuts down the word list based on those parameters, such as removing all words that don't end in "L." it doesn't work as expected sometimes. like if "S" is the highest weighted letter, it'll return the word "sissy" because it's mostly the highest weighted letter. 🤷

This was it's first dub, I was actually quite impressed with it's discovery because to me this is a very obscure word:

![first wordle dub](https://raw.githubusercontent.com/spencerhhubert/wordle-bot/main/dub_example.png)
