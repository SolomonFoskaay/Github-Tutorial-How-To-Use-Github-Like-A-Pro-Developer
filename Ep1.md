# Github Tutorial Episode 1: How To Use Github Like Pro Developers

This was inspired by my friends at Emerald DAO to help beginners submit their Bootcamp quests easily using Github. Yet it packed with Github and Markdown Cheat Sheet for any beginner developer to Github. Meanwhile you can checkout Free dApp development/coding Bootcamp from EmeraldDAO under the Credit Section at the end of this guide.


## SECTION A: Intro To Github For Beginners


### QUESTION 1: What Is Git And Github?
### ANSWER:
Git can be define as a version control system. This makes it possible and easier for developers to track thier code version as they make changes to it from time to time.

Github on the other hand is a cloud based hosted version of Git. This makes it easier to access git features remotely across the web. Github Encourages developers collaboration and has grown to be one of the top frontier for opensource codes on the web.

<hr>

### QUESTION 2: How To Create Github Account (Github Account Creation)?
### ANSWER:
Github account is free and you can easily open a Github account just by going to <a href="https://github.com">GitHub.com</a>.

Then click `SIGN UP` button. Follow the instructions step by step to register an account free on Github.

<hr>

### QUESTION 3: How To Switch To Dark Theme on Github?
### ANSWER:
You can switch to dark theme easily in Github just by checking out `Settings`, then go to `Appearance`

<br/>
<hr>
<br/>

## SECTION B: Setting Up Github Repo For Quests Submission

### QUESTION 1: How To Create Github Repository (Creat  Github Repo)?

### QUESTION 2: How To Create ReadMe File In Github (Create Github ReadMe File)

### QUESTION 3: How To Commit Changes In Github (Add Description To Repo File Changes)

### QUESTION 4: How To Create A Folder In Github?

### QUESTION 5: How To Add File To Folder In Github Repository?

### QUESTION 6: How To Upload Images In Github?

### QUESTION 7: How To Upload Video In Github ReadMe File?

### ANSWER:
All above questions answered in the video above.



<br/>
<hr>
<br/>

## SECTION C: Basic Writing and Formatting Syntax for Github ReadMe File


### QUESTION 1: How To Add Headings To Github?
### ANSWER:
It auto seperate/break the headings from content body with an underline similar to horizontal line but not as bold
```
# for heading 1
## for heading 2 
### for heading 3
#### for heading 4
##### for heading 5
###### for heading 6
```

#### EXAMPLES (am made with heading 4):
# Am Heading 1
### Am Heading 3
###### Am Heading 6

<hr>

### QUESTION 2: How To Highlight Text In Github?
### ANSWER:
Markdown:
```
 `text highlight here`
```
Example:

This is a `text highlight here` for you

<hr>

### QUESTION 3: How To Add Horizontal Lines To Github?
### ANSWER:
HTML: 
```
<hr>
```
Example:

<hr>

### QUESTION 4: How To Add Line Break To Github?
### ANSWER:
HTML: <br/> per new line break space needed
```
<br/>
```

<hr>

### QUESTION 5: How To Add New Paragraph To Github?
### ANSWER:
HTML: per new paragraph space needed
```
<p>new paragraph space content here</p>
```
Examples:
<p>1 new paragraph space content here</p>
<p>2 new paragraph space content here</p>

<hr>

### QUESTION 6: How To Add Hyperlink To Github?
### ANSWER:
<p>A: Absolute Links (best for referencing contents existing outside the repository)</p>
    HTML: 

```
<a href="https://dProgrammingUniversity.com">dProgramming University</a>
```
 
   Markdown: 

```
[dProgramming University](https://dProgrammingUniversity.com)
```

Example: Both HTML and Markdown above will render as

[dProgramming University](https://dProgrammingUniversity.com)




<br/>

<p>B: Relative Links (best for referencing contents existing within the same repository)</p>
    HTML: 

```
<a href="../Ep2.md">Episode 2</a>
```

   Markdown: 

```
[Episode 2](/Ep2.md)
```

Example: Both HTML and Markdown above will render as:

NOTE: When using relative path, be aware that the url is case sensitive. If the actual url of the page you are trying to link to is for example `Ep2.md` (upercase `E`) and you reference it as `ep2.md`(lowercase `e`). It will lead to 404 eror page as seen below.

<a href="/Ep2.md">Episode 2</a> (page hyperlinked to correct file with Ep2.md)

[Episode 2](/ep2.md) (hyperlink lead to 404 error page with ep2.md)




<hr>

### QUESTION 7: How To Add Ordered List To Github?
### ANSWER:
Markdown:
```
1. item 1
2. item 2
3. item 3 and so on
```

Example:
1. item 1
2. item 2
3. item 3 and so on


<hr>

### QUESTION 8: How To Add Unordered List To Github?
### ANSWER:
Markdown:
```
- item 
- item 
- item and so on
```

Example:
- item 
- item 
- item and so on


<hr>

### QUESTION 9: How To Add Images To Github?
### ANSWER:
A) HTML:

