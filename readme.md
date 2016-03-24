# Angular and Single-Page Apps

## Learning Objectives
- Explain the difference between directives, models, and controllers in Angular

## Framing

Single page apps (SPAs) are so hot right now. Single page does **not** necessarily mean:

> The user sees everything on one page.

It **does** mean:

> The user never *actually* goes to a different page in their browser, but they may *feel* like they do. There's one main `index.html` page, and then other "pages" are really just pieces of HTML that are loaded in and out as necessary.

There's no single definition of a SPA.

Some examples:

- [Hyrule Potion Shop](http://ga-wdi-exercises.github.io/hyrule_potion_shop/)
- [RepoTagger](http://repotagger.github.io/?name=ga-wdi-lessons), which uses Angular
- [Google Maps](https://www.google.com/maps/@38.9048728,-77.0362223,17z)

Google is one big multi-page app that contains smaller SPAs, like Google Maps. Same for Trello and Pinterest.

#### Why do people like SPAs?

### Angular

Angular markets itself as being "what HTML would have been, had it been designed for building web apps."

Angular is considered a *framework*, not a library.,

#### What's the difference between a framework and a library?

Angular is all Javascript, just like jQuery is all Javascript, but it's very picky. Angular forces you to organize your code in a very structured way.

Confusingly, it uses a lot of the same words as Rails, but with different definitions. Please refer to [the comparison to Rails](#references) at the end of this lesson plan.

To introduce Angular, we're going to *do* some Angular.

## [We Do: Inventory Tracker Walkthrough](walkthrough.md)

## References

### Comparison to Rails

|An Angular [this]... |is like a Rails [that].|
|------------|---------------------|
| module     | gem                 |
| controller | controller's action |
| resource   | model               |
| model      | model's field       |
| directive  | helper              |
| service    | ActiveRecord::Base  |
| view       | view                |
