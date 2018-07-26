# SpringCloud-HystrixCircuitBreaker-Simple-Example

Download the two project and start the both project using 'gradle clean bootRun' command individually.

Try it out
Run both the Bookstore service and the Reading service, and then open a browser to the Reading service, at localhost:8080/to-read. You should see the complete recommended reading list:

Executed reading list

Now shut down the Bookstore application. Our list source is gone, but thanks to Hystrix and Spring Cloud Netflix, we have a reliable abbreviated list to stand in the gap; you should see:

fallBackMethod executed
