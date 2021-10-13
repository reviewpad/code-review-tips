# List of code review tips

![List of code review tips](images/CodeReviewTips@2x.png)

<p> New to code review? Expert? These tips will still be very useful to elevate the quality of your code reviews doesn't matter your experience in code reviews. We have split them into different categories to help you even further. Feel free to send us more tips that you think are important.</p>

|Code Review Tip                                                                                                                                                                                                                                                                                                                                                        |Category     |
|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------|
|Focus on the code, not the person. Be kind and open-minded. Code review is a dialogue. It is easier to fix code than relationships.                                                                                                                                                                                                                                   |Mindset      |
|Be your first reviewer. If the code is harder for you to review, it will be much harder for others. Leave notes to guide reviewers.                                                                                                                                                                                                                                   |Mindset      |
|Always have a reviewer in mind.                                                                                                                                                                                                                                                                                                                                       |Mindset      |
|Don't force your suggestions, kindly suggest them if you think there's a better way.                                                                                                                                                                                                                                                                                  |Mindset      |
|Don't question your teammate's skills. As @BhavaniRavi_ puts it: You can always fix the code but not relationships.                                                                                                                                                                                                                                                   |Mindset      |
|Concentrate on the whys, less on the hows.                                                                                                                                                                                                                                                                                                                            |Mindset      |
|Spread positivity in your code reviews! It will come around to you, be sure of that! If something is good, say it. If something is not good, say it could be better and provide constructive feedback.                                                                                                                                                                |Mindset      |
|Take feedback to your code reviews constructively. You should strive to respond to feedback quickly but don't just do everything you're told right away. Take your time and judge if that's the best for the project.                                                                                                                                                 |Mindset      |
|Set goals and expectations for your reviews and, when possible, share it with the team. It's wonderful to have everyone on the same page, and it'll do wonders for productivity.                                                                                                                                                                                      |Mindset      |
|Make educated guesses before checking something you’re reviewing. Over time you develop confidence and a sixth sense for bugs and patterns.                                                                                                                                                                                                                           |Mindset      |
|Cut negativity as much as possible. If code reviews are charged with positivity developers will actually look forward to them.<br>"This method doesn't have tests" is much kinder than "You forgot to write tests"<br>"What about instead doing ..." is much kinder than "Do this instead ..."<br>"We usually do this ..." is much kinder than "Make it like this ..."|Mindset      |
|"Would this comment be useful if I was the author?", consider making yourself this question before you write a review comment.                                                                                                                                                                                                                                        |Mindset      |
|Leverage automation. Use as much as you can, so that reviewers can focus on changes that matter.                                                                                                                                                                                                                                                                      |Productivity |
|Use draft PRs - get your reviewers involved as early as possible. You will be amazed at the number of issues that will be avoided.                                                                                                                                                                                                                                    |Productivity |
|Keep pull requests small, ideally one PR per concern. You know the drill: 5 lines, finds 5 bugs. 500 lines, #LGTM                                                                                                                                                                                                                                                     |Productivity |
|Build your Code Review Hall of Fame. Keep 10 PRs somewhere handy where you can learn and refer to, at any time.                                                                                                                                                                                                                                                       |Productivity |
|Time your code reviews. A little timeboxing is healthy as long as it's reasonable. It keeps you from distracting, and over time you'll do it automatically. Are you using any tools to measure your productivity?                                                                                                                                                     |Productivity |
|Group your code requests in batches. Try not to bomb your teammates with many change requests at the same time.                                                                                                                                                                                                                                                       |Productivity |
|Find your rhythm. Don't review too much code in one sitting. Stopping at the 1-hour mark is usually a good idea, but your mileage may vary.                                                                                                                                                                                                                           |Productivity |
|If you see the same error in multiple lines, don't repeat the same comment over and over, comment and ask the author to fix the pattern.                                                                                                                                                                                                                              |Productivity |
|If you're just starting on a new job, code reviews are probably one of the places where you'll find more knowledge in practice and being exchanged among teammates.                                                                                                                                                                                                   |Productivity |
|Anticipate feedback for your PRs. It's a small thing, but you'll actually catch some bugs and missing things.                                                                                                                                                                                                                                                         |Productivity |
|Expect criticism and suggested changes in your reviews. Code review is a team effort and feedback is what you want to make better code. Don't take it personally, and remember, some developers might not be as nice as you, but that's ok.                                                                                                                           |Productivity |
|Know when to stop a code review. As you get tired (and distracted) that last stretch of the code review can take ages. Learn to recognize when you're in that situation and consider a break, or simply take it up the next morning.                                                                                                                                  |Productivity |
|If you're insecure about a specific part of your pull request, let the reviewers know when you request their review. That way they'll be prepared to give you more focused feedback.                                                                                                                                                                                  |Productivity |
|Find how the code you are reviewing could fail by thinking of edge cases. Kindly let the author know about them.                                                                                                                                                                                                                                                      |Coding       |
|Code-review (very) basic checklist:<ul><li>📋 Requirements met?</li><li>🤝 Code conventions followed?</li><li>🦄 Magic values/scenarios accounted for?</li><li>🤓 Code easy to read?</li><li>✅ Good test coverage?</li><li>💤 No unused code?</li></ul>                                                                                                               |Coding       |
|"Good code is like a good joke: It needs no explanation" @russolsen                                                                                                                                                                                                                                                                                                   |Coding       |
|Prioritise readability over fewer lines of code. Code readability is very important for the developer reviewing your code. You might write everything in only one line, but how easy will it be to review?                                                                                                                                                            |Coding       |
|Comment your own code reviews. It will probably make it easier for reviewers, and also will prevent reviews stating what you already know (because you just commented it :D)                                                                                                                                                                                          |Collaboration|
|Emojis, use them. Be playful with your teammates in a kind manner. Approve 👍, praise 👌, dislike 👎, show doubt 🧐, go crazy with them.<br>Extra tip: If you're on mac, hit control + command + space to pull up the emoji panel anywhere(!).                                                                                                                        |Collaboration|
|If there's an ongoing PR and you're already assigned to it, start reviewing it earlier. It will be way easier to do the final review later, and you might actually find some defects very early in the process. Win-win situation.                                                                                                                                    |Collaboration|
|Make sure new teammates have a very good experience with their first code reviews! They'll have a higher standard hold. Win-win situation.                                                                                                                                                                                                                            |Collaboration|
|If you're reviewing a big PR, it might be a good thing to let the author know that you've already started. On the other hand, if you're waiting for a review of your long PR, give the reviewer extra time.                                                                                                                                                           |Collaboration|
|If you add too many reviewers, there's a high chance they will think somebody else will step forward to do the review.                                                                                                                                                                                                                                                |Collaboration|
|Sometimes is good to give a heads-up to the reviewer. You shouldn't do it all the time, but if you know the reviewer is busy, or if you're in a hurry, a heads-up goes a long way.                                                                                                                                                                                    |Collaboration|
|If you happen to solve an unrelated issue, open a different PR. Otherwise, discussions will be mixed, and if the review isn't approved, you (or somebody) will have to do it again.                                                                                                                                                                                   |Collaboration|
|Provide reviewers with the sources for the problems you just solved. It can be handy to understand your code. You can do it by documenting your code, or simply by commenting on your own review with those #StackOverflow links.                                                                                                                                     |Collaboration|
|Encourage reviewers to be co-owners of your changes.                                                                                                                                                                                                                                                                                                                  |Team Culture |
|Guide your reviewers. Get them onboard with your thought process with a quick description. If you want to be extra let them know where to start, and go after.                                                                                                                                                                                                        |Team Culture |
|If you want your changes reviewed quickly, review the changes of your teammates quickly as well. Reciprocity works better than you might think in most cases!                                                                                                                                                                                                         |Team Culture |
|Make a checklist! If your team doesn't have one, build it for yourself and share it with your teammates.                                                                                                                                                                                                                                                              |Team Culture |
|Nitpicks can be a good thing. Be clear when suggesting a nitpick so it doesn't get in the way of more urgent issues. Improving the codebase is in everybody's interest, even the small things.                                                                                                                                                                        |Team Culture |
|Embrace the team. Use "we" and "our" as much as possible. #TeamWork                                                                                                                                                                                                                                                                                                   |Team Culture |
|If you keep seeing the same pattern repeating through several PRs, go one step further and suggest a new convention to your team.                                                                                                                                                                                                                                     |Team Culture |
|If you're working on something visual take two seconds and add a screenshot, even for the most basic change it will make it much easier for the reviewer to get in the context.                                                                                                                                                                                       |Team Culture |
|Unless there is an obvious issue, try not to use the "request changes" option. It has a negative connotation. Prefer "comment".                                                                                                                                                                                                                                       |Team Culture |
|Consider starting the review with a compliment. Developers take pride in their code, and this little tip can go a long way with your teammates.                                                                                                                                                                                                                       |Team Culture |
|When commenting in a review, always propose an alternative or something to take action. Otherwise, it might just be empty criticism.                                                                                                                                                                                                                                  |Team Culture |
|The code should fit the project's style, not yours. Have this in mind when suggesting style changes.                                                                                                                                                                                                                                                                  |Team Culture |
|The goal code review is to make a better team code, not to make it as if you had written it.                                                                                                                                                                                                                                                                          |Team Culture |
|Develop a code review culture, don't just force one on your team.                                                                                                                                                                                                                                                                                                     |Team Culture |
|Add junior devs as reviewers. You might not get a thorough review, but they will learn a lot.                                                                                                                                                                                                                                                                         |Team Culture |
|Anytime there's a useful discussion in a code review consider leaving it documented on the code. If a dev had that question now, probably it will happen again. Of course, if you use Reviewpad these discussions will automatically appear in the review 😉                                                                                                          |Team Culture |
|Split your pull request. It won't be that complex and it will make the review much easier.                                                                                                                                                                                                                                                                            |Team Culture |
