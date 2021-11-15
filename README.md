# 02-Professional-Portfolio

This project is the first draft of my professional website. It is the foudation for displaying my projects and accomplishments as I move along in the Bootcamp.

## Criteria

- The page includes:
    - My name and photograph
    - A work section linking to my projects
        - The first project image is larger than the others
    - A navigation section that links to the corresponding sections on the page
    - My contact information
    - The page layout is responsive and will change based on the size of the user's viewport
    - The page follows a provided mock-up

### Caveats

Because I have not completed enough projects to fill out the links in the 'Work' section, many of the links are dummies. When you mouse-over, you will see the browser reacts as if there is a link. The only one that actually links is Run Buddy, which links to the GitHub page.

The background images in the Work section are placeholders as well, save again for run-buddy, which is a screenshot of the actual page, as found in the mock-up.

## HTML

The HTML is straightfoirward. The body is divided into 5 primary parts - the header, hero, bio, list of work, and footer. I defined the class 'stylebox' early on, noticing the mock-up used light blue boxes for h1, the tagline in the hero, and for labeling in the list of work. I figure in the future I can change this class for color schemes or whatever seems fit. 

The 5 primary parts are then subdivided - the final 3 all share the indent class, another design approach used in the mock-up. In general the idea was to create a layout that would be CSS-friendly.

### Links

As previously mentioned, many links in the work section are dummy links, save for Run Buddy. All navigation section links send the user further down the page, except for the resume link, which opens a pdf in browser. In the contact information section, telephone, email and url links are used.

## CSS

The CSS is developed in accordance with the mock-up. This includes hover pseudo-class defined in the work section to allow for opacity in the images to change based on the position of the cursor. A pseudo-element is also defined to allow for placement of the tagline in the hero.

![](/assets/images/screenshot.jpg "Header and Hero")

## Responsive Layout

The CSS defines 3 media screen width parameters for the page - 980, 768, and 575 pixels.

### 980 Pixel Media Screen

At 980 pixels, the site stacks the indent divs on top of their respective sections, allowing for more horiszontal screen space for these sections. There are also minor changes to font-size where needed.

![](/assets/images/readme-980.jpg "980 Pixels")

### 768 Pixel Media Screen

At 768 pixels, the header splits to allow the navigation section its own row. In addtion, the About Me section centers. In the Work section, the images each gain their own row. And in the Contact Me section, the links each gain their own row.

![](/assets/images/readme-768.jpg "768 Pixels")

### 575 Pixel Media Screen

At 575 pixels, the links in the Navigation section each gain their own row.

![](/assets/images/readme-575.jpg "575 Pixels")