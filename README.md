Below, you can find the description of your eleventh assignment, which also
includes its output through a series of GUI screenshots.
In this assignment, you are expected to improve your existing Hotel
Reservation System by incorporating multithreading to search among existing
Reservations by hotelName.
In order to perform multithreaded search, you need to create at least 8
reservations first (see Fig 1). Furthermore, also please notice that a new button
has been introduced to the frame called Multithread Search.
Fig 1. System GUI after 8 new Reservations are created and displayed
As stated above, in order to be able run a multithreaded search the system
requires having at least 8 Reservations. Therefore, the system should check the
number of reservations made so far before executing a multithreaded search. If
the prerequisite is not satisfied then it should prompt the user to create 
enough Reservations (see Fig 2). Please note if the Multithread Search button is
clicked, it should first check the total number of reservations so far before
staring the multithreaded search process.
Fig 2. System prompts the user to create at least 8 reservations.
After the required number of Reservations is created and the Multithread
Search button is clicked on; a JOptionPane should pop up and ask the user to
insert a hotel name (see Fig 3) to conduct a search on.
Fig 3. Pop up asks for a hotel name to conduct Multithread Search
If the user enters a hotel name that is exists within the Reservations, the
Reservation IDs for the hotels with given name should be returned (see Fig 4a).
For example, in Figure 4b a multithreaded search for all hotels named
“Sheraton” is requested and the search conducted on the reservation data set
provide in Figure 1 resulted with the IDs shown in Figure 4c.
(a) (b)
(c)
Fig 4. Multithread Search

