# π Code Review Emoji Guide

A simple emoji legend to help convey intention and added meaning in code review comments.

> ~~A picture is worth 1,000 words.~~ _An emoji is worth 20 words._

A little bit of emoji can go a long way when it comes to code reviews and make giving and receiving code review a little bit more enjoyable π.

Using CREG (Code Review Emoji Guide) puts more ownership on the reviewer to give the reviewee added context and clarity to follow up on code review. 
For example:
* Knowing whether something really requires action (π§)
* Highlighting nit-picky comments (β)
* Flagging out of scope items for follow-up (π) 
* Clarifying items that donβt necessarily require action but are worth saying (π, π, π­)

## Emoji Legend

| | `:code:` | Meaning |
| :-: | :-: | - |
| ππππ | `:+1:` `:ok_hand:` `:tada:` `:pray:` | I like this... <br /><br /> ...and I want the author to know it! This is a way to highlight positive parts of a code review. |
| π§π£ | `:wrench:` `:bomb:` | Mandatory change that impacts the behavior of the code. <br /><br /> I feel this might lead to a bug or crash and I think this needs to be changed. |
| β | `:pick:` | This is a nitpick. <br /><br /> This is small adjusment I think should be made in order to improve readability, coherence with the codebase or compliance to the guidelines. Might also be an organization suggestions. |
| π­ | `:thought_balloon:` | Let me think out loud here for a minute. <br /><br /> I might express concern, suggest an alternative solution, or walk through the code in my own words to make sure I understand. |
| π | `:clock1:` | The comment may be addressed in later. A Jira ticket has to be created (and referenced in the code). |
| π | `:camping:`  | Here is an opportunity, not directly related to your changes, for us to leave the campground [code] cleaner than we found it. Might be |
| β | `:question:` | I have a question. <br /><br /> This should be a fully formed question with sufficient information and context that requires a response. |
| π | `:memo:` | This is an explanatory note, fun fact, or relevant commentary that does not require any action. |

## Usage

Prepend comments with the appropriate emoji to convey the meaning associated with it. Combine emoji for added fun.

## Examples:

> π§ This method feels overly verbose and I can see can that we can simplify this approach by [...]. I think this should be refactored before we merge this feature and this becomes a permanent pattern in our codebase.

> β We have an existing helper, `ApiHelper`, that accomplishes this same task. Let's pull it in and replace your implementation with it.

> βπ This section of code feels like it could be extracted nicely into a separate module. I feel like that would create clearer boundaries and increase readablity here.

> β These intermediary variables and if statements could be simplified down to a single ternary expression.

> π Wow, I would never have thought of that myself. Swell work!

> π­π I've been meaning to explore library X which claims to solve this exact problem. That could be worth exploring and peeking under the hood to see what concerns they are specifically addressing.

> π We really need to invest some time in refactoring out our use of this deprecated library. _Issue created: [LINK TO ISSUE]_.

---

### Credits

This is inpired by this repository with little adaptations to meet our team needs.

* https://github.com/axolo-co/code-review-emoji-guide
