# Unbabel Applied AI Backend Challenge

Hey 😄

Welcome to our Applied AI Backend Challenge repository. This README will guide you on how to participate in this challenge.

In case you are doing this to apply for our open positions for an Applied AI Software Engineer make sure you first check the available jobs at https://unbabel.com/jobs

Please fork this repo before you start working on the challenge. We will evaluate the code on the fork.

FYI: Please understand that this challenge is not decisive if you are applying to work at Unbabel. There are no right and wrong answers. This is just an opportunity for us both to work together and get to know each other in a more technical way.

## Challenge

1. Build a basic web app with a simple input field that takes an English (EN) input translates it to Spanish (ES).
2. When a new translation is requested it should add to a list below the input field (showing one of three status: requested, pending or translated)
3. The list should be dynamically ordered by the size of the translated messages

### Requirements

* Use Flask web framework
* Use PostgreSQL
* Create a scalable application.
* Use the Marian-decoder (C++ framework) as a way to translate from English to Spanish
* Use RabbitMQ to communicate in between your web application (python) and Marian (C++)
* Use C++ to build the wrapper that will manage the communication between Marian and RabbitMQ
* Have tests

### Notes

* Page load time shouldnt exceed 1 second
* You should not have to touch Marian code (the documentation for developers is almost non existing) but information on how to use Marian-decoder are available [here](https://github.com/marian-nmt/marian) and you should be able to understand the minimum on how to use marian-decoder


### Resources

* Marian links
* RabbitMQ links
