<!SLIDE>
# Deploying Java and Play! Apps on Heroku

## Craig Kerstiens
## @craigkerstiens
## craigkerstiens.com

<!SLIDE>

# Heroku = Polyglot + PaaS + Cloud Components

## Forget servers and focus on building your app

.notes Find out how many have heard of heroku. Give over view of our background and what a PaaS is

<!SLIDE bullets>

# Polyglot

* Ruby
* node.js
* Clojure
* Java
* Play!

<!SLIDE bullets>

# Polyglot

* Scala
* Python

<!SLIDE>

# 450,000+ Apps Running on Heroku

.notes We run a lot of apps, we've been doing it for a while. Because of this we have a unique opportunity to not only scale us, but know how our users scale their applications and how to build to scale.
<!SLIDE incremental>

# Cloud Application Platform

* HTTP Routing / Load Balancing
* Elastic Polyglot Runtime
* Management & Logging
* Component as a Service Ecosystem

.notes Gave high level cloud application platform, taking a deeper dive. The HTTP routing layer is a responsible for knowing where your traffic goes. The elastic polyglot runtime is what takes responsibility for running your application. Heroku call's these dynos, they're essentially an LXC contained instance. As for management and logging, as i mentioned earlier you don't think about logging. 
<!SLIDE center>

![how-it-works](../images/how-it-works.png)

.notes here's a visual representation of how this looks.
<!SLIDE>

# Instant App Creation

## `heroku create --stack cedar`

.notes So i've talked a good bit about what a PaaS is, and how heroku works. Just a couple more pieces as we'll get into some actual demos. First how do you create an app on cedar. I'm going to assume you already have the heroku client installed. If you don't its available for windows, mac, and debian on our site. To create an application you'd run this command. The reason for the stack is heroku has 3 iterations of its stack, the latest cedar is the one that supports Java. This is not the default yet but it will be soon.
<!SLIDE>

# Instant Deployment

## `git push heroku master`

.notes Now we've created an app, so lets deploy one. Has everyone used git? If not are you familiar with it? Heroku uses git as its receiving mechanism for your application. If you're not familiar with git, its just another form of version control, the largest difference is its distributed instead of centralized. So when we created our app it added the heroku remote so we can push instantly.
<!SLIDE>

# Demo!

### java-workbook/tutorial-5

### Any questions?
