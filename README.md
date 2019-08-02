# springboot-memcached

Java客户端三种方式都在这

    memcached-java-client 推出较早，应用最广泛，阻塞式IO，稳定性高，高并发下性能低
    较早推出的memcached JAVA客户端API，应用广泛，运行比较稳定，使用阻塞IO，不支持CAS操作。
    Spymemcach基于JDK的Concurrent和Nio，存取速度高，并发性能高，支持CAS操作
    XMemcached同样基于NIO实现，减少了线程创建和切换的开销，这一点在高并发下特别明显。
    
此项目中把memcached通过Java客户端实现的三种方式都做了集成，方便大家学习。
