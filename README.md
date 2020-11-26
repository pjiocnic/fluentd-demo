cd  fluentd
docker build -t pjoisha/fluentd-base .

docker stack deploy --compose-file docker-stack.yml efkdemo

