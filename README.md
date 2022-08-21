![ml-logo](https://user-images.githubusercontent.com/107034179/185223287-482e20e8-79f6-47e5-b98f-11dae908e9c3.png)

# Machine Learning - Project 1

This is the website for Machine Learning, an online electronic music academeny based in Dublin, Ireland. 

From their Dublin studio they have created an extensive library of production tutorials and courses which range from focused workshops on specific pieces of hardware to general topics like mixing and mastering in Ableton Live. Their courses are structured to maximize your development of theortical knowledge, technical skills and creative abilities in a short space of time.

The goal of this project was to build a creative & striking website which helps to create an indentity for the company as well as one which is easy to navigate, properly structured and responsive. 

The website was created using HTML and CSS. 
<br>
<br>

![machinelearning layouts](https://user-images.githubusercontent.com/107034179/185805565-10ba1a75-eabf-4a89-8ecb-fea2baa7bc03.png)

<hr>

# Features

### Header 

The header section appears on all pages of the website (apart from thankyou.html) and contains the Machine Learning logo positioned on the left and a nav menu with links to each part of the website on the right. The links in the nav menu change color to indicate to the user which section of the website they are currently browsing.

![header3](https://user-images.githubusercontent.com/107034179/184014417-94409fa9-6de8-4df5-9692-6b7f8ac3c600.jpg)

Using responsive CSS styling, the list items disappear when the screen reaches 900px in width and is replaced with a burger menu icon which generates a drop down list when clicked.

![headermobile](https://user-images.githubusercontent.com/107034179/184014942-449812c4-76df-4545-88e2-0f0ac4878239.jpg)

<hr>

### Footer

The footer appears at the bottom of all pages (apart from thankyou.html) and contains the Machine Learning logo positioned on the left alongside links to the contact, about and privacy pages. There are icons which link to social media platforms positioned on the right. 

![footer](https://user-images.githubusercontent.com/107034179/184015786-6a9187a2-2f2c-4f53-840b-dddb5708ccd3.jpg)

Using responsive CSS styling, all items are centered and the social media icons are placed underneath logo and website links when the page reaches 900px in width.

![footer-mobile](https://user-images.githubusercontent.com/107034179/184016126-978ff217-6a7a-4bb7-9dd1-7b74700f9496.jpg)

<hr>

### Home Page

This is the first page users will see when they enter the website and needs to serve two purposes. The first is to be visually appealing, presenting the companies aesthetic to gain the users attention. The second is provide information on who the company are and what they can offer to encourage the user to continue and explor all  other areas of the website. The home page is split into 4 sections; the hero image, the about section, the latest tutorials section and the latest courses section. 

#### Hero Image

The hero image covers the width of the page and is coded to be 70vh in height. It contains an visually striking studio set up overlayed with the Machine Learning logo and color scheme. 

![hero-index](https://user-images.githubusercontent.com/107034179/185805639-9e550054-b170-4082-b6e6-92089b3e6d54.png)

#### About Section

The about section contains essential information about Machine Learning, and what they offer to customers. It also contains links to relevant sections on the website. 

![about-section](https://user-images.githubusercontent.com/107034179/185805689-5f1d8f7a-c76e-44ca-b3c3-8e59c6a74609.png)

#### Latest Tutorials Section

To engage potential customers as soon as they land on the site, it was important to include links to the Machine Learning content on the home page. The latest tutorials section was chosen to appear first as this is free content and can be used to entice customers to other sections of the website. The tutorials section containts two more images which span the widht of the page, containing a tutorial title and brief description. 

![tutoritals section](https://user-images.githubusercontent.com/107034179/185805881-25a7d19e-1a61-4a2d-87b0-918f0a6baf4e.png)

#### Latest Courses Section

Finally, the latest courses section gives customers a look at the paid content offered on the website. It was constructed with CSS grid and displays an image and description of 3 courses. 

![courses](https://user-images.githubusercontent.com/107034179/184019533-744568f6-1170-4f43-987e-d50727c9c8ba.jpg)

<hr>

### Courses Pages

Both of the courses pages, hardware and software, are structed in the same way. The are split into three sections, the hero image, info section and courses section.

#### Hero Image

The courses page hero image spans the width of the website with a height of 60vh. The hero images contain overlay text with a header displaying the page name and a prompt underneath which links users to the contact page where they can sign up to a course. 

![software-hero](https://user-images.githubusercontent.com/107034179/185806089-0af5740c-b8f7-4c78-8478-3ab6a22d2ef7.png)

#### Info Section 

The info section contains details about all of the courses available through Machine Learning. It also contains an offer of a 7 day free trial and another link to the contact page where users can sign up to a course. 

<img width="1167" alt="coursesabout" src="https://user-images.githubusercontent.com/107034179/184039743-ac2adfdc-8ace-4339-9001-fc4b8cd4ad51.png">

#### Courses Section

The courses section uses the same code and layout structure as used on the home page. Three different courses are layed out using CSS grid, with an image displaying over the course description. Both the image and the description are linked the relevant course page. 

<img width="1421" alt="coursesgrid" src="https://user-images.githubusercontent.com/107034179/184040112-bfe47285-05b5-4fa2-b99c-7287e8641e10.png">

<hr>

### Course Info Pages

Each of the course info pages are layed out in the same way. They are split into 3 sections. First there is a hero image, beneath that there is a course info section and course offers section next to each other. This was created using a combination of flex boxes and CSS grid. 

#### Hero Image

Each of the hero images used displays the machine that is being taught in the course. For the hardware courses I layered png images of the machines being used over backgrounds created in photoshop which use the Machine Learning color scheme and stlying. There is text overlaying the hero images with a header displaying the course type and name. 

<img width="1421" alt="courseshero" src="https://user-images.githubusercontent.com/107034179/184040998-f189412d-f82b-4775-9718-4c19d72b949d.png">

#### Course Info & Offer Section

The main section of the page is split in two using a flex box with a ratio of 3:1. The left section then contains grids on top of divs to display the course info and the right section displays the different pricing options for each of the courses on offer. 

![courseslayout](https://user-images.githubusercontent.com/107034179/184042511-71d6f1cc-0588-401a-983b-038a27d2c5df.png)

<hr>

### Tutorials Page

Each of the tutorials pages is split into two sections. The pages contain a hero image and the tutorial itself below. 

#### Tutorial Hero

The hero images used for each tutorial page displays the machine that is being used for the tutorial. The images were created by layering png images of the machines over backgrounds created in photoshop that use the Machine Learning color scheme and stlying. There is text overlaying the hero images with a header displaying the tutorial name and brief description underneath.

<img width="1428" alt="Tutorial-Hero" src="https://user-images.githubusercontent.com/107034179/184046549-dea5d32d-7c60-4305-8d94-71fb183aa1c5.png">

#### Tutorial Section

The turorial section is where users learn tips and tricks for creating electronic music for free. The tutorials use a combination of images a easy to follow intructions. 

<img width="1428" alt="Tutorial" src="https://user-images.githubusercontent.com/107034179/184047053-3b04e9b7-1f4c-4827-836a-1bddd12bebd4.png">

<hr>

### About Page

The about page contains a run down of Machine Learning including details of how and when the company started, information on the types of courses offered on the website and a link to the contact section.

<img width="1227" alt="About Section" src="https://user-images.githubusercontent.com/107034179/184044139-6005f608-3c6a-4d4a-b461-6da2fdc0bf49.png">

<hr>

### Contact Page

The contact allows users to sign up to any of the courses available on the website or get in touch if they have any questions about the content available.
The form allows users to submit their name, email address, phone number and select which course they are interested in. 


<img width="1366" alt="Contactpage" src="https://user-images.githubusercontent.com/107034179/184044436-308aa562-6c56-4a69-8f97-f98a60e50870.png">

<hr>

### Privacy Page

The privacy page provides information on Machine Learnings' privacy policy. The user can see what information is stored and they are given assurances that it will not be shared with a third party. The page also gives information on cookies and whether they are in use on the website. 

<img width="1000" alt="privacy-page" src="https://user-images.githubusercontent.com/107034179/184046313-1ec4cf4c-e4ca-4ae4-8d8e-7129a624be13.png">

<hr>


