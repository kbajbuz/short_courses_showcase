# How to deploy new html files (e.g. SCORM export, or any other html) as a github page:

[Watch steps as Video](https://media.ed.ac.uk/media/t/1_goj3rwr6)

## On Github Website:

- to create a new repo, go to https://github.com/orgs/DDI-Talent/repositories and click **NEW REPOSITORY**
- when creating a new repo use this one as a **template** (from dropdown choose github-page-template). 
- among options: make it **public**
- give the repo a meaningful name, say new repo is about bananas, call it 'banana'. 
- click **CREATE REPOSITORY**
- once it finished creating it (5 seconds), copy the url like https://github.com/DDI-Talent/banana
- still on that github page click **Settings > Pages** (or go to https://github.com/DDI-Talent/banana/settings/pages)
- in the **Branch** header select 'main' and '/docs'. Click **SAVE**

## On your computer in Github Desktop App
- Now let's head to github desktop app, to create a local copy of that repo (clone it).
- In github desktop go **File > Clone Repository > Url**, use the url from above like https://github.com/DDI-Talent/banana
- click the 'current repository' in top left and **open/reveal in File Exporer/Finder**
- you will see the folder called 'banana'. **Drag-and-drop the files** you want into the /docs sub-folder in there. This folder will be the source of your 'github page'
- among the files you want to publish there will most likely be one called index.html - that's how you know you're copy-pasting the right thing.
- back in github desktop app, on the bottom left there is a window for your **commit** message. Write a short note there what you are uploading (e.g. 'new version of course X').
- And the press a large blue **COMMIT TO MAIN** buttom.
- a new big blue button called **PUSH ORIGIN** will show up. Click that.

## Back on Github Website:

- in a few minutes your content will be uploaded to https://ddi-talent.github.io/banana - this is the public link you would share with students/clients
- if for whatever reason you're unsure if things worked, in your github repository page click **Actions** (or go to https://github.com/DDI-Talent/banana/actions) and you should see a green tick next to 'pages build and deployment' e.g. 2 minutes ago. If it's still in progress, orange spinner will spin.


## To update a repo with new files

- just drag and drop new stuff again into that same /docs folder on your computer, and in github desktop app repeat clicking the COMMIT and PUSH buttons
