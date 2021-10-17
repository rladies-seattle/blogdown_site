# R-Ladies Seattle Blogdown Site <img src='static/img/hex_big.png' align="right" height="150" />



Available at: [www.rladiesseattle.org](http://www.rladiesseattle.org)

## To Update the Site

To update the site with a new presentation:

1. Go to data > projects.yml.
2. Add a new entry at the top with the icon, date, title, speaker, and link (leave description blank), then run `blogdown::serve_site()`. The icon should correspond to your link — `fa fa-file` for a Google presentation, `fa fa-github` for a Github repo, etc.
3. Tag `ivelasq`, `katiejolly`, or `monicagerber` to review and approve. Thanks for your patience!

## To Update the Front Page

To update the front page, go to themes > hugo-sustain > layouts > index.html, then run `blogdown::serve_site()`.
