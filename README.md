# Advent Of Code 2023
Solutions to AoC 2023 problems in Rust.

## Requirements
Create ``session.txt`` file in the project root (file ignored by git) with this line:

```sh
export AOC_SESSION={number} # cookie session value in your browser
```

![files](./images/files.png)

![session](./images/session.png)

## Get problem inputs
```sh
bash scripts/fetch-input.sh {day} # current day with 2 digits, e.g 01
```

## Run problems using bash scripts
```sh
bash scripts/run-problem.sh {day}  # run a specific day, e.g 01
bash scripts/run-all.sh            # run all days
```

## Run problems using cargo commands
```sh
cargo run --release --bin {day} # run a specific day, e.g 01
cargo run --release             # run all days
```

## Leaderboard placings

![leaderboard](./images/board.png)

## Benchmark
The following table contains wall-clock timings of all 25 solutions, as well as the produced answer to both parts. The time includes computing both parts of the problem, using the timing method in [lib.rs](src/lib.rs). It was done on an `AMD Ryzen 7 5800X @ 3.8GHz`.

| Day | Part 1 | Part 2 | Time |
|:----|:------:|:------:|-----:|
| 01  |   0    |   0    |    0 |