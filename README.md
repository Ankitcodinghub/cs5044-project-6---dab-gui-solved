# cs5044-project-6---dab-gui-solved
**TO GET THIS SOLUTION VISIT:** [CS5044 Project 6 – DAB GUI Solved](https://www.ankitcodinghub.com/product/cs5044-project-6-dab-gui-solution/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;100433&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;3&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (3 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS5044 Project 6 - DAB GUI Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (3 votes)    </div>
    </div>
<h2>Overview</h2>
Your assignment is to create an application that provides a Swing-based GUI front-end to the Dots and Boxes implementation from Project 4. Although the exact layout is up to you, it must look reasonably neat and tidy. Here’s one very nice example of how the interface could look:

The graphical rendering of the game grid is handled by a custom Swing component that you’ll download below. You’ll need to create all of the other interface elements, design a layout that’s responsive to resizing, and ensure all your components work properly with the custom component and the underlying DABGame implementation.

<h2>Details</h2>
Your implementation must be named edu.vt.cs5044.DABPanel and your JUnit test suite must be named edu.vt.cs5044.DABPanelTest. The system relies upon your Project 4 DABGame implementation as the fundamental engine for this system, although generally you should begin with a provided solution; see the next section for details.

<h3>Reference Implementation</h3>
It is fully recognized that some of you may have outstanding bugs and/or missing features in your Project 4 DABGame implementation. That’s not any problem at all. Everyone is highly encouraged to download a fully operational implementation of Project 4 (as a JAR with class files only; no source code) that can be integrated within this project. Once your Project 6 is working with the reference implementation, you can easily replace the reference solution with your own.

<h3>Graphical Interface Description</h3>
When your implementation is launched, it should begin with a newly-initialized 3×3 game displayed, along with a menu bar, status indicator components, and input components. The layout does NOT need to precisely match the sample above, but it should still appear at least reasonably neat and professional in nature. It should also be reasonably responsive to resizing, such that the interface neatly expands or contracts to fill the available space given to its window.

The menu bar will contain one “Game” menu with a sub-menu that must look exactly like this (there is some very small degree of flexibility in the test cases, but not much):

The menu includes items to initialize a 2×2, 3×3, and 4×4 grid, as well as an item to toggle on/off interactive mode (see the “DABGrid” section below). The status indicators must include the score for each player, along with a display of which player has the current turn (or a “game over” message, as applicable). The status indicators must always reflect the current state of the game. The input components must include drop-down boxes to specify x and y parts of a coordinate (with only valid options shown, meaning 0, 1, and 2 for a 3×3 grid), along with a direction drop-down, plus a button to attempt to draw the specified edge when clicked. The button should be disabled (grayed-out) when the game is over, but enabled at all other times.

<h3>DABGrid</h3>
DABGrid is the custom component responsible for drawing the grid. You must integrate this component within your overall layout. By default, this component simply displays the current state of the grid, by calling DABGame accessor methods. When this component is set to interactive mode, the grid will become interactive, responding to mouse movements and clicks. Hovering the mouse near an un-drawn edge will highlight the edge. Clicking a highlighted edge will cause this component to call the DABGame drawEdge() mutator to draw the edge, then notify your system via a listener that the status indicators must be refreshed. Interactive mode must be activated and deactivated by your code, in response to the menu system.

<h3>Testing</h3>
Testing of GUI applications is notoriously complicated. Because the Swing system actually takes primary control of&nbsp; application, we can’t just call the application code directly as in our previous systems. In order for test code to interact with the application, we first need to be sure that each component has a name assigned. The test code must search through the component hierarchy looking for these names, in order to fetch references to the named components.

Once you have references to the Swing components, your test code needs to ask Swing to schedule your method calls. At that point you may query the state of the the GUI directly with accessors, and make assertions as normal.

This can all be done via standard JUnit test cases, but there a few additional issues that we won’t have time to cover in detail. Thus a <em>complete</em> JUnit test suite is provided for download below. This is exactly the same test suite used by Web-CAT for this assignment. Assuming you don’t have any redundant conditionals or other such problems in your code, this test suite will also achieve 100% coverage of your code.

<h2>Getting started with Eclipse</h2>
The setup of this project is very similar to our last few projects, and the process is identical. The only difference is that here there are three library files to add, rather than just one. Two of these libraries have associated API files containing the Javadocs; the final library doesn’t need an API. You also need to add the JUnit 4 library, as usual.Starter code and test code

Then, hownload the DABPanel.java and DABPanelTest.java files anywhere convenient that is outside of your project folder, then import them from the file system to your project. If you’ve configured the build path properly, both files should compile immediately with no errors (although there are lots of Checkstyle issues with the starter code).

Please carefully review both the starter file and the test file before you begin. Note that you don’t need to alter the test file in any way, nor do you need to write any of your own test cases. The comments are there to help you understand how it works. The starter file is also heavily commented to help guide your implementation approach. There’s a “TODO” comment in each location where you must develop code.

<h2>Downloads</h2>
DABGUI:

<ul>
<li><u>jar</u> – DABGrid library (includes a custom JComponent subclass)</li>
<li><u>dabgui-api.jar</u> – API for the DABGrid library</li>
</ul>
DABGame:

<ul>
<li><u>dabgame-ref.jar</u> &nbsp;&nbsp;– Library providing a reference implementation of Project 4</li>
</ul>
<ul>
<li>DAB5044:</li>
</ul>
<ul>
<li><u>dab5044.jar</u> &nbsp;&nbsp;– DAB library from Project 4 (must be added to this project)</li>
<li><u>dab5044-api.jar</u> &nbsp;&nbsp;– API for the DAB library from Project 4</li>
</ul>
<ul>
<li>Starter code:</li>
</ul>
<ul>
<li><u>DABPanel.java</u> &nbsp;– The basis of your implementation</li>
<li><u>DABPanelTest.java</u> &nbsp;– Complete JUnit test code</li>
</ul>
&nbsp;
