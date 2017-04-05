# Sourcery

## Where does your food come from?

When you buy an "organic" piece of fruit, what does that really mean? If you wanted to get in touch with the people who produced it and learn more about the product, would you know how to reach them? If you found a coffee bean you couldn't get enough of, would you know how to find more when the grocery store runs out?

There are countless reasons consumers might want to trace the path backwards from table to farm. There are even more reasons why a regulator might want to use a streamlined technology to easily investigate the origins of any agricultural product, even if it's an individual fruit. This app provides an easy and trustworthy way to do that, no matter what you need to use it for.

### How do I use it?

This repository is the collection of smart contracts (written in Solidity) that power our origin tracking application. It also has a [React front end](https://github.com/tmikeschu/sourcery-client) and a [Rails API](https://github.com/DavidKnott/sourcery-api) to minimize data storage on the blockchain. As a user, you'll want to check out our [production site](sourcery-client.herokuapp.com), and if you're a developer, check out the "Getting Started" section below.

### About Us

We are a group of four [Turing School]() students, and this is our capstone
project for the back-end engineering program. You can learn more about our
development process at these links: [DTR (team expectations)](), [stand-ups](), [Pivotal Tracker]().

### Getting Started

```javascript
git clone https://github.com/ethanbennett/sourcery.git

// Install dependencies:
npm install truffle
npm install solidity

// Run the tests:
truffle test