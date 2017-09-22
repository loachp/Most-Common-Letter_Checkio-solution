def checkio(text):
    cleaned = sorted(text.lower())
    maximum = 0
    highest = ""
    for letter in cleaned:
        if letter.isalpha() and cleaned.count(letter) > maximum:
            maximum = cleaned.count(letter)
            highest = letter
    return highest
