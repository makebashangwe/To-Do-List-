main menu
side bar/ menu tabs : 
    TASK MANAGER
        Tasks
        Habits
        Goals (Progress)
        
    Calandars
    Analytics Dashboard
    Forum 
        Self Reflection Log
    Schedules
    Tools:
        Pomodoro Timer

    Finance Manager
    Settings

INITIALIZATION:
** Will Autogenerate CATEGORIES & more based on goals
    1. USER selects what they'd like auto generated (EX. CATEGORIES, HABITS, CALENDAR)
    2. INPUTS GOALS (ex. "I want to lose weight in my thighs)
    3. AI GENERATES CATEGORY FITNESS  and stores specification in challenge cache 

    4. USER INPUTS HABITS THEY'D LIKE TO BE MOREE CONSISTENT WITH AND THE FREQUENCY
    5. AI GENERATES HABITS & Tracks consistency in schedule cache to auto generate a schedule 
    6. INTEGRATE OUSIDE CALANDARS (ICAL, GOOGLE CAL)


    
TASK MANAGER:
    add task (basic)
        due time 
            specific time and day
            set completion date range
                Allow users to input estimated time to complete tasks, and the system can use this to block out the right amount of time in the calendar.
        add to collaborative user folder?
            yes 
            select folder (must be added to the folder)
        priority (high, low, medium)
        repeat? (daily, weekly, monthly, yearly, custom)
        Tags/Labels:  a tagging system for quicker sorting or task grouping. For example, “Work,” “Personal,” “School,” etc.
        Add to folder
        assign to calandar?
            calandar name
    add dependent tasks in time scheduler:
        Add an option to mark tasks as dependent on each other. 
        If Task A must be done before Task B, Task B would remain locked until Task A is marked complete.
        ex. relaxation tasks cannot be complete before homework.
    remove task 
    view tasks by date / importance / folder
    search tasks
    edit tasks
    share/print task list
    
GROUPS
    Groups:
    [group list]
    FORUM 
        Sharing your progress with other users of the app
        Inspiration to work towards your goals
        Meet like minded people
        Self-Reflection Logs
            Can be private, noone can see but you and friends you allow
            Can be public, people can see your progress
            A section that allows users to journal their thoughts, struggles, and achievements each week. 
            This can tie back into their habits and progress logs. Can share suggestions for others.
                Privacy Clause & Banned for negative language (No swearing, No profane language -- slurs, name-calling)
    
    create group:
        name:
        add collaborators:
        message permissions (manager, member, viewer):
            Task Delegation: Allow a group admin or task owner to assign tasks with deadlines to individual group members, with notifications/reminders sent to them.
            Real-Time Collaboration: Add features for real-time task collaboration, like shared checklists or commenting on tasks.

        create shared folder: 
            set task permissions (edit, view, manage)
            progress tracker? on/off? 
           
            manage: assign tasks, delete project, add constituentss to progress, 
            determine what percentage each task group contributes, add collaborators,
            add to group calandar, 
            everything an editor and viewer can do
            
            edit: self-assign tasks, add to completion progress, check off tasks (self only), 
            add notes, share habits/goal progress

            view: view tasks, add task to personal task list

HABITS:
    Habit tracker views:
        consistency calendar view (30 days from start date)
            desktop: print view
            streak bar (tracks consistency)
            badge for continuous streak
            Introduce habit strength tracking, where missed days reduce the strength of the habit, but extra efforts can boost it. 
            This way, users can catch up if they fall behind. 
        Habit Suggestions: 
            The AI suggest habits based on past habits and goals. 
            For example: if a user’s goal is "improve productivity," the AI could suggest habits like “start the day with a to-do list.”
        
        calandar view (monthly)
            desktop: print view

    chcek off habit:
        update progress log
        check off on calandar
        popup after checking off: add notes to track journey or specifics

    add habit
        priority (low, medium, high)
        how would you like to be reminded? (check all that apply: text, email, local device notification)
        how would often? daily, weekly, monthly, custom
            generates task labeled habit in calandar and schedule views 
        attach progress?
            select progress to attach (associate completion of the habit with progress)
    
    CREATE A CHALLENGE:

    USER :
        Habit Reinforcement Suggestions: Provide AI-generated suggestions based on user data to refine or strengthen their habits 
        (e.g., "Try reducing your daily screen time by 30 minutes")

    AI (optional):
        Habit Reinforcement Suggestions: 
            Provide AI-generated suggestions based on user data to refine or strengthen their habits 
            (e.g., "Try reducing your daily screen time by 30 minutes").
        
        Generate habit challenge
            category (eventually custom):
                fitness (will autopopulate fitness goal)
                habit calandar specifically for challenges 



GOALS:
    [UI] 
    GOAL NAME
    PROGRESS BAR - PERCENTAGE 
    BADGES

    add goal:
            click existing consitutents for progress (ie. study, research, build a specific part, pass test, learn skill) 
            create new constituent (temp)
            priority : long term, short term
                long term (6 months > ) low
                short term (< 6 months ) high
            notes on progress
            (if attached to habit, update habit log)
            
            MILESTONES:
                frequency: 
                    user-generated: User inputs incriments for percentage reminders (ask: 5%, 10%, 25%, 50%, 100%)
                    auto-generated: Automatically generate reminders based on reaching certain percentages (e.g., 25% milestone for a long-term goal).

    add sub goal: Allows users to create sub-goals within a larger goal 
        goal: [list of goals]
        progress contribution (AI CALCULATED???)
        due dates
        priority:

    
    manage goal (progressive tasks):
        progressive task name -- progress bar -- percentage
            edit consituents (edit / add / remove)
            attach habit? yes/ no
                select habit to attach (associate completion of the habit with progress)
            add/remove badge / reward?
                associate percentage of completion with a badge (may purchase or create custom)
    share progress
    


CALENDAR : 
    options:
        add new calandar (up to 15)
            name calandar:
            pick color (RGB or HEX value):
            automatically prioritize? yes/no
                if yes: low, medium, high
            auto-populate?
                task filter: auto populates with task from the filter
        views:
            year
            month
            week
            day
        sort events
    share/print calandar

SCHEDULE:
    new time-block schedule (up to 2 per 7 day overlap)
        manual
            populate date : task manually with priority selection
        AI generated/ automated (based on calandar and/or tasks)
            populates date : task based on combined calandars + auto prioritize habits and tasks based on availability
            Ask AI to find time for task or Populate Prioritization (Conflict Addressed below):
                Implement a smart prioritization feature where the AI can suggest alternative times for tasks if there’s a conflict, 
                or notify users to manually adjust.
    share schedule  (TABLE)

FINANCES:
    finance tracker:
        (SIMILAR TO ROCKET MONEY) --> Sync Bank Account (NAME & BALANCE ONLY)
        Finance Manager

    SUGGESTIVE : 
        - Generate Debt Reduction Plans: 
            Create financial goals that are directly tied to debt reduction strategies with AI-generated payment suggestions based on user spending habits.
                - ask if you want to add the suggestion to the bills calandar under debt category
        - Subscription Tracker: 
            Automatically categorize and track recurring payments like subscriptions, bills, and rent.
                ask if want to add the suggestion to the bills calandar

        Add financial goal
            attach account
            attach priority (low, medium, high)
            date: 
            attach notes
            attach picture
            attach amount goal
        view progress
    
    create budget:
        add to category () or custom
        add amount 
        add account to track
        add notes

    FINANCE CALANDAR
        payday calandar
        bills calandar
        ai suggestions for when to pay for certain bills (find a name for this lol)
            off/on

VISION BOARD   (Pinterest integration):
    create a vision board on pinterest, add link, populates into screen/tab
    or add photos from gallery and select lay out
    Custom Integrations: 
        Besides Pinterest, offer direct image uploads, links to YouTube, or other media as part of the vision board. 
        Allow drag-and-drop for ease of layout changes.
    AI-Generated Inspirations: The app could suggest visual inspirations based on the goals users input, 
    helping them populate the vision board with motivational imagery.

ANALYTICS:
Analytics Dashboard
    Track user performance and progress across all categories (Tasks, Habits, Finances) and visualize them with graphs and charts.
    Provide actionable insights, like "You’re 30% behind your finance goal" or "You have completed 70% of your yearly goals."


Possible feature? QUICK NOTES:
    integration with notes app (ios, samsung, android typical apps)
    or native to the application to do handwritten and typed notes that can be autopopulated into scheduler or calandar with dates, times, and event

SETTINGS: 

account manager
theme
    font
    color scheme
    background
    layouts
    music
Backup & Sync
Support the Creator -- Membership ($2+/mo -- pick your contribution)
    better themes and badges 
    cool avatars
    custom thank you  
accessibility
    voice commands
    screen reader
    high contrast 
auto-scheduler config
reset
contact us (help)