# Encoding Dictionaries with TEI: A Masterclass

This is the repository for the masterclass on encoding dictionaries with TEI at the Lisbon Summer School in Linguistics.

At the moment, it's quite empty, but don't worry, we'll fill it up with content during the week.

## GitHub Workflow

### Setting up the repo on your computer

1. Install GitHub Desktop on your computer
2. Open GitHub Desktop
3. Sign in with your GitHub credentials
4. Go to https://github.com/BCDH/TEI-Lisbon2019
5. Fork the repository ![Снимок экрана 2019-07-01 в 15.31.52](https://i.imgur.com/UFKV0vY.png)
6. Now (1) Make sure you are in the forked repository; (2) click on "Clone or download"; and (3) select "Open in Desktop" ![Снимок экрана 2019-07-01 в 15.36.05](https://i.imgur.com/HO3QPFV.png)
7. In GitHub Desktop choose where you want to save the TEI-Lisbon2019 clone on your computer
8. If "Open in GitHub Desktop" doesn't work on your operating system, copy your forked repo's URL by clicking on the icon next to it.![Снимок экрана 2019-07-01 в 15.50.30](https://i.imgur.com/AadWYxR.png) Then, in GitHub Desktop, go to File>Clone Repository; select the URL tab and paste the previously copied URL into the Repository URL input field. You can also choose where on your system will you save your clone. Remember it! ![Снимок экрана 2019-07-01 в 15.54.06](https://i.imgur.com/dZ4uR9D.png)

### Make your first commit

1. Go to the TEI-Lisbon2019 folder on your computer.
2. Inside the TEI-Lisbon2019 folder, go into the folder called "Participants"
3. Inside "Participants", create a folder with your own full first and last name.
4. Inside this folder, place the sample images/PDF files of your dictionary data.
5. Go to GitHub Desktop. You should see something like this: ![Снимок экрана 2019-07-01 в 16.08.28](https://i.imgur.com/NYgy0VX.jpg) Note the "Changes" tab and the "History" tab.
6. Click on "Commit to master". After committing, you should be seeing something like this: ![Снимок экрана 2019-07-01 в 16.08.57](https://i.imgur.com/E6UGJJG.png) Check the "History" tab to see your commit.
7. Pay attention to the messages that GitHub is displaying to you and follow instructions to push to origin (i.e. to send your locally committed changes to your "origin", i.e. your forked repo.)
8. Go to your fork on GitHub.com and you will see your first commit there.

### Sharing your work with others

This may seem very complicated at first, but, once you get the hang of it, it will become much easier.

#### First-time contribution

1. **Locate your working copy.**  
   Go to the folder where you cloned your fork.
2. **Do your work.**  
3. **Commit your work.**  
   This will save your initial work to _your local working copy_.  
4. **Push your work.**
   This will save your intial work to _your_ fork _remotely_.  
5. **Create a pull request.**  
   This will alert the repository admin person that there are changes that should be merged into the original repository.

![basic workflow](https://i.imgur.com/7DKZGc4.png)

#### Subsequent contributions

Before you make your next contribution, you have to make sure that your local branch is up to date and in sync with the original repo. Remember, you made a fork off of the original repo at some point, but other people may have contributed to it in the meantime. So it's very important that you follow  this procedure _every time_ you start doing work on your branch again.

1. **In GitHub Desktop, in your local working copy, fetch origin.**  
   This will check whether there were any changes made to _your_ fork _remotely_ (i.e. if you committed and pushed some stuff to your fork from a different computer)
2. **If GitHub Desktop instructs you to pull origin, pull origin.**  
   This will make sure that _your local_ and _your remote_ files are in sync.
3. **Branch > Merge into current branch > Upstream/master**  
   This will now, in addition, update _your fork_ with all the contributions that have been merged into the original repo from other forks. Remember, each contributor works in their own fork.
4. **If GitHub Desktop instructs you to push origin, push origin.**  
   This will make sure that the changes from the original repo, which you've just added to  _your local master branch_ in the previous step, will also make it to _your remote master branch_. With your local and remote branches fully updated and sync you can finally get to do your work.
4. **Do your work.**
5. **Commit your work.**  
   This will save your work to _your local branch_.
6. **Push origin.**  
   This will save your work to _your remote branch_.
7. **Create a pull request.**  
  This will alert the repository admin person that there are changes in your fork that should be merged into the original repository.

![sync](https://i.imgur.com/mu1HBVg.png)
