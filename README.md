# Collection of important lessons from SWEBOK
The SWEBOK Guide V3.0 may be downloaded free of charge for personal and academic use via www.swebok.org. Here I would 
like to summarize the lessons that seem most relevant to me. My focus is a subjective and hands-on one; I try to 
apply the knowledge from the book to my daily work, which is very backend-centric.

## Key issues in software design
General topics:
* performance 
* security
* reliability
* usability

Cross-cutting system functionality - these topics will appear in any software program:
* Concurrency
* Control flow and handling of events
* Data persistence
* Distribution of Components - deployment of components and their interaction
* Error and Exception Handling and Fault Tolerance
* User Interaction and Presentation
* Security - access control, authentication, authorization

These topics will be part of any code review.
  
## Key issues in software construction

Software construction fundamentals include
* robustness - we build software that can tolerate human and technical errors or outages and that can still work 
  correctly. It must be idiot-proof.
  * see also defensive programming
  * "be tolerant in what you accept and strict in what you pass on"
* simplicity - minimizing complexity:
  * "In software construction, reduced complexity is achieved through emphasizing code creation that is simple and 
    readable rather than clever." 
  * We write code for the human reader / programmer and not for the machine.
  * Fewer moving parts (that achieve the same function) are better. If we reuse an existing module, that reuse counts as 
    one moving part, so code reuse is one possibility to limit complexity.
  * see also KISS principle
* anticipating change - we build software such that it can be easily extended.
  * Important topics: modularization, information hiding, abstraction, central configuration 
* constructing for operations
  * we build software that can be easily inspected, fixed and deployed.
  * The deployment process must be simple and robust (e.g. idempotent)
  * the software behaves according to the principle of minimum surprise - the software should do what the user or 
    support specialist anyway thinks that it is doing based on their experience and common sense.   
* reuse
  * reuse of your own, new code in another project
  * reuse of existing components (COTS) or building blocks / solutions in the current project



