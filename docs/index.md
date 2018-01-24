# Modules template Quickstart

## Required software

It is possible to get up and running with a Jekyll Academic website using only your web browser and a GitHub account. Full documentation for **local installation and editing** can be found on the [Documentation ](/documentation/) page.

## Quickstart

This QuickStart guide is geared to getting you up and running quickly, using only a web browser and GitHub account. Following the directions below will result in you having a Modules template website hosted on GitHub pages live on the web. Before you begin working through the QuickStart guide you may want to familiarise yourself with the following technologies that will be used to create your Jekyll Academic website:

* [Jekyll](https://jekyllrb.com/)
* [Markdown](https://daringfireball.net/projects/Markdown/)
* [GitHub](https://github.com/)
* [GitHub Pages](https://pages.github.com/)

---


#### 1) Register for a GitHub Account
_Skip this step if you have already setup your GitHub account_

* In a web browser, navigate to [GitHub.com](https://github.com/)
* Fill Out Username*, Email Address and Password
* Click Sign up for GitHub button
* Click the Finish Sign Up button

\*Make a note of the username that you create, as you will be required to use it in setting up your GitHub pages repository.

#### 2) Verify Email Address
* Navigate to the email account you used to sign up
* Verify your email address by clicking on the “Verify email address” button in the email you received from GitHub


#### 3) Setting Up your Modules template Repository:
* From your main profile page in GitHub click on New Repository
* If you plan on having this site as your personal or organisation site name your repository like so: **[username].github.io *** otherwise choose a suitable name (e.g COM777)
* Click on Create Repository
* Click on the **Import Code** button under the **"...or import code from another repository"** section
* Paste the following URL in the “Your old repository’s clone URL" section `https://github.com/trallard/Modules-template`
* Click on Begin Import
* Once the import is complete go to your repository settings tab and make note of the URL address for you site.

\*Note: For for GitHub Pages site to work correctly, the repository name must exactly match the format of [username].github.io. For example if your GitHub username is student1234 your GitHub Pages repository must be named student1234.github.io

#### 4) See your Live Website
* Click on the URL you found in Step 3. You should see the site live with the demo content

#### 5) Edit Site Files via GitHub Browser Editor
* Open a second web browser tab that shows the files in your repository github.com/[username]/[username].github.io
* Edit the main settings file for your website to add your name, and to link your accounts
* Click on the  `_config.yml` file in your repository to see the contents of that file
* Click on the ‘Edit This File’ button
* Edit the following entries of the `_config.yml` file
```yaml
title: Module template
description: Lorem ipsum dolor sit amet understanding yourself in the universe tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
baseurl: "/Module_template"
url: "" # the base hostname & protocol for your site

# Author's information
author:
  name: Tania Allard
```

These constitute the basic setup needed for your website and **must** be set accordingly.

The title and description are used in the landing page as well as to generate canonical urls for the website.

The variable
`baseurl` is the name of your repository which is **/Modules_template** by default (as per this repository).

Make sure to change this to match your own repository and website.

If you have trouble understanding what the `baseurl` and `url` variables are visit <https://byparker.com/blog/2014/clearing-up-confusion-around-baseurl/>.

#### 6) Commit Changes to GitHub
* After making changes to the file, make a note under the ‘Commit Changes’ section documenting the changes that you made (e.g. Updated social media usernames)
* Click ‘Commit changes’
* Refresh the browser tab that contains your live website ([username].github.io) and confirm that changes were made to your site


## Next Steps
After following the steps above you now have a fully functioning website that others can view online. You can continue to edit other files on the site.

Following the instructions on the [Documentation](/documentation/) will allow you to set up your computer to edit your files locally. It also offers a full explanation of the site structure, providing detailed instructions for fully customising your new website.
