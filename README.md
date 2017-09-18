# textillate-preserved
Modified textillate jquery plugin to preserved formatting tags

The original jquery.textillate.js was using jquery.lettering.js, the issue with the library was unable to preserved tags in the animation sentence. I have modified the jquery.textillate.js to use charming.js which able to keep the tags. However, the issue with charming.js was not wrapping the characters based on original wording, that will introduce problem when having a multi-lines sentence. In order to make it to work, i have modified charming.js to wrap the letter into word grouping.  

In order to test, you can use jquery.textillate.preserved.js and includes dependency files assest/charming-word-wrap.js and assest/format.css.
