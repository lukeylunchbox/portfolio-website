# Luke's Portfolio Website
### www.lukecolcott.netlify.com

## Target audience
My primary intended audience is employers. I'd like this site to act more as a visual portfolio to store all of my work (once I've got some to show).
It is a lot more visually aesthetic than just a simple Github link.
Secondly, this site could function as a simple way for other developers to contact me to collaborate or just discuss code. 

## Design Goals
My website was created to satisfy the following criteria;
- Friendly and inviting landing page
- Design reflects my style and personality
- Compatible with multiple devices of multiple resolution
- One page setup
- Page features downloadable resume

# Inspiration for my website

Being completely new to design, I really struggled to conceptualise an idea.
I decided to make the website reflect me and my personality. At least that would be a good place to start.
I knew I loved urban environments. I am very much a city kid. To me, there's something hypnotic about the chaotic life in a busy city.
I spent three years living in some of Asia's biggest cities, no doubt perpetuating my love for the hustle and bustle.

I needed to bring this together into a design. I decided it would be based on cities. It needed to illustrate a busy, generic city, yet symbolise some sort of individualism. 

To achieve the generic city mood, I decided to go black and white. To create individualism, I decided to sparingly use a really 'out-there' colour.
That's me. I can be a little out-there. 

Of course, all this had to be done tastefully. I love the idea of minimalism, however I'm afraid of boring. My initial images were to be of Asian cities where I've lived. However finding the perfect image after many, many hours of searching wasn't going well. Until I found a perfect city image of Melbourne.    

## Pinterest Mood Board and Figma

Initially, I was going for a lot of colours. I'm fairly outspoken at times, so I felt this was appropriate. 
I loved the city images of Hong Kong and other parts of China, having lived there for a few years. I also love the sea and everything logistics, hence the shipping and ports images. 

![designs](/assets/img/moodboard1.png)

After selecting the image I thought suitable, I chose a color scheme to match.

![designs](/assets/img/first-design.png)

After creating the above image in Figma, I then realised there was a bit too much going on for a landing page.
I felt the image was distracting. Back to the drawing board!

After creating an assortment of different style and colour schemes, I decided to go black and white.
All the colour seemed distracting. I ended up going super-minimalist, with a hint of colour. Aquamarine!
As soon as I saw the contrast of the aquamarine on a black and white image of Melbourne, I knew I'd found my combination. 

![designs](/assets/img/final-design.png)

This was the mock up design and colour palette I ended up with. I still cannot believe how long the design process took. Even though the style is simple, it took me many, many hours to agree with myself on. 

