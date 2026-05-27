Nutrition Plan App

A desktop application built in Java that generates personalized daily meal plans based on the user's physical profile and fitness goals.

 Features
- Calculates BMI, BMR and TDEE using the Harris-Benedict formula
- Generates a daily meal plan: breakfast, lunch, dinner + 2 snacks
- Supports 3 goals: weight loss, maintenance, muscle gain
- Admin panel to add or remove foods from the database
- Simple GUI built with Java Swing

 How to Run
1. Open the project in NetBeans
2. Run `FereastraNutritie.java`

 Classes
| Class | Description |
|-------|-------------|
| `Utilizator` | Base user with email and password |
| `Admin` | Extends Utilizator, can manage food list |
| `Aliment` | Food item with nutritional values |
| `Masa` | A meal containing foods and quantities |
| `PlanAlimentar` | Generates and stores the full daily plan |
| `ProfilNutritie` | Stores user physical data and goal |
| `CalculatorNutritie` | BMI, BMR and TDEE calculations |
| `FereastraNutritie` | Main GUI window |

 Tech
- Java 17+
- Java Swing
- OOP (inheritance, composition, encapsulation)
