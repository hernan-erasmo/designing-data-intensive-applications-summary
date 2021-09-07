# Reliable, Scalable, and Maintainable Applications

Useful applications meet several requirements, which are generally grouped into 2 categories

- Functional, the *purpose* of the application
- Nonfunctional, the *behavior* of the application

While there are several examples of nonfunctional requirements, we'll focus on 3

- Reliability: The system should be able to work correctly, even in the presence of faulty hardware, buggy software or dummy humans. These occurences are unpredictable, but there are techniques that the system can apply in order to continue operating as expected.

- Scalability: The system must perform as good as always, even under variations in load. The idea behind a scalable system is that it you can add processing power when it needs it (and remove it when it doesn't) and it should still operate reliably.

- Maintainability: "Always code as if the guy who ends up maintaining your code will be a violent psychopath who knows where you live". Architect the application in a way makes life easier for devs and ops teams in charge of changing and operating your app. Good visibility into the app and frequent health checks will go a long way towards this goal.
