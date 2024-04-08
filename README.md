## Description
This app was made to perform simple mathematical operations on fractions. A large part of this was to create a Fraction class as part of a library, which can be used to solve fraction computations in both console and graphical applications at th same time.

To that end this App has some large seperate parts:
- A class library containing the Fraction class.
- Unit tests for this Fraction class.
- A console application to demonstrate the basic usage of the class.
- A graphical WPF application to allow the user to solve fractional computations. 

## Author
This App was made by Olivier Westerman while studying at Vives Brugge in Spring 2024.

## Screenshots
### Console Demo App
![ConsoleDemoSelection](https://github.com/OlivierWesterman/FractionCalculator/assets/145467433/4f1ad93a-d12f-4ff2-85d0-035261ec8914)
![ConsoleDemoOriginalFractions](https://github.com/OlivierWesterman/FractionCalculator/assets/145467433/eb3ae74b-fd02-48b9-8772-b9d02f66db7e)

![ConsoleDemoOriginalFractionsSolutions](https://github.com/OlivierWesterman/FractionCalculator/assets/145467433/ee3107a6-7a97-4944-a286-f8e8e04c2930)
![ConsoleDemoRandomFractionsSolutions](https://github.com/OlivierWesterman/FractionCalculator/assets/145467433/b2b5715c-7b84-42b4-bc91-abf668fa771e)

### Unit Tests
![UnitTests](https://github.com/OlivierWesterman/FractionCalculator/assets/145467433/2663e098-998e-442c-a8f6-f155a96ac2f3)

### WPF Application
![StartupWPF](https://github.com/OlivierWesterman/FractionCalculator/assets/145467433/33808c5b-f9b6-4ea2-9ee2-a167fb5c0342)
![StartTabWPF](https://github.com/OlivierWesterman/FractionCalculator/assets/145467433/cae196f6-9eb0-4e96-a9a7-2c83a44928f2)
![OperatorsTabEmptyWPF](https://github.com/OlivierWesterman/FractionCalculator/assets/145467433/6557e233-3df3-4547-b948-90991e5f4ea5)
![OperatorsTabActionWPF](https://github.com/OlivierWesterman/FractionCalculator/assets/145467433/2a06b241-5889-4b2c-b54d-0ecb27a8a5fa)
![ManipulatorsTabEmptyWPF](https://github.com/OlivierWesterman/FractionCalculator/assets/145467433/a80971fd-360c-421c-81e4-fa62e719df91)
![ManipulatorsTabActionWPF](https://github.com/OlivierWesterman/FractionCalculator/assets/145467433/0e59df37-d673-4b40-9347-3b1ccc67c376)

## Setup
To set up and use the App effectively, you'll need to make sure you have Microsoft Visual Studio installed and enable or install the xUnit testing module.
It is also important to make sure you are working in a .NET 6 or higher environment.
You can find a step-by-step guide for installing these packages here:
- Visual Studio Community edition by following this [link](https://learn.microsoft.com/en-us/visualstudio/install/install-visual-studio?view=vs-2022).
- xUnit by following this [link](https://xunit.net/docs/getting-started/netfx/visual-studio).
- .Net by following this [link](https://dotnet.microsoft.com/en-us/download/dotnet-framework).

Once everything is installed, open the project solution named 'FractionsApp.sln'. Then, build the solution to ensure all dependencies are resolved. 
At the top of your window, select which project you want to run with the dropdown and the click on the play button next to it to run.
![RunningProgram](https://github.com/OlivierWesterman/FractionCalculator/assets/145467433/74dbbb2b-fbe2-4001-870e-06ce6338deac)

## Unit Tests
The UnitTestFractions class contains tests for the Fraction class, ensuring methods perform as expected and give correct results in various scenarios.\
It checks for properties like Numerator and Denominator, ensuring the safeguard for the Denominator works properly.\
Arithmetic tests cover addition, subtraction, multiplication, and division with various values. \
Reciprocal and Invert methods are validated, alongside Simplify method for large fractions. \
Result method is tested for correct floating-point approximation, and ToString method for correct string representation.\
To run these tests see Chapter Setup above.

## UML diagram
The following is the UML diagram for the Library as well as the other projects that it connects to.\
The UML of the Fraction class would only be the blue class.
![UML diagram](https://github.com/OlivierWesterman/FractionCalculator/assets/145467433/0ee281cc-5494-4e63-a24e-7e36ec2fb8fb)

This [link](https://lucid.app/lucidchart/719c3ac3-6d12-45f4-9c02-9b0dc1dd661d/edit?viewport_loc=-2167%2C-39%2C3216%2C1221%2CHWEp-vi-RSFO&invitationId=inv_b5f2439a-9d1e-47bd-999a-76f4c800788b) also leads to a diagram version that can be zoomed in on but you do need to sign in with a Lucid account for that.

## Future Improvements
- The layout of the WPF does not exactly conform to what was requested because I wanted to add my own touch to the project.
- It also could use some more work in terms of user experience since the amount of information on the screen could be overwhelming.
- I'm also sure there is a more powerful way to code the WPF-application without as much repetition in term of functions, I might have overused the copy-paste buttons.
- I would have loved to be able to use radial progress bars to create circles like piecharts to resemble each fraction but this was not a standardard tool. Alot of time was 'wasted' on my end to try and make that work but in the end I also like my regular progress bars.
- In term of functionality there is alot more that could be added. Logaritmic function, exponentials, square roots and the like.

