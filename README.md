# Welcome to Open Assistant!

Open Assistant or OA for short aims to create an open source voice controlled assistant for use at home or at work. This will make use of neural networks / paths for planning and voice recognition for control.


# Installation

OA is designed to run entirely on the go but a back-end / server might come in the end to help build a network better for more in-depth voice control. It can be setup by downloading a release and running the `.exe` .

## Running from source

To run and build from source you will need to ensure the required modules are installed. This can be done by running `npm i`

# Contributing

Contributing documentation to come soon!

## Diagrams / Workflow / Methodology

Diagrams to come soon!

```mermaid
sequenceDiagram
Alice ->> Bob: Hello Bob, how are you?
Bob-->>John: How about you John?
Bob--x Alice: I am good thanks!
Bob-x John: I am good thanks!
Note right of John: Bob thinks a long<br/>long time, so long<br/>that the text does<br/>not fit on a row.

Bob-->Alice: Checking with John...
Alice->John: Yes... John, how are you?
```

And this will produce a flow chart:

```mermaid
graph LR
A[Square Rect] -- Link text --> B((Circle))
A --> C(Round Rect)
B --> D{Rhombus}
C --> D
```
