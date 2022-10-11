# Learning to Reuse Distractors to support Multiple Choice Question Generation in Education
This benchmark dataset accompanies the article paper titled ``**Learning to Reuse Distractors to support Multiple Choice Question Generation in Education**''. It contains 298 educational questions for secondary school students covering six subjects: English, French, Natural Sciences, History, Biology and Geography, and a 77k multilingual pool of distractor vocabulary. 
The dataset has two parts put in two folders.
1. The first folder, **test-MCQs**, contains 6 JSON files, each corresponding to a subject as indicated by its filename. Each JSON file contains a list of all questions for the particular subject in the following format:
```
[

{
  "question": "What is the capital of Belgium?",
  "answer": "Brussels",
  "language": "en",
  "distractors": ["Ghent", "Amsterdam", "Antwerp"
        ]
},

{
  "question": "1.47 How do I get to the airport from here ? Do n't worry , I ... ... ... ... you .",
  "answer": "'ll show",
  "language": "nl",
  "distractors": [
      "show",
      "am showing",
      "'m going to"
  ]
  },
.
.
.
]
```
2. The second folder, **vocab**, has one JSON file containing the pool of multilingual distractors. It contains a set of all distractor: frequency tuples.  
```
{
    "ongelofelijk": 30,
    "geloven": 17,
    "afbeelding 2": 4,
    "afbeelding 3": 1,
    "United Kingdom": 1,
    "variete": 1,
    "vitesse": 1,
    "wide band": 1,
    "big band": 1,
    "browser": 1,
    "bref": 1,
    "absent": 1,
    "achter op": 1,
    "gsm'en": 1,
    "Alles Gute zum Vorstellungsgesprach ": 1,
    "Mein herzliches Beileid ": 1,
    "Ouvre la fenetre ": 1,
    "verlangens en behoeften ": 1,
    "onpartijdig analyse van de markt ": 1,
    "0,53 ": 1,
    "1,00 ": 1,
    "1,09 ": 1,
    .
    .
    .
}

````
