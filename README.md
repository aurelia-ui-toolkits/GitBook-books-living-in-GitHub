# GitBook books living in GitHub

This document is a part of Aurelia-Tools internal documentation library. It describes the **process of its own creation** using only the browser to do it.

#### If you already have a book in GitBook repository and want to transfer it to GitHub, start reading at section 2. below.

***

## 1. Create a new book 

Point your browser to our GitBook main page:  https://www.gitbook.com/@aurelia-ui-toolkits and click on the **`+ NEW`** button (Image 1, below)

<p align=center>
  <img src="https://cloud.githubusercontent.com/assets/2712405/19396694/4cc8fdce-9212-11e6-8382-0f3da5d9f68e.png"></img>
 <br><br>
Image 1 
</p>

<br>

This should result with the **`Create a new book`** dialog: (Image 2 below). Define your choices in the order suggested by red markers.

<p align=center>
  <img src="https://cloud.githubusercontent.com/assets/2712405/19396808/db182622-9212-11e6-94f2-298daca8f74d.png"></img>
 <br><br>
Image 2
</p>

<br>

I also deleted the "Chapter 1" page that is a part of the template selected with the click on item tagged with red marker 1 on the Image 2 above. For this document, a single page is sufficient.

Now, our book is created and can be accessed via URL https://aurelia-ui-toolkits.gitbooks.io/gitbooks-living-in-github/details and as the URL suggests, it is persisted on the **`gitbooks.io`** server - not in GitHub.

## 2. Transfer the book to GitHub

#### 2.1 Open the book 

Point your browser to https://aurelia-ui-toolkits.gitbooks.io/gitbooks-living-in-github/details and click on the **`SETTINGS`** link (Image 3 below)

<p align=center>
  <img src="https://cloud.githubusercontent.com/assets/2712405/19400465/562aef14-9224-11e6-859b-c5deb50de2de.png"></img>
 <br><br>
Image 3
</p>

<br>

#### 2.2 Create the empty repository on Github (new home for your book)

This is the critical step that is not well explained in the existing documentation. The summary of actions described [How can I transfer my content to GitHub?](https://help.gitbook.com/github/how-can-i-export-to-repo.html) - section **`Using the command line`**   is:

- create the new repository in GitHub that should have the same or similar name to your current repository on GitBook, created as the consequence of the action in step **`1. Create a new book`** above.
- get the **`git`** url of your GitBook book repository which is typically defined as **`https://git.gitbook.com/MyName/MyBook.git`**
- -clone this book to your machine
- push this local clone to the newly created GitHub based repository (with the intent to ovewrite that destination.




