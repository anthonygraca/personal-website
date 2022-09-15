{:title "Book Review: Continuous Integration"
 :layout :post
 :tags ["ci" "book review"]}

![book](https://dynamic.thoughtworks.com/gatepages/image0-df68c36c00d6d10a254f3697494f7572.png)

The term ```agile``` is quite bizzare in tech because each person has a different
definition of what it means. I have encountered conversations with people where
they think ```agile == scrum```, so any bad experiences with scrum has also
influenced their opinion on agile as an effective development process.


I do want to address to people who have had poor experiences with scrum that
although agile does thrive with short development cycles, micromanagement is not
agile and anything that comes close to micromanagement is a massive red flag. I
have previously worked on a team where daily stand-ups were turned into a
"justify your existence" event and that eventually led to management being more
out-of-touch with project status as engineers feel uncomfortable with sharing
blockers. So I feel for y'all, we need to do better as an industry in defining
these development processes and not letting non-engineers co-opt them try to
squeeze every last drop of productivity.


If I had to give a firm definition of what agile really is about, my 
tongue-in-cheek response would be "the opposite of waterfall". However the most
accurate answer would be following the principles of the 
[agile manifesto](https://agilemanifesto.org). Which is ultimately four key 
values:
* Individuals and interactions over processes and tools
* Working software over comprehensive documentation
* Customer collaboration over contract negotiation
* Responding to change over following a plan


As I gain more experience and read over these values year after year, I always 
uncover some new insight based on these values and I think that continuous 
integration is a prerequisite & necessary practice for enabling agile.


So I was pretty excited to read this book. This is a short read and it can be read 
cover-to-cover within a day. The techniques shared use dated technologies (for 
example, subversion for version control instead of git) however the concepts are
still highly relevant no matter the tooling. The greatest value I got is reading
all of the justification provided for each step of the process because it is
difficult to advocate for continuous integration if it prevents entire classes of
problems from occuring.

Despite it all, I think the book itself is pretty light on material and the
process itself can be found with enough google searching.  Speaking of
supplimental information, I feel like this book is missing some content from this
Fowler article, [Patterns for Managing Source Code
Branches](https://martinfowler.com/articles/branching-patterns.html), because
it's pretty convincing that continuous integration makes merge conflict
effectively disappear.

Overall, I am excited to read the next book that follows up on this: Continuous
Delivery.


