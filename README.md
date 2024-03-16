# Clone-Commit-Push

In this exercise, we are just practicing the barebones basics of cloning, updating, and pushing Github repos. 

## Instructions 

1. Before you start, fill out this [quick anonymous survey](https://docs.google.com/forms/d/e/1FAIpQLSdn-6E5Q-TqoU78aMdkFsTs8M7ghpUyT8h1lsxXiFZwWC2G3g/viewform?usp=sf_link) about local packages. 
2. Open you `CMPSC-100` folder in VSCode.
3. Copy the clone link for this repo by clicking the \<Code\> dropdown just above the list of files, then choose SSH and hit the double-square copy icon.

<img src = 'assets/copy_thumbnail.png' width = "300px" />

3. Open the Terminal in VSCode with Terminal>New Terminal then enter
   
```git clone <text you just copied>```
   
    
4. When repo finishes cloning, `cd` into the new directory.
5. Delete the paragraph text in the file called STORY.md and replace it with a 20+ word very short story. 
6. Save your changes (File>Save). 
7. Push your changes to github with the following Terminal commands:
```
git add .
git commit -m "Add short story"
git push

```

