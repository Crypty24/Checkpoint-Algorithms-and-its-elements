# Checkpoint-Algorithms-and-its-elements
# Sentence Analysis Project

This is a simple Python project. The program reads a sentence entered by the user and analyzes it based on the following criteria:

- **Length**: Counts the number of characters in the sentence (excluding the final period).
- **Words**: Counts the number of words in the sentence (words are assumed to be separated by a single space).
- **Vowels**: Counts the number of vowels (a, e, i, o, u) in the sentence, regardless of case.

## How It Works

1. The program prompts you to enter a sentence that ends with a period (`.`).
2. It reads the sentence character by character until it reaches the period.
3. As it reads, it:
   - Increments a counter for every character (excluding the period).
   - Increments a counter for vowels when it detects any vowel.
   - Increments a counter for words whenever it encounters a space.
4. The final word count is the number of spaces plus one.
5. It then outputs the length of the sentence, the total number of words, and the total number of vowels.
