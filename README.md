# Airline-Reservation-System

The main menu of Reservation System is:
	Add [P]assenger, Add [G]roup, [C]ancel Reservations, Print Seating [A]vailability Chart, Print [M]anifest, Print [F]irst/[E]conomy Matrix, [Q]uit

If you want to add an individual passenger, enter "P" at the prompt.
Then Reservation System will ask for a passenger name with the prompt, "Name:".
Enter the name of the passenger.

Reservation System will then ask for a preferred class of service with the prompt, "Service Class:".
Enter "F" for First Class or "E" for Economy Class.

Next, Reservation System will ask for your preferred choice of seating with the prompt, "Seat Preference:".
If you entered "F", then enter "W" for Window Seat or "A" for Aisle Seat.
If you entered "E", then enter "W" for Window Seat,   "A" for Aisle Seat, or "C" for Center Seat.

Reservation System will then display the available seat number.
If no seats are available, then Reservation System will display the message: "Request failed."

If you want to add a group of passengers, enter "G" at the prompt.
Then Reservation System will ask for group name with the prompt, "Group Name:".
Enter the name of your group.
Reservation System will then ask for the individual names of each member in your group with the prompt, "Names:".

Enter the names of the members in your group separated with commas.
Next, Reservation System will ask for a class of service with the prompt, "Service Class:".
Enter "F" for First Class or "E" for Economy Class.

Reservation System will then display the available seat numbers, if seats are available.
If no seats are available, then Reservation System will display the message: "Request failed."

If you want to cancel a reservation, enter "C" at the prompt.
Then Reservation System will ask for cancellation type with the prompt, "[I]NDIVIDUAL cancellation or [G]ROUP cancellation?"
Enter "I" for Individual Cancellation, or "G" for Group Cancellation.
If you entered "I", Reservation System will ask for a passenger name with the prompt, "Name:".
Enter the name of the passenger.
If the cancellation was successful, Reservation System won't display any message.
Otherwise, the Reservation System will display the message:
	Cancelling individual reservation with name 'passenger name' failed.

If you entered "G", Reservation System will ask for a group name with the prompt, "Group Name:".
Enter the name of your group.
If the cancellation was successful, Reservation System won't display any message.
Otherwise, the Reservation System will display the message:
	Cancelling group reservation with name 'group name' failed.

If you want to view the seat availability chart, enter "A" at the prompt.
Then Reservation System will ask for class of service with the prompt, "Service Class:".
Enter "F" for First Class or "E" for economy class.
Reservation System will then display the seat availability chart of the chosen class.

If you want to view the passenger Manifest, enter "M" at the prompt.
Then Reservation System will ask for class of service with the prompt, "Service Class:"
Enter "F" for First Class or "E" for economy class.
The Reservation System will then display the passenger manifest for the chosen class.

If you want to quit the Reservation System, enter "M" at the prompt.
The Reservation System will then save the reservations made so far to the text file
whose name was given on the command line and quits.
