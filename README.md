# The Isle of Trees HOA Site

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

## Update Standard Pages


## To-Do
- [X] Allow for community maintenance
- [X] Secure new url (avalonhoasc.com)
- [ ] Include Map of community
- [ ] Include Picture of Sign @ Front
- [ ] Build internal email addresses for board members
- [ ] Fix link for Property Improvement Request form
