# Developer Guidelines
The Guidelines are defined to onboard developers to the Main development process and structure incoming requests from other departments.
## Table of Contents
[Basic Workflow (graph)](#basic-workflow)<br/>
[Process details](#process-details)<br/>
[Idea or Need](#idea-or-need)<br/>
[Read more](#read-more)<br/>


## Basic Workflow
Details to on each step are described below the graph.
```mermaid
graph TD
    A[Idea or Need] -->|Create request Ticket| B(Prioritization Process)
    B --> C{Needs validation?}
    C -->|yes| D(Validation Process) ---> E
    C -->|no| E(Create PBI Ticket)
    E --> F(Create Tasks for Developers)
    F --> G(Development)
    G --> H[Roll-Out]
```
## Process Details
The process details give you an insight on the steps defined in the graph. 
The workflow described is used for new feature requests. 
Bugreports and Error handling is described [here](ErrorHandling.md).

### Idea or Need


# Read more
[Bug report and error handling](ErrorHandling.md)
  