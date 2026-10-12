# Lesson 6 Project

A client has reviewed your portfolio so far and you have been hired to create a basic web page that will be shared with the client’s company to explain the difference between different social media sites that could be used for the company. Think professionally and complete research on common social media sites to focus on sites whose purpose is to raise attention or awareness to a new company.

## Project Prep
1. If you haven't done so already, clone the repo to your computer within your course folder.
2. Open the repo within VS Code. You can open this `readme.md` file within VS Code to view the project directions there. 
   > **TIP:** Right click on the file and choose the `Open Preview` option.
3. If there are files and folders present other than this `readme.md` file, take some time to familiarize yourself with the files within the repo so you know where they are located. This will help you when asked to use them within the project directions.
   > **TIP:** Before beginning any work on the project, read through all the steps to understand what you will be doing.

<br>
You will need to do some research to find content for this assignment. Use what you learned in Lesson 2 to conduct your search, and remember to find and record the source of where you located your images or text.

1. Find and record the name and URL of three (3) different social media websites.
2. Find and save the logo for each social media site you find. 
3. Find and save an image you can use as the background for the web page.

   > **TIP:** Pay attention to the copyright assigned to your images - refer to [Using Images Legally](http://libguides.riosalado.edu/c.php?g=181380&p=1438887) for guidance. [Wikimedia Commons](https://commons.wikimedia.org/) is a good resource with many images that are copyright free, or with an open license. Use best practices for saving images and save the images to a subfolder named "images" within your Lesson 6 Repository folder. (Reminder: the folder for the repository can be found on your c: drive under your User directory in a folder titled **github-classroom**.)

<br>

***
**IMPORTANT: Be sure to Save and Sync your work to GitHub regularly, applying appropriate Commit comments as you go.**
***

## Create a Web Page

### Part 1:
Create a new HTML file in your Lesson 6 Repository. In VS Code, you can select **FILE>NEW**, or you can click the **New File** button next to the Respository name in the Explorer Pane.
   1. **Save** the file as `social_media.html`.
   2. Include the following on the new page:
      - Add an appropriate HTML comment with your name, course, and project info.
      - Define the appropriate DTD for an HTML5 web page.
      - Add all four main elements to define the page.
      - Create a page title with the text: Social Media Demo
      - Create metadata elements based upon the following information:
        - Identify the author of the web page and use your own first and last name as the author.
        - Add an appropriate description for the web page.
        - Add at least five (5) keywords that appropriately define the page content.

### Part 2:
Structure the web page and add content using these directions:

   1. Create a header element with the following elements within the section:
      - Add a first-level heading with the title: `Social Media`.
   2. Create a navigation menu using the NAV element. There should be 3 menu items that use Absolute Links linking to your Lesson 3, 4, and 5 repositories on GitHub. To obtain the links to these files, navigate to the GitHub organization site for our class: [CIS133DA](https://github.com/rsc-cis133DA-in-v12). Then locate the repository and file, right-click the file name, and then select `Copy Link`.
      - **Template** which should link to template.html in your Lesson 3 Repository.
      - **Poetry** which should link to poetry.html in your Lesson 4 Repository.
      - **Inline CSS** which should link to inline_css.html in your Lesson 5 Repository.
      - **Note:** At this point, don't worry about the formatting of your navigation menu. We will work on that in future lessons. You may use non-breaking spaces between each menu item to space them out if desired, but no other formatting is required.
   3. Create a main section below the navigation menu and include the following:
      - Add a paragraph and write a brief introduction to the concept of social media to explain what it is to an individual who is new to computers.
      - Add a second-level heading that reads: `Social Media Comparison`.
      - Add a description list that includes the following:
         - The name of the three social media websites you researched during the project prep. Each name should link to its respective social media website. Be sure to use the appropriate tag for these **terms** within your Description List.
         - Provide a description of each platform and its main usage(/s). Be sure to use the appropriate tags for these **definitions** within your Description List.
         - Add an image of the site's logo. Change the size of each image to display the same width but will adjust height automatically.
         - Add a caption for each image that displays: `Source: ImageName.FileName`. Link the source of the image using the image name and file name as the display text. Use an appropriate text-level semantic tag for the caption.
         > **TIP:** See the example image below.
   4. Create a footer section to include:
      - A paragraph that displays: Copyright by {YourName} &copy; {CurrentYear}
      - Add an appropriate text-level semantic tag to the copyright information.

***Have you saved and synced your work lately? Now would be a good time to do so!***

***
<br>
<br>

## Example Project
![Screenshot of social_media.html without CSS](https://raw.githubusercontent.com/rsc-cis133DA-in-v12/CourseResources/main/L6-example1.png)

## Apply CSS

NOTE: ALL CSS must be created INLINE within your HTML.

1. Add the background image you found during project prep to the body of the web page.
   1. Apply styling so the image does not repeat and is centered on the page.
   2. If necessary, style the background image so it covers the entire web page.
   > **TIP:** Use best practices when applying background images in the case your image cannot display on the page.
2. Apply a background color to the header and footer elements. **TIP:** Change the color of the links within the navigation bar to make them more visible, if necessary.
> **TIP:** When applying color, don't forget you can use [Rio Salado College's Color Tool](https://www.riolearn.org/content/_resources/interactives/colortool/dist/index.html). You may use the From Image tab within the Color Selection tool to choose colors from your background image to provide a uniform and professional look to your web page.
3. Adjust the header text color so that the text in the header is readable.
4. Apply a background color to the header and footer elements.
   > **TIP:** Change the color of the links within the navigation bar to make them more visible, if necessary.
5. Center align the text within the header and footer elements using the least amount of styles possible.
6. Apply a white background color to the main element.
7. Increase the font size and weight of the names of each social media website.

## Example Project
This is an example of what the project should look like at this point in the lesson.

![Screenshot social_media.html with CSS](https://raw.githubusercontent.com/rsc-cis133DA-in-v12/CourseResources/main/L6-example2.png)

## Submit the Project
Once you have completed your project, you need to let your instructor know that it is ready to be graded. This is done by submitting the Repo URL to the assignment in RioLearn.

   > **TIP:** If you need a refresher on how to submit your work, view: [Submitting Assignments & Viewing Feedback](https://riosalado.coursearc.com/content/cis-public/git-github-and-vs-code/submitting-assignments-and-viewing-feedback).
1. Review your work and make any necessary updates. Save the file. You can either select **FILE>SAVE** or use the keyboard shortcut **CTRL+S**.
2. **Sync** the changes and apply a final **Commit** that says: `Completed final review and updates before submission.`
3. Verify that all files appear on GitHub.

   > **TIP:** You can view any of your repos by going to the GitHub organization for the course - [RSC-CIS133DA-IN-V12 Organization](https://github.com/rsc-cis133DA-in-v12). Once you are viewing the class organization, you should see all of the Repos that you have accepted assignment invitations for. It is recommended that you bookmark this page for future reference. Push (i.e., sync) the files on your computer with GitHub to ensure all files are uploaded to GitHub for your instructor to view.
4. Right-click the link to your repository and select **Copy Link Address**.
5. Go to the Assessing Your Learning page in your RioLearn lesson, and click the link to submit the assignment. Paste the link to your repo in the assignment submission box.
