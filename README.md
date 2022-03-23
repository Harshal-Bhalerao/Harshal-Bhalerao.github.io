# Hosting your Resume on Github Pages using Markdown format
**Purpose**: The goal of this document is to help host a Markdown resume on Github Pages. This guide will follow the practices decribed in Andrew Etter's book [*Modern Technical Writing*](https://www.amazon.ca/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS).

## Prerequisites
It is best recommended to be familiar to Markdown to follow this document properly. Also, make sure you have a resume which is tailored to the position you are applying for.
Refer to [*More Resource*](https://github.com/Harshal-Bhalerao/Harshal-Bhalerao.github.io#more-resources) section for more resources on Markdown and Resume writing.

## Instructions
Follow the instructions listed below in order to host your resume on Github Pages following practices mentioned in Etter's book *Moden Technical Writing*.

1. If you are new to Github, then [**Sign up for Github**](https://github.com/signup?ref_cta=Sign+up&ref_loc=header+logged+out&ref_page=%2F&source=header-home)
    > Etter has an irrational bias towards Static Site Generators. He loves their simplicity, speed, portability and security. They could be hosted anywhere without any issues.
2. Create a repository
    - On the top right of the Github Website, you will find a `+` icon as shown in the image below. Click that and select `New Repository`.
      
      <img width="343" alt="Capture1" src="https://user-images.githubusercontent.com/102128579/159593482-38d966d0-ed9b-4252-9097-e119ea0968f0.PNG">
    - To use Github Pages, type `<Your Username>.github.io` and create your repository.
    > **Andrew Etter** in his book *Modern Technical Writing* encourages to store all the documentations in the same repository as its corresponding products. Although, Andrew here is talking about having documentations and code in the same repository. He mentions that having a single repo storing all the documents is more likely to be accessed, removes the chances of documents getting lost and it's portable as everything is up on the internet.
3. Now, you can add your upload your resume in Markdown. In order to do that:
    - Click `Add File` at the top of the file section.
    - If you already have an resume, you can just upload it. Or else, you can just begin from scratch by clicking create new file.
    - Make sure the name of your resume file is `index.md`. This is the file name that Github searches for, in order to render it on Github Pages.
    > In *Modern Technical Writing*, **Andrew Etter** mentions how easy it is to make changes on a static website. As time passes, even the best of softwares get out of date. Hence, to easily update any information, it is better to host your resume on a website.
4. Choosing a Jekyll theme:
    - Click the `Settings` tab along the top.
    - Click the `Pages` tab along the side.
    - Under `Theme Choose`, select `Change theme`.
    - Select the theme you like and click `Select theme`
      ![Animation](https://user-images.githubusercontent.com/102128579/159598822-cf1463bf-b168-46a0-b0a3-fed2a336247e.gif)
    > **Etter** mentions how to spend time effectively. He says how important it is to spend 90% of your time learning and the remaining 10% writing. Although, Etter emphasized on writing, it is important to get enough time to do so. Customising PDFs is not possible, we have to use other softwares like Word. Here, we have in-built themes which can help customize ones resume. Also, if your time is well spent on learning some CSS, then you can end up making a beautiful looking resume of your liking. This also shows how powerful static websites are, it is easier to customise and update information.
5. View your website
    - After selecting your theme, you will find a link in a green or blue box. That's the link to your website. 
    - Or else, you could use this `https://<Your Username>.github.io/` to view your resume hosted on Github Pages.
    > From one of the points mentioned above, the portability aspect of a static website makes it stand above PDFs. It is easy to remember the link mentioned above and we can access this website from anywhere in the world. Unlike PDFs where you would send them to others and others would have to download it. Such PDFs could hold security threat and static websites mitigate those.

    ![Animation2](https://user-images.githubusercontent.com/102128579/159615790-b382697b-6960-4b6a-924b-386c20345d3f.gif)

### More Resources
- [Markdown Tutorial](https://www.markdowntutorial.com/)
- [Andrew Etter's book Modern Technical Writing](https://www.amazon.ca/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS)
- [How to write better resume](https://www.jobbank.gc.ca/findajob/resources/write-good-resume)


## Authors and Acknowledgements
Thanks to Ben Balter and the rest of the team for [Cayman Theme](https://github.com/pages-themes/cayman).

Editors:
- Azizul Hakim
- Deepta Mandal
- Joshua Smallwood

## FAQs
### Why use Markdown or other lightweight markup options?
In *Modern Technical Writing*, **Andrew Etter** has mentioned the following key points 
- Markdown is stored in pure text format
- It is simple to understand and it is used professionally by most for documentations. Thus, it has great documentations online and good community which can help solve any issues.
- Works well with other Version Control options
- Can be written in any text editor or even GitHub. 

### How to make title from `_config.yml` file to show up as heading on your `index.md`?
Add a `<div>` tag in the beginning of your `index.md`. For example, I used the code snippet shown below as my beginning line and continued in Markdown. This might not be applicable to you, but this is one of the ways to solve your issue.
        
        <div style="color: #2E8B57; font-size: 27px;">EDUCATION</div>
