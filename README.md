def unique_characters(text):
    return sorted(set(text.replace(" ", "").lower()))

if __name__ == "__main__":
    sentence = "Build momentum every single day"
    print(f"Sentence: {sentence}")
    print(f"Unique characters: {unique_characters(sentence)}")
