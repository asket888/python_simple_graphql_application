Simple GraphQL API Application
==============================

This application is a GraphQL backend to practice with API automated testing on localhost.

Setup
=====
1. `git clone git@github.com:brainly/python_simple_graphql_application.git`
2. navigate to project directory
3. run `pipenv install`
3. run `pipenv shell`
3. run `python -m recipes_manager` to start application
4. After an application is started, its should be available in URL `http://localhost:8080/graphiql`

Examples
========
1) Query all recipes
![Screenshot](screenshots/1_query_all_recipes.png)
2) Query one recipe
![Screenshot](screenshots/2_query_one_recipe.png)
3) Mutate recipe
![Screenshot](screenshots/3_mutate_recipe.png)
4) Subscription session
![Screenshot](screenshots/4_subscription.gif)
4) Directives (validation)
![Screenshot](screenshots/5_ratelimiting.gif)
