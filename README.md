# messaging redis
I will build an application that uses StringRedisTemplate to publish a string message and has a POJO subscribe for the message by using MessageListenerAdapter.

# Standing up a Redis server
Before you can build a messaging application, you need to set up the server that will handle receiving and sending messages.

Redis is an open source, BSD-licensed, key-value data store that also comes with a messaging system. The server is freely available at https://redis.io/download. You can download it manually, or, if you use a Mac, with Homebrew, by running the following command in a terminal window:
* **brew install redis**

Once you unpack Redis, you can launch it with its default settings by running the following command:
* **redis-server**