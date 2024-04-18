# Project Title: Go for Statistics

This project tests using Golang for statistics with linear regression using the Anscombe Quartet Data 

## Files

- 'regression.py': Python script for linear regression analysis with execution time
- 'regression.R': R script for linear regression analysis with execution time
- 'gostats.go': Go script for linear regression analysis
- 'regression_test.go': Go script for testing and benchmarking of gostats.go

## Setup and Run (Ensure in correct directory)

### Go 
'go run gostats.go' to run go script for linear regression
'go test -v' to test the linear regression script and give execution time
'go test -bench=.' to give benchmarks on Go scriptExe

### Python

Within terminal of the directory of gostats, ensure python environment is up to date and numpy and scipy are installed
This can be done with 
'python3 -m venv myenv
source myenv/bin/activate
pip install numpy scipy' to ensure the environment we are working in is able to install/run numpy and scipy

'python3 regression.py' to run the python script in repository 

### R 
'Rscript regression.r' to run the R script in repository