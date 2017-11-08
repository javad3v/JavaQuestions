# JavaQuestions

About Projects & Past experience
Role & Responsibilities in Past Projects
SDLC Scenarios
Technologies worked on
Problem Solving skills
Core Java [Collections, Garbage collections, Multi-threading]
OOPS
Data Structure, Algorithm
Code writing (scenario)
Frameworks
Design Patterns
Method for Data Structure, Multi-threading
Merging tools –Tibco, JMS, IBM MQ

14)What things you have to take care while creating hash map.
	a. When two objects are equals then there equals and hashvode must match respectively.
	b. Choose load factor and intial capacity in such ways that as much less collisions must be there for data in list.


15) Difference between equals and ==.
		Equals if Both objects are equals based on equals condition.
		While == checks of both objects points same instance.

16) There is a person class .It has two fields - firstName and last name. How would you implement equals method. – he was asking code line by line.
                -if you are passing null to object variable of equals method then what will happen. ?  - 
                -Can we pass subclass object to equals method.?
17) What is volatile ? where do you use it.?
18) if we have two threads , one is reading that variable and one is writing into it.? What will happen? – based on your answer , how would you prevent dirty reading.?
19) We have two threads. one thread prints odd number and another prints even number. He asked for code line by line. 
- How will you make sure that 1 will print first.

20. Student and Marks classes stored as Key value Pair in Map
    -- hascode and equals methods not overridden - How the put and get will work
    -- hascode is implemeted in such a way return constant number, equals not implemented - How the put and get will work

21. TreeMap Student is Stored how it will work 
    -- Throws excpetion if not implemented Comparable or not passing Comparator
    -- If Comparable is implemented and only hashcode is overriden which one is fast Treemap or HashMap

22. Which one you will prefer, Comparable or Comparator and why?

23. We have N Queues and trade mesaages should be send to four queues in load balancer mannner.
     Conditions, If same trade id is in the message it should send it to same queue already processed.

24. We have N independant threads and each thread will create M threads to do the job post processing.
    -- How will you implement it ?

25. What is Future? what is the diffence between Runnable and Callable?

26.What is internal implementation of hashmap?

27.Explain singleton design pattern. When to use?
He asked me number of sub question based on singleton.
Implement your own singleton class.
What is difference between singleton and static?

28.What is immutable? 
Create your own immutable class
Why we need to define class as final.

29.What are inner classes?
He asked number of questions on static classes.
Why we need to use final keyword in front of classes, methods and variables?
What is volatile?

30 . Core Java ( Collections , Multi Threading ) 

31 . J2EE

32. Framework ( Spring / Hibernate ) 

33. Design Patterns

34. Database

35)Explain internal design of LinkedHashMap

36)Explain hashing and how get works in hashing

37)Explain the latest memory model of Java

38)How will u preserve singleton in serialization

39)How will u find second largest salary in employee table….later which he continued with tell me an algo to find nth number of salary

40)In which scenarios to use abstract and when to use interface

41)Explain Memory sharing in multi threaded env

42)Explain synchronization..which were followed by few synchronization scenario based questions.

43)Memory allocation for normal class and static..

44)Optimize way of overriding hashcode method

45)Few scenario based questions on singleton and static

46)Base and subclass related questions like whose method will be called etc

47) Various modules in spring framework and how you used it in your previous projects.

48) Inner class uses and situation where to apply them

49) Db queries

50) LinkedHashMap working 

51) Locking in multithreaded environment.

52) Abstraction in java 

53) How to optimize code for some synchronization scenarios given.

54) Deadlock concept.

55). Difference between abstract class and interface. Cases when to use each of them.

56). Tell me some methods available in Object class. 

57). Internal implementation of Hashmap and Hashset. Lot of questions on hashcode() and equals().

58). Can a method be overloaded if only return types of method are different?

59). Implementation of Red black tree and binary search tree.

60). Write a pseudo code for finding factorial of a number (N). 

61). What is Big Integer?

62). Why java does not allow multiple inheritance?

63).  What does Treeset use internally?


64).Singleton design pattern ?

65). How to break singleton ? (Using threads ... if u dont keep double null check it can be broken)

66). How to make unbrekable Singleton class ? (Using double null check)

67). String s1 = new String(“abc”); how many objects it will create ? (Two Object one in String Pool one in Heap)

68). Some new features added in 1.7 and 1.8 of Java ?

69). What are the functions of JVM what all it does ?

70). what is Clonable how to clone object Shallo Copy, Deep Copy

71). Different ways to create new Object in Java ?

72). What is shadowing ?(When Local veriable in a methos hides class veriables)

73). Method hiding ? (Static method in Parent class same static method in Child class .... Its methos hiding)

74). internal implementation of HashMap

75). Internal Implementation of HashSet

76). Internal implementation of Tree Map and Tree Set

77). how to override hashCode and Equals and when ?

78). Internal Implementation of LinkedHashMap

79). What all design patterns you know
Main are –  Decorator
Proxy
Abstract Factory
Factory
DTO
DAO
Singleton
MVC
Prototype
Adapter
Facad

80). Java Memory Model ?

81). How to get data from Hashset ?(There is no get method for Set... We need to iterate take data)

82). Iterator vs Enumerator ?

83). Iterator vs Foreach ?

84). Access Modifiers in Child classs? Can it be more restrictive?

85). How to achieve Thread Safety if not using Synchronized Keyword?

86). Inner classes Anonymous classes? Can class be static?(Inner class can be static)

87). How Thread synchronization achieved?

88). Ways to create Threads?

89). Executor Framework ?

90). Countdown latch , Cyclic Barrier ?

91). wait(), notify() and join() ?

92). Why wait() and notify() are in Object class ?

93). Exception handling ? How Exception is propagated in inheritance tree ??
(Explain the very well on JavaTpoint)

94). Custom Exceptions ?

95). How Garbez collection is done (Indepth understanding)?

DB
96). Optimistic lock and Passimistic locks in DB ?

97). Different Joins, Aggregate Functions?

98 ). Collections and multi-threading(internal logics).

99).DB – query writing

100). immutability, concurrency, Data structures

101). what is synchronization? what happens if there are two sync methods in a class and two threads try to access same time?

102. How do you search for a string in a 1gb file?

103. Tell syntax for reading a file in java

104. what is hash map and what happens if you do not override equals and hashcode()?

105. what is immutability in java?

106. how do you create a singleton class in java?

107. what is diff between synhcronizationa and static sync method?

108. what is the life cycle of jsp?

109. what is diff between include and forward ?

110. what is mvc pattern in spring?

111. What is hashmap ? (In depth about it)

112. what is arraylist and internal datastructre used for it?

113. What is null in Java/What do you mean when an object is null?
    114. Why is finally block used in code?
    What is an enum?

   115. Design Patterns:
    Why should we use design patterns?
    How do you make a class singleton?

116  .J2EE:
    What is the life cycle of a Servlet?
    How does servlet achieve multi-threading?
    What would happen to a HTTP POST request if the doPost method is not implemented in a Servlet?
    What is the difference between a Servlet and a Filter

117. Web Services:
    What is the difference between SOAP based and RestFul Web Services?
    When do you use SOAP / RestFul web services and Why ?

118. Spring:
    Why do we use Spring over traditional Java development
    What is the default scope of beans in Spring

119. Hibernate:
    Why do we use Hibernate?
    What are the settings to be done for Hibernate?
    ​How do we initialise the sessionObject in Hibernate?
