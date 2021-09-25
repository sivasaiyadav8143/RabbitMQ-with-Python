# RabbitMQ-with-Python
**RabbitMQ** is an open-source message-queueing software or message broker where queues are defined, to which applications connect in order to transfer a message or messages.
It is suitable for distributing messages among more than one consumer or load balancing among consumers under high load.It offers both synchronous (when one app directly 
communicates to other app, using HTTP protocol,the app does require immediate response directly from the server) and asynchronous (it’s does not required immediate response from the server, and the message that sent will be placed to a message queue) modes of communication.<br>

<h2> Installation </h2>

1. Install Erlang
    Download the latest Erlang from the [official website](https://www.erlang.org/downloads) and install it.<br>
    **NOTE**: Erlang must be installed using an administrative account or it won't be discoverable to the RabbitMQ Windows service.
2. Install RabbitMQ
    Download the latest RabbitMQ server from the [official website](https://www.rabbitmq.com/install-windows.html#downloads) and install it.
3. Enable RabbitMQ Management Plugin
    If you want to access RabbitMQ from the web interface, we need to enable the RabbitMQ management plugin by using the below command on your RabbitMQ command prompt.
    >*rabbitmq-plugins enable rabbitmq_management* 


