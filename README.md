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

    
2)  //11:27