# quizGame

Simple CLI quiz game made in Go.

## Flags
- -csv
    - Accepts a csv file in the format question,answer
    - Default "problems.csv" provided
    - example: `-csv="nameOfFile.csv"`
- -limit
    - Time limit on quiz in seconds
    - Default 30s
    - example: `-limit=10`

## Usage
- Clone repo, `cd` into quizGame folder and run `go build`. Run executable to start quiz with default problems and time. When time is up, score is presented.

## Examples
- `go build . && ./quizGame`
- `go build . && ./quizGame -csv=problems2.csv -limit=10`
