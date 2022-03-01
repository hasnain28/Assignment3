**Front-end command**

docker run -it --rm --name frontend --network application --init -p 9091:8080 frontendabc




**Back-end command**

docker run -it --rm --name backend --network application --init -p 9090:8085 python
