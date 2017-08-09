# trellis-jms

[![Build Status](https://travis-ci.org/trellis-ldp/trellis-jms.png?branch=master)](https://travis-ci.org/trellis-ldp/trellis-jms)
[![Build status](https://ci.appveyor.com/api/projects/status/sx770kkhbbvn7q5x?svg=true)](https://ci.appveyor.com/project/acoburn/trellis-jms)
[![Coverage Status](https://coveralls.io/repos/github/trellis-ldp/trellis-jms/badge.svg?branch=master)](https://coveralls.io/github/trellis-ldp/trellis-jms?branch=master)

A JMS-based messaging connector. This implements an event bridge to
JMS-based brokers, such as ActiveMQ.

## Building

This code requires Java 8 and can be built with Gradle:

    ./gradlew install
