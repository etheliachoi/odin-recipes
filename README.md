# odin-recipes
This project is a website with three of my favourite recipes~! 

## HTML
The first step is to build the HTML files where I demonstrate my skills of partitioning the webpage into sections, inserting images and links, and creating ordered and unordered lists.

Problems I ran into 
(1): When I git push, I got an error saying `remote: error: GH007: Your push would publish a private email address.` 
The problem is that whenever a commit is pushed, the user email will be exposed with it. Since the function "Block command line pushes that expose my email" is enabled on my GitHub settings, my push was blocked. 

To solve this, I untoggled the setting, changed the user email in my current repo (on my local directory via terminal) to the no-reply email addresss provided by GitHub, and reset the author information of my last commit. More details can be found [here](https://stackoverflow.com/questions/43863522/error-your-push-would-publish-a-private-email-address). 