# Lab Report 2

### File with image reference
Code change diff screenshot:
![code diff](images/lab-report-2-1.png)
[Link to test file with failure-inducing input](https://jadenbanawa.github.io/markdown-parser/test-file.md)
![symptom of failure inducing input](images/lab-report-2-2.png)

The bug that the code encountered was that the MarkdownParse method getLinks was returning an array that included an image source link, when it is not supposed to. The assertEquals was comparing the outputted array to an expected array that does not include the image link, therefore it displayed an error. This is because, in the getLinks method, there is no code that approaches the syntax of an image link, which is the same as a normal link, except with an exclamation point.


### File that starts with a link


### File that has characters after link

