# Hashes

## Question 1:

**If the following commands are executed:**

    hset hash-one a "abc"
    hincrby hash-one b 10

What is returned when the following is executed?

      hgetall hash-one

-      1) "a"
       2) "abc"

-       1) "a"
        2) "abc"
        3) "b"
        4) "0"
-      1) "a"
       2) "abc"
       3) "b"
       4) "10"

<details>
  <summary>Click here for the solution</summary>
    <ul>
 <li>
 
    1) "a"  
    2) "abc"  
    3) "b"  
    4) "10"

  </li>
	<ul>
</details>
