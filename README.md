# Choosing-teams
Artificial Intelligence

Initial state:- Initial state is no  student assigned to any group
statespace: combination of the groups in a way that satisfies the preferences of student selected randomnly.(optimised the code to great level)
Cost function:- calculating the total complaints of that particular group.
Successor function:- randomn select a student and get all possible groups which satisfies his prefence
goal state:- list of stuident groups with least complaints

Procedure:
    keep the initial state into the fringe. 
        check for goal state. if goal display
        take min from fringe calculates cost using cost function  and append them to fringe
        we are not visiting the already visited states if their cost is greater than existing cost of that state. (By using this idea we are getting results quicker)

