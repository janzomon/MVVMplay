# MVVMplay

Multiple Button examples in the style of Neumorphism

## Contents

- [MVVM](https://github.com/janzomon/MVVMplay#mvvm)
- [Steps](https://github.com/janzomon/MVVMplay#steps)
- [Images](https://github.com/janzomon/MVVMplay#images)
- [Feedback](https://github.com/janzomon/MVVMplay#feedback)


## MVVM
The Model-View-ViewModel (MVVM) pattern helps cleanly separate an application's business and presentation logic from its user interface (UI). 
Maintaining a clean separation between application logic and the UI helps address numerous development issues and makes an application easier to test, maintain, and evolve.


## Steps
1. Build ViewModel
   - place the Viewmodel in an extension to say its a View MODEL for contenview
   - make viewModel class `@Observable` to report changes back to swiftui view
2. Add instance of ViewModel in View
   - `@State private var viewModel: ViewModel = ViewModel()`
3. Add Properties to ViewModel
   - add @State properties with out the `@State private`, that you you would use in view normally
5. Add functions to ViewModel
   - add fucntions like `func CalculateAge() throws -> String` to your viewmodel

  
## Images
![Simulator Screenshot - iPhone 16 Pro Max - 2024-11-16 at 17 44 51](https://github.com/user-attachments/assets/57eb84e6-dc2d-4d82-91b3-4b1997455f81)


## Feedback
Please feel FREE to conatct me with feedback or anything else here on github or my email [damon.r.gonzalez@gmail.com](mailto:damon.r.gonzalez@gmail.com)
