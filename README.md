# Yarn2FountainExp
A tool that converts stories written in Yarn Spinner by Secret Lab to Fountain Exponential.

Fountain Exponential and Yarn Spinner are very similar, but where Ink focuses on programming power, Fountain Exponential focuses on readability. This means that Yarn Spinner messes things together for briefness. This is specifically so with varying the display of the text. Fountain Exponential will separate thing out so it will be easier to see where things start and end.

## Technical approach
The conversion will probably entail the following steps:
1. A parser for Yarn Spinner  by YarnSpinnerTool will be created based on the sources available on Github.
2. After the story has become a parse tree in memory, we match the elements with those in Fountain Exponential.
3. Then we might do some optimizing and beautifying on the converted parse tree.
4. At last we flush the Fountain Exponential parse tree to a file.
