---
title: Spring Annotation - @Lazy
date: 2021-06-26 20:42:56

---

### @Lazy
By default, Spring creates all singleton beans eagerly at the **startup/bootstrapping of the application context**. The reason behind this is simple: to **avoid and detect all possible errors immediately rather than at runtime**.

However, there're cases **when we need to create a bean**, not at the application context startup, but when we request it.

##### Reference: https://www.baeldung.com/spring-lazy-annotation




