docker-slate
============

# Create container and specify an export directory
docker run -i -t -p 4567:4567 -v ~/projects/test:/export avalawn/docker-slate bash

# Activate Ruby
source /etc/profile.d/rvm.sh

# Start middleman
bundle exec middleman server
