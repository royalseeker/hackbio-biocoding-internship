## stage-zero

**Topics Covered:** Coding Syntax, Data Types, and Data Structures

**Instructions:**
1. Form a team of at least 5 people with different programming languages.
2. Using either R or Python, produce the solution with only one of the two languages.
3. Use any data structure of your choice to organize the following information:
   - Your names
   - Your Slack username
   - Your email
   - Your hobby
   - Your countries
   - Your discipline
   - Your preferred programming language
4. Don’t use functions, loops, conditionals, or any complex concepts.
5. Your code should include a final print statement that prints the organized output in a logical and understandable way.
6. Finally, create a simple video tutorial that includes all your teammates. Publish the video on LinkedIn and remember to tag us. We will ❤️ like it!

**Modules to Study:**
- **R**
  - Stage 1: R Syntax
  - Stage 2: R Data Types
  - Stage 3: Data Structures
- **Python**
  - Stage 1: Python Syntax
  - Stage 2: Python Data Types
  - Stage 3: Data Structures

## Code Breakdown

This section provides a detailed breakdown of the code used in the [Stage0.ipynb](Stage0.ipynb). The code is designed to organize and display team member information in a structured format without using complex programming constructs.

### Data Structure Definition

The code begins by defining a dictionary to store information about each team member. Each key in the dictionary represents a team member's name, and the corresponding value is another dictionary containing their details.

```python
team_threonine = {
    "Aparna Padmanabhan": {
        "slack_username": "Aparna",
        "email": "aparna2118@gmail.com",
        "hobby": "Badminton",
        "country": "India",
        "discipline": "Molecular biology",
        "programming_language": "Python"
    }  
}
```
### Print Statement

The main output of the program is generated using a single print statement that formats the information for each team member. This is done using formatted strings (f-strings) to insert values directly from the dictionary.

```python

print(
    "Team Threonine Members:\n"

    f"Name: {team_threonine['Aparna Padmanabhan']['slack_username']}\n"

    f"Email: {team_threonine['Aparna Padmanabhan']['email']}\n"
)
```
### Formatted Strings

The code utilizes f-strings to dynamically include member details in the output. This allows for clear and concise formatting of the information.

Example of a formatted string for a team member:

```python
f"Slack Username: {team_threonine['Aparna Padmanabhan']['slack_username']}\n"
```

### Output Structure

The output is structured in a readable format, with each member's details clearly labeled and separated by newlines for better readability. 
The final output will look like this:

```
Team Threonine Members:
Name: Aparna Padmanabhan
Slack Username: Aparna
Email: aparna2118@gmail.com
Hobby: Badminton
Country: India
Discipline: Molecular biology
Preferred Programming Language: Python
```

### Summary

The code effectively organizes and displays team member information using a simple dictionary structure and formatted print statements. It adheres to the guidelines of avoiding complex programming constructs, making it accessible for all participants in the internship.

