# Schedule

* All classes are **6-8pm** at the CUNY Graduate School for Journalism, **[219 W. 40th St.](https://www.google.com/maps/preview?ie=UTF-8&fb=1&gl=us&sll=40.755362,-73.988805&sspn=0.0249669,0.0439463&cid=11463841082808986305&q=cuny+graduate+school+of+journalism&ei=FT4OVJaODI7gsASN2YDIBg&ved=0CKIBEPwSMA4)**. Take the elevator to the third floor, check in with the security guard there, then take the stairs to **room 436**.
* Assignments:
    * Estimated times are included, where possible.
    * Unless otherwise specified:
        * Go through the entire resource
        * Should be completed by the following class
* Bring a laptop to class.
* Everything on this page is subject to change.

## July 22

* Introductions
    * Name
    * School
    * What do you want to learn?
    * What are you afraid of?

### Homework

1. [Set up your machine](setup.md)
1. [The twelve most important Unix commands](http://lab.demog.berkeley.edu/Docs/12important/12important.pdf) - 2 hrs
1. [Git Real](https://www.codeschool.com/courses/git-real) - 4 hours
1. [Mastering GitHub](https://www.codeschool.com/courses/mastering-github), levels 1, 2 & 4 – 4 hours
1. Submit your info to [the student directory](https://github.com/cuny-nytech/students) – 15 mins

## Sept 8
* Language Landscape (why ruby and what are the alternatives), and how the inter web works
* Peter

### Homework

1. [Codecademy HTML/CSS track](http://www.codecademy.com/en/tracks/web) – < 7 hours
1. Create project showcase on GitHub Pages from scratch
    * Follow instructions on [Pages](https://pages.github.com/) site, using these options:
        1. User or organization site
        1. A terminal
    * Doesn't need to be fancy
    * Add some existing projects, or placeholders
    * Inspiration:
        * http://twitter.github.io/
        * http://square.github.io/
        * http://gilt.github.io/
        * https://cfpb.github.io/
        * http://bigcartel.com/examples
1. Join these meetups:
    * [NYC.rb](http://www.meetup.com/NYC-rb/)
    * [NYC on Rails](http://www.meetup.com/nyc-on-rails/)
    * [Hack & Tell](http://www.meetup.com/hack-and-tell)

## Sept 22

* Front-end (HTML/CSS 101)
    * Sandboxes
    * Local development
    * Dev Tools
    * External files
* GUEST ([Donn Morrill](http://www.linkedin.com/pub/donn-morrill/3/609/69a), [Amazon, Clouds and Computing](http://aws.amazon.com/))
* Aidan

### Homework

1. [Try Ruby](https://www.codeschool.com/courses/try-ruby) – 4 hours
1. [Ruby Bits](https://www.codeschool.com/courses/ruby-bits), through "Hide instance variables" (a.k.a. up to "ActiveSupport") – 2 hours
1. [Create a Choose Your Own Adventure game](https://github.com/cuny-nytech/adventure) – 4 hrs
1. Read:
    * A handful submissions (including comment sections) on [Hacker News](https://news.ycombinator.com/)
        * Take the comments with a grain of salt
    * [The Valve Handbook for New Employees](http://www.valvesoftware.com/company/Valve_Handbook_LowRes.pdf)

## Oct 6

* Guest speaker: [Bernard "Bernie" Kravitz](http://www.linkedin.com/in/bernardkravitz), [GoWatchIt](http://gowatchit.com/)
* Look at Choose Your Own Adventure assignment
* Review Ruby
* Introduce Sinatra
* Aidan

### Homework

1. Go through [Singing with Sinatra](http://code.tutsplus.com/tutorials/singing-with-sinatra--net-18965)
1. Look at the [example Sinatra app](https://github.com/cuny-nytech/sinatra-example)
1. Go through [Getting Started with Ruby on Heroku](https://devcenter.heroku.com/articles/getting-started-with-ruby)
    * Note that your `Gemfile` will be much simpler than [their example](https://devcenter.heroku.com/articles/getting-started-with-ruby#declare-app-dependencies), since you won't be using a database. Specifically, don't include `gem "pg"` unless you know you need it.
1. Complete the [Single-Purpose App](https://github.com/cuny-nytech/single-purpose) assignment

## Oct 20

* Cover command-line and SQL
* David

### Homework

* Complete [persistence assignment](https://github.com/cuny-nytech/persist)

## Nov 3

* Look at Sinatra projects
* Talk about hosting
* Rails 1
* Aidan

### Homework

1. Go through the [Thinkful Ruby on Rails Tutorial](http://www.thinkful.com/learn/ruby-on-rails-tutorial/)
1. Go through chapters 1-2 of [Michael Hartl's Rails Tutorial](https://www.railstutorial.org/book)

## Nov 17

* Talks from the journalism incubator
* Software craftsmanship
* Guest speaker: [Trace Wax](https://twitter.com/tracedwax), [thoughtbot](http://thoughtbot.com/)
* Peter

### Homework

1. Go through [Rails for Zombies 2](https://www.codeschool.com/courses/rails-for-zombies-2)
1. Complete the [persist-rails assignment](https://github.com/cuny-nytech/persist-rails)

## Dec 1
* Rails 2
* GUEST/Company visit
* Aidan

## Dec 15
* Rails 3
* Guest speaker: [Adam Gotterer](https://www.linkedin.com/in/agotterer), [Nomi](http://nomi.com/)
* Aidan

## Jan 5
* This session *may* not happen - to be determined

## Feb 9
* Rails 4
* Aidan

## Feb 23

* Rails project
* Go through [Test to Learn](https://github.com/afeld/test_to_learn) talk
* Aidan

### Homework

1. Take a look at the [`complete`](https://github.com/afeld/test_to_learn/tree/complete/src) version of the TodoList example we were looking at in class - note the [additional resources](https://github.com/afeld/test_to_learn#resources)
1. Go through [Testing with RSpec](https://www.codeschool.com/courses/testing-with-rspec)
1. Add tests to one of your applications
    1. Unit tests around at least one model using [rspec-rails](https://relishapp.com/rspec/rspec-rails/docs) (or [Minitest](http://docs.seattlerb.org/minitest/) or [Test::Unit](http://test-unit.github.io/) if you prefer), e.g.
        * Ensure [validation](http://guides.rubyonrails.org/active_record_validations.html) is set up correctly
        * Test any custom methods work as expected
    1. Functional/integration tests using [Capybara](https://github.com/jnicklas/capybara)
        * Pick one "flow", e.g. signing up, creating a new Post, etc.

## Mar 2

* Cover testing in Rails
* Look at various testing libraries
* Pick group projects

### Homework

Continue work from last week on testing.

## Mar 9

* Introduction to APIs
    * HTTP libraries
        * [`OpenURI`](http://www.rubydoc.info/stdlib/open-uri/OpenURI)
        * [`REST Client`](https://github.com/rest-client/rest-client)
    * https://gist.github.com/afeld/4952991
* Kickoff for final project
* Set up initial tasks

### Homework

* Set up and do preliminary user interviews
    * Take copious notes, and direct quotes where possible
        * Record the call/meeting (with the participant's permission), or
        * Have two NYTech people on the call, where one can talk notes while the other asks questions
* Come up with an implementation plan
    * What is the problem we are trying to solve?
    * What are we actually going to build?
    * What are we *not* going to build?
    * What are the known unknowns?

## Mar 16

* Present interview results
* In-person chat w/ Ricky
* GUEST: Jeremy Canfield from 18F, on User-Centered Design

## Mar 21, 11am-4pm

Visit CoderDojo event at SquareSpace.

* Observe event setup procedures
* Observe registration procedures
    * Try to talk to some first-time attendees/parents, and those who have attended before
    * Take note of issues/bottlenecks/confusion

## Mar 23

* Aidan out of town
* Professional presence, interview prep - Peter
* Resources
    * http://www.pcworld.com/article/2457500/5-ways-to-use-social-media-to-boost-your-career-prospects.html

## Mar 30

TBD

## Apr 6

TBD

## Apr 13

TBD

## Apr 20

Open work session

### Homework

Prepare resume

* Bring four printed copies (unless it's in an easily-annotateable format like Google Docs)

## Apr 27

* JS fundamentals
    * [Sandboxes](http://documentup.com/advanced-js/syllabus#resources/tools)
    * Syntax overview
        * Everything is a value
        * Lightweight functions
    * jQuery
        * Manipulating elements
    * [AJAX](https://github.com/advanced-js/deck/tree/gh-pages/demos/ajax)
* Resume review

## May 4

* Mock interviews
* Professional Presence talk w/ Peter
* Final project demo prep

## TBD

* Final project demo at a meetup
* Farewell dinner

---

## Topic backlog

* SQL - David
* NoSQL
* Guest panel
