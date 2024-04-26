

## Server-Sent Events with Spring WebFlux and Reactive Kafka

This project teaches you how to build a real-time data streaming server using Server-Sent Events (SSE) and Reactive Kafka with Spring WebFlux.

### Understanding the Concepts

-   **Server-Sent Events (SSE):**  
    SSE enables a server to push updates to connected clients in a one-way stream. Clients can continuously receive new information without needing to actively request it. ([https://developer.mozilla.org/en-US/docs/Web/API/Server-sent_events](https://developer.mozilla.org/en-US/docs/Web/API/Server-sent_events))
-   **Spring WebFlux:**  
    A reactive web framework built for handling a massive number of concurrent connections efficiently. It excels at handling real-time data flows. ([https://docs.spring.io/spring-framework/reference/web/webflux.html](https://docs.spring.io/spring-framework/reference/web/webflux.html))

### Building the Server

This project guides you through creating a WebFlux server that leverages these technologies:

1.  **Kafka Topic Creation:**  
    You'll learn how to set up a topic in Apache Kafka, which will act as the central message broker for your application. ([https://kafka.apache.org/intro](https://kafka.apache.org/intro))
2.  **Kafka Consumer Configuration:**  
    We'll explore how to configure a Kafka consumer within your server to listen for messages published to the topic.
3.  **Spring WebFlux Controller:**  
    A controller will be implemented using Spring WebFlux to expose a REST API. This API allows clients to:
    -   Send messages to the Kafka topic.
    -   Subscribe to an SSE endpoint, where they will receive real-time updates from the Kafka consumer.

### Sample Application

The project includes a sample application that demonstrates how to utilize SSE with Spring WebFlux and Reactive Kafka in a practical scenario. This provides a hands-on experience to solidify your understanding.

By following this project, you'll gain the skills to build robust real-time data streaming applications using these powerful technologies.
