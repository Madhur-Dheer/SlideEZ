# An automated tool, is an impromptu PPT generator which considers the input as response from the speaker and converts it into a slide in the presentation.

## Benefits of SlideEZ:

1. Saves time for both the speaker and the listener
2. Easy use, starts converting speech to text at the press of a simple button
3. Gives summarized information along with image keyword recognition
4. Your notes partner for every lecture, class or seminar


##Build flow:

1. Speech to text conversion
2. Sentence segmentation and sentimental analysis
3. Image request and extraction
4. Keyword generation and summarizing
5. Final presentation



## Tools and frameworks:

1. TextRazor API
2. Bing API
3. Python pptx library
4. DeepSegment library
5. Google Speech Recognition API
6. EEL python framework


## Steps to run:

1. Open a terminal in the folder.
2. Run the mainApp.py
3. Use the Eel desktop app to generate the ppt

### Concept used for indentifying the request for object/image in a sentence

The sentimental analysis was carried out by creating a custom dataset which will differentiate between a sentence requesting an object or not.

### Determining the heading of every Slide of the ppt

An n-gram nlp based model was designed to analyze the text recieved and create an important heading for every slide. Similar model was used for summarizing text etc.

### Deep Segment Utilization

It was used to convert the text into important sentences. It is an Bert and Elmo model based open scoure library developed by Stanford.


