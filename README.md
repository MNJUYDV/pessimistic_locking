A naive queue implementation is not thread-safe at all, 
which means when multiple threads add or removed from a queue, 
it may lead to incorrect results and worse runtime exceptions.

This implementation is a Concurrent Thread-safe Queue in Golang to get a deeper understanding