Absolute image path:
```
<img src="https://github.com/SolomonFoskaay/Github-Tutorial-How-To-Use-Github-Like-A-Pro-Developer/blob/main/Media/Screenshots/Web3-GameFi-Images-001a-Platformer.jpg" width="100%" height="100%">
```

Relative Image path:
```
<img src="/Media/Screenshots/Web3-GameFi-Images-001a-Platformer.jpg" width="100%" height="100%">
```

B) Markdown:

Absolute image path:
```
![This is an image](https://github.com/SolomonFoskaay/Github-Tutorial-How-To-Use-Github-Like-A-Pro-Developer/blob/main/Media/Screenshots/Web3-GameFi-Images-001a-Platformer.jpg)
```

Relative Image path:
```
![This is an image](/Media/Screenshots/Web3-GameFi-Images-001a-Platformer.jpg)
```

Example: Any of the above image paths will be rendered as below:

![This is an image](/Media/Screenshots/Web3-GameFi-Images-001a-Platformer.jpg)

Image of DancingDino  - extracted fom my [Free NoCode Web3 GameFi Development Course](https://dprogramminguniversity.com/courses/web3-gamefi-development-101/)


<hr>

### QUESTION 10: How To Add Videos To Github?
### ANSWER:
Simply drag and drop where its needed to upload video directly to github (watch how I uploaded the video below in the full guide video above)

Example:



<hr>

### QUESTION 11: How To Add Code Blocks/Boxes To Github?
### ANSWER:
Markdown: 

![This is an image](/Media/Screenshots/Github-001a-screenshot.png)


Example:
```Javascript
YOUR JAVASCRIPT OR RELATED CODES (LIKE CADENCE, SOLIDITY) HERE
```
Note: The above code is in Blue because we specify it as `Javascript` code. Try changing it to `CSS` and it will turn `Green` and so on. Changes colour from one programming language to the other - interesting!
```CSS
YOUR CSS OR RELATED CODES HERE
```
Sample Cadence code:
```Cadence
pub contract PetCenter {

    //SolomonFoskaayQuestsSubmission

    //create event
    pub event NewPetAdded (petType: String, petName: String)

    //resource interface
    pub resource interface IPet {
        pub var petType: String
    }

    //resource type @Pet
    pub resource Pet: IPet {
        pub var petType: String
        pub var petName: String

        init() {
            self.petType = "Dog"
            self.petName = "Puppy" 
        }
    }

    //create & return @Pet resource
    pub fun createPet(newPetType: String, newPetName: String): @Pet {
        let petAdded <- create Pet()

        //emit event details of newsly created pet to users
        emit NewPetAdded (petType: newPetType, petName: newPetName)
        
        return <- petAdded   
    }

    //initialize variables
    init() {
    }

}    
```

<hr>

### QUESTION 12: For Other Intermediate User Questions like 
how to git clone from github (clone repository github)

how to download code from github (same as clone repository github)

how to push to github

how to push code to github from visual studio

how to delete repository github

how to download github

how to upload project on github desktop

how to create pull request in github (create github pull request)

github pages

github profile link

And a lot more - KINDLY GO TO  [Episode 2 of this tutorial here](/Ep2.md)

### Want Your questions to be added or need support?
#### Kindly reach me on [Discord Here](https://dprogramminguniversity.com/discord) & Follow me on [Twitter Here](https://twitter.com/SolomonFoskaay)
#### PLEASE REMEBER TO STAR THIS REPO IF YOU FIND IT HELP FOR ME TO DO MORE - THANK YOU!

<br/>
<hr>
<br/>

## SECTION D: CREDIT:
[Presearch](https://dprogramminguniversity.com/community/general/how-to-earn-presearch-pre-token/) - Decentralize search + earn while searching as devs

[Emerald DAO](https://www.ecdao.org/) - Join Free Cadence Bootcamp & Learn To Build dApps on Flow Blockchain

[Unlock Protocol](https://dprogramminguniversity.com/course-category/unlock-protocol-programming/) - Decentralized Membership as NFT Protocol 


https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax

https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/quickstart-for-writing-on-github

https://docs.github.com/en/account-and-profile/setting-up-and-managing-your-personal-account-on-github/managing-personal-account-settings/managing-your-theme-settings


## Regards
## Solomon Foskaay
