# KMUTNB - Code Challenge

````npm start````

Test multiple concurrent API requests using
> seq 1 21 | xargs -n1 -P10 curl -X POST "http://localhost:9000/get-ticket"
