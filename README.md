# egt309-singapore

## Group
Group name: <team name>
Members: <name 1>, <name 2>, <name 3>

## Who wrote what
| File | Author |
|---|---|
| eda.ipynb | <name> |
| Dockerfile | Daniel |

## Development environment (Docker)
Requires Docker Desktop. From the project root:
```
docker build -t egt309-dev .
docker run --rm -it -p 8888:8888 -v "${PWD}:/app" egt309-dev
```
Open the `http://127.0.0.1:8888/lab?token=...` link printed in the terminal.
`-v` mounts the project folder into the container, so edits are saved to your own copy.
(On Mac/Linux/WSL use `"$(pwd):/app"`.)

## Data
Place `proj_machine_readings.csv` in `data/`.

## Running the pipeline
To be added (week 7).

## Key EDA findings
To be added.

## Feature engineering
To be added.

## Models and tuning
To be added.

## Evaluation metrics
To be added.