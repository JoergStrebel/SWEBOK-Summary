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

Another important issue is how to decompose, organize, and package software components.

Cross-cutting system functionality:
* Concurrency
* Control flow and handling of events
* Data persistence
* Distribution of Components - deployment of components and their interaction
* Error and Exception Handling and Fault Tolerance
* User Interaction and Presentation
* Security - access control, authentication, authorization

## Key issues in software construction

Software construction fundamentals include
* minimizing complexity:
  * "In software construction, reduced complexity is achieved through emphasizing code creation that is simple and 
    readable rather than clever." We write code for the human reader / programmer and not for the machine.
  * Fewer moving parts (that achieve the same function) are better. If we reuse an existing module, that reuse counts as 
    one moving part, so code reuse is one possibility to limit complexity.
* anticipating change - we build software such that it can be easily extended.
* constructing for verification
* reuse
* standards in construction



