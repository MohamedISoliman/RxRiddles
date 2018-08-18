RxRiddles
=========

This repository contains some riddles for RxJava to help you learn and master RxJava. There is an [accompanying medium article](https://medium.com/@vanniktech/riddling-your-way-to-master-rxjava-145d5de99b55) that gives some more information.

Each riddle is in a single file with an accompanying unit test that will check your implementation. Next to the unit test, I have also put up my solution. Note that there are multiple ways to achieve and solve the riddles but usually there's a dedicated operator or function that I want to show you.

The riddles are not sorted in any real preference and I plan to keep it that way. Just start with whichever one you prefer. Riddles with numbers lower than 100 can be solved with a single operator while every other riddle requires multiple operators.

### Contributing

I'm very open to having some more riddles. Especially some complex common use cases. In case you want to contribute create an issue and let's talk.

I want every riddle to be unique and have as little duplication as possible while also having some actual real-world use case for each riddle in mind. Something you can relate to and hopefully use in your everyday life.

### Things to Remember
- Scan operator it's a map but return the old and the new value for each emission.
- Reduce is same as the Scan but it emits the last result, may it equals scan().takeLast()
- There is a flatMap overload flatMap(mapper, resultSelector) which is useful when you want to map the result with some logic and have the result from the mapper and the flatMap input itself. 

# License

Copyright (C) 2018 Vanniktech - Niklas Baudy

Licensed under the Apache License, Version 2.0
