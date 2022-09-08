- Towers of Hanoi
	- The Towers of Hanoi is a mathematical game or puzzle. It consists of three rods, and a number of disks of different sizes which can slide onto any rod. The puzzle starts with the disks in a neat stack in ascending order of size on one rod, the smallest at the top, thus making a conical shape.
	  
	  The objective of the puzzle is to move the entire stack to another rod, obeying the following simple rules:
	  
	  1. Only one disk can be moved at a time.
	  2. Each move consists of taking the upper disk from one of the stacks and placing it on top of another stack or on an empty rod.
	  3. No larger disk may be placed on top of a smaller disk.
	  with recursive and iterative solution.
	  
	  Recursive solution:
	  
	  function hanoi(n, source, helper, target) {
	    // Base case
	    if (n === 1) {
	      console.log('Movedisk ' + n + ' from ' + source + ' to ' + target);
	      return;
	    }
	    // Recursive call
	    hanoi(n - 1, source, target, helper);
	    console.log('Move disk ' + n + ' from ' + source + ' to ' + target);
	    hanoi(n - 1, helper, source, target);
	  }
	  
	  hanoi(3, 'A', 'B', 'C');
	  
	  Iterative solution:
	  
	  function hanoiIterative(n, source, helper, target) {
	    let numOfMoves = Math.pow(2, n) - 1;
	    for (let i = n; i >= 1; i--) {
	      if (numOfMoves % 2 === 1) {
	        console.log('Move disk ' + i + ' from ' + source + ' to ' + target);
	        source = helper;
	        target = target;
	      } else {
	        console.log('Move disk ' + i + ' from ' + source + ' to ' + helper);
	        source = target;
	        target = helper;
	      }
	      numOfMoves--;
	    }
	  }
	  
	  hanoiIterative(3, 'A', 'B', 'C');