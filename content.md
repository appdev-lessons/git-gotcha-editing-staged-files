# Don't edit the files from the Source Control tab

<div class="bg-red-100 py-1 px-5" markdown="1">

Even if you have not experienced these difficulties, read this lesson and answer the quiz questions to get credit.
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

---
