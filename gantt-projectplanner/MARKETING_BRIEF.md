# MyGantt v2.0 - Strategic Project Planning & Visualization

MyGantt is an interactive, client-side Gantt charting tool designed to empower teams and leaders with unparalleled visibility into project timelines, dependencies, and critical paths. It transforms static task lists into dynamic, actionable project plans.

## Solving Key Business Challenges

In today's fast-paced environment, project plans are complex and constantly evolving. MyGantt addresses the critical pain points that managers and executive teams face:

- **"Why is this project delayed?"**
  MyGantt provides a clear visual answer. With our dependency highlighting, you can click any task to instantly see its entire downstream impact, making it easy to identify bottlenecks and communicate the root cause of delays to stakeholders.

- **"What happens if we move this deadline?"**
  Conduct real-time "what-if" analysis during live meetings. Drag any task to simulate a schedule change, and watch as all dependent tasks automatically realign. This empowers leaders to make informed, data-driven decisions by instantly visualizing the impact on the overall project timeline.

- **"How can we maintain a single source of truth?"**
  Stop the cycle of editing and re-importing static files. MyGantt features an integrated, editable task table. Make changes in a familiar spreadsheet-like interface, click "Sync to Chart," and your visual plan is immediately updated. This ensures your Gantt chart is always the definitive source of truth.

## Core Features

- **Dynamic Scenario Modeling**: Drag tasks left or right to shift dates and see the entire dependency chain react in real-time. Extend a task's duration by dragging its end date and instantly assess the impact on project completion.

  _A short GIF demonstrating this feature would be perfect here!_
  ![Dynamic Date Shifting Demo](media/dynamic-date-shifting.gif)

- **Critical Path Visualization**: Click any task to highlight all its successors. This immediately clarifies complex dependency networks and helps identify high-risk tasks that could jeopardize deadlines.

  _A short GIF demonstrating this feature would be perfect here!_
  ![Dependency Highlighting Demo](media/dependency-highlighting.gif)

- **Unified Interactive Workspace**: An editable task table sits directly below the chart. Modify task names, dates, progress, or dependencies, and sync your changes to the visual chart with a single click.

- **Seamless Data Integration**: Import your existing project plans via CSV to get started instantly. When you're done, export the current state of your chart back to a CSV for reporting or use in other tools.

  _A short GIF demonstrating the table sync feature would be perfect here!_
  ![Table Sync Demo](media/table-sync.gif)

## Getting Started

1.  **Launch**: The application opens with a sample project for immediate exploration.
2.  **Import**: Click the "Import CSV" button to load your own task list.
3.  **Interact**: Drag tasks, edit details in the table, and sync your changes to see the tool in action.

## Uncompromising Data Privacy & Security

In an era where data security is paramount, MyGantt is architected for complete privacy.

- **Zero Data Transmission**: Your data never leaves your machine. All processing, including CSV parsing and chart rendering, happens entirely within your browser. We do not collect, store, or transmit any of your project information.

- **Full Offline Capability**: Once the website is loaded, you can disconnect from the internet and continue working without interruption. This provides an "air-gapped" level of security, ensuring your sensitive project data remains completely private and under your control.

## Known Issues

- **Task Movement Lock**: On rare occasions, a task may become unresponsive to dragging. A quick workaround is to make a minor edit to the task in the table below and click "Sync to Chart," which restores its interactivity.

## Learn More

For a deep dive into all the features, bug fixes, and technical implementation details, feel free to explore the `docs` folder in the project repository.

We believe MyGantt will become an indispensable tool for your strategic planning and execution.
