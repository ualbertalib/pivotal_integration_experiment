# pivotal_integration_experiment
A usability test for using pivotal tracker to schedule work

The work flow appears to be:
* Put work into pivotal and prioritize backlog there
* Do commits here on github, but reference the pivotal stories in the commit
* ...?
* Profit!

The above is an example of some work added to the story

https://www.pivotaltracker.com/story/show/142863541

Okay the first time I committed, I forgot to put square braces around my story reference, this time I will add the following to the commit log:

[Fixes #142863541]

Let's see if that worked.

Yep it did work, the story moved from the started to the finished state, so now lets deliver it by adding to the next commit log:

[Delivers #142863541]

Will it work?

Yes it did work. The pivotal interface now says "Accept / Reject".

The documentation for this integration is here, by the way: https://www.pivotaltracker.com/help/articles/githubs_service_hook_for_tracker/

Let's just add a comment via a commit to the pivotal story by mentioning it in square brackets like this:

[#142863541]
