# RubyOnRails-TODOList-Web-App

## Overview
The **RubyOnRails-TODOList-Web-App** is a web-based Todo list application built with Ruby on Rails. This application allows users to track their completed tasks, manage user authorizations, and utilize a Pomodoro timer for productivity.

## Features
- **Task Tracking**: Users can create, update, and delete tasks.
- **User Authorization**: Secure user authentication and authorization.
- **Pomodoro Timer**: Integrated Pomodoro timer to boost productivity.

## Getting Started

### Prerequisites
Ensure you have Docker installed on your machine.

### Running the Project
To run this project, follow these steps:

1. Start the Rails container:
   ```sh
   docker-compose run --rm --service-ports ruby_dev
1. Start the Rails server:
   ```sh
    rails server -p $PORT -b 0.0.0.0
