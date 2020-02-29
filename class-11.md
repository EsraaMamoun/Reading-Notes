## Images
* Images are very helpful and important in coordinating pages and clarifying many things.
- In CSS and HTML:
> We can specify the dimensions of images using CSS. This is very helpful when we use the same sized images on several pages of our site.
> Images can be aligned both horizontally and vertically using CSS.
> we can use a background image behind the box created by any element on a page.
> Background images can appear just once or be repeated across the background of the box.
> we can create image rollover effects by moving the background position of an image.
> To reduce the number of images our browser has to load, we can create image sprites.

## Practical Information

### Search Engine Optimization (SEO)
* The Basics:
- Search engine optimization (or SEO) is the practice of trying to help your site appear nearer the top of search engine results when people look for the topics that your website covers.

* On-Page Techniques
> - On-page techniques are the methods you can use on your web pages to improve their rating in search engines. The main component of this is looking at keywords that people are likely to enter into a search engine if they wanted to find your site, and then including these in the text and HTML code for your site in order to help the search engines know that your site covers these topics.
>> 1. Page Title.
>> 2. URL / Web Address.
>> 3. Headings.
>> 4. Text.
>> 5. Link Text.
>> 6. Image Alt Text.
>> 7. Page Descriptions.

*Off-Page Techniques
- Getting other sites to link to you is just as important as on-page techniques. Search engines help determine how to rank your site by looking at the number of other sites that link to yours. They are particularly interested in sites whose content is related to yours.

* Analytics tools such as Google Analytics allow you to see how many people visit your site, how they find it, and what they do when they get there.
* To put your site on the web, you will need to obtain a domain name and web hosting.
* FTP programs allow you to transfer files from your local computer to your web server.

## Flash
- Flash is a very popular technology used to add animations, video, and audio to websites, but now it is not supported on iPhone or iPad, and it is not used much.

## HTML5 video and audio
- The <video> and <audio> elements allow us to embed video and audio into web pages.

* The HTMLMediaElement API makes a wealth of functionality available for creating simple video and audio players.

`The <video> element contains two <source> elements so that different formats can be loaded depending on the browser viewing the site.`

**The controls HTML is probably the most interesting:**
> <button>We have four buttons — play/pause, stop, rewind, and fast forward.
>Each button has a class name, a data-icon attribute for defining what icon should be shown on each button (we'll show how this works in the below section), and an aria-label attribute to provide an understandable description of each button, since we're not providing a human-readable label inside the tags. The contents of aria-label attributes are read out by screenreaders when their users focus on the elements that contain them.
>There is also a timer  div, which will report the elapsed time when the video is playing. Just for fun, we are providing two reporting mechanisms — a span containing the elapsed time in minutes and seconds, and an extra div that we will use to create a horizontal indicator bar that gets longer as the time elapses. 