# Benchmarks

## Holoclean

Holoclean runs using the `hc36` docker image and a postgres container `pghc`.

To build the `hc36` image, navigate into `benchmarks/holoclean` and run `docker build -t hc36:latest .`.

To run an experiment, execute `docker-compose up` in the `benchmarks/holoclean` directory. Adjust the `DATASET` and `RUNS` variable in `docker-compose.yaml` to configure the measurements.


