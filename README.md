Introduce Yourself
------------------
I have been into web dev for 9 years, have built a [client-side MVC][halo], [jsmin with sourcemaps][jsmin], [a spritesheet with variables tool][spritesmith], and [smaller utilities for developers][projects].

I have been a big BDD enthusiast and would like to introduce people, cover why it is practical, and what I think the future holds.

[halo]: https://github.com/Ensighten/Halo
[jsmin]:https://github.com/twolfson/grunt-jsmin-sourcemap
[spritesmith]: https://github.com/Ensighten/grunt-spritesmith
[projects]: http://twolfson.com/projects


Name of Your Talk
-----------------
Behavioral driven development and the future


Description of What You Expect to Cover
---------------------------------------
This talk will be a chronological progression through BDD.

Starting with an introduction and example to give those who don't have a feel for it. Give a snippet of practicality here:

- Less thought during testing
- Testing things more like a black box
- Testing functionality that you actually care about rather than "that one method in that one module"

Then, we jump back to the past. How did BDD come about? What were its foundations and roots? What languages did it pass through until it made it to JS? Definitely show examples here.

Next, we observe the present. What frameworks are out there? Why do we choose some over others (e.g. better async handling, cleaner/easier to understand)? Expand on more use cases and practicality.

Lastly, we look to my thoughts on the future (which are far from certain). Just as BDD separated black box vs grey box testing from TDD (more convention than actual code), I think we will be separating test implementation from test description.

It is a bit of a far shot, but it has slick components:

- Aliasing of actions and assertions
- Chaining of actions and assertions (https://github.com/twolfson/sculptor#aliasingchaining-commands)
- Break down current actions and assertions without changing outline
- Swapping out different test frameworks

I have done some work on this which can be found here:
 - https://github.com/twolfson/doubleshot
 - https://github.com/twolfson/sculptor - Abandoned predecessor which was overgeneralized
 - https://github.com/Ensighten/crossbones - Abandoned predecessor which was short sighted (compiles to different frameworks)

Thank you.