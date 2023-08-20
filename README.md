# Android SDE 2 Interview Preparation - Checklist and Resources

### Kotlin Advanced

inline, noinline, crosslinline

Suspendable lazy
https://proandroiddev.com/once-upon-a-time-in-kotlin-65f6e643e96
[https://gist.github.com/elizarov/f27400a55c1502aacc35b4a3b2f5c9af](https://gist.github.com/elizarov/f27400a55c1502aacc35b4a3b2f5c9af)

[Idiomic Kotlin series](https://medium.com/tompee/idiomatic-kotlin-variance-82355d9a71df)

invariance, covariance & contravariance

Delegations

DSL Basics

Flows Channels, actors
[https://bladecoder.medium.com/kotlins-flow-in-viewmodels-it-s-complicated-556b472e281a](https://bladecoder.medium.com/kotlins-flow-in-viewmodels-it-s-complicated-556b472e281a)

[https://elizarov.medium.com/shared-flows-broadcast-channels-899b675e805c](https://elizarov.medium.com/shared-flows-broadcast-channels-899b675e805c)
Basic flow impl from scratch

Anonymous functions

Sequences and ranges

Functional programming

Sealed classed & interfaces

@field:Json() syntax

custom lazy implementation

[https://dev.to/kotlin/kotlin-standard-library-safari-strings-3lj1](https://dev.to/kotlin/kotlin-standard-library-safari-strings-3lj1)

Dependency Injection
The dependent class should not care how the dependency is initialized
[https://proandroiddev.com/lets-build-our-own-simplified-version-of-koin-19a887306258](https://proandroiddev.com/lets-build-our-own-simplified-version-of-koin-19a887306258)

---
###  Android Advanced

1. Why use view models
2. Why not pass context in viewmodels
3. Do you know about single activity arch
4. How would you centre 3 items horizontally in a layout
5. How would perform a heavy calculation in background and then update textview 
6. Have you used pending intents?
7. Would you recommend using asynctask for bg tasks, why
8. Can you use java.file api to write a file to device storage, what are the limitations
9. How would you incorporate  deep link support
10. What's better,  in running a background task in asynctask, a service or a coroutine
11.  whats your opinion on Cordova, react native, flutter, native
12. What are dex files, vector drawables?
13. Have you worked on projects using frameworks and architecture ?, which ones?
14. How to deal with app getting killed?
15. http header vs form data
16. What's the advantage of nested class
17. How to pass data from activity to activity, activity to fragment, fragment to activity
18. Structure of apk, how apk signature works
19. Why we use gradle , is it compulsory
20. How can I access context in activity, fragment, view, service , view modal and custom class
21. Have you heard about jetpack libraries
22. How do you share a file to other app in android
23. What factors affect app size
24. Val vs const val
25. Can we use destructuring declarations in class
26. lazy vs lateinit
27. Viewbinding vs kotlin synthetics vs butterknife
28. How would you implement dynamic grid in recycler view
29. How would you call a kotlin function in java which takes a lambda argument
30. What is property delegation in kotlin
31. Handle back in fragment
32. sealed class
33. IPC in android
34. singleevent
35. couroutine runs on main or bg thread?
36. Variable type of R.string.mystring
37. print all fragent name from acivity
38. Is launch a suspend function?
39. launching suspending fun of viewmodal from activity - coroutine getting killed behaviour after activity rotate
40. Is until in 0 until n, a kotlin keyword
41. What if i write Thread.sleep(2000) in suspend function
42. How can i use async in a suspend function
43. Why synchronised doesnt work on coroutine
44. Lazy runs in which thread?
45. Hiding string secrets
46. Passive vs active MVC in android
47. In viewmodalscope.launch what is viewmodalscope and what is launch, is viewmodalscope. question about extension functions
48. How do you make a function blocking in kotlin
48. How can we pass a lambda to setOnClickListener
49. Can an inline function work if inline is removed
50. Will async run if await is not called?
51. What is type of variable a in: val a = listOf(null)
52. Write a program which take a lambda and returns a suspedable lambda
53. Does Koin use reflection?
54. If we add a usecase module, how would the gradle dependencies change?
55. How would you implement showing a bar chart with legend in clean arch project
54. should presentation store pagniation data eg current offset or data layer and how?
55. Is it always necessary to create interface in one module and its impl in another? (No, reference Refractor PaymentHelper scenerio)
56. REST vs HTTP
57. What are the domain entities out of: registration, token, user
More at [https://hit-alibaba.github.io/interview/Android/Questions.html](https://hit-alibaba.github.io/interview/Android/Questions.html)

Android Studio Profiling basics

Lifecycle of view
Do static view refresh as much as a refreshing view how does the animating view refresh itself, repeating runnable? 

Lifecycle of screen, repeatOnLifecycle

RxJava basics+

IPC Communication - 3 part series on IPC
[https://perihanmirkelam.medium.com/ipc-techniques-for-android-aidl-bb03ed62adaa](https://perihanmirkelam.medium.com/ipc-techniques-for-android-aidl-bb03ed62adaa)

DI with dagger, hilt and AndroidInjector

jetpack compose
KTLint DeteKT [Kakao](https://github.com/KakaoCup/Kakao)

[Viewbinding delegate](https://gist.github.com/gmk57/aefa53e9736d4d4fb2284596fb62710d)

Screenshot testing

Handler ThreadLocal

Kotlin Gradle DSL

Touch system

Better way to handle and deliver activity results

Android Touch System
[https://stackoverflow.com/questions/7449799/how-are-android-touch-events-delivered/57222691#57222691](https://stackoverflow.com/questions/7449799/how-are-android-touch-events-delivered/57222691#57222691)

[https://stackoverflow.com/questions/13283827/onintercepttouchevent-only-gets-action-down](https://stackoverflow.com/questions/13283827/onintercepttouchevent-only-gets-action-down)

MVVM vs [MVP](https://github.com/antoniolg/androidmvp) vs MVC vs [VIPER](https://medium.com/omisoft/https-medium-com-omisoft-viper-in-android-the-practical-guide-or-how-to-catch-a-snake-78cc17e96d63)

Window system in android

Dialog onStart vs onResume

How automated tests works

why extension function in BaseFragment on livedata wont work? or will it?

---

System Design



Cracking the Mobile System Design Interview (iOS & Android) [https://themobileinterview.com/cracking-the-mobile-system-design-interview/](https://themobileinterview.com/cracking-the-mobile-system-design-interview/)


A Simple Framework For Mobile System Design Interviews | by Alex Lementuev | ProAndroidDev [https://proandroiddev.com/a-simple-framework-for-mobile-system-design-interviews-89f6f4134b84](https://proandroiddev.com/a-simple-framework-for-mobile-system-design-interviews-89f6f4134b84)

System design mock interviews by Alex Lementuev, Google
https://www.youtube.com/watch?v=PYsXmMt5Kdw&list=PLaMN-JyH50OYAfxJEpiQTYTD-gxTf7x9d

weeeBox/mobile-system-design: A simple framework for mobile system design interviews [https://github.com/weeeBox/mobile-system-design](https://github.com/weeeBox/mobile-system-design)



Mobile System Design Interviews (iOS and Android) | by Nasir Mahmood | Medium [https://naxirmahmood.medium.com/mobile-system-design-interviews-ios-and-android-f5d360292c22](https://naxirmahmood.medium.com/mobile-system-design-interviews-ios-and-android-f5d360292c22)


System Design Interview For Mobile Engineers | by Shashank Thakur | Geek Culture | Medium [https://medium.com/geekculture/system-design-interview-for-mobile-engineers-ce712d6ac2c1](https://medium.com/geekculture/system-design-interview-for-mobile-engineers-ce712d6ac2c1)


https://proandroiddev.com/mobile-system-design-exercise-image-library-83999eb0ad3c


System Design for Mobile App Developers - LeetCode Discuss [https://leetcode.com/discuss/interview-question/system-design/691010/System-Design-for-Mobile-App-Developers](https://leetcode.com/discuss/interview-question/system-design/691010/System-Design-for-Mobile-App-Developers)

Grokking the Mobile System Design interview | by Artem Goncharov | Medium [https://artem-goncharov.medium.com/grokking-the-mobile-system-design-interview-6a06fa94491b](https://artem-goncharov.medium.com/grokking-the-mobile-system-design-interview-6a06fa94491b)

Android System Design Interviews? : r/androiddev [https://www.reddit.com/r/androiddev/comments/mrxgkr/android_system_design_interviews/](https://www.reddit.com/r/androiddev/comments/mrxgkr/android_system_design_interviews/)


The System Design Interview For Mobile Developers – Dave's Commute Blog [https://davescommutebloghome.wpcomstaging.com/2019/08/27/system-design-interview/](https://davescommutebloghome.wpcomstaging.com/2019/08/27/system-design-interview/)


An App Developer’s Guide to Mobile System Design Interviews | by Neel Bakshi | Better Programming [https://betterprogramming.pub/an-app-developers-guide-to-mobile-system-design-interviews-74cd552bd963](https://betterprogramming.pub/an-app-developers-guide-to-mobile-system-design-interviews-74cd552bd963)

--- 
## GIT

basic git commands

solving merge conflicts

rebase vs merge

cherrypick

usage without Github Desktop

---

## CI CD Basics

Fastlane

Github Actions

Firebase app distro

[https://proandroiddev.com/ci-cd-pipeline-for-flavoured-android-apps-using-fastlane-and-github-actions-51667b7175af](https://proandroiddev.com/ci-cd-pipeline-for-flavoured-android-apps-using-fastlane-and-github-actions-51667b7175af)

[https://proandroiddev.com/ci-cd-for-android-devs-ii-github-actions-masterclass-8a033bbaf42d?source=collection_home---4------12-----------------------](https://proandroiddev.com/ci-cd-for-android-devs-ii-github-actions-masterclass-8a033bbaf42d?source=collection_home---4------12-----------------------)

[https://medium.com/mindful-engineering/setup-your-cicd-pipeline-with-fastlane-and-github-actions-for-android-apps-587a48b743c4](https://medium.com/mindful-engineering/setup-your-cicd-pipeline-with-fastlane-and-github-actions-for-android-apps-587a48b743c4)

--- 
## Performance

Overdraw

Nested layouts

---

### Questions to Interviewer

Company specific curate questions based on online research
Product, Profitability, Growth, Layoffs, Culture, Work life balance

Can you tell me what a typical day looks like?

What qualities are most important in order to excel in this role?

How an ideal candidate for this role looks like?

[https://www.internships.com/career-advice/interview/best-questions-to-ask-in-an-interview](https://www.internships.com/career-advice/interview/best-questions-to-ask-in-an-interview)

---
### DSA

Basics of List, Sets, Maps and kotlin collections functions

Arraylist, LinkedList, Hashmaps


---

### Coroutines
suspend fun


suspendCoroutine {}

builder functions

withContext

CoroutineScope

Structured Concurrency

Cancellation

flows hot and cold, shareflow , stateflow, callbackflow

channels, mutex


CoroutineContext - indexed set


Job - parent child relationship

Java Future API under the hood

---

### Profile building 

Github open source projects
Blog posts

Linkedin Profile SEO
Give a talk

Prepare Assignment starter base code

Linkedin posts

---
### Clean Arch

Core understanding of clean arch 

Multi module project structure

SOLID principals with whys and hows

layer wise vs feature wise  separation


https://github.com/ESchouten/CleanArchitecture

https://github.com/Elbehiry/Delish

https://proandroiddev.com/enforcing-clean-architecture-using-android-custom-lint-rules-aa8fc1708c59
