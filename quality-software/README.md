# Why quality software **always** matters

In software development, often there is a push from business to deliver something **good**, **fast** and **cheap**.

Unfortunately we all know that this is a utopian view and reality is much harsher:

![good_cheap_fast](good_cheap_fast.png)

Yes, you really can only pick two:
* On time
* On budget
* Or high quality

## Cheap and Fast

We live in a time where technology evolves at a fascinating rate, where competition is merciless and promises to solve any new technological problem.

On the other hand, around 90% of startups fail and a tiny amount of source code repos are mature enough to be used on a Production environment.

Part of the problem is related with a mindset, too focused on delivering "Cheap and Fast", compromising a product minimum quality that can survive new business/feature requirements (we all know they always happen) and technology requirements (scalability challenges and library/framework changes).

The "Fail Fast" approach hurts on the long run when taken too lightly and this is often ignored until the pain is felt.

It is my view that we should **always** apply **proper Software Development foundations** from the very start of any project.

The benefit outweighs the minor time cost on building these foundations and this will give you the necessary momentum to adjust, debug and improve.

## Fast and Good

As mentioned above, "Fast and Good" won't be cheap. And to stay competitive, it's important to minimise cost. So, what is the solution?

The solution is to be **smart** 😉 Not only take advantage of years of learning from the Tech community and the latest tools that automate work (Open-Source), but also maximise the strength within your company, bringing together expertise already built, applying InnerSource and never under-appreciating the value of **best practices** and **quality software** from the very start.

Because most (if not all) of the above is free, the only challenge is to leverage what already exists.

## Finding the sweet spot

> Can we really build something good, fast and cheap?

We can definitely build something reasonably good, reasonably fast and reasonably cheap, if we apply the following guidelines:
1. Don't ask what the customer **wants** but what do they **need**
    * Be thorough on the definition-of-done, even if it's not the final product
    * Be honest and transparent to the customer and never hide problems
1. Check (both FOSS and internally), **who** is doing **what**
    * Lookup source code using [GitHub Advanced Search](https://github.com/search/advanced?q=)
    * Reuse code added as a versioned dependency (as opposed to copy-paste)
    * Contact people that are (or were) involved in those relevant projects
    * Ensure you are not developing the same thing twice
1. Choose technologies (and programming languages) that deliver **efficiently** your solution, don't solely focus on what you know
    * Choosing non-scalable technologies or stale open-source libraries or interpreted languages can be costly on the long term
1. Build software with CI/CD, unit-tests, static code analysis, ... from **day one!**
    * CI (Continuous Integration) will save time by finding issues early in the codebase and CD (Continuous Delivery) will allow you to deploy automatically your libraries
    * Unit-tests will ensure your newly block of code is working as you expect and future refactoring won't "break" your expectation on that small unit of code saving potentially days of hard debugging on nasty side effect issues
    * Apply static code analysis so you find already red-flagged code issues early
    * Apply (and enforce on CI) style checkers so all developers can better understand and contribute to the codebase and rely on regex to refactor code
    * Add minimum documentation (README, Wiki, GitHub Pages, …) to lessen the learning curve for anyone new to the project
    * Add integration and smoke tests when applicable (the more a machine can test, the faster you go!)
1. Make an effort to **join people** (and break silos!)
    * Specially in big companies, make sure you have 1 team collaborating on delivering 1 use-case instead of having multiple teams competing on the same use-case/product
    * Do not underestimate the value of a mix of skills in a project, (FullStack, UX, Product Owner, QA, DevOps, etc…)
1. Avoid meetings and avoid slides as much as possible
    * Use GitHub Issues to discuss topics in a productive way
    * Use GitHub Wiki to document your repository
    * Do not underestimate the power of the written word (write decisions made after each meeting)
1. Trust your team
    * Managers should leave technical project decisions to the development team
    * Trust developers experience when they say "can't be done". Sometimes projects suffer delays on issues that were flagged early-on but were still pushed by business
1. Understand "costs"
    * Cost of Delay - Ask yourself, what will cost us the most, by delaying its delivery?
    * Cost of Opportunity - Ask yourself, what are you gaining and what you are giving up on each decision?
    * Cost of Demotivation - Give your developers autonomy, mastery, and purpose

## Conclusion

Developing software is hard. Done right is hard, done poorly it's even harder.
And a great software product is much more than its source-code.

The temptation of delivering fast often leads to a poor quality proof-of-concept that later struggles to mature, leading to unnecessary frustration from all sides.

I believe if we always apply solid software foundations and principles, we can work towards this optimal balance of good, fast and cheap project development, when so many other variables are unknown.

### References

* Does Test Driven Development Work?
https://dev.to/ruairitobrien/does-test-driven-development-work-p54
* TDD × ROI: Is Test-Driven Development worth the money?
https://medium.com/crowdbotics/tdd-roi-is-test-driven-development-worth-the-money-d535c8d5a5f
* Realizing quality improvement through test driven development:
https://rd.springer.com/article/10.1007%2Fs10664-008-9062-z
* A Longitudinal Study of the Use of a Test-Driven Development Practice in Industry (IBM):
http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.104.6319&rep=rep1&type=pdf
* Cost of delay:
http://blackswanfarming.com/cost-of-delay/
* Cost of opportunity:
https://www.thebalance.com/what-is-opportunity-cost-357200
* Cost of demotivation:
https://phauer.com/2019/motivate-team-software-developers/
