# Realtime-Digital-Clock



Digital Clock

Description :
This is a simple digital clock application built using Python's Tkinter module. The clock displays the current time, date, and AM/PM status in a graphical window. The time updates dynamically every second using the after() method of Tkinter.


Features:
  Displays the current time in HH:MM:SS format.
  Shows the date in DD MMM YYYY format.
  Automatically updates every second.
  Simple and user-friendly graphical interface.


Installation:
  To run this script, ensure you have Python installed on your system. No additional libraries are required as Tkinter is included in standard Python distributions.




Usage:
  Run the Python script.
  A window will open displaying the current time and date.
  The clock updates automatically every second.
  Close the window to exit the application.



:Code Breakdown:

1) Importing Required Modules:

  tkinter is used for creating the graphical user interface (GUI).

  strftime from the time module is used to get the formatted current time and date.

2) Initializing the Main Window:

  tk.Tk() creates the main application window.

  root.title("Digital Clock") sets the window title.

3) Defining the time() Function:

  Uses strftime('%H:%M:%S %d %b %Y %p') to format the current time and date.

  Updates the label text dynamically.

  Calls label.after(1000, time) to refresh the time every second.

4) Creating and Configuring the Label:

   The tk.Label() widget is used to display the time.

   Font is set to 'calibri', size 50, and bold.

   Background color is black, and text color is white.

   label.pack(anchor='center') places the label at the center of the window.

5) Starting the Clock and Running the Application:

   The time() function is called to start updating the clock.

   root.mainloop() runs the Tkinter event loop to keep the window open.



Example Output

14:30:45 10 Mar 2025 PM



Contributing

Feel free to improve the UI or add more features like different time zones or custom themes.



