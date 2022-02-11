# Lab Report 2

How do I get the change diff from GitHub when it was done on screenshare with VScode? 

Original:
![Image](labreport2-1.png)
Change:
![Image](labreport2-3.png)

## Code Change 1
We added ```MarkdownParse.``` in front of ```getLinks()``` because getLinks was not a part of the test file. We had to reference it back to the Markdown file.

## Code Change 2
We added ```throws IOException``` to the end of ```getLinksTester()```. This will let us know if we have an input or output operation that failed.

## Code Change 3
In that same code, we also changed the values passed into ```assertEquals()``` since we were not getting the output correctly.
1. Instead of calling ```getLinks()``` on links, we referenced links directly.
2. Instead of passing in 1, we passed in ```new ArrayList<String>(List.of("https://something.com", "some-page.html"))```.

In the end, we were unable to fix all the bugs to get the test running smoothly.

Compiling errors:
![Image](labreport2-2.png)