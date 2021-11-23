# What is Java?

Java is the general name of java object-oriented programming language and Java platform launched by Sun Microsystems in May 1995. It was jointly developed by James Gosling and colleagues and officially launched in 1995.

Later, sun was acquired by Oracle, and Java became Oracle's product.

Java is divided into three systems:

JavaSE（J2SE）（Java2 Platform Standard Edition）
JavaEE(J2EE)(Java 2 Platform,Enterprise Edition）
JavaME(J2ME)(Java 2 Platform Micro Edition)

In June 2005, the JavaOne conference was held, and sun company disclosed Java se 6. At this time, various versions of java have been renamed to cancel the number "2": J2EE has been renamed Java EE, J2SE has been renamed Java se, and J2ME has been renamed java me.

## Java features

The Java language is simple:
The syntax of Java language is very close to C language and C + + language, which makes it easy for most programmers to learn and use. On the other hand, Java discards those confusing features that are rarely used, difficult to understand and confusing in C + +, such as operator overloading, multiple inheritance and automatic forced type conversion. In particular, the Java language does not use pointers, but references. It also provides automatic allocation and recycling of memory space, so that programmers do not have to worry about memory management.

The Java language is object-oriented:
The Java language provides object-oriented features such as classes, interfaces and inheritance. For simplicity, it only supports single inheritance between classes, but supports multiple inheritance between interfaces, and supports the implementation mechanism between classes and interfaces (the keyword is implements). The Java language fully supports dynamic binding, while the C + + language only uses dynamic binding for virtual functions. In short, the Java language is a pure object-oriented programming language.

The Java language is distributed:
Java language supports the development of Internet applications. Among the basic Java application programming interfaces, there is a network application programming interface (Java net), which provides class libraries for network application programming, including URL, urlconnection, socket, ServerSocket, etc. RMI (remote method activation) mechanism of Java is also an important means to develop distributed applications.

The Java language is robust:
Java's strong typing mechanism, exception handling and automatic garbage collection are important guarantees for the robustness of Java programs. Discarding pointers is a wise choice for Java. Java's security checking mechanism makes Java more robust.

The Java language is secure:
Java is usually used in network environment. Therefore, Java provides a security mechanism to prevent malicious code attacks. In addition to many security features of the Java language, Java has a security protection mechanism for classes downloaded through the network (class classloader), such as allocating different namespaces to prevent replacing local classes with the same name and byte code checking, and providing a security management mechanism (class securitymanager) to let Java applications set up security sentinels.

The Java language is architecture neutral:
Java programs (files with suffix Java) are compiled into architecture neutral bytecode format (files with suffix class) on the Java platform, and then can be run in any system implementing the Java platform. This approach is suitable for heterogeneous network environment and software distribution.

The Java language is portable:
This portability comes from architecture neutrality. In addition, Java strictly stipulates the length of each basic data type. The Java system itself also has strong portability. The java compiler is implemented in Java and the Java running environment is implemented in ANSI C.

The Java language is interpretive:
As mentioned earlier, Java programs are compiled into bytecode format on the Java platform and can then run in any system implementing the Java platform. At runtime, the Java interpreter in the Java platform interprets and executes these bytecodes, and the classes required in the execution process are loaded into the running environment in the join phase.

Java is high performance:
Compared with those interpreted high-level scripting languages, Java is indeed high-performance. In fact, with the development of JIT (just in time) compiler technology, the running speed of Java is closer and closer to C + +.

The Java language is multithreaded:
In the Java language, a thread is a special object that must be created by the thread class or its children (grandchildren). There are usually two methods to create a thread: first, the use type is thread (runnable) The constructed subclass of wraps an object that implements the runnable interface into a thread. Secondly, it derives a subclass from the thread class and overrides the run method. The object created with this subclass is a thread. It is worth noting that the thread class has implemented the runnable interface. Therefore, any thread has its run method, and the run method contains the run method to be run by the thread The activity of a thread is controlled by a set of methods. The Java language supports the simultaneous execution of multiple threads and provides a synchronization mechanism between multiple threads (the keyword is synchronized).

The Java language is dynamic:
One of the design goals of Java language is to adapt to the dynamic environment. The classes required by Java programs can be dynamically loaded into the running environment, or the required classes can be loaded through the network. This is also conducive to software upgrading. In addition, classes in java have a runtime representation, which can check the type of runtime.