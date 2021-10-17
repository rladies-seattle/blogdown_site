# R-Ladies Seattle Blogdown Site <img src='static/img/hex_big.png' align="right" height="150" />



Available at: [www.rladiesseattle.org](http://www.rladiesseattle.org)

## To Update the Site

To update the site with a new presentation:

1. Fork and clone the repository.
2. Go to data > projects.yml.
3. Add a new entry at the top with the icon, date, title, speaker, and link. The icon should correspond to your link — `fa fa-file` for a Google presentation, `fa fa-github` for a Github repo, etc. If you have the notes document for your session, please paste the "View Only" URL under description.
4. Run `blogdown::serve_site()`. The site should render.
5. Tag `ivelasq`, `katiejolly`, or `monicagerber` to review and approve the pull request.

If you would like assistance at any point, please [file an issue](https://github.com/rladies-seattle/blogdown_site/issues) and we'll get back to you as soon as possible. Thanks for your patience!

## To Update the Front Page

To update the front page, go to themes > hugo-sustain > layouts > index.html, then run `blogdown::serve_site()`.
