Mystery Item Matcher



Overview

Mystery Item Matcher is a Python console application that helps users record lost and found items and identify possible matches based on their details.



Features

\- Add lost and found item records.

\- View all recorded lost and found items.

\- Search for items by name, ignoring uppercase and lowercase differences.

\- Find possible matches using item name, category, color, and location.

\- Calculate a matching score out of 6.

\- Mark found items as returned.

\- Delete lost or found item records.

\- Use a simple numbered menu to access features.



Technologies Used

\- Python

\- Classes and objects

\- Lists

\- Functions

\- Loops and conditional statements



Matching System

The program assigns points when details match:



| Detail | Points |

| Item name | 2 |

| Category | 2 |

| Color | 1 |

| Location | 1 |

| Total | 6 |



A score of 3 or more is displayed as a possible match. Items already marked as returned are skipped.



How to Run

1\. Install Python.

2\. Open a terminal in the project folder.

3\. Run the Python file using:



&#x20;  python ItemMatcher.py



Replace ItemMatcher.py with the actual name of your Python file if necessary.



Limitations

Records are stored in memory and are not saved after the program closes. Matching uses exact comparisons for each detail.



Future Improvements

\- Save records permanently in a file.

\- Improve matching to recognize similar item names.

\- Add more input validation.

