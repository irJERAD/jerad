The newest version of Jerad.xyz using a custom version of academia

# Development  

## TODO  
- Theme
    - [ ] Set to 1950's
    - [ ] Create Archetype for post
        - Start with default
        - use features from other posts in the folder

- Logo
    - [ ] Create: use picture pixel app to make small png 
    - small picture (face), small image (boat, penguin) or initials?

- Menu bar
    - [x] add blog; says.jerad.xyz
    - add music page; music.jerad.xyz

- Front page
    - certificates
        - [ ] Lynda select
        - [ ] Linkedin select
        - [ ] Coursera select

- Articles to write
    - [ ] You are what you do / have done
        - list of things with pictures of fun stuff you loved having done
            - sail, time with family, bike, tennis, surf, etc ..

- Articles to transfer
    - [ ] from academic site
    - [ ] from current jekyll site
    - [ ] from blog site? says.jerad.xyz?

- Projects to do 
    - Teaching / Lectures
        - [ ] Sleep lesson

# Customization  

## Changes to Academia Theme

This website was built using the [Hugo](https://gohugo.io) **open-source** statis site generator. The customized theme I have published is based on the [Academia Theme](https://themes.gohugo.io/academia-hugo/) which itself is a derivative of the [Academic Theme](https://themes.gohugo.io/academic/).  

For documentation sake I am / have been tracking significant changes, fixes, and customizations to how I use hugo and grow the theme this site generator is using.  

### Fixes to Academia  

- [Formspree.io](https://formspree.io)
    - change `site.Params.formspree` in `/config/_default/params.toml` to use the project baed string provided by formspree.io
        - Theme formally used the email / formspree account name for a variable.
    - add `/f` to formspree action link at `layouts/partials/widgets/contact.html`
        - from `"action=\"https://formspree.io/%s\" >> "action=\"https://formspree.io/f/%s\" on line 24