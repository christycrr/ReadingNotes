Begin with a statement addressing why this topic matters as it relates to what you are studying in this module.
Answer each and every question or prompt presented in the assignment above.
If there are no questions provided, summarize and explain this topic via an analogy from your previous work or home experience.
Make a section in your notes titled ## Things I want to know more about, and anytime a question arises in your mind, or something catches your curiosity, note it under this heading.
If you utilize any content directly from the reading sources, be sure to identify what you are quoting, and cite the source.  
Answer 1:  "HTML can be used to structure a page of text by adding headings and paragraphs, emphasizing words, creating lists, and more." In HTML, each paragraph has to be wrapped in a <p> element, like so:

<p>I am a paragraph, oh yes I am.</p>
Copy to Clipboard
Each heading has to be wrapped in a heading element:

<h1>I am the title of the story.</h1>
Copy to Clipboard
There are six heading elements: <h1>, <h2>, <h3>, <h4>, <h5>, and <h6>. Each element represents a different level of content in the document; <h1> represents the main heading, <h2> represents subheadings, <h3> represents sub-subheadings, and so on."

Internal stylesheet
An internal stylesheet resides within an HTML document. To create an internal stylesheet, you place CSS inside a <style> element contained inside the HTML <head>.

The HTML for an internal stylesheet might look like this:

<!DOCTYPE html>
<html lang="en-GB">
  <head>
    <meta charset="utf-8" />
    <title>My CSS experiment</title>
    <style>
      h1 {
        color: blue;
        background-color: yellow;
        border: 1px solid black;
      }

      p {
        color: red;
      }
    </style>
  </head>
  <body>
    <h1>Hello World!</h1>
    <p>This is my first CSS example</p>
  </body>
</html>
Copy to Clipboard
"In some circumstances, internal stylesheets can be useful. For example, perhaps you're working with a content management system where you are blocked from modifying external CSS files.

But for sites with more than one page, an internal stylesheet becomes a less efficient way of working. To apply uniform CSS styling to multiple pages using internal stylesheets, you must have an internal stylesheet in every web page that will use the styling. The efficiency penalty carries over to site maintenance too. With CSS in internal stylesheets, there is the risk that even one simple styling change may require edits to multiple web pages."
JavaScript itself is relatively compact, yet very flexible. Developers have written a variety of tools on top of the core JavaScript language, unlocking a vast amount of functionality with minimum effort. These include:

JAVESCRIPT: "Browser Application Programming Interfaces (APIs) built into web browsers, providing functionality such as dynamically creating HTML and setting CSS styles; collecting and manipulating a video stream from a user's webcam, or generating 3D graphics and audio samples.
Third-party APIs that allow developers to incorporate functionality in sites from other content providers, such as Twitter or Facebook.
Third-party frameworks and libraries that you can apply to HTML to accelerate the work of building sites and applications."
GIT COMMIT MESSAGES
$ git log --oneline -5 --author pwebb --before "Sat Aug 30 2014"

5ba3db6 Fix failing CompositePropertySourceTests
84564a0 Rework @PropertySource early parsing logic
e142fd1 Add tests for ImportSelector meta-data
887815f Update docbook dependency and generate epub
ac8326d Polish mockito usage
"Conditional statements allow us to represent such decision making in JavaScript, from the choice that must be made (for example, "one cookie or two"), to the resulting outcome of those choices (perhaps the outcome of "ate one cookie" might be "still felt hungry", and the outcome of "ate two cookies" might be "felt full, but mom scolded me for eating all the cookies".)"
ut a well-cared for log is a beautiful and useful thing. git blame, revert, rebase, log, shortlog and other subcommands come to life
if...else statements
Let's look at by far the most common type of conditional statement you'll use in JavaScript — the humble if...else statement.

Basic if...else syntax
Basic if...else syntax looks like this:

if (condition) {
  /* code to run if condition is true */
} else {
  /* run some other code instead */
}