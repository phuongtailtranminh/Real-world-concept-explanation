# Real-world-concept-explanation
The collection of real world explanation for software concept

### Connection Pool

"Connecting to a database server typically consists of several time-consuming steps. A physical channel such as a socket or a named pipe must be established, the initial handshake with the server must occur, the connection string information must be parsed, the connection must be authenticated by the server, checks must be run for enlisting in the current transaction, and so on.
In practice, most applications use only one or a few different configurations for connections. This means that during application execution, many identical connections will be repeatedly opened and closed. To minimize the cost of opening connections, ADO.NET uses an optimization technique called connection pooling." - [MSDN](https://msdn.microsoft.com/en-us/library/8xx3tyca.aspx)
