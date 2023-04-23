Download Link: https://assignmentchef.com/product/solved-605-201-mini-project-1
<br>
Please do the following to complete this assignment.

<strong>Purpose:</strong>

The purpose of this project is to provide non-trivial practice in the use of Java programming constructs discussed from the beginning of the course through Module 05 and have a bit of fun doing it.

<strong>Resources Needed:</strong>

You will need a computer system with Java 8 or greater SE edition run-time and JDK.  You may optionally use a Java IDE for example NetBeans, Eclipse, etc.  However application builders are not allowed.

<strong>Submitted Files:</strong>

Design and Analysis:

This word-processed document is required to be written in <u><a href="https://owl.english.purdue.edu/owl/resource/560/01/">APA style</a></u> minus the Abstract section.  The file format can be ODT, PDF, DOC, or DOCX. The length of the document should be between 1.5 and 2 pages plus a reference section.  The following subjects should be discussed in this order:

<ol>

 <li>General program design. How is the program organized?  What major data structures were used?  How are commands processed?  How is the PacMan’s state maintained? Etc.  This section should take about ½ to 2/3 of the paper content.  Do not repeat the project specifications (assume the reader is knowledgeable of the project specifications).</li>

 <li>What alternative approaches were considered and why were they rejected?</li>

 <li>What did you learn from doing this project and what would you do differently?</li>

</ol>

Source file:

All Java source will be in a single text file containing a <em>single public class</em> which can be compiled and executed in a standard Java 8 or later SE environment.  Multiple methods can be used but all usercreated methods must be in a single Java public class contained in the single Java text file.

The format of the Java source must meet the general Java coding style guidelines discussed so far during the course.  Please use course office hours or contact the instructor directly if there are any coding style questions.

Submit file:

The submit file is to be a Zip file containing both your design and analysis document and your single Java source text file.  Name your Zip file MiniProject1_&lt;Blackboard ID&gt;&lt;Section Number&gt; for example: MiniProject1_jdealjr182.zip (note with Windows the .zip extension is added automatically).

<strong>Collaboration:</strong>

It is encouraged to discuss technical or small design parts of this project with your fellow students.

However the resulting design and implementation must be your own.  For example, it is acceptable to discuss different ways of maintaining the PacMan state but not detailed design or implementation information on processing the Move command.  When in doubt, ask during office hours or contact your instructor.

<strong>Program Specification:</strong>

<ol>

 <li>Create a new Java program which implements a simple PacMan-type text game which contains the following functionality:

  <ol>

   <li>At program startup, constructs and displays a <em>2-dimensional grid using standard array(s)</em> (no collection classes allowed) with the size dynamically specified by the user (X and Y sizes can be different). Places the PacMan in the upper-left corner of the grid facing left  All grid cells should have the empty cell character of ‘.’ except for the start position of the PacMan which will have the appropriate PacMan symbol (see below).  Also 8% of your grid (rounded down if necessary) should contain cookies randomly located on the grid except for the initial PacMan position.  The grid must be displayed after each command.</li>

   <li>Use these symbols for the grid:

    <ol>

     <li>Cookie symbol – shows were cookies are in the grid (‘O’)</li>

     <li>Empty symbol – shows empty unvisited grid cells (‘.’) (dot)</li>

     <li>Visited symbol – shows grid cells where the PacMan has visited (‘ ‘) (space)</li>

     <li>PacMan symbol depends on the current PacMan facing direction.

      <ol>

       <li>Left ‘&gt;’</li>

       <li>Up ‘V’</li>

       <li>Right ‘&lt;’</li>

       <li>Down ‘^’</li>

      </ol></li>

     <li>The following menu of commands <em>must</em> be provided and must be displayed when appropriate. The command number is what the user should enter to execute the command.  Just display the command number and text (ex. 1: Menu), not the explanation of what the command does:

      <ol>

       <li>Menu – Display the menu of commands.</li>

       <li>Turn Left – turns the PacMan left (counter-clockwise) but the PacMan stays in its current location

        <ol>

         <li>Current: up, new: left</li>

         <li>Current: right, new up</li>

         <li>Current: down, new right</li>

         <li>Current: left, new down</li>

        </ol></li>

       <li>Turn Right – turns the PacMan right (clockwise) but the PacMan stays in its current location

        <ol>

         <li>Current: up, new: right</li>

         <li>Current: right, new down</li>

         <li>Current: down, new left</li>

         <li>Current: left, new up</li>

        </ol></li>

       <li>Move – Moves the PacMan one grid location in the facing direction if possible. Adds one to the count of move commands if successful or not.  If the move command is successful, the previous location is replaced with Visited Symbol (see above).  If the move command results in the PacMan moving to a cell where a cookie is located, the cookie is “eaten” and the number of cookies eaten is increased by one.</li>

       <li>Exit – exits the program displaying the game statistics of the number of total moves and the average number of moves per cookie obtained.</li>

      </ol></li>

     <li>The main processing cycle is the following:

      <ol>

       <li>The grid must be displayed after each command showing the effects of the command. B) Optionally display the list of commands</li>

       <li>Display the grid</li>

       <li>Accept user input. Code will be provided for reading user input.

        <ol>

         <li>If an invalid command number is entered, an appropriate error message should be displayed and the menu of commands and grid gets redisplayed. An invalid command does not count as a command in the statistics.</li>

         <li>Process the command and add one to the number of move commands entered if it is a move command.</li>

         <li>If the user enters the Exit command, the program will display the number of commands and the average number of commands per cookie.</li>

         <li>E) If the resulting move places the PacMan over a cookie, indicate the cookie was eaten and add one to the number of cookies eaten for the program statistics.</li>

        </ol></li>

       <li>Observe the PacMan demonstration for an example of one implementation.</li>

       <li>Create a compressed zipped folder containing your Design and Analysis document and your Java</li>

      </ol></li>

    </ol></li>

  </ol></li>

