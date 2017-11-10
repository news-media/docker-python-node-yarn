FROM newsmedianl/python-node-yarn:latest

RUN \
    echo "Setting up Heroku toolbelt" && \
    wget -q https://cli-assets.heroku.com/branches/stable/heroku-linux-amd64.tar.gz && \
    mkdir -p /usr/local/lib /usr/local/bin && \
    tar -xzf heroku-linux-amd64.tar.gz -C /usr/local/lib && \
    ln -s /usr/local/lib/heroku/bin/heroku /usr/local/bin/heroku
