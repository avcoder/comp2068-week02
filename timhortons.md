(use notepad application to create draggable items)

# Desk Rules

* The worker at the desk can only do fast tasks
  * Fast tasks are making coffee
  * Slow tasks are making sandwiches
* If the worker at the desk receives a slow task, delgate it to kitchen
* Once an order is done, call out "quote" and give food

# Kitchen Rules

* When an order is received from the desk, take time to make it right
* Once it's done, then place the food and the ticket (i.e."quotes") on the Done Lineup

# Turnstyle Rules

* When the desk is not doing anything, then look at the Done Lineup and send food and ticket to Desk

# Questions

1.  What do the following items symbolize in JS land?

* desk (stack V8)
* kitchen (web APIs)
* done line up (callback queue)
* turnstyle (event loop)
* sequence (console)

1.  What methods in JS land take a long time? (setTimeout, XMLHttpRequest/fetch/getting JSON data, DOM, readfiles)

1.  The analogy for panini("Albert") isn't quite right. It should be panini(to-do-later() { .log("Albert")}). Why?
