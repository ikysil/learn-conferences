How Rust Views Tradeoffs
* https://youtu.be/2ajos-0OWts

Node Summit 2017 - PLATFORM AS A REFLECTION OF VALUES: JOYENT, NODE.JS, AND BEYOND - Bryan Cantrill
* https://vimeo.com/230142234
* https://www.slideshare.net/bcantrill/platform-as-reflection-of-values-joyent-nodejs-and-beyond
* https://www.slideshare.net/bcantrill/platform-values-rust-and-the-implications-for-system-software
* https://www.slideshare.net/bcantrill/andreessens-corollary-ethical-dilemmas-in-software-engineering

# Autonomy vs Authority

Autonomous (sub)systems communicate with outside world using events.
Authoritative (sub)systems use synchronous Request-Response style.

Greg Young - The Long Sad History of MicroServices 
* https://youtu.be/MjIfWe6bn40

# Reuse vs Autonomy

Goal:  Getting done faster
Via:  Spending less time debugging/rebugging/stabilizing
Via:  Having less dependencies reasonably requiring a bug fix to touch the dependent side
Via:  Not reusing non-generic code

As use and reuse go down, we can see that service autonomy goes up. And vice-versa.

Reuse may make sense in the most tightly coupled pieces of code you have, but not very much anywhere else.

When designing services in your SOA, stay away from reuse, and minimize use (with EDA patterns).

http://udidahan.com/2009/06/07/the-fallacy-of-reuse/

# Evaluating a Service-Oriented Architecture 

Evaluating a Service-Oriented Architecture 
http://www.sei.cmu.edu/reports/07tr015.pdf
