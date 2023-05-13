# Pooled Tip Sheet Calculator and Organizer (WIP) minor functionality.
 This project is designed for use in a restaraunt, food service or retail setting that pools their tips amongst several employees.
 
 The calculator and organizer is written in and runs on Google's AppScript based on JavaScript. The project itself only interfaces with Google Sheets and Google Forms.
 
USE CASE and CONTEXT
 Management at a restarant created a Google sheet that collects their manager's end of day data at mid shift and end shift. The sheet collected data from employees thru use of a Google Form, however, the general manager ran into an issue where employees would leave the restaurant but it wouldn't be possible to remove their name from the form without deleting data or creating a new form. This is due to the strict link between a Google Sheet and Form when used together. To solve this issue the general manager would have to reformat and update the form every single time there was a staff change it added work hours and had the possibility of errors or data loss.
 This restaurant pools all employee tips and distributes them based upon hours total hours worked per shift. This restaurant has two shifts: lunch and dinner. Tips can come from different sources (ie. cash or doordash). 
 
REASONING
 To fix their issues I decided to use a simple AppScript. The problem the manager used could probably be solved via smart tricks instead of writing any code. however, the general manager also requested that the sheet be easy to delegate to other managers and lower the amount of training required to utilize the sheet. So alongside form automation the following features are to be implemented into the script
  1. Little to no manual data entry.
  2. Implement a main page that presents data and can view historical data by use of buttons or drop-downs.
  3. Custom tool-bar scripts to manipulate the sheet such as adding or deactivating employees.
  4. Complete retention of historical data even from past employees.
  5. Automatic form field updating.
  6. Automatic tip calculation for all individuals.
  7. Ability to select pay periods, employees or dates to filter data presentation.

These features will help the managers to reliably calculate tips for their employees, reduce time spent organizing the sheet, make financial data easily available when requested by their accountant and will allow them to delegate this sheet to other managers with minimal training.

CURRENT STATUS
 The sheet and form programming was completed however the genral manager requested a different format. Before the sheet was implemented to allow all employees to submit their own data. That data would then be parsed using unique identifiers for each employee. The change would be to only allow managers to submit data including the tip totals as well as a record of each lower level employee's worked hours. This means that instead of parsing the data based on who submits it I would have to create a form that would automatically add or remove fields with employee's names based on the coniditon of if they're active or not. This is still a work in progress.
 
