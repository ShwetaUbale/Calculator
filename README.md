STeps to run the file 

STEP 1:-
docker build -t html-css-calculator .

STEP2:-
docker run -d -p 8081:80 --name my-calculator-v2 html-css-calculator

STEP3:-
you'll view your new app at http://localhost:8081