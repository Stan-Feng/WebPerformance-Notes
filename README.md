## Performance Golden Rule
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