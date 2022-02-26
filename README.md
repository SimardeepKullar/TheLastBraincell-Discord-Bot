# TheLastBraincell-Discord-Bot

A friendly bot, that helps provide fun interactive games and functions.
  - Allows users to play multiple games of Wordle with a file of 5 letter words, as well as request definitions of the words using a dictionary API.
  - Other functions include presenting jokes and anime quotes from their respective APIs

The bot is able to many functions which are:

$commands                                             $giveup
  - This is the help command.                           - Display the answer to the wordle.
$hello                                                $mention name num
  - A greeting.                                         - Pings the person a number of times.
$joke                                                 $randnum min max
  - Get a joke.                                         - Random number generator.
$coinflip                                             $randquote
  - Flip a coin.                                        - Random anime quote generator.
$wordle                                               $animequote anime_name
  - Generate a new wordle.                              - Generates a quote from that anime.
$guess word                                           $charquote anime_character
  - After generating a new wordle guess the word.       - Generates a quote from that character.

The bot is also able to detect if a user is spamming and send a message to tell them to stop spamming.

The bot uses three online APIs, which helps the bot collect information from these APIs to help fulfil its command. The three APIs include a
Dictionary API, Joke API and Anime API. The Dictionary API works alongside the wordle functions of the bot. If the user is unsure about what
a certain word means, that the bot choses for the wordle game, the user is able to use the command $wordDef to get a definition of the word.
The Joke API allows the bot the access a database of jokes which can be presented to the user, by using the $joke command. Lastly, the Anime 
API essentially does the same function as the Joke API however, instead of jokes it presents anime quotes. Whether the user wants a quote 
from a certain anime or character, the bot access the API to retrieve that information and display it to the users. 
