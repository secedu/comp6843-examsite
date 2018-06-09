Hello friends. After the past semester it has been a pleasure teaching you all. I hope you've enjoyed the wargames and materials as much as I have had building them. I've definitely enjoyed running all the tutorials and writing these challenges and hopefully you enjoy breaking webapps as much as I do after a semester of my sadistic tendencies. You have all been a wonderful cohort to teach and its been a very enjoyable semester. 

The following exam should be challenging but also fun. All the challenges have working solver scripts, so don't tell me its unsolvable. If you're not sure on what to do, you already know what meme i'm going to post. I'll be online most of the time to help, but enjoy the exam. 

If you would like to contribute to how the course is run in later years, please don't hesitate to fill in this [feedback form](https://docs.google.com/forms/d/e/1FAIpQLSctBhjom877Xd1VUAGm7bseXnXpk3hjMD26mjUjXnZsHm5kYw/viewform?usp=sf_link). Its different to the one for cs6443, so don't worry.

Here are some spotify playlists so you can listen to them while you work:
* [hyphy](https://open.spotify.com/user/minight/playlist/2ippMIWgPnLZ4SGdnEWbdn?si=Lcj4wk9xQByXdbvyYVc_Ng)
* [swing](https://open.spotify.com/user/leahbrownmusic/playlist/7p0Mc4z8Kr7w43zw1rhvLj?si=lYG45VX_Rs-ITjtFgQ6Chw)

kthx   
> sy

also thx from the entire team  
> norman, abhi, nina, ceyx, carey, sketch, clonsdale, grc, glem, bugcrowd.

## """"""hints""""""

* A contact page probably means there's an admin viewing your links
* If you manage to get **code execution** (not lfd), the flag will be at /flag
* `/etc/hosts` will tell you what ip ranges/subnets you should look at

## Annoucements

* No bruteforcing is required for the auth challenge. 
* The admin is logged in to their own profile when viewing links sent to them.

## FAQ

> Is it possible to achieve the flag by interacting with that subdomain only

Yes. Each subdomain has its own flag. You may be required to chain vulnerabilities into the isolated network for that challenge, e.g. via ssrf etc. These domains will each have their own isolated network if needed for chaining. You will know when you get there.

> do I need to dirbust for directories

no. Please don't. but if you do, my logs will show it. straight away, and i'll call you out.

> Can the same vulnerability appear in multiple sites?

yes. You may have the same vulnerability across multiple domains. 

> Will the same vulnerability appear more than once in a single domain

no. No domain requires you to use multiple exploits of the same kind in a chain. e.g you won't be required to do something like XSS -> CSRF -> XSS -> XXE -> XSS. 
