This is the homepage of Hann. Theme by  [Yevgeniy Brikman](http://www.ybrikman.com).

## Key features
1. about 
2. CV
3. Research with paper, video, presentation
4. some notes about study, tools & service, review on paper/book,
course

### Tools

* cheet sheets *

  [Markdown](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)

* Latex writing *

$\omega = d\phi / dt$.
$$I = \int \rho R^{2} dV$$

## Local setup

1. ./setup.sh
2. ./serve.sh
4. To test: `http://localhost:4000`

## Docker

docker build -t webapp .
docker run -d -v $(pwd):/src -p 4000:4000 -e LIMIT_POSTS=5 webapp



See the [Jekyll](http://jekyllrb.com/) and [GitHub Pages](https://pages.github.com/)
documentation for more info.