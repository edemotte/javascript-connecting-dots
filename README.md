🎤 Part 1 Agenda: Why Frameworks Feel Confusing
1. 🚀 Introduction (2–3 mins)
What developers commonly struggle with in frameworks
The illusion: “Frameworks are complex”
Core idea: Most confusion comes from JavaScript fundamentals
2. 🧠 Framing the Problem (2 mins)
Why do frameworks feel confusing?
State issues
Unexpected re-renders
Async confusion

👉 Set expectation:

“We’re going to break each of these down using both React and Angular”

3. ⚙️ State Issues (8–10 mins)
3.1 React Perspective
Multiple state updates behaving unexpectedly
Closure-based state behavior
Batching of updates
3.2 Angular Perspective
Mutating vs replacing state
Change detection behavior
Impact of reference vs mutation
3.3 Root Cause (JavaScript)
Closures
Execution timing
Reference vs value

👉 Key takeaway:

“State is not immediate—it’s controlled by JavaScript behavior”

4. 🔄 Unexpected Re-renders (8–10 mins)
4.1 React Perspective
Function identity problem
Props comparison (shallow equality)
useCallback / memoization
4.2 Angular Perspective
Change detection cycles
Functions in templates
Performance implications
4.3 Root Cause (JavaScript)
Functions as values
Reference equality
Re-execution of logic

👉 Key takeaway:

“Re-renders are not random—they follow JavaScript rules”

5. ⏳ Async Confusion (8–10 mins)
5.1 React Perspective
State updates are asynchronous
Render cycle dependency
Using effects to observe updates
5.2 Angular Perspective
Async tracking via Zone.js
Change detection triggered by async tasks
Edge cases when outside Angular zone
5.3 Root Cause (JavaScript)
Event loop
Task scheduling
Execution order

👉 Key takeaway:

“Async confusion comes from how JavaScript schedules work”

6. 🔗 Connecting the Dots (3–4 mins)
Mapping Everything Back to JavaScript
Problem	JS Concept
State issues	Closures, references
Re-renders	Functions, identity
Async confusion	Event loop

👉 Message:

“Framework behavior is a reflection of JavaScript behavior”

7. 🎯 Part 1 Conclusion (2–3 mins)
Framework problems = JavaScript fundamentals
Understanding JS → Predictable framework behavior
Transition to Part 2 (if applicable)
💡 Strong Closing Line

“If you fix your mental model of JavaScript, you automatically fix most of your framework problems.”
