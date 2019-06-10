+++
    #this is the "front matter" of the template of a project. It's the variables associated with the file
    #this portion is written in TOML (Tom's Obvious Minimal Language)
    
    title = "Davis Boba Run"
    #replace takes the filename and replaces all hyphens with spaces so that when it appears on your page, it's using spaces. The filename is used in the URL and URLs can't have spaces so use hyphen in the filename.
    #title converts to title-case (using capital letters for principal words only)
    
    date = 2019-05-19T17:02:23-07:00 #the date the file was created
    
    shortDescription = "Entertainment video with the crew trying popular boba spots in Davis."
    projectVideo = "eNiLHGScP1k"
    #Project video is just the unique part of the URL  
    # For example, if the link is https://vimeo.com/285189099 then the unique part is  285189099
    projectVideoType = "youtube"
    #Enter "youtube" or "vimeo". You can add other video types as well by editing single.html 
    projectImage = "Boba Run.png"
    #Enter the filename only. For example, "metropolis_album.jpg" 
    #This image should be saved in the project folder with the name of your project 
    projectImageAltText = "Boba Run thumbnail"
    #Alt text is the text that gets read by screenreaders for accessibility (typically for the visually impaired) 

+++


<h2 class="section-title">About the Project</h2>
<p>Davis Boba Run is an entertainment video for Aggie Studios. Here, two of our reporters set off to try popular boba joints in Davis and judge each spot based on their most popular or recommended drink. </p>

    

<!-- a new line in markdown will not be displayed in the browser.
\
\
\ 
the lines above this line showed up because they started with backslash (NOT A NORMAL SLASH) \
*here's some "emphasized" text, which defaults to italics but you can make it anythign you want in css*
**here's some "strong" text, which defaults to bold but you can make it anything you want in css**

Below is a list
* asterisks make bullets
- hyphens make bullets
+ plusses make bullets
* you can choose! -->
