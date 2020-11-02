# Contributing

Hello! Welcome to Appstract's contribution guide.

## Icons

You're welcome to designs icons for apps you'd like to see supported by Appstract.

Don't know what to add, but want to help? See Appstract's [most-requested icons](https://github.com/mirrorkeydev/Appstract/blob/master/icons/most-requested-icons.txt). You'll want to verify that these icons don't already exist using the Appstract app - the `appstract-light` and `appstract-dark` folders don't necessarily have all current icons. You're also welcome to redesign existing icons if you don't like the way they look, but be aware that redesigns will have to hold up to a higher level of scrutiny than adding new icons.

#### Color Palette
![](https://raw.githubusercontent.com/mirrorkeydev/Appstract/master/colorpalette.png)

#### Design Ethos
- Keep shapes simple and large
- Use as few lines as possible
- When in doubt, prefer simplicity over recognizability

To add new icons to Appstract, follow these steps:

### For people who have used Git/GitHub before:

1. Fork this repository. ([Github's guide](https://docs.github.com/en/free-pro-team@latest/github/getting-started-with-github/fork-a-repo). Open the `icons` folder - you can safely ignore all of the other folders.
2. Open one of the template icons in the [`svgs` folder](https://github.com/mirrorkeydev/Appstract/tree/master/icons/svgs). Save it to have the name of your new icon, separated by underscores where there were spaces (e.g. "Clash Of Clans" becomes `clash_of_clans.svg`), and design your icon. Icons use a document size of 192x192 pixels, and a stroke size of 6px. The template icon should already have these properties set up, but sometimes scaling will mess up the size of your lines if you're not careful.
3. Export the icons as 192x192px .PNGs to the [`appstract-light` folder](https://github.com/mirrorkeydev/Appstract/tree/master/icons/appstract-light) with black lines, and to the [`appstract-dark` folder](https://github.com/mirrorkeydev/Appstract/tree/master/icons/appstract-light) with white lines.
4. Open a pull request and explain your changes. [Github's Guide](https://docs.github.com/en/free-pro-team@latest/github/collaborating-with-issues-and-pull-requests/creating-a-pull-request).
5. Provide the activity names of the icons you've added in your pull request.
    - These should look something like `com.dkanada.icecons/com.dkanada.icecons.MainActivity`, and if your app is in the list of [most-requested icons](https://github.com/mirrorkeydev/Appstract/blob/master/icons/most-requested-icons.txt), you should be able to find it there. Note that there may be multiple of these names for each app.
    - If you can't find any activity names, I recommend googling `"ComponentInfo" [name of app] "appfilter.xml"` (with the `"`s) - there you should find other `appfilter.xml` files, with the corresponding activity names there.
6. Once I approve the icons, I'll merge the pull request (add your changes to the main repository), and add you to the contributors section of the app.

### For people who haven't used Git or GitHub before:
More detailed details coming soon!

1. Follow [this guide](https://dev.to/highflyer910/the-beginners-guide-to-contributing-to-projects-with-githubdesktop-46o3). It'll tell you to install GitHub Desktop and walk you through the steps of forking a repository and getting it open on your local machine. It assumes that you already have Git [installed](https://git-scm.com/downloads), so make sure that you've done that before starting the guide.
2. Open the `icons` folder using file explorer, and then open one of the template icons in the [`svgs` folder](https://github.com/mirrorkeydev/Appstract/tree/master/icons/svgs) using your preferred editing software (Inkscape, Illustrator, or similar). Save it to have the name of your new icon (creating a new file in the same folder), separated by underscores where there were spaces (e.g. "Clash Of Clans" becomes `clash_of_clans.svg`), and design your icon. Icons use a document size of 192x192 pixels, and a stroke size of 6px. The template icon should already have these properties set up, but sometimes scaling will mess up the size of your lines if you're not careful.
3. Export the icons as 192x192px .PNGs to the [`appstract-light` folder](https://github.com/mirrorkeydev/Appstract/tree/master/icons/appstract-light) with black lines, and to the [`appstract-dark` folder](https://github.com/mirrorkeydev/Appstract/tree/master/icons/appstract-light) with white lines.
4. "Commit" your changes (mark them as a finished step in Git's history), "push" them to your "fork" (sync your changes with the repository under your account), and then open a "pull request" (a request to add your changes back to this repository). You can refer back to the article in the first step for help with this.
5. Provide the activity names of the icons you've added in your pull request.
    - These should look something like `com.dkanada.icecons/com.dkanada.icecons.MainActivity`, and if your app is in the list of [most-requested icons](https://github.com/mirrorkeydev/Appstract/blob/master/icons/most-requested-icons.txt), you should be able to find it there. Note that there may be multiple of these names for each app.
    - If you can't find any activity names, I recommend googling `"ComponentInfo" [name of app] "appfilter.xml"` (with the `"`s) - there you should find other `appfilter.xml` files, with the corresponding activity names there.
6. Once I approve the icons, I'll merge the pull request (add your changes to the main repository), and add you to the contributors section of the app.

If at any point you're having trouble with any of the steps, feel free to reach out to me at mirrorkeydev@gmail.com :)

## Code

I don't have any plans for code changes - Appstract is currently built on [Sarsa Murmu's](https://github.com/sarsamurmu) maintained Candybar fork: [zixpo/candybar-sample](https://github.com/zixpo/candybar-sample). If you want to contribute to that, head over to his repo :)

