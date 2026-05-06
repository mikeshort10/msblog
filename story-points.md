# Story Points

I've worked at a few different engineering shops using a variety of ticketing systems. Something that inevitably comes up when using these systems is "How do we want to track story points?". That inevitably leads me to respond with, "Well, what are they for?". Interestingly, the answer can vary wildly, from capacity planning to tracking "complexity" of tasks. In the article, I plan to discuss what I think story points should (and should not) be used for, what they should accomplish, how they should be tracked.

## What are Story Points For?

I'd like to define some high level requirements for what the story point system should look like:

1. It should be used to track time
2. You should be able to perform arithmetic on it
3. It should be simple to explain, e.g. to new hires
4. It should live in each team members head, i.e. it should not require keys or documentation

Some of these may seem ridiculous at first, but I'll got through each one and demonstrate how I've seen systems that have not abided by these and how that caused issues. Ultimately, we want to define a system that is both used and useful. If team members stop tracking story points or no one is using them, then we should just do away with them altogether.

## Tracking Time

I've heard two main uses for story points: tracking time and tracking complexity. Which is more helpful? I'd start with asking what you would do with either. Tracking time makes sense. Managers can use them to determine who has capacity for unplanned work and can even push back on requests from the organization by saying that each member of the team is at capacity. Tracking complexity is less useful. What manager is going to push back on work because their team is dealing with a lot really complicate stuff right now? So if we use the system for tracking complexity, inevitably it will no be used, and so we should just do away with the system altogether.

## Conforms to Arithmetic

This requirement sounds the most ridiculous but it is extremely important. I've seen story point system that are either used a ranking for time a task will take, in some cases doing away with numbers altogether, e.g. T Shirt Sizes. What I think these systems are trying to accomplish is ease of use, since engineers only need to select for a prescribed list. However, this results in some odd math. For example, a real world system I've heard used is a Fibbonaci sequence for story points that works as follows:

1. One day
2. More than one day
3. More than one week
4. More than two weeks

In this system, the math can work as (1 * 10) < 4. Maybe the intention isn't to do that, but then when we're trying to determine if the team or a particular teammate has time, how do we do that without looking at each ticket individually. In that case, do we even need the storyp oints?