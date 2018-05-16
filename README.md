[![Build Status](https://travis-ci.org/tzoght/sandbox-java-example.svg?branch=master)](https://travis-ci.org/tzoght/sandbox-java-example) [![Join the chat at https://gitter.im/sandbox-java-example/Lobby](https://badges.gitter.im/sandbox-java-example/Lobby.svg)](https://gitter.im/sandbox-java-example/Lobby?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)
[![Code Climate](https://codeclimate.com/github/codeclimate/codeclimate/badges/gpa.svg)](https://codeclimate.com/github/tzoght/sandbox-java-example)

# Getting Started Examples
## Solace Messaging API for Java (JCSMP)

This example will show how to quickly get started with "...." using PubSub+

To access a PubSub+ service or broker to run the samples please go [here](https://github.com/tzoght/samples-embeded-docs/blob/master/general/access-pubsub.md). 

If you already have access to a PubSub+ VPN or service, that's great, let's get going

## Contents

This repository contains code and matching tutorial walk throughs for the following scenarios:
1. Hello World

## Prerequisites

If any ...

## Building & Running

# Build and run the Examples

Just clone and build. For example:

  1. clone this GitHub repository
  1. `./gradlew assemble`

## Running the Examples

To try individual examples, build the project from source and then run them like the following:

    ./build/staged/bin/topicPublisher <msg_backbone_ip:port>

The individual tutorials linked above provide full details which can walk you through the examples, what they do, and how to correctly run them to explore Solace messaging.

## Exploring the Examples

### Setting up your preferred IDE

Using a modern Java IDE provides cool productivity features like auto-completion, on-the-fly compilation, assisted refactoring and debugging which can be useful when you're exploring the samples and even modifying the samples. Follow the steps below for your preferred IDE.

#### Using Eclipse

To generate Eclipse metadata (.classpath and .project files), do the following:

    ./gradlew eclipse

Once complete, you may then import the projects into Eclipse as usual:

 *File -> Import -> Existing projects into workspace*

Browse to the root directory. All projects should import
free of errors.

#### Using IntelliJ IDEA

To generate IDEA metadata (.iml and .ipr files), do the following:

    ./gradlew idea

## Contributing

Please read [CONTRIBUTING.md](https://github.com/tzoght/samples-embeded-docs/blob/master/general/CONTRIBUTING.md) for details on our code of conduct, and the process for submitting pull requests to us.

## Authors

See the list of [contributors](https://github.com/SolaceSamples/solace-samples-java/contributors) who participated in this project.

## License
This project is licensed under the Apache License, Version 2.0. - See the [LICENSE](LICENSE) file for details.

## Resources

For more information try these [useful resources](https://github.com/tzoght/samples-embeded-docs/blob/master/access-more-resources.md)

