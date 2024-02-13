# Week2--Graphics-to-Forms
HTML Working with Graphics and Images
  -four attributes that need to be included for every image. 
      -First, we have the source attribute (SRC), which tells the browser which image file to load. 
      -Then we have the alt attribute (ALT), which provides a text description of the image. 
      -we have the width
      -height attributes, which determine the size of the image
       an ALT attribute, which serves as a replacement for the image when it cannot be seen. For instance, people who are visually         impaired may use a screen reader that reads the ALT text aloud to them.
       
  -Image Formats
    -There are four main file formats commonly used on the web these days, each with its own strengths and weaknesses when it          -comes     to compressing images. 
      GIF
GIFs are great for compressing illustrations that have large areas of the same color, but it falls short when it comes to photographs. It only supports 256 colors, and images can end up looking pixelated, unless you want that retro vibe. GIFs can have transparent areas, but the edges between transparent and solid parts can be jagged.

-SVG
    - perfect for logos, icons, and other types of illustrations. 
    -Unlike GIF, SVG is a vector file that contains instructions for drawing rather than individual pixels. 
        -means it can be scaled to any size without losing quality, and the file size remains small.

  -JPG
    -JPGs are a popular choice for compressing photographs. Most digital cameras save images in JPG format, but when placed on the web, it is important to resize and compress them appropriately. Avoid using gigantic, half-compressed JPGs on your websites as they will slow the loading speed. 

-PNG
  -PNG is a newer format that works well when you need transparency in a photograph. It sometimes outperforms both GIF and JPG in compressing certain types of images.

Responsive images
  -when resizing images, the size can be ideal for phone devices. When you load it on a pc, the picture can com across as a blurry picture . Responsive images come to this aid.  
    -HTML allows us to deliver different image files to screens of different sizes. We can create multiple image files and include them as options in our HTML code. Then, the browser, in collaboration with the operating system, takes into account the device's hardware capabilities and network speed to decide which image to download. 
    -create multiple copies of an image with different resolutions and inform the browser about these options. Then, the device can choose which image to use based on factors like screen density, network connection, and user settings. Even if someone has a high-resolution screen, the browser might opt to download a lower-resolution image.


HTML Content Identification
  -HTML Language Support
     - tools to indicate the language of your content. 
     - Indicating the language of your content in HTML is crucial for several reasons:
         -Search Engine Optimization (SEO) = Search engines like Google use the language information to index and rank websites for relevant searches. If your website's language is unclear, it might miss out on traffic from users searching in specific languages.
 -       - Spell Checking - By including the language attribute, you ensure the browser or text editor uses the correct spell checker dictionary for its suggestions, preventing embarrassing typos and improving the overall quality of your content. 
         - Accessibility - Assistive technologies like screen readers rely on language information to adjust their output, enabling individuals with visual impairments to understand the content effectively.


Responsive Images


 The lang attribute
    •The lang attribute is used to specify the primary language for the content of the HTML document.
    •	It is added to the opening <html> tag.
    •	This attribute helps search engines and browsers identify the language of the content, aiding in proper rendering and              accessibility for users.
    •	Example: <html lang="en"> specifies that the primary language of the document is English.
        -specify the language of a webpage.
        
The Meta Attribute
    •	The meta element is used to provide metadata about the HTML document.
    •	It is commonly used within the <head> section of the document.
    •	The name attribute is often used to specify the type of metadata being provided, such as name="description", name="keywords", etc.
    •	The content attribute provides the actual value or data for the specified metadata type.
      -used by browsers.
  
The charset attributes
  -•	This attribute ensures that browsers interpret the text correctly, especially when dealing with characters from different          languages or special symbols.
      -to specify the character encoding for the HTML document.


HTML Integration
  -HTML Page
    -
  

    Working with Forms and Interactive Elements
      
      -Form Fundamentals
      
      
