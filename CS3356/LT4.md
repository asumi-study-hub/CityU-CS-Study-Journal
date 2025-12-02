# Project Time Management
## Managing Software Projects

### Project Management Processes Overview
```
Project Charter → Project Plan
    ↓
Collecting Requirement → Defining scope → Create WBS
    (Project Scope Management)
```
*Initiating and Planning Stages*

## Importance of Project Schedules

- **What will be the problem of missing a delivery schedule?**
- Time has the **LEAST amount of flexibility**
  - It passes even if you do nothing
- Scope and resources/cost could have multiple dimensions to argue
  - I have met the scope. Why not?
  - Reallocate resources to other projects to reduce cost
- Scheduling (time) issues are the main reason for conflicts on projects, especially in the latter stages (approaching deadline) of a project. Asking more resources/time to meet deadline
- Many business opportunities are time-dependent
  - A quick response to business environment is critical to the success of a business
  - Especially for IT projects (now we are talking AI. What will be the future?)

## Project Time Management Processes

1. **Planning schedule management**: determining the policies, procedures, and documentation that will be used for planning, executing, and controlling the project schedule
2. **Defining activities**: identifying the specific activities that the project team members and stakeholders must perform to produce the project deliverables
3. **Sequencing activities**: identifying and documenting the (dependencies) relationships between project activities
4. **Estimating activity durations**: estimating the number of work periods that are needed to complete individual activities
5. **Developing the schedule**: analyzing activity sequences, activity resource estimates, and activity duration estimates to create the project schedule
6. **Controlling the schedule**: controlling and managing changes to the project schedule

### Project Time Management Process Flow
```
Planning Schedule Management
        ↓
Defining Activities → Sequencing Activities → Estimating Activities durations
        ↓
    Developing Schedule
        ↓
    Controlling schedule
```
*Note: some processes are performed concurrently*

## Planning Schedule Management (1)

- tools to develop the schedule management plan (how to management the schedule):
	-  expert judgment
	- analytical techniques
	- meetings 
- **A schedule management plan includes**:
  - The scheduling methodology (e.g., PDM)
  - Level of accuracy and units of measure (e.g., days)
  - Control thresholds (e.g., when need to be alert)
  - Rules of performance measurement (weekly? Monthly?)
  - Reporting formats

### Planning Schedule Management Considerations
- Project charter states the expected start date and end date of a planned project
  - Agreed amongst the top management and main stakeholders
- Project charter also includes estimations on how much money and resources will be allocated to a project
  - Preliminary and overall: Cost Vs. Scope Vs. Time
- Project manager starts with the project charter to develop a project scope statement and WBS (refined) to fit into the committed time and resources constraints
  - Given the targeted cost and scope, define a feasible schedule. How? Based on the initially defined period!
- To define a schedule, the project manager defines an activity/task list, their attributes and a list of milestones
  - A schedule consists of a list of activities/tasks and their start/end dates

## Defining Activities (2)

- **Scope management**: a list of identified tasks to be done before the project deadline
- An **activity or a task** is an element of work normally found on the work breakdown structure (WBS)
- An **activity/task list** is a tabulation of activities:
  - The activity name
  - An activity identifier
  - A brief description of the activity
- **Activity attributes**: provide information about an activity, i.e., predecessors, successors, logical relationships (dependencies), leads and lags, resource requirements, constraints, imposed dates, and assumptions (to be completed in other time management processes)

### Milestones (monitoring progress)
- You may divide (add) a project into several milestones (check points)
- A **milestone** is a significant activity that normally has no duration (just a check point)
  - A good indicator of the current status of your project
  - checkpoint 
- It often takes several activities and a lot of work to reach a milestone
  - A project has several milestones
  - Examples include obtaining customer sign-off on key documents or completion of specific products
- They are useful tools for monitoring progress
  - If you miss a milestone, then you may need to consider to do something to catch up the schedule
  - Meeting every milestone => higher chance to meet the final project delivery deadline

## Sequencing Activities (3)

- After defining the activity list, the next step is to define their dependencies (sequencing activities)
- A **dependency**:
  - *E.g., Task Two can be started only after Task One has been completed*
  - A one-to-one relationship
  - What are the other relationships? Many to one/may to one/...
  - *E.g., the precursor of a course*
- You must determine dependencies in order to use critical path analysis
  - Critical path is the most important path (in a schedule) that you need to meet
  - A delay in the critical path will delay the whole project
- Activity sequencing limits the project schedule as they are constraints on the start times of project activities

### Three Types of Dependencies
1. **Mandatory dependencies**
   - Inherent in the nature of the work being performed on a project, sometimes referred to as hard logic
   - Something that you must follow
   - *I.e., testing after coding*

2. **Discretionary dependencies**
   - Defined by the project team
   - Sometimes referred to as soft logic and should be used with care since they may limit later scheduling options
   - *e.g., Implementation is started only after design is completed*

3. **External dependencies**
   - Involve relationships between project and non-project activities
   - *e.g., installation after the arrival of new equipment*

## Network Diagrams

- Use a diagram to show the dependencies
  - Easy to understand and communicate
  - A figure worth thousand words in particular to senior management
