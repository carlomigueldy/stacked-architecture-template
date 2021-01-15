# flutter_stacked_architecture_starter

This starter project implements the stacked architecture by FilledStacks, it is heavily reliant on code generators where we don't have to write boilerplate code again and again in every feature you might need for building the app. This template is not entirely opinionated and you may modify it to your needs but I recommend to follow the pattern where code can be testable, loosely coupled and comes with consistency that it means code is easier to maintain and potentially scale with ease. And it also comes with an Authentication Service that handles token-based authentication from a RESTful API.

## Common Issues 

- Auto build loop: https://stackoverflow.com/questions/57934341/error-this-requires-the-non-nullable-experiment-to-be-enabled