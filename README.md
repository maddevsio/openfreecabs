# OpenFreeCabs

https://openfreecabs.org Web/mobile app that shows nearest taxi's by your location

# History behind service

So history starts in Bishkek city, Kyrgyzstan. Here we have some problems to decide on, namely, which taxi service to choose from.
Let's imagine.
You live in the microdistricts of Bishkek city and you're in a hurry to work. You know that upon order almost all taxis will arrive to your destination within around 20-30 mins. And then what? You book the first taxi company and receive text message that "We can't find you a car". You book the second one and the same thing takes place. You think, that there is no way that could be happening.

That was the motivation to create this service. We would like for the time that people spend to book a taxi during rush hour to be less.

# What we do? And some architecture of service

We decided to take all free drivers from open sources of all taxi services in Bishkek and make a service that provides us the information as to which service we should place an order with.

Service consists of these components:

1. [Storage](https://github.com/maddevsio/openfreecab-storage) - In-memory storage for openfreecabs.org that stores spatial data
2. [Crawler](https://github.com/maddevsio/openfreecab-crawler) - Crawler for openfreecabs, that crawls data from open sources (websites, mobile apis, etc)
3. [Android App](https://github.com/maddevsio/openfreecabs-android) - Android  app for users, that shows nearest taxi drivers
4. [iOS App](https://github.com/maddevsio/openfreecabs-ios) - iOS  app for users, that shows nearest taxi drivers
5. [Web App](https://github.com/maddevsio/openfreecabs-web) - Web  app for users, that shows nearest taxi drivers


# Installation
