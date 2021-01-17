web: RAILS_ENV=production bundle exec rails server -p $PORT
worker: RAILS_ENV=production QUEUE=* bundle exec rake resque:work
