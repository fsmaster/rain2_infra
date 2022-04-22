# rain2_infra


create .env file with content (specify credentials)

RABBITMQ_ERLANG_COOKIE=mosh

RABBITMQ_DEFAULT_USER=admin

RABBITMQ_DEFAULT_PASS=password

run

docker-compose -f rabbitmq.yml up --remove-orphans
