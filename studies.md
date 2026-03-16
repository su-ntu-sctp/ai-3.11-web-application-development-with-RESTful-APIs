# Self Studies: Web Application Development with RESTful APIs

## Overview

This lesson marks an important transition — you will be building your first Spring Boot backend from scratch. The concepts covered (REST design, routing, MVC, Dependency Injection) form the foundation of everything that follows in the course. The self-study materials below will help you arrive at the lesson with a clear mental model so you can focus on coding rather than catching up on concepts.

**Estimated Prep Time:** 60–80 minutes

---

## Task 1: Spring Boot Setup and RESTful Endpoints

This video walks you through creating a Spring Boot project from scratch and building REST endpoints with query parameters and path variables — exactly what you will do in Parts 4 and 5 of the lesson. Watch it in full and follow along if you can.


**Watch:** Spring Boot REST API Full Beginner Tutorial
🎬 https://www.youtube.com/watch?v=wfj-Z9OQpCA&t=800s


**Then read:** Lesson 3.11 — Parts 1 to 5

**Guiding Questions:**
- What is the difference between a query parameter and a path variable? When would you use each?
- Why should REST endpoints use nouns instead of verbs?
- What does `spring-boot-starter-web` add to your project when you include it as a dependency?

---

## Task 2: MVC Pattern and Dependency Injection in Spring Boot

This video covers the second half of the lesson — separating your controller from the main class, and using `@Component` and `@Autowired` to inject dependencies rather than creating objects manually. These are core Spring Boot patterns you will use in every project going forward.

**Watch:** Spring Boot MVC and Dependency Injection Explained
🎬 https://www.youtube.com/watch?v=5cRaQqQb14Q&t=132s



**Then read:** Lesson 3.11 — Parts 6 to 8

**Guiding Questions:**
- What are the three components of the MVC pattern and what is each responsible for?
- What is the difference between creating an object with `new` versus injecting it with `@Autowired`?
- What does the `@Component` annotation tell Spring Boot?

---

## Active Engagement Strategies

- As you watch the first video, try to set up your own Spring Boot project alongside it — even just getting the app to run on `localhost:8080` is a great head start
- After reading Part 3 (REST Design Guidelines), write down 3 endpoint URLs for a fictional app of your choice using the correct noun-based format
- If you are unsure about any annotation (`@RestController`, `@GetMapping`, `@Autowired`, etc.), note it down and bring the question to class

---

## Additional Reading Material

- [Spring Boot Official Documentation — Getting Started](https://docs.spring.io/spring-boot/docs/current/reference/html/getting-started.html)
- [REST API Design Best Practices — Baeldung](https://www.baeldung.com/rest-with-spring-series)
- [HTTP Status Codes Reference — MDN](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status)
- [MVC Pattern Explained — FreeCodeCamp](https://www.freecodecamp.org/news/model-view-controller-mvc-explained-through-ordering-drinks-at-the-bar-efcba6255053/)