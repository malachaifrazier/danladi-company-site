web: bundle exec puma -t 5:5 -p ${PORT:-3000} -e ${RACK_ENV:-development}
worker: bundle exec sidekiq
redis: bundle exec redis-server --port $REDIS_PORT
