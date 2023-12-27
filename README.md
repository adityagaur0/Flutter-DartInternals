# FlutterDartInternals

## ***Section 1:***
## ***Section 2:***
## ***Section 3:***
## ***Section 4:***
## ***Section 5:***
## ***Section 6:***
## ***Section 7:***
---
## ***Section 8:*** (*Meals App*) [Building Multi-Screen Apps & Navigating Between Screens](https://github.com/adityagaur0/meals.git)
### 1.  Managing sceen stacks.
### 2.  Working with Tab bars.
### 3.  Using side Drawers.
---
## ***Section 9:*** (*MealsApp*) CROSS WIDGET STATE MANAGEMENT
### 1.  Problem:
### 2.  Solution: [Riverpod](https://riverpod.dev/docs/introduction/getting_started) Solution
![Screenshot 2023-12-27 at 2 56 30 AM](https://github.com/adityagaur0/Flutter-DartInternals/assets/112656570/5adb8597-616a-48b3-9b8e-0e385eb450aa)
![Screenshot 2023-12-27 at 2 56 40 AM](https://github.com/adityagaur0/Flutter-DartInternals/assets/112656570/9b52ad4e-90d4-4583-9e39-076490e87c3d)
![Screenshot 2023-12-27 at 2 56 51 AM](https://github.com/adityagaur0/Flutter-DartInternals/assets/112656570/803477bb-f334-4b8f-bff3-093ee564e5c2)
>this on toggle function passing as a parameter is cool for small app but for the large apps it can cause complexity .
therefore we use state management to counter this issue.

![Screenshot 2023-12-27 at 3 41 27 AM](https://github.com/adityagaur0/Flutter-DartInternals/assets/112656570/a75dedfb-1736-42d4-a359-d5608b1714b3)
>this provider provide dynamic value , and the value can change and then in our app for any kind of widget we can set up consumer that connected to the provider by riverpod package ,
and in that consumer we can listen to the changes and also trigger those changes by calling methods provided by provider. 
PROVIDER <----> CONSUMER
1. stateful => ConsumerStatefulWidget && state = >ConsumerState
2. stateless => ConsumerWidget
