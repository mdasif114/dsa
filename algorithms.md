Algorithm
- an algorithm is programming language and hardware independent, it can be analyzed using complexity analysis (space/time)
- a program is an implementation, thus language dependent, it can be executed and the execution-time/memory-usage can be measured
  
- an algorithm often operates on some input and produces some output (however it doesn't have to operate on any inputs, it just has to produce an output, otherwise it is useless)
- an algorithm must terminate after a finite number of steps (no infinite number of steps)
- an algorithm must not have any unnecessary steps
  
- There is no fix syntax for writing an algorithm

How to Analyse an algorithm
- First Criteria is Time: (How much time it is taking based on the procedure written)
- Second, Space: How much memory & space it consumes
- Network (Data transfer and network consumption is important)
- Power (How much power it is consuming)
- CPU Registers (In case of developing device drivers & system level programming it is important to consider how many registers it is consuming)
  
Time Analysis
- Each single statement in an algorithm takes 1 unit of time.
- The below program takes 3 units of time -> f(n) = 3
- In algorithm, we simply measure time based on each statement (not worrying about complexity of the statement at this stage) 
- Algorithm swap (a,b)
    {
        temp = a; -> 1 unit of time
        a = b;    -> 1 unit of time
        b = temp; -> 1 unit of time
    }

Space Analysis
- Each variable is taken as one word.
- The below program takes 3 units of time -> s(n) = 3
- In algorithm, we simply measure space based on each word/variable -> O(1) - it represents constant 
- Algorithm swap (a,b)
    {
        temp = a; -> 1 variable
        a = b;    -> 1 variable
        b = temp; -> 1 variable
    }

Frequency Count Method


  
