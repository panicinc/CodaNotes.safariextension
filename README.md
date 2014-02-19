At WWDC 2010, Apple introduced Safari 5. And with Safari 5? [Safari Extensions](https://extensions.apple.com), a new way for developers to add new functionality to Safari.

We do a pretty good job making life easier for people who hand-code websites using [Coda](http://panic.com/coda), our all-in-one web development environment. But is there anything we can do to make life better for the *client?* The person who’s paying the bills, or the marketing person, or the guy or girl who’s likely to call you and say, “Hey, can you make that one thing bigger, move that one thing and do that thing? By tomorrow?” Nobody knows what that means. And that’s something we thought we could improve.

Introducing **Coda Notes**, our Safari Extension for website annotation, and a fun little project.

![Coda Notes Front](http://www.panic.com/blog/wp-content/uploads/2010/06/CodaNotes1.jpg)

When you install Coda Notes, you’ll get a new button in your toolbar. Click it to see all our annotation tools, built right into Safari. Draw some notes on your favorite website. Communicate changes, ideas, concepts, or problems. Then, when you’re done, hit the Send Notes button and **the whole page flips over as a postcard**.

![Coda Notes Back](http://www.panic.com/blog/wp-content/uploads/2010/06/CodaNotes3.jpg)

Enter your comments, e-mail addresses, hit the nice looking “Send Notes” button, and that’s it! The developer gets an e-mail with your screenshot and notes, instantly. **In short, with Coda Notes, you can communicate in seconds what would have been much harder to communicate before, all without ever leaving Safari.**

And let’s not forget cool thing #2: **we literally added a new feature to Safari.** In a standards-based, clean way. This, my friends, is awesome.

(**Tech Note:** The Coda Notes extension is built entirely in JavaScript, HTML, and CSS; the extension bar is basically an HTML file, and the page-flip effect is accomplished using a CSS transform. We draw on a transparent `canvas` element injected over the target page. Live text editing is done by setting the `contentEditable` attribute on the body of the page, thus turning Safari into an editor, similar to how Apple Mail works!)

Thanks to Apple for letting us play with Safari Extensions, and thanks to [Neven](https://twitter.com/mrgan‎) and [Garrett](https://twitter.com/garrettmoon) for such great quick work on this project.

## License

Coda Notes is distributed under a modified version of the MIT License. See LICENSE for more information.
