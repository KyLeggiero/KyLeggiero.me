---
layout: portal

date:
    published: 2020-02-03 23:45 MT
    modified: 2022-04-04 11:00 -0600

page-specific-stylesheets:
    - /styles/portal.css

nav-button-kind: 'sidebar'
app-bar:
    trailing-control:
        kind: 'link'
        target: 'github'

portal:
    sections:
        -
            items:
                -
                    style: card
                    title: Résumé
                    description: My résumé which I keep up-to-date. It's even mobile-friendly!
                    url: https://Resume.KyLeggiero.me
                    thumbnailUrl: https://resume.kyleggiero.me/img/Social-Preview.png
                -
                    style: card
                    title: Scheduling
                    description: View my availability & schedule meetings with me
                    url: /Scheduling
                    thumbnailUrl-light: /images/Portal-Thumbnails/Calendar/Light Mode.svg
                    thumbnailUrl-dark: /images/Portal-Thumbnails/Calendar/Dark Mode.svg
                    openNewTab: false
                -
                    style: card
                    title: Blog
                    description: My blog, where I post thoughts and ideas too complex for a tweet
                    url: https://Blog.KyLeggiero.me
                    thumbnailUrl-light: /images/Portal-Thumbnails/Blog/Light Mode.svg
                    thumbnailUrl-dark: /images/Portal-Thumbnails/Blog/Dark Mode.svg
                -
                    style: card
                    title: Recipes
                    description: I love to make food, and I love to share! Here's some of my recipes
                    url: https://Recipes.KyLeggiero.me
                    thumbnailUrl: https://Recipes.KyLeggiero.me/images/Social-Preview.png
        -
            title: Social
            id: Social
            flex-horiz: center
            items:
                -
                    style: mediumEmphasisButton
                    title: Mastodon
                    url: https://Mastodon.Social/@KyLeggiero
                    fontAwesomeIcon: fab fa-mastodon
                -
                    style: mediumEmphasisButton
                    title: Twitter
                    url: https://Twitter.com/KyLeggiero
                    fontAwesomeIcon: fab fa-twitter
                -
                    style: mediumEmphasisButton
                    title: LinkedIn
                    url: https://LinkedIn.com/in/ky-leggiero
                    fontAwesomeIcon: fab fa-linkedin
        -
            title: Contact
            id: Contact
            flex-horiz: center
            items:
                -
                    style: titledLink
                    title: eMail
                    note: Feel free to send me eMails!
                    display: Ky<wbr/>@KyLeggiero.me
                    url: mailto:Ky@KyLeggiero.me
                    materialIcon: email
                -
                    style: titledLink
                    title: Phone Number
                    note: Contact me via eMail first 🙂
                    materialIcon: phone
---
