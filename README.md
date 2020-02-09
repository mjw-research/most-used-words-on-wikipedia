# Most used words on Wikipedia

**The full list is way to big for GitHub (~1GB).**

**If you want the full list you will have to build it by your own like this:**

1. Download a Wikipedia dump from here: https://dumps.wikimedia.org/enwiki/
2. Extract the file (`bzip2 -d FILE`)
3. Rename the extracted file to `dump.xml`
4. Run `convert_to_text`
5. Run `calc_most_used_words`
6. (Optional) Modify the file