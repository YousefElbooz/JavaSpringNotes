file:///C:/Users/Yousef/Desktop/JavaSprinBoot/quickstart/src/main/java/com/elbooz/quickstart/HelloWorldController.java
empty definition using pc, found symbol in pc: 
semanticdb not found
empty definition using fallback
non-local guesses:

offset: 253
uri: file:///C:/Users/Yousef/Desktop/JavaSprinBoot/quickstart/src/main/java/com/elbooz/quickstart/HelloWorldController.java
text:
```scala
package com.elbooz.quickstart;

import org.springframework.web.bind.annotation.GetMapping;
import org.springframework.web.bind.annotation.RestController;

@RestController
public class HelloWorldController {

    @GetMapping("/hello")
    public@@ String helloWorld(){
        return "Hello World";
    }
}

```


#### Short summary: 

empty definition using pc, found symbol in pc: 