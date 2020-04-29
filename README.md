# Avalon HOA Site

The site is built with a basic [Hugo](https://gohugo.io/) framework, using the config.toml file to dictate a final version of the build be created inside of the /docs directory for hosting purposes.

## Setup Hugo
If you are going to maintain this site, you are going to need to start with [acquiring](https://gohugo.io/getting-started/installing/) Hugo. Once you have Hugo, you can clone this repository to your local system and modify it to your hearts desire. To test a build, run `hugo server -D`. Once you are confident the page looks how you want, you need to execute `hugo -D`.

## Create New content

### Create new blog posts
The file structure for blog posts is *content/posts/fourDigitYear/twoDigitMonth/filename.md*. So the initial post was made in `content/posts/2020/03/meetingAgenda.md`. This is going to be important to continue for posterities sake. Create a new post with the following:

```
hugo new posts/2020/03/meetingMinutes.md
```

Obviously, we replace the year, month, and file name with what we actually want to use.

## Rebuilding the Themes Folder

Because the theme used is most likely a submodule, you have to do a little clean-up and rebuild when building this site on a new computer.
1. We assume you've cloned the repo onto your local box. Navigate to $PATH/hoamaster/
2. Run <code>git rm -r --cached themes</code>
3. Run <code>git submodule add url_to_repo themes/themeName</code>
 * currently running <code>git submodule add https://github.com/budparr/gohugo-theme-ananke.git themes/ananke</code>
## Update Standard Pages


## To-Do
- [X] Allow for community maintenance
- [X] Secure new url (avalonhoasc.com)
- [X] Include Map of community
- [X] Include Picture of Sign @ Front
- [X] Build internal email addresses for board members
- [X] Fix link for Property Improvement Request form
- [X] Fix the contact us link
- [X] Point contact us link to President's email
- [ ] Check on Sweet Pea's Ice Cream and Cafe to see what is needed for them to come to Avalon. 803-318-2133

