# OpenFreeCabs

https://openfreecabs.org Web/mobile app that shows nearest taxi's by your location

# History behind service

It all has started in the Bishkek city, Kyrgyzstan. There are some problems here people come across everyday, namely, which taxi service to choose.
Just imagine.
You live in one of the microdistricts in Bishkek, and you're in hurry to the work. You think that upon ordering almost all the taxis will arrive to your destination in 20-30 mins. Guess what? You call the first taxi company and get the text message: "We can't find you a car". You call the second one and the same happens again. You think it is impossible to happen. But it happens and so you're late to your work. 

That was the motivation to create this service. We simply want to save time people spend to find the right taxi.

# What we do? And some architecture of service

We took all free drivers info from open data sources of all taxi companies in Bishkek and made a service that shows this aggregated info in single place. So you can see what taxi services are available near you and order one of them.

Service consists of these components:

1. [Storage](https://github.com/maddevsio/openfreecab-storage) - In-memory storage for openfreecabs.org that stores spatial data
2. [Crawler](https://github.com/maddevsio/openfreecab-crawler) - Crawler for openfreecabs, that crawls data from open sources (websites, mobile apis, etc)
3. [Android App](https://github.com/maddevsio/openfreecabs-android) - Android  app for users, that shows nearest taxi drivers
4. [iOS App](https://github.com/maddevsio/openfreecabs-ios) - iOS  app for users, that shows nearest taxi drivers
5. [Web App](https://github.com/maddevsio/openfreecabs-web) - Web  app for users, that shows nearest taxi drivers


# Installation step by step

Installation is easy. Just follow steps described in README.md. The order is

1. [Storage](https://github.com/maddevsio/openfreecab-storage)
2. [Crawler](https://github.com/maddevsio/openfreecab-crawler)
3. And maybe [Web App](https://github.com/maddevsio/openfreecabs-web)

Running this project at production isn't described here because everyone may choose their own path to run it.

# Contributing, PR, issues

You're welcome!
