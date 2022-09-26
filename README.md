## Reveal Playground for SCS

This repo holds a playground for providing slides made with
[revealjs](https://revealjs.com/) for SCS. The `scs-template` branch is 
already useable to a certain degree. It is far from perfect, but it provides
enough to serve as a good starting point for further exploration.

### Howto

* There is a `master` branch that holds upstream revealjs.
* There is a `scs-template` branch which holds the scs theme and where the `master` branch is regularly merged into.

If you want to create a new slideset, choose the template-branch you want to base on
(for now, there is only `scs-template`) and branch of that. If you want to create a
template slideset that is personalized, name it `scs-<github-username>-template`.

### Branch naming conventions

For slidedecks use the following naming convention: `slides/<year>-eventname`.


### Images

A lot of standard scs images are in `images/`. If there are specific images for a certain
slide set, those images should only be added to the branch of the corresponding slides.
If images are suiteable for numerous scs-related slides, please add them to the `scs-template` branch
as well.