</ol>




source file.

<ol start="5">

 <li>Submit your compressed zipped folder as directed by your instructor. <strong>Assessment:</strong></li>

</ol>

<strong>60%                      70%                80%                   90%</strong>




<strong>100%                Weight</strong>

<strong>Design &amp;                   </strong>Majority               All but one     All document    All                    All document    <strong>15%</strong>

<strong>Analysis                    </strong>document            document      subjects            document        subjects

<strong>Document              </strong>subjects subject            covered with   subjects           covered with covered with    covered           accurate          covered           insightful accurate      with    information.    with     and accurate information.      accurate          Maybe some    insightful         information.  Some fluff.        information     fluff.     and accurate   Document is Document is       .  Maybe          Document is    information.    of specified over half the   some fluff.       close to the     Document is    length and specified            Document       specified          of specified      properly

length with 2-4 is close to length with length with formatted to minor APA the 1-3 minor 1-3 minor APA style.

style or other     specified          APA style or     APA style minor issues.    length with      other minor     or other 2-4 minor    issues.  minor

APA style                                issues.

or other minor issues.

<strong>Program                    </strong>All but two           All but one     All but two        All but one       All specified      <strong>60%</strong>

<strong>Correctness              </strong>major specified    major             minor                minor              features work

features work      specified        specified           specified          with neat and

Note:                        but a noble          features         features            features           easy to

Compilation             effort is made.     work but a      work.  For         work.  For       understand

errors and      For example    noble effort     example the    example the    information warnings are part         the PacMan     is made.           PacMan           PacMan           display.  of this           will not move For       facing is not     facing is not evaluation.          up or down the          example          always always grid and the     the       correct or the  correct or PacMan can           PacMan           display of the  the display

move off the will not grid is a little of the grid is grid. move up or off. a little off.

down the grid or the

PacMan can move

off the grid.

<strong>Code Style                </strong>Most                    Most              Most                 Functionalit     Functionality     <strong>25%</strong>

functionality functionalit functionality y properly properly not properly y properly properly segmented segmented segmented into segmented segmented into into methods. methods.  into into methods. methods.  All variable Some variable methods.  Most Most use proper use proper Most variable use variable use names and names and variable proper names proper types.

types.  Some use proper and types.  names and Appropriate commenting. names and Appropriate types.  commenting. Some use types.  commenting. Appropriate Proper proper Some Mostly use commenting indentation indentation commentin proper .  Mostly line line g. Some indentation use proper continuation, use proper line indentation etc.

indentation                              line

line

If you have any questions about the specification of this project, contact your instructor <em>before</em> the project is due.