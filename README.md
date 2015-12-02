## Web Performance Notes
This is all about web performance. Notes taken from FrontEnd Master(https://frontendmasters.com)
The course demonstrated by Kyle Simpson(https://github.com/getify).

## Make Performance a Priority
#### Performance Golden Rule
  - "80%-90% of the end-user response time is spent on the front-end. Start there." -- Steve Souders
  - "Premature optimization is the root of all evil." --Donold Knuth
  - "Immature optimization is the root of all evil." --Getify

#### Why web performance?
  - If $$ related to your web application
  - Quality (maintainable, readable)

#### How web performance?
  - Measurement, Perception (Incredibly Important!)
  - Efficiency --> Speed, Memory (How much bandwidth load per second? This is both science and art)
  - Performance --> Benchmark, Optimize
    - (It's highly important!!! to QUANTIFY the improvement. You have to do that! No Feel! Also Do User Study!)

#### Focus on critical path
  - Noncritical, Critical
  - There's saying in front-end industry:
    - "If you don't have something that takes more than 1000ms, it's not in the critical path"
    - "Death by a thousand paper cuts."
  - Inefficiency is systemic

#### The myth of refactor
  - "Just Do it Now! We'll come back fix it later."
  - By a large the refactor that get promised never happens.
  - Often time, you got one chance to make code write.

#### Total cost of ownership
  - Non-performant code is higher than performant code
  - Performant by default instead of maintainability and readability by default
  - Dirty little secret:
    - Most of "front-end" optimization actually happens in the "middle-end"
    - Middle-end:Templating, URL Routing, Headers, Caching, Ajax, etc

## The Middle-End: YSlow
#### YSlow rules
  1. Fewer HTTP Requests
  2. Use a CDN
  3. Expires/Cache-Control Header
  4. Gzip
  5. CSS at Top
  6. JavaScript at Bottom (What above two rules actually mean -- make a priority of your web app)
  7. External JS/CSS
  8. Fewer DNS Lookups
  9. Minify JS/CSS
  10. ETags (Conditional Loading)
  11. Cacheable Ajax
- But some of these rules are contradictory
  - 1 & 7
  - 2 & 8
  - 3 & 10



## Resources:
  - http://webpagetest.org
  - http://whichloadsfaster.com
  - http://www.gidnetwork.com/tools/gzip-test.php
  - https://developer.yahoo.com/performance/rules.html
  - http://www.stevesouders.com/blog/2012/02/10/the-performance-golden-rule/

