To see all my design choices, visit my Figma page [Figma](https://www.figma.com/file/ZjH2R84aPIWzQ6t00ui62XdK/Portfolio-website-design)

Next it was onto fonts.

## Fonts

As I knew nothing about font whatsoever, it was research time. The most important this I learnt was that fonts need to be paired.
I spent a long time hanging around Google Fonts to find my perfect font.
Even then, the fonts I liked didn't compliment each other. I did some more research and found an 'approved' partner for Raleway. That was Roboto Slab.

![fonts](/assets/img/fonts.png)



## Site design brainstorming
### [Link to figma design page](https://www.figma.com/file/RnGsy5M5tvyq9G7XC8Fadb9j/Portfolio-site-init)

Having no idea what direction to take it in, I thought incorporating water in some way would be a good start, so I searched some splash screens I thought did a good job of that to serve as some inspiration:

![splash screens featuring water](/readme-assets/splash-water-examples.jpg)

I then searched [unsplash.com](https://unsplash.com/) for some photos and came across these:

![unsplash photos with sea themes](/readme-assets/unsplash-pictures-chosen.jpg)

I liked the plain rock cliff with water at the bottom, but didn't like the person floating so I edited it so that the person was removed, then started brainstorming some [design ideas for the top banner of my site to be on figma](https://www.figma.com/file/RnGsy5M5tvyq9G7XC8Fadb9j/Portfolio-site-init). I still had no idea what general direction I wanted to go in and was just trying out things to see what looked good. Eventually got the look of the white fading into the cliffs which I liked, it was during this process that I realised the profound difference your font choice really does make to the look of the site, and liked the look of the Josefin Slab font.

![process of brainstorming my banner](/readme-assets/my-banner-brainstorming.jpg)

### Design realised!


### Alignment conventions

Text blocks shall be centered on the site and left justified.
Image content and buttons where possible shall be right justified.

### Font

#### Body text
Use the Google font 'Josefin Slab', bolded, with line spacing of 120%, fallback to generic system serif font.

#### Heading 1
Same as body text font but 80/18 (4.45x) times larger font size.

#### Heading 2
Same as body text font but 36/22 (1.6x) times larger font size.

#### Buttons
Same as body text font.

### Link behaviour

#### Text link properties (including hover behaviour)
Same as general body text but has a dotted underline (no colour change upon visiting a link), upon hovering remove underline and change text colour to the light blue of the colour scheme (#A0EBDD).

#### Icon links
Minimum width (mobile phone screen) 45 pixels, ideal width (mobile phone screen): 50 pixel, maximum width: 100 pixels. Default colour same as general body text colour #DEE8E0. Upon hover, change colour to #A0EBDD and add white shadow 1 px on the right.

### Borders
Button and text/input box borders: use color #A0EBDD for border, use 1 px width and radius the corners by 3px.

## Image optimisation
To ensure that the website loads in a reasonable time, the backdrop image that shows the coastal cliff was edited in GIMP to fix in the fade to white at the top and the fade to turquoise at the bottom. 
This simplifies the image as it now does not need to do any transparency and neither do I need to fiddle with trasparent blending with CSS. I then shrunk the image to a resolution where its width was the maximum number of pixels I would support before constraining all the content of my site via ‘tunnel vision' such as in this example:

![tunnel vision example](/readme-assets/tunnel-example.jpg)

Since the image would never be stretched farther than this maximum width of the content then its resolution doesn't need to be any higher. 
Additionally I then also lowered the quality of the final JPG compression when I exported the image from GIMP and this resulted in a filesize of 112KB, down from an original photo size of 2.9MB

![backdrop editing](/readme-assets/backdrop-editing.jpg)

Since the image fades to that turquoise colour it was trivial to achieve a seemless blend with the &lt;div&gt; that comes afterwards which fades from that turquoise to black signifying the deeper the darker.

## Sourcing icons
The icons I've used on my site (such as LinkedIn, Github and Twitter) were added with icon resources that use special fonts as the icons. 
I used http://konpa.github.io/devicon/ for the Github and Twitter icons but that didn't have one for LinkedIn.
I used http://fontawesome.io/icon/linkedin/ for the LinkedIn icon.


## Usability

Designing the site I kept reader usability in mind at all stages:

* A single page site was adopted to ensure no content would be missed (such as might have happened if multiple HTML pages were used with navigation links between them).
* Site content was optimised for viewing on a mobile phone as this typically represents the most constrained amount of space to present the content as well as what the vast majority of visitors will be viewing from.
* Bio text was revised throughout to make it as concise as possible while still conveying my personality but keeping it short so that users would not be hit with an intimidating wall of text. 
* Increased font size and line spacing was used to make the site more pleasant to read.
* Line lengths were kept within the optimal 50 to 60 character range of readability.
* Opengraph and Twitter metadata was added for seemless social media link summaries.
* Customised Thankyou screen to be displayed to the user after they submit a message through the Netlify integrated form.

## Domain name
My domain name alexpalma.io was purchased through [namecheap.com](https://www.namecheap.com/),
The .io top level domain (TLD) belongs to the British Indian Ocean Territory and from some reading around seems to have been unofficially adopted by the tech community. For me alexpalma.com was already taken and alexpalma.com.au seemed to require a proof of an Australian business (ABN number, patent number, trademark application etc). alexpalma.io was not too expensive at under $40 a year so I opted for that. 
I registered on namecheap as part of purchasing the domain.

## Web hosting service
### Hosting
I went with hosting on [netlify.com](https://www.netlify.com/) (predominantly because it is the service we had already used in class before *and* it was free.)

Hosting on Netlify allowed me to easily update my site by just dragging the folder that contains all the site's files into my netlify deploy screen.

Netlify also provides the functionality to facilitate the processing of messages submitted through the contact form on the page, which keeps my email away from spam bots looking for email addresses.
#### Setting up the contact form
When you have a Netlify page being hosted, you can log into your Netlify account and click on your page and there's a section in the settings for the page called 'Forms' which pretty much has some source code you can copy and paste into your site's code if you want to implement a contact form that is handled through Netlify, you can view any messages submitted through your form by logging in to your Netlify account and viewing them there, but even easier you can adjust the settings to direct Netlify to forward a copy of any messages to an email address of your choice. (Some of the other students went with a solution called [formspree](https://formspree.io/) for the implementation of their contact forms.

### Associating my domain name to my Netlify site
I did a quick search online for any guides as to the general process of linking domain names to a particular server and from that learned that the general process is:
* Inform your web hosting service what your custom domain name is and which one of your sites you would like them to direct it to.
* Determine what your web hosting service's servers are for resolving domain names. Typically at least 2 servers but may be more.
* Go to the domain name registrar you registered your domain name with and instruct them to redirect requests for your domain name to the servers you determined in the previous step.

The process really was that easy, I got the list of servers netlify uses for custom domains from within the settings of my site where I also specified what custom domain it would have (alexpalma.io) and then I went to [namecheap.com](https://www.namecheap.com/), logged in, and instructed it to redirect to a third party web hosting service and entered the server names in the fields provided.

It was really much easier than I would have thought!

### Establishing HTTPS on my site
Another plus for Netlify, the process for procuring and establishing an SSL certificate for your site was super straight-forward. On Netlify I just had to follow the instructions to run a couple commands to verify that my domain name *was* being correctly routed to netlify and then it was just a matter of clicking a button to get Netlify to arrange for a free SSL certificate provided by the [Lets Encrypt](https://letsencrypt.org/) initiative.

## The process
### Favourite parts
* When I finally realised what I wanted the site's design to look like, I got really excited to work on it then!
* Getting my backdrop image to display correctly aligned which was the result of me messing around with random values for the background-position-y attribute and giving up when using a percentage value seemed to get close to what I wanted but didn't seem to be making any sense to me, then reading the documentation on the attribute and seeing the actual definition of percentage as being the difference between the image's height and the height of the container the image had to fit in so setting it to 100% worked to ensure the bottom of the image would remain ‘pinned' to the top of the edge of the subsequent container &lt;div&gt;.

### Struggles
* Spending over an hour trying to wrestle css into making link underlines appear how I wanted them to. It was all because after a quick search and finding **text-decoration** and **text-decoration-style** I mistakenly assumed for some reason that the two were the same thing and they had just gone with a different name in later versions of HTML. They were actually different things. My current understanding is that **text-decoration-style** *depends* in a sense on **text-decoration** in that **text-decoration-style** doesn't matter if **text-decoration** is set to none.
* Not knowing how I should have applied the process of design to final implementation. I assumed we were to design our completely finalised design in wireframes before moving onto the actual development of the site but struggled to pin down how exactly I wanted it to look before moving onto the coding aspects. I felt like it may have been faster for me to just code it up and change the code to get to where I would feel happy with the look because otherwise it meant I would have to go back to the design of the wireframes and redo aspects if I wanted to change or add extras which I felt would be an inefficient process. Admittedly the importance of the wireframes may have been slightly lost on me given that I was not working on this with anyone else collaboratively.

### What would I do different next time?


* Make use of git from the start. I didn't start using git till towards the end of the week. 
* Make use of SASS or some other CSS preprocessor to aid in consistency. Currently values in my website are getting their final *style* after they 'cascaded' multiple times which I feel is difficult to read. The reason I didn't do this or git from the start is that I underestimated the complexity that my CSS file would grow to become and did not feel completely confident in the advanced use of either git or SASS and felt I did not have enough time to get the site looking as good as I wanted if I was spending time learning intricacies of git and SASS which in hindsight was a mistake as both would have added to my productivity in a huge way.
* Start on the README.md file from the beginning. I was just keeping notes in a word document and the translation into the README.md file took up a bit of time that wouldn't have been needed if I'd written straight into the README.md from the beginning.
* Planned the build process better from the start in that I should have determined what the absolute bare minimum viable product would be, and which features were my desirable nice-to-have's and then completed all aspects of this project to the point of the bare minimum and from then subsequently improving. Instead I didn't decide to do this until later in the week, which meant I was still working on my documentation on Saturday which should have been spent polishing it all and working on my presentation of it on Monday. I've since learned the huge importance of progressively improving the project through git branches which only get merged into the master branch once they're perfect which ensures the master is in an ever ready-to-present state.

## Notes

Some of my earliest thoughts for what effects I might do which never eventuated:
* Have progressively out-of-focus images of circuit boards in transparent images stacked on top of each other with parallax effect happening.
* Produce a CSS effect that mimics little dust particles that sparkle when in the light of a torch.
* Maybe an effect to simulate text printing on the screen as if it were being typed, including a blinking cursor could be incorporated somehow.

## Notes from observations of fellow students sites
A collection of some of the things other students did which I did not consider but will now are:
* Using a CSS and HTML minifier to shrink the code so as to shrink the file size for a faster loading site.
* Setting my links to my other pages (like github etc) to open in a new tab instead of the same tab.
* Using [online tools](http://leaverou.github.io/contrast-ratio/) to verify the readability of my site's text
* Mentioning some of the exercises we've done in class as projects, while not true projects in the same sense they still showcase what I've spent a lot of my time during this course working on and can be replaced by more 'serious' projects as I acquire more experience.
