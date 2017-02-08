# Testing Fundamentals

This is a document written as a primer about unit testing.  It has a wide scope, 
including philosophy and rationale for testing, types of testing, economics of
testing and examples of writing tests in practice.  

Over the years I have been witness to many deplorable examples of testing that 
tend to be indicative of not understanding the larger picture of testing and
software development.  These include not testing at all, using system tests 
that are pitifully slow and extremely brittle to test basic functionality that 
would be best served with unit tests, pervasive misunderstanding of what to 
actually test (e.g. your own code, not basic functions of existing tested 
frameworks), planning and decision making that is not conditioned on any 
understanding of frequency of errors in code (and tests), and a great many 
other horrors.  This document is intended as a primer to avert these many
disasters.

The purpose of this document is to provide a wide scope overview of testing
and how testing fits into software development.  The target audience is large:
a new employee on a software development team who should be made aware of larger
vision issues in testing rather than just the rote work of writing tests, managers 
and leaders who should be made familiar with some of the decision making as
relates to both language and platform choice as well as issue related to 
allocation of team resources between developers and testers, and for system and 
acceptance testing staff as understanding lower level tests is critical to 
knowing what appropriate higher level tests are for.  The document has been made
with these target audiences all in mind, and with a notion of brevity since it 
is intended to actually be read and understood.  That said, some depth is lost 
to breadth, and some decisions had to be made with regard to best presentation.

With any luck, this provides a good and useful read for your management staff,
development and testing teams.  If you want to adapt this to your needs, just fork
it and adapt it as you see fit.  For any typos just submit a PR.  Thanks!
