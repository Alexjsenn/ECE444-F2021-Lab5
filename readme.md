# ECE444 Lab 5
Alexander Senn
this repo is a clone of https://github.com/nelaturuk/education_pathways.


## Activity 1
![Screen Shot 2021-10-14 at 9 48 04 PM](https://user-images.githubusercontent.com/28233112/137419375-65540241-f579-4a3a-8cae-00e696f1e20b.png)


## Activity 2-5
![Screen Shot 2021-10-15 at 4 53 11 PM](https://user-images.githubusercontent.com/28233112/137552261-d2542b49-44f5-4d90-9a43-bdd6909524f1.png)
![Screen Shot 2021-10-15 at 4 53 36 PM](https://user-images.githubusercontent.com/28233112/137552268-4ffe0046-20cc-465a-91c8-c39974471a21.png)
![Screen Shot 2021-10-15 at 4 53 44 PM](https://user-images.githubusercontent.com/28233112/137552280-19186a7a-6fcc-4287-b239-440fa2993343.png)

## Activity 6
The use of colors, spacing and layout (i.e. forcing the vertical layout) make the input fields drastically more intuitive. The previous interface made it confusing to determine what information needed to be entered, as some fields were side by side and others were below eachother. The new color scheme increases contrast as well, which makes it easier to see the actual input boxes.


## CARTE Education Pathways

## Description
Welcome to CARTE's in-development tool for course selection at UofT. Education Pathways allows for more intelligent course searching, by matching not just the terms you search, but ones relevant to them. The more terms you search for, the more relevant your results will be! Even try searching across disciplines for the courses that best cover each.

Whatever year you are looking for, Education Pathways will also suggest courses in earlier years that will best help you to prepare. To get the most out of this, try searching for courses in a later year and see what is suggested for your current one.

We are looking for feedback to improve Education Pathways and make it more useful for students. If you have ideas or suggestions, please email us!

## Setup Instructions

### With Docker



## Repository files:

`./Procfile ./wsgi.py` *tells gunicorn how to run the program*

`./environment.yml  ./requirements.txt` *specifies python requirements for anaconda and pip respectively*

`./__init__.py` *main flask code*

`./readme.md` *this file*

`./resources:` *contains datasets used in the program*

`course_vectorizer.pickle df_processed.pickle`

`course_vectors.npz       graph.pickle`

`./static:` *contains any static elements of the webpage, in this case just the CARTE logo*
`CARTE_logo.jpg`

`./templates:` *contains flask templates for rendering HTML*

`_formhelpers.html course.html       index.html        results.html`
