# Initializing a Git Repository and Making Commits

---

## ***Initializing a Git repository***

### After the installation of `Git` on the computer, the next step goes thus:

#### I opened a terminal on the computer, in my own case MacBook

**My working directory is named SAMPLE**
1. Create a working folder or directory using the command `mkdir Sample`
2. Change or move into the working directory using `cd Sample`
3. Inside the folder, run `git init` to initialize the local repo.

![Alt text](<Image/image1.png>)

![Alt text](<Image/image2.png>)

---

## **Making my first Commit**

### These steps were followed in creating my `first commit`:

1. Inside the working directory, a file named `index.html` was created using command `torch index.html`
2. I used `nano` command to insert some text into the `index.html`, and it was saved using `:qw!`
3. The changes were added to the `git` staging area with the command `git add .`
To commit ,use the command `git commit -m "here is my new file"`

![Alt text](<Image/git commit.png>)

---
## **Working with Branches**

### ***My first git branch***

 To create a new branch ,run this command `git checkout -b abdullah`

![Alt text](<Image/Screenshot 2023-09-21 at 4.51.46 PM.png>)

### ***My Branch Listing***

 To view the branches available, use this command `git branch`

 ![Alt text](<Image/Screenshot 2023-09-21 at 5.48.47 PM.png>)

### ***Changing into an Old Branch***

To change from an old branch into a new branch using `git checkout akin`

### ***Merging a branch into another***

To achieve this, lets run a command `git merge Zyzou`' my newbranch name is **Zyzou**

![Alt text](<Image/Screenshot 2023-09-22 at 6.23.58 AM.png>)

### ***Deleting a branch in git***

To delete a branch in git, simply run command `git branch -d Chenko`, the branch I am deleting is `Chenko`

![Alt text](<Image/Screenshot 2023-09-22 at 7.06.03 AM.png>)

## Collaboration and Remote Repositories 

### ***Pushing of local Git repository to the remote Github repository***

Having created a github account and a github repository, let's send a copy of our story to our repository in github

simply run `git add .` 

![Alt text](<Image/Screenshot 2023-09-22 at 12.34.51 PM.png>)

To push the added content to the remote repository

The command to run is `git push origin main`

![Alt text](<Image/Screenshot 2023-09-22 at 12.42.00 PM.png>)

## **Cloning remote git repository**

To achieve this, simply run `git clone https://github.com/Fredricksecures/nodeApp.git`

![Alt text](<Image/Screenshot 2023-09-22 at 12.54.34 PM.png>)

## Introduction to MarkDown Syntax

### Let's take a look at some of the most commonly used mardown syntax:

1. **Heading**

   `# Heading 1`
   `## Heading 2`
   `### Heading 3`

2. **Emphasis**

    `*italic* or _italic_`
    `**bold** or _bold_`
    
3. **List**   

### Let us take some look at unordered list syntax examples

`- Item 1`
`- Item 2`
`- Item 3`

### Ordered list examples come next in the below:

`1. First item`
`2. Second item`
`3. Third item`

4. **Links**

`[visit darey.io] (https://darey.io)`

5. **Images**

`! [Alt text](https://google.com/image.png)`

6. **To display a code**

`console.log('This is Tinubu's Nigeria')`