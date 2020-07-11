# Fareez Aziz Resume Website

## Project 1: User Centric Frontend Development 

### Context
This website is designed to showcase the user's resume in the form of a website. It is designed to incorporate aspects of the user's education and work history to be able to get the recruiters' attention and contact.
It is meant to be able to show the user as more than just a worker but also a person whom the recruiters feel can assimilate in their corporate culture and someone they would one to have as a colleague.
It is to give a more holisitc view of the user's profile.

## UX

### Strategy

The design for this website aims to showcase the soft skills and hard skills of the user in mind. It also takes into account from the recruiter's point of view of what they would like to see in a candidate.

1. As a job seeker, I would like to be able to show my character to potential recruiters so that they can contact me should they find that I may be suitable for their company.
2. As a job seeker, I would like to be able to showcase my skillsets and experiences so that I may be offered various roles for a job.
3. As a recruiter, I would like to hire a candidate that will fit into my company culture for the current vacancy.
4. As a recruiter, I would like to contact a candidate that is adaptable to the changing demands of the economy for an interview.

The website follows the 3 click rule to ensure that the user and recruiter can access to any information quickly.
It is minimalist and clean design to allow easy navigation of the pages and enable users to identify where the information is placed.
It is also mobile responsive for mobile, tablet and laptops.

### Wireframe

The wire frame illustrates the strategy above.

![](image/index_me_wireframe.JPG)
![](image/work_experience_wireframe.JPG)
![](image/edu_wireframe.JPG)

The navbar is placed at the top to allow the users to locate where they are add and where they want to go.
Contact list is placed at the footer so that whenver a recruiter require contact information it is readily available.
The index starts off with a photo and an elevator pitch to entice the recruiter.
3 top skills of the user is showcased as well.

In the about me page, it shows the attribute profile base on Holland code and Myers-Briggs while below the page shows the interest.
This would give the recruiter a sensing of the user's character and if they can fit in the company.
In the work experience page, theere is a picture collage of an oil rig and its environment.
This is to allow the recruiter to visualize the working environment that the user has undergone to better understand the how the user had perform his duties.

In the self-development page, the courses that the user has taken or is taking will be shown to indicate the skills that has been gained since leaving the previous job.
In the education page, it will highlight the projects that were done in schools.
Both of these highlight character and skills that allows the user to be adaptable and gives the recruiter different aspect of the user profile.

## Features

- Navigation bar at the top of the pages to link it to other pages, it is mobile responsive and collapsible
- Logo (cutout of face photo) brings the page back to index.html
- Footer links the user's Linkedin profile
- In self development, there are links to the user respositories, Numpy and Pandas project and a facebook video of Race Academy
- A video with controls plays a UAV flying
- Download resume button is meant to allow recruiters to download resume

### Features Left to Implement
- Download resume button to be linked to actual resume so that is can be downloaded but as of this point JavaScript has not been taught
- Picture collage in work experience can be replaced with a carousel for mobile version so that the recruiter does not have to scroll down so much
- For the respositories in self development, it is still incomplete and will require more projects to be done.

## Technologies Used
1. HTML, https://whatwg.org/, to structure the website
2. CSS, https://www.w3.org/Style/CSS/, to style the website
3. Bootstrap (4.5), https://getbootstrap.com/, to create navigation bar
4. GoogleFonts, https://fonts.google.com/, to style the typography
5. FontAwesome, https://fontawesome.com/, to style Linkedin icon

## Testing

### Manual Testing

Automated testing was not done during the testing.
Testing was done on mobile to laptop.
It was tested on Chrome, Firefox and Edge.

Navigation Bar
- Navigation bar will collapse from laptop to mobile
- Titles on the navigation will change color when the mouse hover over them
 
Web Pages
- From Index page, it will navigate to About Me, Work Experience, Self Development and Education
- From About Me page, it will navigate to Index, Work Experience, Self Development and Education
- From Work Experience page, it will navigate to Index, About Me, Self Development and Education
- From Self Development page, it will navigate to Index, About Me, Work Experience and Education
- From Education page, it will navigate to Index, About Me, Work Experience and Self Development

Links
- Linkedin Icon in footer will change color when hover over and lead to https://www.linkedin.com/in/fareez-aziz-4667b8a6/
- Respositories link in self development will lead to https://github.com/Freezefaz?tab=repositories
- Numpy link in self development will lead to https://github.com/Freezefaz/Python-Practice/blob/master/Data%20Analysis%20of%20HDB%20Flats.ipynb
- Pandas link in self development will lead to https://github.com/Freezefaz/Python-Practice/blob/master/Data%20Analysis%20of%20NP%20vs%20SP.ipynb
- Robot car link in self development will lead to https://www.facebook.com/1395197123827291/videos/2525139214441222/?__so__=channel_tab&__rv__=all_videos_card

Video
- Video will run when played from mobile to laptop

### Bugs

Index page
- At screen size from 900px to 990px, the photo will shrink in size while the elevator remains in the same size.

Work Experience Page
- At screen size 1020px to 1369px, the picture collage is not able to expand out ot the whole screen, leaving 1 photo at center below the rest.

Education Page
- At screen size from 700px to 770px, the video will shrink to a very small pixel before expanding out again.

## Deployment

This site is hosted by using GitHub pages. It is then deployed from the master branch.

Website can be open directly using this link: https://freezefaz.github.io/Project-1-Frontend/.

My github for this website can be accessed: https://github.com/Freezefaz/Project-1-Frontend.

## Credits

1. Development Icons (HTML, CSS, Python) - https://icons8.com/icons/set/html

2. National Oilwell Varco Logo - https://www.nov.com/

3. Trent Global College Logo - https://www.trentglobal.edu.sg/

4. Singapore Polytechnic Logo - https://www.sp.edu.sg/

5. RACE Academy Logo - http://raceacademy.com.sg/

6. Nanyang Technological University Logo - https://www.ntu.edu.sg/Pages/home.aspx
