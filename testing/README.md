## How to test
Choose your graylog version, then you can run `docker-compose up` to spin up graylog + nginx that serves a simple static page.
Log into graylog (`admin`, `admin`) and import+apply the content pack.
Then, browse to (http://localhost:8080/a.html)[http://localhost:8080/a.html] to create a nginx log record that will be sent to graylog.
