# word-cloud
Here is the python code which graphically represents the word frequency that give greater prominence to words that appear more frequently in a source text. The larger the word in the visual the more common the word was in the document.

For this project, you'll create a "word cloud" from a text by writing a script. This script needs to process the text, remove punctuation, ignore case and words that do not contain all alphabets, count the frequencies, and ignore uninteresting or irrelevant words. A dictionary is the output of the calculate_frequencies function. The wordcloud module will then generate the image from your dictionary.

<h1>Things to remember</h1>

- Before processing any text, you need to remove all the punctuation marks. To do this, you can go through each line of text, character-by-character, using the isalpha() method. This will check whether or not the character is a letter.

- To split a line of text into words, you can use the split() method.

- Before storing words in the frequency dictionary, check if they’re part of the "uninteresting" set of words (for example: "a", "the", "to", "if"). Make this set a parameter to your function so that you can change it if necessary.

<h1>Project goal</h1>

-Create a dictionary with words and word frequencies that can be passed to the generate_from_frequencies function of the WordCloud class.

-Once you have the dictionary, use this code to generate the word cloud image:
>cloud = wordcloud.WordCloud()
><br>
>cloud.generate_from_frequencies(frequencies)
><br>
>cloud.to_file("myfile.jpg")

<h1>Outcome</h1>
![word_cloud output](https://user-images.githubusercontent.com/70971734/140272000-9b72dd8f-1254-4240-9c99-f54300ac825b.png)

  
