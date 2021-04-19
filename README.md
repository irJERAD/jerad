The newest version of Jerad.xyz using a custom version of academia

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