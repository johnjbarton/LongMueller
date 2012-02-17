Promises, XHR and other asynchronous JS operations result in short call stacks
 where the initiating 'cause' is separated from the observed 'effect'. A 
 "long" stack trace merges the cause stack with the effect stack, recursively.
 
 This version of long stacks was written for the Q promises library
   https://github.com/kriskowal/q
 on the Chrome browser. 
 
 The stacks here are formatted in Pat Mueller style. 
 https://gist.github.com/312a55532fac0296f2ab