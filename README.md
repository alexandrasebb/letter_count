
---

# Letter Count

A small project to practice my Python skills.

## Name Letter Frequency Analyser

This Python script analyses the frequency of letters in a given name, identifies which letters of the alphabet are missing, and calculates the percentage of the alphabet that the name covers. Additionally, it calculates the Scrabble score for the name both with the limited number of tiles available and assuming unlimited tiles.

### Features

- **Letter Frequency Analysis:** Counts how many times each letter appears in the given name.
- **Missing Letters Identification:** Determines which letters of the alphabet are not present in the name.
- **Alphabet Coverage Calculation:** Calculates the percentage of the alphabet that is represented by the unique letters in the name.
- **Sorted Output:** Provides a dictionary of letters sorted by frequency (highest to lowest) and alphabetically in case of ties.
- **Scrabble Score Calculation with Limited Tiles:** Computes the total Scrabble score for the name based on the available tiles.
- **Maximum Scrabble Score Calculation:** Computes the maximum possible Scrabble score for the name assuming unlimited tiles.

### Getting Started

#### Prerequisites

- Python 3.x

#### Installation

Clone the repository:

```bash
git clone https://github.com/alexandrasebb/letter_count.git
cd letter_count
```

Run the script:

You can simply run the script using Python:

```bash
python letter_count.py
```

### Usage

By default, the script analyses the Welsh place name `Llanfairpwllgwyngyllgogerychwyrndrobwllllantysiliogogogoch`. If you wish to analyse a different name, modify the `name` variable in the script:

```python
name = "Your Name Here"
```

Run the script to see the results. The output will include:

- The total number of characters in the name.
- The number of unique letters in the name.
- The percentage of the alphabet represented by the name.
- A list of missing letters.
- A dictionary of letters sorted by frequency and alphabetically.
- The total Scrabble score with the limited number of available tiles.
- The maximum possible Scrabble score assuming unlimited tiles.

### Example Output

```
Llanfairpwllgwyngyllgogerychwyrndrobwllllantysiliogogogoch is 58 characters long and contains 13 unique letters.
You have collected 50% of the alphabet.
Number of missing letters: 13
These are: ['b', 'd', 'e', 'h', 'i', 'n', 'o', 'r', 's', 't', 'u', 'v', 'z']
These are the letters Llanfairpwllgwyngyllgogerychwyrndrobwllllantysiliogogogoch contains, sorted by frequency (highest to lowest) and alphabetically: {'l': 14, 'g': 8, 'o': 7, 'w': 6, 'y': 6, 'n': 5, 'r': 3, 'a': 3, 'i': 3, 'f': 1, 'p': 1, 't': 1, 'c': 1}
The total potential Scrabble score for Llanfairpwllgwyngyllgogerychwyrndrobwllllantysiliogogogoch is: 57
The maximum Scrabble score for Llanfairpwllgwyngyllgogerychwyrndrobwllllantysiliogogogoch with unlimited tiles is: 75
```

### Customisation

Feel free to customise the script to:

- Analyse different types of text (not just names).
- Include additional metrics or data visualisations.

### Contributing

Contributions are welcome! Please fork this repository and submit a pull request for any enhancements, bug fixes, or features you would like to add.

### Contact

For any questions or feedback, please reach out to:

Alexandra Boliver-Brown - aboliverbrown@hotmail.com  
GitHub: [alexandrasebb](https://github.com/alexandrasebb)

---
