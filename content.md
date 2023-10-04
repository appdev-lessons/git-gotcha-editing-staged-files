# Don't edit the files from the Source Control tab

<div class="bg-red-100 py-1 px-5" markdown="1">

Even if you have not experienced these difficulties, read this lesson and answer the quiz questions to get credit. 

Before you read this lesson, quickly review our guide on [making git commits and pushing changes](https://learn.firstdraft.com/lessons/50-git-commit-and-push).
</div>

Have you found yourself in a curious situation where you get a git message along the lines of:

> You have divergent branches and need to specify how to reconcile them.

## What is happening?


## How do I avoid this?


## How do I fix it if it does happen?

If you make the mistake and need to fix the divergent branches, here are the steps.

1. Take a look at your files in the codespace and your app in the live app preview browser tab. Are they the current up-to-date version of your code that you want to keep? If yes, then:

2. At the bash prompt in your terminal pane, run this command:

```
git push --force
```

That command will "force push" your current code to the GitHub repository, overwriting the divergent commits. 

Just be sure that the current version of the code in your codespace is what you _actually_ want to keep. If you answered "no" to step 1 above, then you should likely visit the [github.com/codespaces](https://github.com/codespaces) dashboard, delete the codespace, then on your GitHub repository for the project (e.g. `github.com/my-username/links`) you can create a new codespace with the current version of your _published_ code (the code as it exists in the GitHub repository).

Please let someone know if you experience difficulty with these steps!

## A few quiz questions

Let's make sure you read the above sections with a few quick quiz questions:

- Check all that are true:
- The "Source Control" and "File Explorer" tabs are the same and I can use both to make edits to my open files.
  - Not quite. Re-read the previous sections.
- The "Source Control" is used to navigate between open files and make edits.
  - Not quite. Re-read the previous sections.
- The "File Explorer" is where I make git commits and push the changes.
  - Not quite. Re-read the previous sections.
- The "File Explorer" tab is how I open files and make changes to them.
  - Yes! And when you want to make another commit, switch to the "Source Control" tab, make the commit, push it, and switch back to the "File Explorer" tab again.
- The "Source Control" tab is how I make git commits and push them to publish the commits on GitHub.
  - Yes! And I am always sure to switch back the "File Explorer" tab after I make my commits.
- I always switch back to the "File Explorer" tab when I am not making git commits.
  - Yes!
{: .choose_all #source_vs_explorer title="Source Control vs. File Explorer tabs" points="3" answer="[4,5,6]" }


- When I finish making commits and syncing in the "Source Control" tab, I should...
- remain on this tab so I can continue editing my files.
  - Not quite. Re-read the previous sections.
- close my codespace.
  - Not quite. Re-read the previous sections.
- switch back to the "File Explorer" tab.
  - Yes! And when you want to make another commit, switch to the "Source Control" tab, make the commit, push it, and switch back to the "File Explorer" tab again.
{: .choose_best #switching_tabs title="Should I switch tabs?" points="1" answer="3" }

---
