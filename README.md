# Clone Commit Push

In this assignment, we will install Git and SSH on your computer so you are working toward industry-standard software development. You can find the relevant lecture content [here](https://github.com/allegheny-college-cmpsc-100-spring-2024/slides/blob/main/README.md).

**CLOS**: This assignment includes experience using industry-standard development tools and builds toward [learning outcome  SP.2](https://github.com/allegheny-college-cmpsc-100-spring-2024/course-materials?tab=readme-ov-file#learning-outcomes).

## Step One | Install Git

### Mac Instructions

1. Open VSCode and from the top menu, choose Terminal > New Terminal
2. Type `git --version` in the Terminal and hit enter. 
3. If Git is already installed, it will display the version. If not, you will get a prompt to install it. Follow the instructions.
4. When finished, try step 2 again. Your version of Git should now output to the command line. 

### Windows Instructions

1. Go to [this page](https://git-scm.com/download/win). If the download doesn't begin automatically, click the "Click here for download" link at the top of the page. 
2. Double-click the executable file that downloads and run the installer. 

See [this link](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git) for more info on installing GIt. 

## Step Two | Create SSH key and add it to your account

**If you prefer a video demo for installing SSH keys, our own Professor Luman has one you can watch [here](https://www.youtube.com/watch?v=qEPjUGQFmzQ&list=PLsYZRXov75ZHSwWiCk0-jd1RcTuu_-zmD&index=2).** Just use headphones if you are in the classroom. If several students want to watch the video together, you can do so if you keep the volume reasonable

1. Go to [this link](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git) and follow the installation instructions appropriate for your operating system. 
2. To generate an SSH key, follow the steps at [this link](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent). For Step 1, Open Terminal, you will follow the same process that you did in Step 2.5
3. To add your SSH key to your Github account, follow the steps at [this link](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/adding-a-new-ssh-key-to-your-github-account)


## Step Three | Write a story in VSCode and push it to GitHub

1. Open your `CMPSC-100` folder in VSCode.

2. Copy the clone link for this repo by clicking the \<Code\> dropdown just above the list of files, then choose SSH and hit the double-square copy icon.

<img src = 'assets/copy_thumbnail.png' width = "300px" />

3. Open the Terminal in VSCode with Terminal>New Terminal then enter
   
```git clone <text you just copied>```
   
4. When repo finishes cloning, `cd` into the new directory.
5. Delete the paragraph text in the file called `story.md` and replace it with a 20+ word very short story. 
6. Save your changes (File>Save). 
7. Push your changes to GitHub with the following Terminal commands:

```
git add .
git commit -m "Add short story"
git push

```
8. If you refresh this page and Github and open `story.md`, you should see your story. 