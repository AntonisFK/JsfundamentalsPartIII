Create a function that takes in one parameter called "name" and returns an object that looks similar to the person object from JS Fundamentals Part II.
The returned object should have a name property that is set to the value of the name argument that was passed into the function.
Each returned person object should also have the following other properties (from JS Fundamentals Part II):
distance_travelled - set this initially as zero
say_name - should alert the object's name property
say_something - have it accept a parameter. It should then say for example "Jay says 'I am cool'" if you pass 'I am cool' as an argument to this method.
walk - have it alert for example "Jay is walking" and increase distance_travelled by 3
run - have it alert for example "Jay is running" and increase distance_travelled by 10
crawl - have it alert for example "Jay is crawling" and increase distance_travelled by 1
Note that in all of the above examples "Jay" is the placeholder for the object's name property.
Change the function name to "personConstructor"
If you have prior exposure to OOP, think about how this "constructor" function is similar to "classes"
If you don't have prior exposure to OOP, think about how this "constructor" function is being used to create many objects of similar types. It is acting as a blueprint for creating person objects.
Now create a ninjaConstructor that can be used to create Ninjas that each have a name, cohort, and belt-level. Give all of the Ninjas a "levelUp" method that increases their belt-level (Have all ninjas start at a yellow-belt).
DO NOT USE "This" or "New" IN YOUR CODE FOR THIS ASSIGNMENT!!!! ONLY USE WHAT WE HAVE TAUGHT UP UNTIL THIS POINT.