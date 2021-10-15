## Welcome to CIS 351!

This is the main website for the course.
The slides, schedule, and links to assignments, labs, projects,
as well as the official course policies,
will be posted here.
The course also uses other websites for specific purposes.
* [Piazza](http://www.piazza.com/gvsu/fall2021/cis351section3/home) is a question-and-answer forum.
*All official announcements will be sent through Piazza*,
and you are responsible for monitoring Piazza to keep up to date with
announcements
(Piazza by default will send an email when an announcement is posted).
    * Signup link:
      [www.piazza.com/gvsu/fall2021/cis351section3](http://www.piazza.com/gvsu/fall2021/cis351section3).
    * You can read the following [Piazza FAQ](misc/piazza-faq.md) if you have
      questions.
* [Zoom](https://zoom.us) will be the video conferencing service for online
  office hours (more about that in the [syllabus](syllabus.md)).
    * Office hours link (Wednesdays only):
      [https://gvsu-edu.zoom.us/j/98637553783?pwd=RzJsazNrcDhFemFRTCtvN2xiblFnUT09](https://gvsu-edu.zoom.us/j/98637553783?pwd=RzJsazNrcDhFemFRTCtvN2xiblFnUT09)
* [Prairielearn](https://www.prairielearn.org/pl/) is where you will
submit all of your assignments, labs, and projects.

That seems like a lot to monitor,
but don't worry -- you really need only actively follow Piazza.
I will release announcements there any time assignments are posted,
and I will post links to them directly on this page.

Be sure to read through the [syllabus](syllabus.md) for course policies,
contact information, and other important info.

Because the course was previously taught online,
there are lecture videos at the previous course website
([https://github.com/bowmnath/cis-351-w21](https://github.com/bowmnath/cis-351-w21))
that you are welcome to use to review the material.
I would not suggest using these as a substitute for coming to class
because the coverage will change slightly from semester to semester
and because we will be doing activities in class to reinforce understanding
of the concepts.

Please fill out our daily contract tracing info in the
[seating chart](https://docs.google.com/spreadsheets/d/1PF0jkL6VA07N5egP6sdNPUWzqdZJ4FYCC2HGK9nehbQ/edit?usp=sharing).

## Schedule

** Note: This is an estimated timeline and subject to change. **

| Week | Topics | Readings and Activities | Deliverables |
| ---- | ------ | ----------------------- | ------------ |
|  1   | Introduction<br>[intro slides](slides/intro.pdf)<br>Combinational circuits<br>[circuits slides](slides/boolean-circuits.pdf)<br>[circuit representation slides](slides/boolean-representations.pdf)<br>[conversion slides](slides/boolean-conversions.pdf)<br>[SOP & PLA slides](slides/boolean-sop.pdf)<br>[logical completeness slides](slides/boolean-logical-completeness.pdf) | Chapter 1<br>[Optional practice](activities/week-01-intro.md) | **Friday 9/3** [Syllabus quiz](https://www.prairielearn.org/pl/course_instance/128859/assessment/2313419)<br>**Friday 9/3** [Lab partner survey](https://forms.gle/NDBke1UTuBKQM444A) |
|  2   | Binary numbers<br>[intro slides](slides/binary-intro.pdf)<br>[usage slides](slides/binary-use.pdf)<br>[tricks/tips slides](slides/binary-hex.pdf)<br>Negative binary numbers<br>[sign-magnitude slides](slides/binary-sign-magnitude.pdf)<br>[two's complement slides](slides/binary-twos-complement.pdf)<br>[overflow slides](slides/binary-overflow.pdf)<br>Boolean algebra<br>[simplification slides](slides/boolean-simplify.pdf)<br>Ripple-carry adder<br>[half adder slides](slides/half-adder.pdf)<br>[ripple-carry adder slides](slides/ripple-carry-adder.pdf)<br>Circuit Timing<br>[circuit timing slides](slides/circuit-timing.pdf) | 2.1 - 2.5<br>[Videos](https://classtranscribe.illinois.edu/offering/25d3a943-1da6-4e69-b804-6f088a538887#plid=a4e3f4e5-9f2d-4686-b3b1-4b5e23550955) | **Wednesday 9/8** [DLUnit Lab](https://www.prairielearn.org/pl/course_instance/128859/assessment/2313438) |
|  3   | Ripple-Carry Timing<br>[ripple-carry timing slides](slides/ripple-carry-timing.pdf)<br>Multiplexors<br>[multiplexor slides](slides/muxes.pdf)<br>Carry-select adder<br>[carry-select slides part 1](slides/carry-select-part1.pdf)<br>[carry-select slides part 2](slides/carry-select-part2.pdf)<br>Carry-lookahead adder<br>[carry-lookahead slides part 1](slides/carry-lookahead-part1.pdf)<br>[carry-lookahead slides part 2](slides/carry-lookahead-part2.pdf) | | **Monday 9/13** [Homework 1](https://www.prairielearn.org/pl/course_instance/128859/assessment/2313531)<br>**Wednesday 9/15** [Breadboard Lab 1](https://www.prairielearn.org/pl/course_instance/128859/assessment/2313671) |
|  4   | Karnaugh Maps<br>[k-map slides](slides/karnaugh-maps.pdf)<br>Latches<br>[latches slides](slides/latches.pdf) | | **Wednesday 9/22** [Adder Lab](https://www.prairielearn.org/pl/course_instance/128859/assessment/2313912) |
|  5   | Flip-flops<br>Synchronous sequential circuits<br>[flip-flop slides](slides/flip-flops.pdf)<br>[synchronous sequential slides](slides/synchronous-sequential.pdf)<br>[timing sequential slides](slides/sequential-timing.pdf)<br>Pipelining<br>[pipelining slides](slides/pipelining.pdf)<br><br>[Practice exam 1](practice-exams/practice-exam-1.pdf) | | **Wednesday 9/29** [Project 1](https://www.prairielearn.org/pl/course_instance/128859/assessment/2313913) (standard credit)<br>**Friday 10/1** [Homework 2](https://www.prairielearn.org/pl/course_instance/128859/assessment/2313986) |
|  6   | Turning circuits into computers<br>[building computer handout](misc/architecture-intro-handout.pdf)<br>[automatic computer](slides/arch-automatic-computer.pdf) | | **Thursday, October 7** Midterm Exam 1 (during lab) |
|  7   | Computer Architecture<br>[architecture](slides/arch-intro.pdf)<br><br>I-type instructions<br>[I-type](slides/arch-mips-i-type.pdf)<br><br>Branches<br>[conditional branching](slides/arch-branches.pdf) | [sequential circuits activity](activities/week-07-synchronous.md) | **Wednesday 10/13** [Project 2](https://www.prairielearn.org/pl/course_instance/128859/assessment/2314043) (standard credit)<br>**Wednesday 10/13** [Sequential Circuits Lab](https://www.prairielearn.org/pl/course_instance/128859/assessment/2314149) |
|  8   | Unconditional branch (jump)<br>[jump](slides/arch-jump.pdf)<br><br>Assembly programming constructs<br>[conditionals (if statements)](slides/assembly-conditionals.pdf)<br>[loops](slides/assembly-loops.pdf)<br><br>Branch microarchitecture<br><br>Memory load/store<br>[memory instructions](slides/arch-memory.pdf) | | **Tuesday 10/19** [Assembly Intro Lab](https://www.prairielearn.org/pl/course_instance/128859/assessment/2314402) <br>**Thursday 10/21** [Homework 3](https://www.prairielearn.org/pl/course_instance/128859/assessment/2314338) |
|  9   | Control logic<br>[control logic](slides/arch-control-logic.pdf)<br><br>Arrays<br>[arrays](slides/assembly-arrays-intro.pdf)<br>[arrays and loops](slides/assembly-arrays-loops.pdf)<br><br>Functions<br>[functions](slides/assembly-functions.pdf) | | **Wednesday 10/27** [Project 3](https://www.prairielearn.org/pl/course_instance/128859/assessment/2314393) (standard credit)<br>**Wednesday 10/27** Branches lab |
|  10  | Stack<br>[stack](slides/assembly-stack.pdf)<br>[recursion](slides/assembly-recursion.pdf)<br><br>Memory<br>[memory map](slides/arch-map-memory.pdf)<br>[loading and executing](slides/arch-loading.pdf) | | **Thursday 11/4** Midterm Exam 2 (during lab)<br>**Friday 11/5** Homework 4a<br>**Friday 11/5** Homework 4b |
|  11  | Memory<br>[data segment code](code-examples/data-segment-final.asm)<br>[heap code](code-examples/malloc.asm)<br>[generic debugging code](code-examples/generic-debug.asm)<br>[stack vs heap vs global (optional -- no video)](code-examples/stack-heap-global.asm)<br><br>Cache motivation<br>[cache motivation](slides/cache-motivation.pdf)<br><br>Direct-mapped cache<br>[direct-mapped cache](slides/cache-direct-map.pdf) | | **Wednesday 11/10** Loops lab |
|  12  | Cache conflicts<br>[cache conflicts](slides/cache-direct-conflict.pdf)<br><br>Associative cache<br>[associative cache mapping](slides/cache-associative-map.pdf)<br>[associative cache conflicts (LRU)](slides/cache-associative-conflict.pdf)<br><br>Varying block size in cache<br>[mapping with larger block sizes](slides/cache-block-map.pdf)<br>[blocks of addresses](slides/cache-block-addresses.pdf)<br>[associativity vs block size and address bits](slides/cache-type-comparison.pdf) | | **Wednesday 11/17** Recursion Lab<br>**Friday 11/19** Project 4 |
|  13  | Cache performance<br>[cache performance](slides/cache-performance.pdf)<br><br>Basic pipelining in MIPS<br>[pipeline intro](slides/micro-pipeline-intro.pdf)<br>[pipeline performance](slides/micro-pipeline-performance.pdf) | | **Monday 11/22** Stack homework<br>**Wendesday 11/24** Computer Instruction Types Lab |
|  14  | Data and Control Hazards<br>[data hazards](slides/pipeline-hazards-data.pdf)<br>[control hazards](slides/pipeline-hazards-control.pdf) | | **Wednesday 12/1** Cache lab<br>**Thursday 12/2** Cache homework |
|  15  | **Final Exam**<br>Wednesday, December 15<br>8 AM - 9:50 AM | | |
