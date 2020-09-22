Build  local environment:
docker-compose -f compose-local.yaml up --force-recreate --build

To stop instance:
CTRL+C docker-compose -f compose-local.yaml down

Start tests inside compose:
docker-compose -f compose-test.yaml up --force-recreate --build --abort-on-container-exit
