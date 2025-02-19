|<a name="start"></a>Introduction to Interactive Media (IGME-110), Fall 2019 | [Syllabus](https://lawleyfall2019.github.io/110-fall2019/) | [Schedule](https://lawleyfall2019.github.io/110-fall2019/schedule.html#week10) |
|----|----|----|

# GitHub Pages Exercise (Week 10, Thursday)

As discussed in the readings, and in lecture, GitHub provides the ability to publish a basic website from a repository. In this exercise, you’ll learn how to create a website associated with your GitHub username, as well as how to create one associated with a specific project/repository.</p>

***Do NOT start this exercise until you have successfully completed the exercise from Tuesday***

## Part 1: Creating a Personal GitHub Pages Site
If you already have a personal GitHub Pages site, you can skip this.)

If you have a repository named *username*.github.io in your GitHub account, it will automatically be used to serve web pages from that address. You can see an example at https://github.com/mamamusings/mamamusings.github.io (the github directory) and http://mamamusings.github.io (the resulting website).

In your GitHub account, create a new (public) repository called *yourusername*.github.io. (This is the same process you used in Tuesday's exercise.) Give it a brief description, make sure the repository is public, and click the box to create a README.md file.You'll be taken to the web page for the new repository. 

In your browser, go to *yourusername*.github.io; you should see the readme page come up. ***If it doesn't work, ask for help before proceeding!!***

Now you need to clone the new repository to your computer, using the same process you used in Tuesday's exercise (copy the clone URL from the GitHub repository, and use the git:clone command in VS Code.
                
Once you've cloned the repo, and you have it open in VS Code, create an index.html file that includes your name and an image (you can use a pseudonym if you want, and it doesn't have to be a picture of you). Use CSS to make it look moderately professional. Commit the new file, and sync your files to GitHub. Then use a web browser to go to *username*.github.io. -- your files should show up there! (*Note*: GitHub can sometimes be slow in updating the website with changes; if you don't see your file appear right away, give it 30 seconds or so, and then try reloading. If it still doesn't show up, ***ask for help***!)

(Note: Once this exercise has been graded, you can feel free to delete the files you created, or replace them with your own content.)

## Part 2: Creating a Project-Based GitHub Site
You're going to create a new repository to hold your web project files. 

While you could just create a subdirectory in your personal site directory, a better approach is to create a separate repository for your work in this class, and using the personal directory you created above for your own non-class-related personal page(s). There are a number of advantages to creating a separate repository for each project you work on, including being able to make the repository private before you want it "go live", giving editing access to specific users, and cloning only the repository that you want to work on.  

You're going to use the igme110 repository that you created in Tuesday's exercise for your web project. If you don't still have a clone of it on the computer you're using right now, use VS Code to set one up (using the instructions from Tuesday). Create an index.html file that at a minimum has the words "My 110 Web Project"; it's just a temporary file, which will be replaced by the files for your web project. 

On the GitHub site, go to your igme110 repository page (github.com/*yourusername*/igme110), select “Settings” from the menu at the top of the page, and scroll down to the GitHub Pages settings. Choose master branch as your source, and save. (Do *not* try to install a "theme"; these do not use standard HTML, but instead use a templating language based on the Ruby programming language. If you want to explore using GitHub Jekyll themes, you should create a separate repository for that.) After you save your new settings, the files in your igme110 directory should be visible at *yourusername*.github.io/igme110; try clinking on the link provided in the settings page to test it.


## Deliverables
Your project repository, with an HTML file in it, should be available at github.com/*yourusername*/igme110 no later than 9am on Friday morning.  
