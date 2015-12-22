# *trans*lipi

## What is *trans*lipi?
The English alphabet is inadequate to accurately denote how words from Indian languages are pronounced.
Consider the word “anuswara”.
Does it refer to the Indic nasalization mark (anu-*swaa*-ra)?
Or does it refer to the subnote of Indian classical music (with the second syllable short)?
This confusion is especially pronounced with blogs and websites that deal with subjects whose vocabulary abounds in Indic terms.

One could write these words in (say) Kannada, but this would put non-Kannada readers at a loss.
The script that each reader is most comfortable in is different.
Hence *trans*lipi.

*trans*lipi consists of two parts:

* A widget with a drop-down list for the user to select a script, and
* Browser-side code (in JavaScript) that transliterates the marked-up text into the chosen script.

The text to be transliterated needs to be in Harvard–Kyoto notation.
One way to mark the text is by surrounding it with `<span lipi=1>` and `</span>` tags.
Alternatively, if the text is already part of an existing HTML element, just include the attribute `lipi=1` in the opening tag.

## Installation

### Blogger blogs

To install *trans*lipi for a Blogger blog:

1. Install the translipi widget.
    1. Open the blog layout management page.  In the sidebar, choose “Add gadget”.
    2. In the popup, select the “Add your own” tab.
    3. Enter ``http://sahityam.net/translipi.xml`` in the URL textbox.  Click on the “Add by URL” link.  Save the gadget settings.
2. Add the JavaScript code.
    1. Open the blog template management page.  Click the "Edit HTML” button.
    2. Copy the two script elements from the [this file](https://github.com/srikanthsubra/translipi/blob/master/blogger/blog.html).  Paste them between the `<head>` and `</head>` tags in the blog HTML code.
    3. Save the changes.

To test, mark up some text in a post for transliteration, as described earlier.  Open your blog and verify.  That's it!
