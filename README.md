I did some copy/pasting from some other projects I had sitting around. It's a quick 3.1 core project done as MVC with some jquery, ajax, bootstrap thrown in.

1) Simple repository reading from xml.   You could take it a step further and add it to configure services so that you could easily swap it out with a database.
	- Uses bootstrap table which gives sorting, paging, etc without much effort
	- Picking up the xml is a little cheesy.  The path is in appsettings.
2) The array code is under the menu option Array Shtuff
	- I did it using list with some linq.   Many ways to solve it.
3) String shift is under the menu option String Thing
	- Simple string shift


I added some validation and some simple error handling.


What would I change about a platform?
Ugh.  I never thought about it before.  My first thought is that I was a VB developer for a long, long time.   I loved not worrying about upper and lower case.
That seems kind of silly as an answer though but once you get used to something, it's hard to get over it.   Similarly, database configurations (our default in
Oracle at my company) can cause the same issue.   When I'm doing SQLServer, I never worry about case comparisons and then I jump over to an Oracle program and
suddenly I have to worry about it.   I'll catch myself converting to upper and lower case so I don't have to think about.  That's not pretty.

That's not a very enlightening answer.   I usually live with whatever is there and do the best I can with my and the framework limitations.   I tend to focus
more on standards of development rather than platform issues.  There are many ways to solve problems but it's easier to read another's code if we all follow
the same guidelines.   I don't even care what those guidelines are as long as we have them and try to stick with them.   Simple stuff like variable naming fits
here.   I used to work with a guy that would change any code that he touched to have variable names with jc at the beginning.  Jc was his initials and no, he
wasn't a savior though he was really smart.  When looking at linq, some people use query syntax and some use method.  It's not hard to read both but you have
to think twice if it's done differently from one program to the next.

It's great to have common libraries and use common tools.   At my company, some people use Infragistics and some use Telerik and some use XCeed etc.  None of them
are perfect but it's certainly not ideal to switch between them from project to project or even in the same project! 
