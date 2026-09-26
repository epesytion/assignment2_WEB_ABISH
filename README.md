Adil Abish SE-2539.
My assignment consist of 5 tasks - from 0 to 4

My directory is like

<img width="209" height="615" alt="image" src="https://github.com/user-attachments/assets/cfb19215-7670-4359-9e70-fba277075148" />

So the main document is index.html. Where I placed every tasks links. Firstly I separated tasks into different packages 
to make it more convinient to see each part of assignment.

Task 0. Navigation bar

<img width="1919" height="943" alt="image" src="https://github.com/user-attachments/assets/0f5b6b96-3087-444e-a9f7-155a787b7d62" />

The HTML:

<img width="849" height="455" alt="image" src="https://github.com/user-attachments/assets/68b9c495-d027-4b7d-b84f-552283c0fa53" />


The CSS:

<img width="555" height="543" alt="image" src="https://github.com/user-attachments/assets/8891d716-7c55-424e-b76f-f74654a50441" />

To make space between 2 elements in flexbox container I used 'justify-content: space-between' in 6th row of CSS stylesheet.
For logo I used basic <img> and aligned it to the center in flexbox. Then I appled align-items for links.


Task 1: Card Row

<img width="1919" height="994" alt="image" src="https://github.com/user-attachments/assets/4a84aee8-455e-49f8-a059-7882f1991c45" />

HTML:

<img width="837" height="776" alt="image" src="https://github.com/user-attachments/assets/0b348c01-3c10-4b13-b0d7-92acaa652fcb" />


CSS:

<img width="569" height="608" alt="image" src="https://github.com/user-attachments/assets/27426a98-e90b-4228-a3e4-aff2cf1373fa" />

This task was not so hard at all.
I created container flexbox and places 3 cards in each of them we have image, title, text and button.
I didn't overdo it, I just placed the same photo.
I also added hover that translates the image to the top (-5px) in the 23-25th rows in CSS stylesheet.

All of cards inherit one class so they are same, so their properties are also same.



Task 2: Page layout with Grid Ares

<img width="1919" height="957" alt="image" src="https://github.com/user-attachments/assets/45e356ce-4100-474e-bb11-1815f126fd3d" />

HTML:

<img width="914" height="592" alt="image" src="https://github.com/user-attachments/assets/7d170107-b0c5-4503-923f-d2eb673512cb" />

CSS:

<img width="712" height="709" alt="image" src="https://github.com/user-attachments/assets/bf8c2d42-143e-4b7d-b943-27c7d5b3e490" />
<img width="478" height="157" alt="image" src="https://github.com/user-attachments/assets/9e0716fc-0bf2-44dc-aaaa-b347a7c6c047" />

I divided HTML document into 4 sections:

header, div with classs="sidebar", main, footer.

I defined display grid on 5th row of CSS Stylesheet. I added sizes of rows 100px 400px 100px, 3 numbers, because we have 3 rows. I also managed the sections in 'grid-template-area' defining first row for header, 
next row for sidebar AND main content, and the next row for footer. But before that we should to add grid-area for every section. I added it at 15, 20, 26, 32 rows. Besides, we can see basic style applying for better seeing the grid's flow.


Task 3: Image Gallery:

<img width="1919" height="961" alt="image" src="https://github.com/user-attachments/assets/4adec79b-3602-467a-ab3b-deb795d372ad" />


HTML

<img width="811" height="531" alt="image" src="https://github.com/user-attachments/assets/b8584e80-28c3-4597-9a1e-80b4fbdb0263" />

CSS

<img width="536" height="351" alt="image" src="https://github.com/user-attachments/assets/d140bc97-420e-4a09-9282-1620ba8faadf" />


I added main container with diplay grid, and placed 9 images inside the container
CSS stylesheet is not so hard too. Parent Container has columns which sizes are equal to size of an image. But we see the gaps between them and the images dont stick together. How? - I used property gap in 7th line of CSS stylesheet. and set it to 20px, interesting fact: I could define grid-template-columns and grid-template-rows to 120px and remove the property gap. Both are nice.
After, I added hover for logos that will make images rotate to 20degrees clockwisely (Z axis)


Task 4: Portfolio

<img width="1909" height="900" alt="image" src="https://github.com/user-attachments/assets/0e2266c0-80be-4582-b727-c07b37c00337" />

HTML

<img width="904" height="767" alt="image" src="https://github.com/user-attachments/assets/da0bbbf0-90d9-483f-bfe8-818db1d62e70" />
<img width="781" height="343" alt="image" src="https://github.com/user-attachments/assets/2760a5d0-a82e-4e9a-809e-96a8c0efd788" />


CSSS

<img width="680" height="718" alt="image" src="https://github.com/user-attachments/assets/12e03e45-5e57-4641-8dbc-01220863e902" />
<img width="613" height="618" alt="image" src="https://github.com/user-attachments/assets/f89d0b49-eb59-41ac-b880-61ebc07816b3" />

Here I had little troubles with included containers (projects container in the left). Well I just added the main container. And containers in it (header, sidebar, main, footer)
Here I used the class sidebar too for div block.




























