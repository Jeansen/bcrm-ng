# bcrm-ng
Rewrite of bcrm in Kotlin Native

When I originally created bcrm, it was meant to be a little helper prject. But soon more and more features were implemented. Technically a nice challenge, but a shell script simply is a script. A couple lines of coude soon became a couple hundred and now even more than 3600 lines of code. In addition a lot of code is used on validation user input, arguments and options. Not to mention it is very hard to run code coverage tests. There are end to end tests which run the script with some given arguments and options and compare the created clone against an expected set of states. Anyway, maintaining such a huge Shell script is painful and cumbersome.

So, I'll port it to Kotlin Native and create a robust wrapper that better glues together waht currently a Shell script does.
