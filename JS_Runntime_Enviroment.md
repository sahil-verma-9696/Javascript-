# JavaScript Runntime enviroment.

    - About Execution context
    - [Official Doc](https://developer.mozilla.org/en-US/docs/Web/API/HTML_DOM_API/Microtask_guide/In_depth)
    - [Visual Video explanation](https://www.youtube.com/watch?v=zdGfo6I1yrA)

# Run, JavaScript, run

    - To run JavaScript code, 
    - the runtime engine maintains a **set of agents** in which to execute JavaScript code.
    - Each agent is made up of 
      - a set of execution contexts, 
      - the execution context stack, 
      - a main thread, 
      - a set for any additional threads that may be created to handle workers, 
      - a task queue, 
      - and a microtask queue.  
    - Other than the main thread—which some browsers share across multiple agents—each component of an agent is unique to that agent.
