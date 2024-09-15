# Load Balancer

> Set up load balancer on nginx that will have 1 server for UK, 2 servers for US, and 1 server for the rest.
> 
> In case of failure, it should send all traffic to backup server. Health check should happen every 5 seconds
> 
> *Please use ngrok and touch vpn chrome extension

## Run the Ngrok

````bash
ngrok http http://localhost:8086
````
![1.png](images/1.png)

## VPN

### I Used the CleanVPN from MacPaw

## Test Rest server

![2.png](images/2.png)

## Test UK server

![3.png](images/3.png)

![4.png](images/4.png)

## Test US server

![5.png](images/5.png)

![6.png](images/6.png)



