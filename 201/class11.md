# Class 11 Notes - Audio, Video, Images

## Video and Audio Content

1. Explain how the ability to use video and audio on the web has evolved since the early 2000s.

- Flash and silverlight were proprietary plugins that were used in the early days of online videos.  they had securoty and accessibility issues and are now obsolete.  

2. Describe the use of the src and controls attributes in the <video> element.

- src works the same as the <img> element, its the attribute that contains a path to the video you want to embed
- controls attribute allows the user to control video and audio playback, especialy important for people with epilepsy bc

3. Why is it important to have fallback content inside the <video> element?
Write a very short story where <audio> and <video> are characters.

- fallback content is important if the browser accessing the page doesn't support the <video> element.  it can be a direct link to the video file

## A Complete Guide to Grid

1. How does Grid layout differ from Flex?

- flex is one dimensional while grid is 2 dimensional
- grid focusses on content placement, flex focusses on content flow
- flex has more widespread browser support

2. Grid container, grid item, and grid line are a few important terms to understand when using Grid. Please describe these terms in a few sentences.

- grid container is a parent element that holds grid items placed within rows and columns
- grid item is child element of the grid container parent, three properties are column, row and area
- grid lines are the lines that represent the startof, end of, or between column and row tracks 


## Responsive Images

1. Besides making a site visually appealing across different screen sizes, why should developers make images responsive?

- using responsive images makes websites quicker to load bc unneccsary data doesnt have to be downloaded and parsed.  

2. Define the following <img> attributes srcset and sizes. Write an example of how they are used.

- srcset attribute defines the set of images we will allow the browser to choose betweem and what size each image is
- sizes attribute defines a set of media conditions and indicates what image size would be best to choose when certain media conditions are true

3. How is srcset more helpful for responsive images than CSS or JavaScript?

- the browser starts loading a page prior to loading and interpretting the pages CSS and JS.  the images are preloaded there it is faster and more efficient
