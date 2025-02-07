Two developers disagree on how to implement a new feature - let's say one developer (Alex) wants to use a microservices approach for a new notification system, while the other (Sam) advocates for adding it to the existing monolithic application.

Here's how to handle this productively:

1. Schedule a dedicated technical discussion meeting. Rather than having fragmented debates in various Slack channels or standup meetings, set aside proper time to explore both approaches.
    
2. Have each person present their solution with specific technical considerations like:
    - Performance implications
    - Maintenance overhead
    - Deployment complexity
    - Scalability needs
    - Integration with existing systems
    - Development timeline impact
        
3. Focus on data and benchmarks rather than opinions. Ask questions like:
    - What are our current and projected notification volumes?
    - How much additional operational complexity would microservices introduce?
    - What's our team's experience with managing distributed systems?
    - Do we have the infrastructure to support either approach?

4. Consider creating a small proof of concept for each approach. Sometimes seeing working code makes the trade-offs clearer than theoretical discussions.
5. Look for middle-ground solutions. Maybe you could start with the monolithic approach but design it in a way that makes it easier to break out into a microservice later if needed.
6. Remember that technical decisions often don't have a single "right" answer - they involve trade-offs based on your specific context, team capabilities, and business needs.
7. If you can't reach agreement, have a clear decision-making framework. Maybe the tech lead or architect makes the final call after considering both perspectives, or you go with the simpler approach by default unless there's a compelling reason not to.

The key is to keep the discussion focused on technical merits rather than personal preferences, and remember that you're all on the same team trying to build the best solution possible.

## Tiebreaker

Having an odd number of participants can help break deadlocks through voting. Though I'd add a few nuances to consider:

1. The vote should ideally come after thorough technical discussion - not as a first resort. Sometimes the process of discussing and debating leads to better solutions than either original proposal.
2. Seniority and expertise in the specific domain should factor in. If you're voting on a database architecture decision, the opinion of your database specialist might carry more weight than a frontend developer.
3. Be careful about creating a culture where everything goes to a vote. It can sometimes lead to "camps" forming within the team or people feeling less invested in decisions they voted against.

A good practice is to try reaching consensus through technical discussion first, and use voting as a tiebreaker when you've hit a genuine impasse. This maintains team cohesion while still having a clear way to move forward when needed.

An alternative to straight voting is having a designated technical lead who makes the final call after hearing all perspectives. This can work well because they're accountable for the decision and its outcomes.