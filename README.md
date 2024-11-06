Based on the Gishushu Traffic Light State Diagram, here is the specification for each state:

State Specifications
Main_Red:

Main Road Light: Red
Cross Road Light: Green
Transition: After the timer expires, the system transitions to the Main_Green state.
Main_Green:

Main Road Light: Green
Cross Road Light: Red
Transition: After the timer expires, the system transitions to the Main_Yellow state.
Main_Yellow:

Main Road Light: Yellow
Cross Road Light: Red
Transition: After the timer expires, the system transitions to the Cross_Green state.
Cross_Green:

Main Road Light: Red
Cross Road Light: Green
Transition: After the timer expires, the system transitions to the Cross_Yellow state.
Cross_Yellow:

Main Road Light: Red
Cross Road Light: Yellow
Transition: After the timer expires, the system transitions back to the Main_Red state.
