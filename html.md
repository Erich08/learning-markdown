# What is wireframing?

Wireframing is used by designers to create the basic design and flow of their website, application, or product. According to this [article](https://careerfoundry.com/en/blog/ux-design/how-to-create-your-first-wireframe/) on careerfoundy wireframing is: 
> Wireframing is a practice used by UX designers which allows them to define and plan the information hierarchy of their design for a website, app, or product. This process focuses on how the designer or client wants the user to process information on a site, based on the user research already performed by the UX design team.

## Online software that can be used for wireframing

* [UXPIN](https://www.uxpin.com/)
    * UXPin has a wide range of functionalities, but one of the best ones is how it facilitates building responsive, clickable prototypes directly in your browser.
* [InVision](http://www.invisionapp.com/)
    * InVision allows you to get feedback straight from your team and users through clickable mock-ups of your site design. It’s completely free too!
* [Wireframe.cc](https://wireframe.cc/)
    * Wireframe.cc provides you with the technology to create wireframes really quickly within your browser, the online version of pen and paper.

# What is HTML?

HTML stands for **H**ypertext **M**arkup **L**anguage. Think of it as the the structural part of a home or building. It consists of _elements_ such as H1 or H2, paragraphs, body, ordered and unordered lists, among many other things. 

According to MDN Web Docs [HTML Basics](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/HTML_basics) the main parts of elements are as follows:

1. The **opening tag**: This consists of the name of the element (in this case, p), wrapped in opening and closing angle brackets. This states where the element begins or starts to take effect — in this case where the paragraph begins.
2. The **closing tag**: This is the same as the opening tag, except that it includes a forward slash before the element name. This states where the element ends — in this case where the paragraph ends. Failing to add a closing tag is one of the standard beginner errors and can lead to strange results.
3. The **content**: This is the content of the element, which in this case, is just text.
4. The **element**: The opening tag, the closing tag, and the content together comprise the element.

## Structure of an HTML document

The structure, or anatomy, of an HTML document is as follows:

* <!DOCTYPE html> — doctype. It is a required preamble. In the mists of time, when HTML was young (around 1991/92), doctypes were meant to act as links to a set of rules that the HTML page had to follow to be considered good HTML, which could mean automatic error checking and other useful things. However these days, they don't do much and are basically just needed to make sure your document behaves correctly. That's all you need to know for now.
* <html></html> — the <html> element. This element wraps all the content on the entire page and is sometimes known as the root element.
* <head></head> — the <head> element. This element acts as a container for all the stuff you want to include on the HTML page that isn't the content you are showing to your page's viewers. This includes things like keywords and a page description that you want to appear in search results, CSS to style our content, character set declarations, and more.
* <meta charset="utf-8"> — This element sets the character set your document should use to UTF-8 which includes most characters from the vast majority of written languages. Essentially, it can now handle any textual content you might put on it. There is no reason not to set this and it can help avoid some problems later on.
* <title></title> — the <title> element. This sets the title of your page, which is the title that appears in the browser tab the page is loaded in. It is also used to describe the page when you bookmark/favorite it.
* <body></body> — the <body> element. This contains all the content that you want to show to web users when they visit your page, whether that's text, images, videos, games, playable audio tracks, or whatever else.
