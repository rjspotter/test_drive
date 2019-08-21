# README

## Challenge Overview
Build a website for a company that sells subscriptions to legal plans in different countries. The app does not need to be hosted anywhere but should work as expected when run locally.

## Features
- A user should be able to visit a url and see the plans available for a country
- Each plan should display a name and price.
- Each plan should have a "subscribe" button (n0p)
- Clicking on a specific plan should take you to a new page listing the full plan details (plan description, list of benefits (name, description))
- You don't need to spend too much time styling the views

## Requirements
- Build server using Rails 5x
- Use sqlite (its the default db)
- Create a way to seed the database so your work can be checked
- Plans should have different benefits and prices in different countries
- Handle edge cases
- Build a RESTful API with the following resources:
   * GET all plans available for a country (return a list of id, name, price)
     - Available at /countries/:id.json
   * GET a single plan for a country (return a list of id, name, price and benefit information (benefit name, description))
     - Available at /countries/:country_id/plans/:id.json
- Write an integration test for at least one of the routes
- Write some unit tests for your models
