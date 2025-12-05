# Debian 13
FROM ruby:3.4

RUN useradd -m -s /bin/bash mint

WORKDIR /work
USER mint

RUN gem install "html-proofer:~>5.0" "jekyll-theme-chirpy:~>7.4"

ENTRYPOINT ["bundle", "exec", "jekyll"]
CMD ["serve", "--host=0.0.0.0", "--future", "--drafts", "--livereload"]
