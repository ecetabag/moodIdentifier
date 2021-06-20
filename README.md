# Mood Identifier

Mood Identifier is a basic emotion analysis program written in Python using the Tkinter library. It is the first draft of a program which will eventually give percentages of each AP exam's positive and negative evaluations done by students. 

## Usage
The program asks for 2 String input values. One being the name of the AP exam, and the other the opinions about the exam. The program then uses the twp String lists that consist of more than 800 words in total, seperated by being "positive" and "negative", to count how many times the evaluation includes unique positive and negative associated words. 

If the amount of unique positive words are greater than the negative words, the evaluation is considered as positive, and the other way around, negative. If the amounts are the same, it is considered as neutral.
```python
import foobar

foobar.pluralize('word') # returns 'words'
foobar.pluralize('goose') # returns 'geese'
foobar.singularize('phenomena') # returns 'phenomenon'
```

## Screenshots
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[MIT](https://choosealicense.com/licenses/mit/)
