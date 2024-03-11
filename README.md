.
├── 404.md
├── _config.yml
├── Gemfile
├── cv.md
└── index.md
Gemfile:gem "cvless"
_config.yml:theme: cvless
$ bundle
$ gem install jekyll-nagymaros
docker-compose up
docker run -p 4000:4000 -v $(pwd):/site bretfisher/jekyll-serve
