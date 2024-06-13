# Contributors

Remember that for every question, you'll get N beekeepers and N+3 opinions? Disagreement is fine - it's healthy. We expect disagremeent on the contents of the wiki. You are welcome to add a different view to some of this content, as long as you give an honest critique of your opinion. Simply put, saying "all of this is wrong because I do it this way and it works for me" isn't going to fly, but saying "This is my experience, and I'd like to add some content to show this as an *option* for people", that does fly - the maintainers will discuss anything you add if it's too edgy. The rules of engagement on this wiki are the same as they are on the subreddit: Be civil, Be respectful, Be helpful - Disagreement is healty when it's communicated in a respectful way. 

If you think (or know) that you have a controversial opinion, such as being treatment-free or letting colonies swarm endlessly, and want to discuss any changes of the content on the wiki, you are *more* than welcome to raise a [discussion on the repo](https://github.com/rBeekeeping/discussions/new/choose) and discuss it with the maintainers, or you can make changes to the repo and raise a pull request (see below). Discussions can then happen based off of the content you wish to add.
 
## Things to remember

Github runs on markdown (the same as reddit) - [here's a cheat sheet.](https://www.markdownguide.org/cheat-sheet/)
 
### Links 
When you make a link by doing `[]()` you must add `` to the start of the page you link to; and also remove the .md from the end. If you don't, it will not add the `` automatically, so links break; and `.md` paths link directly to the file rather than the page. For example, if you added a link like this: `[link text](/directory/page.md)` you would need to make it `[link text](/directory/page)`

* [Here is an example of a link without the ](/guides/equipment.md)
* [Here's an example of a link with the .md in the path](/guides/equipment.md)
* [And here is an example of a fully working link](/guides/equipment)

### Folder structure

* If you want to change the folder strucutre, discuss it with the contributor group first.
* Everything should be all lower case in snake_case.
    * Files should be `example_file_name.md` 
    * Directories should be `example_directory`
* Directories should always have an index.md either; describing what the directory is for; or containing any content that should be navigable... such as /biology containing an `index.md` with a general overview of the section including links to the child pages.
* directories that should never be linked to should start with an underscore (eg. _my_hidden_directory)

## Adding / changing content 

### Creating account

1. If you don't have an account on github, or want to use a new account: Sign up to github
1. Go to [this page](https://github.com/settings/emails)
1. Make sure the two boxes for "keep my email address private" and "block command line pushes that expose my email" are set
    * This will make sure that your privacy is maintained in the commit tree
1. If you are part of the main contributor group, send your username to the contributor chat
    * You will be invited as a contributor. Once that happens, you can continue.

> **Note:** Currently, there are no blockers on committing content for approved contributors. Once the main wiki is finished, we will revoke this so that only our maintainers can approve content.

1. Go to https://github.dev/rBeekeeping
1. Write whatever content you want to add (see below)

### Adding a new page

1. Find the section you want to add a page to in the left hand directory window
1. Right click the directory you want to add a page to and click "New file"
1. Give the file the same name as the title (shorten it if it has a long name), for example `this_is_not_a_disease.md` 
    * ensure the file name has `.md` as the extension
1. Add the content there, ensuring that the formatting follows a similar structure to the existing pages
1. Commit and push your content (see below)

### Updating existing content

1. Find the page you want to amend. It will be in the same path as the URL of the website. i.e. `/diseases/efb` will live at `/diseases/efb.md`.
1. Modify the content as you need to
1. See below

### Committing content

1. Click on the button on the left sidebar that has the blue icon with the number in it (it's the 3rd one down)
1. Write a brief description of the changes you made in the box titled "message"
1. Commit and push
    * If you are part of the pre-approved contributor group:
        * Click "Commit and push"
        * Currently, there are no blockers on committing content for contributors. Once the main wiki is finished, we will revoke this so that only our maintainers can approve content.
    * If you are not part of the pre-approved contributor group:
        * You will need to push a branch and open a pull request

> TODO: Update the instructions for not-part-of-the-group bit

### Merge conflicts

When you push new content and it conflicts with work that has been pushed since you started, you will find what's known as a "merge conflict". You will be asked to fix the merge conflict. The content of the page will appear with a conflict like this:

```text
<<<<<<< HEAD
my content
=======
Some other content
>>>>>>>
```

Review the difference of the content between these two break points (the bit between `<<` and `==` and then `==` and `>>`), remove the markers and modify the content to whatever the content should be now. Whatever you change the content to here is what will be commited into the repo.

You can then mark the conflict as resolved and push the changes. If you are unsure on how to resolve a conflict, push a new branch to the repository, and let one of the maintainers (who knows git) fix the conflicts and push your changes for you.

## Maintaining content

This is not yet a thing, but will be. Everyone is free to contribute as much as they like for now, as long as they are in the pre-approved group.