- A **network diagram** shows the precedence relationships among project activities
- Two main formats are the arrow and precedence diagramming methods

### Arrow Diagramming Method (ADM)
- Also called **Activity-On-Arrow (AOA)** network diagrams
- Activities are represented by arrows
- Nodes or circles are the starting and ending points of activities
- Can only show finish-to-start dependencies
  - Activity B starts after activity B is finished

### Network Diagrams (AOA) Example
*(Diagram showing activities as arrows connecting nodes)*

### Precedence Diagramming Method (PDM)
- **PDM**: Precedence Diagramming Method
- Activities are represented by boxes
- Arrows show relationships between activities
- More popular than ADM method and used by project management software
- Better at showing different types of dependencies:
  - **FS**: finish-to-start
  - **SS**: start-to-start
  - **FF**: finish-to-finish
  - **SF**: start-to-finish
- What kind of dependency can be shown in ADM?
  - FS only

### Task Dependency Types
*(Illustration showing different dependency types)*
*Dependencies will affect the start time of an activity*

### Sample PDM Network Diagrams


## Activity Duration Estimating (4)

- **Duration**: end time – start time
- **Effort**: the number of workdays or work hours required to complete a task (i.e., man-day, man-week)
  - Effort does not normally equal duration (holidays; 8hrs per day, weekends)
  - A task requiring 24hr to complete needs 3 man-days to finish
- **How to make a good estimation**:
  - People doing the work should help create estimates, and an expert should review them
  - Project manager and team members should agree on the duration for completing a task


### Three-Point Estimates
- Instead of providing activity estimates as a discrete number, such as four weeks, it is often helpful to create a three-point estimate:
  1. **Optimistic**
  2. **Most likely**, and
  3. **Pessimistic**
- *E.g., three weeks for the optimistic, four weeks for the most likely, and five weeks for the pessimistic estimate*
- It needs not to be the final value, but it provides a more realistic estimation
- Why three points? Four or five points are better? Not necessary. Both are not accuracy and contain a lot of uncertainty
- Three-point estimates are needed for PERT

## Developing the Schedule (5)

- List of activities, dependencies and durations => determine the start and end dates for the set of activities and the project
- The ultimate goal is to create a realistic project schedule that provides a basis for monitoring project progress
- **How to determine whether a schedule is realistic or not?**
  - Look into the details (from rough to details)
  - Ask the team members who are responsible for the tasks
  - A realistic schedule does not mean it will not need to be changed => a lot of uncertainties
- Important tools and techniques include Gantt charts, critical path analysis, and critical chain scheduling, and PERT analysis
  - Graphical presentation easy for reading, communication and identifying problems (delays in schedule)

### Gantt Charts
- **Gantt charts**:
  - Displaying project schedule information
  - Listing project activities
  - Their corresponding start and finish dates in a calendar format
- **Symbols include**:
  - Black diamonds: milestones
  - Thick black bars: summary tasks
  - Lighter horizontal bars: durations of tasks
  - Arrows: dependencies between tasks

### Tracking Gantt Chart
*(Gantt chart showing actual vs. planned progress)*

### Adding Milestones to Gantt Charts
- Many people like to focus on meeting milestones, especially for large projects. Why?
  - You know what you have finished
  - *i.e., Ten steps and you have finished eight ...*
- Milestones emphasize important events on projects
  - If you miss the schedule for an important event, then you may miss the final schedule
- Normally create milestone by entering tasks with a zero duration, or you can mark any task as a milestone

## Critical Path Method (CPM)

- **CPM** is a network diagramming technique used to predict the total project duration (project end date – project start date)
- A **critical path** for a project is a series of activities that determines the earliest time by which the project can be completed
  - Each activity has a start date to an end date
- The critical path is the longest path through the network diagram and has the least amount of slack
- **Slack** is the amount of time an activity may be delayed without delaying a succeeding activity or the project end date

### Calculating the Critical Path
1. First develop a good network diagram, e.g., PDM
   - Realistic activity dependencies
2. Add the duration estimates for all activities on each path through the network diagram
3. The longest path (in time duration) is the critical path
4. If one or more of the activities on the critical path takes longer than planned, the whole project schedule will slip unless the project manager takes corrective actions
   - What should be the corrective actions?

### Determining the Critical Path
*(Example network diagram showing critical path calculation)*

### More on the Critical Path
- A project team at Apple computer put a stuffed gorilla on the top of the cubicle of the person currently managing critical task
- The critical path is not the one with all the critical activities; it only accounts for time
  - Remember the example of growing grass/tree being on the critical path for Disney's Animal Kingdom
- There can be more than one critical path if the lengths of two or more paths are the same
- The critical path can change as the project progresses

### Using Critical Path Analysis to Make Schedule Tradeoffs
- **Free slack** is the amount of time an activity can be delayed without delaying the early start of any immediately following activities
  - Free slack of those activities on the critical path is always equal to zero
  - Free slack = Early Start (next activity) – Early Finish
- **Total slack or total float** is the amount of time an activity may be delayed from its early start without delaying the planned project finish date
  - Late start – Early Start OR Late Finish – Early Finish
