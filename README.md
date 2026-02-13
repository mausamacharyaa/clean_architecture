So for Clean Architecture we follow the SOLID Principle.

*What does SOLID Principle means?
SOLID actually contains 5 main aspects they are :

*****************************
1) S --> Single Responsibility Principle
    Yo vanya chai like euta class ma dherei  kam na garne k. The class Should have only one reason to change.

    Example:
        void userAuth () {
            void class username{
                ..............
            };

            void class userPass () {
                .............
            }
        }   // this basiallly is a bad thing and makes the code messy since there are 2 classes inside a sama class


        void class username() {
            ....
        }

        void class userpass () {
            .........
        }// there are 2 separate class for 2 different purpose

    
2)  O--> Open/close principle
        so basically it tells that the code should be open for extensions but closed for modification. It's pretty easy concept.

    

3) L--> Liskov Substitution Principle
        It tells that the the subclasses must be replacable by the main class.



4) I--> Interface Segration Principle
        It tells that we dont have to force a class to impletements methods that doesnt need. like a machine dont eat but work and humans do both . so a machine dont have to implement the eat class . we should manage that.


5) D--> Dependency Inversion Principle
        It tells that " Depend on Abstarction but not on complete implementation".

***********************************************************************************************



APP FLOW.

![APPFLOW](pics/Screenshot%202026-02-13%20064755.png)


