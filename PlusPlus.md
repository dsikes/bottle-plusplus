# Bottle++

Let me start out by saying that I think Bottle is a wonderful microframework.

Its easy to use, straitfoward and lightweight. In a world full of bloated frameworks,
this is one solid micro framework that really stands out as a beacon of hope
in a dark, dark world.

For 90% of the use cases I have, Bottle is a perfect fit.

My idea for this project is not to re-create the wheel (literally) - but to add (optional) layers
of improvement on a already solid framework.

Django is awesome - and I've used Django Rest Framework a lot.
But Damn. Sometimes you just don't need the battleship when a speedboat is what you're really looking for.

Bottle++ will bring some nice-to-have features, without adding a steep learning curve to complicate your workflow.

Bottle++ borrows the "convention over configuration" Mantra from Django (and Rails). This has it's pros and cons,
but overall I think its a good choice for several reasons.

Flask is a great Micro framework as well. I considered using Flask when I started to work on Bottle++.
The reason I chose bottle is its a single file, (and Bottle++ is committed to staying that way as well), and has no external dependencies.
Flask also has a lot (too many in my opinion) of "extensions" and it can be quite overwhelming deciding on which ones to use, configure, etc.

But rest assured, Flask will always have a special place in my heart, as it was my first microframework. <3

## Features

Bottle++ brings a few new goodies to the awesome Bottle micro framework.

- MVC Structure
  - A well defined MVC structure suitable for small to medium web apps.

- Logging Middleware
  - Request Logs
  - Application Logs
  - Structured Logs
  - Log Forwarding via syslog (maybe one day)

- Container Optimization
  - Focus on microservices

- Scaffolding CLI tool
  - Generate common files to save yourself some typing.

## TODOs

- [ ] Add Config File Parser
- [ ] Add Environment Variable Support
