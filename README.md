# Women in CS at UMass Amherst
[![Build Status](https://travis-ci.org/wicsumass/wicsumass.github.io.svg?branch=src)](https://travis-ci.org/wicsumass/wicsumass.github.io)

Website for the UMass Amherst chapter of Women in CS (WiCS@UMass). Based on [Type-on-Strap](https://github.com/Sylhare/Type-on-Strap); both the Type-on-Strap and the [Type theme](https://github.com/rohanchandra/type-theme) page, on which ToS is based on, has some useful information on front matter conventions. 

### Adding a new blog post

Jekyll supports [Markdown](https://jekyllrb.com/docs/posts/); format accordingly. File names follow the format `YYYY-MM-DD-title.md`. Submit a [pull request](https://help.github.com/articles/about-pull-requests/) for every new post if you don't have push privileges; one of the co-chairs will look over it before adding it to the website. Use the `_draft` folder to store any articles in progress, and read the sample articles intentionally kept in the `_draft` folder for a quick markdown refresher. The `layout` for any event updates or posts should be `post` with preferably a header image. To add an image to the header use `feature-img` in the front matter, and for previews on the main website feed use `thumbnail`. 

### Managing post assets and media 

Place all media in `assets`. **Please** organize media by posts as it gets confusing very quickly! All media for posts should go into `assets/posts/YYYY-MM-DD-title/title-descriptor.jpg`, where `YYYY-MM-DD-title` is the name of the post. The cover image of the whole website is `assets/cover.jpg`. To update thumnails for the past events page (under construction), put them under `assets/portfolio`; a descriptive name is good enough. Profile images for the co-chairs (or any future profile images) will be stored in `assetts/profile`. A rule of thumb is put all media for a particular post in the same directory, otherwise group by category. 

### Developing locally

0. Install `ruby` if it's not installed
1. Clone the repo and `cd` into the cloned directory
2. Type `gem install jekyll` to install Jekyll
3. Type `bundle install` to install dependencies
4. Type `jekyll serve` to preview changes locally. Note that all updates should be dynamic with the exception of `_config.yml` (which really shouldn't be touched much, unless something's broken...) 


### Todo list for the website

- [x] Fix and enrich posts from WECode (**Completed 03/14/18**)
- [x] Fix thumbnail/gallery issues (**Completed 03/15/18**)
- [x] Update [past events](https://wicsumass.github.io/past-events) page (currently shows default filler from theme) (**Temporarily disabled; Completed 03/15/18**) 
- [x] Change header size on desktop (**Changed to fixed header, Completed 03/15/18**) 
- [x] Create and use placeholder favicon (**Completed 03/10/18**) 
- [x] Decide on material for [front page](https://wicsumass.github.io) - news feed or others? (**Completed 03/15/18**) 
- [x] Add `news` page (**Completed 03/15/18**)
- [ ] Add social media wall with Facebook/Instagram/Twitter integration
