# NOTES — P1 · Color + Typography

## Intent
The first page should be travel blog about a young couples trips they go on together. It should feel clean, modern, and appeal to other young couples interested in traveling. The second page is a memorial home's home page for families that have lost someone, or are planning in advance, that descrbies their services and businesses. It should feel professional, empathetic, and trustworthy.

## AI use
I asked the VS Code Copilot chat for help creating a plan to build to three pages. On each page I suggested a theme and colors for the palette, but asked for font pairing suggestions. I worked on the travel blog first by describing the structure I wanted and then asking AI to build out my description. Then I asked AI to build a prototype of the second page for me to review, edit, and refine. For example, "On the memorial page put cream block backgrounds behind each of the services. There should be 3 total and they should be equal in size". Lastly, I had AI create a homepage that connects those two pages together.

## Accepted / changed / rejected
I accepted the general structure of both pages, like section headings and filler content suggestions, but I rejected the page titles. They were pretty blang originally and I customized them to myself. I ended up with Tagge Trips and Tagge Family Memorial Care. I rejected the original color schemes that were suggested to be. The were dark teal, black, and white. I changed that to white, black, gray, and light blue for the travel page and a cream color on the memorial page. I went through severl layout iterations for each page to change then structure. On the blog I added the blog posts, and on the memorial page I changed the layout of the our services section. I rejected the original styling of the home page becuase it was also dark teal and changed it to a minimilistic black and white page so it was easier to read.

## Dig deeper
One thing I looked up to dig deeper was the hero section I requested be built on the travel page. I was wondering how the inset: 0 worked inside of the .hero-overlay, so I looked up the inset CSS property (https://developer.mozilla.org/en-US/docs/Web/CSS/Reference/Properties/inset) and learned that inset: 0 sets the overlay's offset on all sides to zero. That streches the overlay to the edges of the container block it's in. This affects the overlay and not the actual image. I changed the inset to 1rem to see what would happen and the overlay pulled away from the edges of the container.

## Open questions
How do you check text contrast when the text is over a photo with a gradient? I just used the lightest spot under the text to check the contrast for this project, but is there a certain way to do that?

