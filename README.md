This is the homepage of Hann. Theme from [Yevgeniy Brikman](http://www.ybrikman.com).

## Run locally

```
% docker
docker build -t webapp .

docker run -d -v $(pwd):/src -p 4000:4000 -e LIMIT_POSTS=5 webapp
```

```
% vscode dev container
bundle exec jekyll serve
```