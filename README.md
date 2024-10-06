# Capacitator

This project is a simple web application designed to help Agile software engineering teams calculate their team's work capacity for a given sprint. The calculation considers the number of available days for each team member, the overall team velocity (measured in Story Points), and a reserved capacity percentage, which accounts for time reserved for non-sprint activities (such as meetings, research, or other commitments).

The name **Capacitator** is a fun nod to capacity and “Back to the Future’s” flux capacitor.

## Purpose

The **Sprint Capacity Calculator** enables Agile teams to estimate their available capacity for a sprint by:

- Defining the available working days for each team member.
- Calculating the total number of days in the sprint, excluding weekends.
- Applying a reserved capacity percentage to account for non-sprint activities.
- Calculating the target story points based on the remaining capacity.

This tool helps Scrum Masters, Product Owners, and team leads plan their sprint work more effectively by getting an accurate estimate of the team's ability to complete work within a sprint.

## Features

- **Sprint Details Input**: Define the sprint name, start date, and end date.
- **Team Member Input**: Add each team member's name and available working days for the sprint.
- **Team Velocity**: Input the team's velocity (in story points) based on previous sprints.
- **Reserved Capacity**: Set a reserved capacity percentage to account for activities outside of the sprint.
- **Automatic Calculations**: The tool automatically calculates:
  - The total number of working days in the sprint (excluding weekends).
  - The total team capacity based on the available days for all team members.
  - The target story points for the sprint, adjusted based on the reserved capacity.
  
## How It Works

1. **Set Sprint Dates**: The user sets the sprint's start and end dates, and the tool automatically calculates the number of working days, excluding weekends.
2. **Input Team Members**: Each team member’s available days for the sprint are added, allowing the tool to calculate total available team days.
3. **Input Team Velocity**: The team’s velocity from previous sprints (measured in story points) is entered.
4. **Set Reserved Capacity**: A percentage of reserved capacity is set to account for time not dedicated to sprint activities (such as meetings or administrative tasks).
5. **View Calculated Story Points**: Based on the available team days and reserved capacity, the tool will calculate the adjusted target story points for the sprint.

## Example

1. The sprint starts on **2024-10-03** and ends on **2024-10-17**.
2. The team consists of 5 members, each with varying availability due to time off or part-time work.
3. The team’s velocity from the last sprint is **88 Story Points**.
4. The reserved capacity is set to **10%** to account for meetings and other non-sprint activities.

The tool will automatically calculate the following:

- Total working days (excluding weekends).
- Total team capacity in terms of days.
- Adjusted target story points for the sprint, based on the reserved capacity.

## Installation and Setup

You can use it online by visiting [Capacitator Online](https://capacitator.online).

This web application is also a static HTML project that can be run in any modern browser. To use it locally:

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/sprint-capacity-calculator.git
    ```

2. Open the index.html file in any web browser.

No additional setup or dependencies are required.

## Contributing

If you’d like to contribute to this project, feel free to fork the repository and submit a pull request. Any bug reports, feature requests, or other suggestions are welcome.

1. Fork the project
2. Create your feature branch (git checkout -b feature/yourFeature)
3. Commit your changes (git commit -m 'Add new feature')
4. Push to the branch (git push origin feature/yourFeature)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](https://raw.githubusercontent.com/omaciel/capacitator/refs/heads/main/LICENSE) file for details.
