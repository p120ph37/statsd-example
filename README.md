# statsd-example
A Spring Boot app that emits statsd metrics

# running locally
./gradlew bootRun

# building a docker image
./gradlew bootBuildImage --imageName=statsd-example

# seeing the metrics locally if you have no statsd collector
https://github.com/zendesk/statsd-logger
