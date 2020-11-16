# WebApp-Assignment1
Small website (HTML, CSS) for a "Web Application Development" course assignment

The website is intended to present a charity foundation of my invention which takes care of homeless people around the world. The name ‘iCare Foundation’ came to my mind from [iCare Housing](https://www.icarehousing.ie).

I tried to use as many HTML5 elements as possible, so I decided to design every page layout with the following semantic elements:
* nav
* header
* section
* footer

The website is structured on five different pages, each with fixed top navbar and bottom footer:
* index.html: the main page and landing page. It contains an embedded YouTube video which I picked as it is short and gives an overview about the homelessness problem (although it is focused on the Los Angeles metropolitan area). For the image logo I used the CSS ‘box-shadow’ property from [this link](https://css-tricks.com/almanac/properties/b/box-shadow). For the text logo I used the CSS ‘text-shadow’ in a pretty similar way.
* about.html: this page gives more text information about the Foundation, and it is made of 3 sections each with a different background image and with some CSS hover property.
* projects.html: this page introduces some projects the Foundation has been working on and it presents the content with the form of a 2-column table, with alternate row colours from CSS ‘nth-child’ (odd&even) properties.
* gallery.html: this page contains an image gallery from [W3Schools](https://www.w3schools.com/css/css_image_gallery.asp) styled with CSS properties and transformations.
* contact.html: this page gives the contact reference for the organisation and contains the <address> tag as long as some social media buttons using an external icon library (from [here](https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css) and [here](https://www.w3schools.com/howto/howto_css_social_media_buttons.asp)).

The ‘icare.css’ file contains the style settings for ‘index.html’ and for the navigation bars and footers in all other pages.
Each page apart from ‘index.html’ refer to two different external style sheets: one is ‘icare.css’ (as written above) and one other dedicated css file (e.g. ‘projects.css’).

I tried to make the navigation bar and footer responsive for small screen use by setting a media query (from [here](https://www.w3schools.com/howto/howto_js_topnav_responsive.asp)); when the browser width falls under 800 pixels the navigation bar as well as the footer should not appear.

Generally speaking, W3Schools has been a great reference for my website, both regarding HTML and CSS.
I found the process of creating a small and very simple website very challenging as I have not had any HTML and CSS experience before.
