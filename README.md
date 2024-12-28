# My-Dev-journal
## 25.12.2024 - Present
### Lessons learned - The Art of Unit Testing By Roy Osherove
- Test Recipes - A test recipe is a test plan, outlining at which level a particular feature should be tested

### Lessons learned - Building Microservicds By Sam Newman
- You should think of microservices as being a specific approach for SOA in the same way that Extreme Programming (XP) or Scrum is a specific approach for Agile software development.
- A five-person startup is likely to find a microservice architecture a drag. A hundred-person scale-up that is growing rapidly is likely to find that its growth is much easier to accommodate with a microservice architecture properly aligned around its product development efforts.
- "Organizations which design systems...are constrained to produce designs which are copies of the communication structures of these organizations" ​—​Melvin Conway,
- The whole point of a microservice is being able to make a change to one service and deploy it without needing to change any other part of the system. This is really quite important.
- "A structure is stable if cohesion is strong and coupling is low." -Larry Constantine, **Cohesion** and **Coupling** are two ways to express the different trade-offs we make about where and why we group code; there is no one ideal method to arrange our code. Finding the ideal balance between these two concepts—one that makes the most sense for your particular situation and the issues you are now facing—is all we can do.
- **Coupling**
  - ```mermaid
    ---
    title: Types of Coupling
    ---
    flowchart LR
    A[Domain] --> B[Pass Through]
    B --> C[Common]
    C -->D[Content]
    A-. Low to High .->D
    ```
  
## 20.12.2024
- SLAP - Single Level of Abstraction Principle (for writing cleaner code)

## 15.12.2024 -19.12.2024
### Lesson Learned - Clean Coder By Robert Cecil Martin
- Make no harm to the function. It is professional developers responsibility to not harm or alter the existing code functions. They should code in a way that QA could not found any bug not the other way around.
- Make no harm to the structure. Because of poor code structuring, tasks used to take days begins to take weeks, then months management add more developers to boost the productivity of the code but instead new developers ends up in damaging existing structure more raising the impediment
- Merciless Refactoring - Always checkout codebase in better shape than you first checkin.
- List of things every every professional developer should know about
    - <b> Design Patters</b>: All patterns from Gang of Four Book and Pattern Oriented Software Architecture.
    - <b> Design Principle </b>: SOLID and component.
    - <b> Methods </b>: XP, Scrum, Lean, Kanban, Waterfall, Structured Analysis, and Structured Design.
    - <b> Disciplines </b>: TDD, Object-Oriented design, Structured Programming, Continuous Integration, and Pair Programming.
    - <b> Artifacts </b>: UML, DFDs, Structure Charts, Petri Nets, State Transition Diagrams and Tables, flow charts, and decision tables.
- Worst code you can write is at 3:00am. Don't write code when you are tired.
- It should be the goal of the development group that QA find nothing wrong.
- Nothing has a more profound or long-lasting negative effect on the productivity of a software team than a mess.
- Professional software developers know how to provide the business with practical estimates that the business can use for planning purposes. They do not make promises that they can’t keep, and they don’t make commitments that they aren’t sure they can meet.
- The first responsibility of the professional programmer is to meet the needs of his or her employer.
- The worst thing a professional programmer can do is to blissfully bury himself in a tomb of technology while the business crashes and burns around him.
      
## 06.12.2024
- Decides to start documentiong everything I am learning 🙂