- A **forward pass** through the network diagram determines the early start date and early finish date
- A **backward pass** determines the late start date and late finish date

### Calculating Early and Late Start and Finish Dates
*(Step-by-step calculation examples)*

### Using the Critical Path to Shorten a Project Schedule
- **Main techniques for shortening schedules**:
  1. **Shortening durations of critical activities/tasks** by changing their scope
  2. **Crashing activities** by obtaining the greatest amount of schedule compression for the least incremental cost
     - *i.e., Change PT workers to full time workers*
     - *I.e., Two men for two weeks => four men for one week*
     - Increase COST
  3. **Fast tracking activities** by doing them in parallel or overlapping them (be careful!)
     - Increase RISK
- The critical path may change as you enter actual start and finish dates
- If you know the project completion date will slip, negotiate with the project sponsor

## Critical Chain Scheduling

- **Critical chain scheduling**
  1. Identify the critical activity in the project
     - May not be the activity on the critical path
     - The activity with limited resources (highest risk)
  2. Create a project schedule and includes buffers to protect the project completion date
     - A buffer is additional time to complete a task
  3. Attempts to minimize multitasking in particular the critical activity
     - When a resource works on more than one task at a time, it will delay the completion dates of the tasks
     - So, no multitasking for the tasks in the critical path

### Multitasking Example
*(Illustration showing how multitasking delays task completion)*

### Buffer and Critical Chain
- A buffer is the additional time to complete a task
- **Murphy's Law** states that if something can go wrong, it will
- **Parkinson's Law** states that work expands to fill the time allowed
- In traditional estimates, people often add a buffer to each task and use it if it is needed
  - If not needed, then ...follow the Parkinson's Law
- Buffer for each activity or buffer for the whole project?
- Critical chain scheduling removes buffers from individual tasks and instead creates:
  - **Project buffers** or additional time added before the project's due date
  - **Feeding buffers** or additional time added before tasks on the critical chain (i.e., take a break)

### Example of Critical Chain Scheduling
*(Diagram showing critical chain with buffers)*

## Program Evaluation and Review Technique (PERT)

- **PERT** is a network analysis technique used to estimate project duration when there is a high degree of uncertainty about the individual activity duration estimate
- PERT uses probabilistic time estimates
- Duration estimates based on using optimistic, most likely, and pessimistic estimates of activity durations, or a three-point estimate

### PERT Formula and Example
- **PERT weighted average** = `(optimistic time + 4 × most likely time + pessimistic time) ÷ 6`
- **Example**:
  ```
  PERT weighted average = (8 workdays + 4 × 10 workdays + 24 workdays) ÷ 6 = 12 days
  where optimistic time = 8 days
        most likely time = 10 days, and
        pessimistic time = 24 days
  ```
  Therefore, you'd use 12 days on the network diagram instead of 10 when using PERT for the above example

## Controlling the Schedule (6)

- **Goals**
  1. Know the status of the schedule
  2. Influence factors that cause schedule changes, determine that the schedule has changed
  3. Manage changes when they occur
- **Tools and techniques include**:
  - Progress reports
  - A schedule change control system
  - Project management software, including Gantt chart
  - Variance analysis (differences between planned and actual outcomes), such as analyzing float or slack

### Reality Checks on Scheduling
- First review the draft schedule or estimated completion date in the project charter
- Prepare a more detailed schedule with the project team
- Make sure the schedule is realistic (based on experiences) and followed
- Alert top management well in advance if there are schedule problems
  - New (adjusted) schedule
  - Not all stakeholders but only related

### Schedule Control Suggestions
1. Perform reality checks on schedules (including the quality)
   - Not just to complete the task to generate the required output. The output also has to meet the quality requirements
   - *I.e., Complete a network with bandwidth of 100mb*
2. Allow for contingencies (always) => unexpected events may happen (Murphy's Law)
3. Do not plan for everyone to work at 100% capacity all the time (e.g., 70 or 80%)
4. Hold progress meetings with stakeholders and be clear and honest (?) in communicating schedule issues

### Working with People Issues
- Strong leadership helps projects succeed more than good PERT charts
- Tools are just for helping you but not for decision-making
- You need to identify the cause of the problem/delay
- The information presents by a tool highly depending on the assumptions and estimations
  - Estimates are just estimates
  - If your estimations are incorrect, who should be blame?
- **Project managers should use**:
  - Empowerment
  - Incentives
  - Discipline
  - Negotiation

### Using Software to Assist in Time Management
- Software for facilitating communications helps people exchange schedule-related information
  - Incorrect information may mislead the stakeholders
- Project management software can help in various time management areas
  - *I.e., MS Project*

## Chapter Summary

- Project time management is often cited as the main source of conflict on projects, and most IT projects exceed time estimates (10% is acceptable)
  - Why? It is difficult ... So, uses tools and methodologies
- **Main processes include**:
  1. Define activities
  2. Sequence activities
  3. Estimate activity resources
  4. Estimate activity durations
  5. Develop schedule
  6. Control schedule

## References

- Chapter 6: Project Time Management
