# csc3002---problem-1-exercise-8-16-solved
**TO GET THIS SOLUTION VISIT:** [CSC3002 – Problem 1 (Exercise 8.16) Solved](https://www.ankitcodinghub.com/product/csc3002-problem-1-exercise-8-16-solved-2/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;115803&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSC3002 - Problem 1 (Exercise 8.16) Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
            5/5 - (1 vote)    </div>
    </div>
If you search the web for fractal designs, you will find many intricate wonders beyond the Koch snowflake illustrated in this chapter. H-fractal, in which the repeated pattern is shaped like an elongated letter H in which the horizontal bar and vertical lines on the sides have the same length. Thus, the order-0 Hfractal looks like this:

To create the order-1 fractal, all you do is add four new H-fractalseach one half of the original sizeat each open end of the order-0 fractal, like this:

To create the order-2 fractal, all you have to do is add even smaller H-fractals (again half the size of the fractal to which they connect) to each of the open endpoints. This process gives rise to the following order-2 fractal:

Write a recursive function

drawHFractal(GWindow &amp; gw, double x, double y, double size, int order);

where x and y are the coordinates of the center of the H-fractal, size specifies the width and the height, and order indicates the order of the fractal. As an example, the main program int main() { GWindow gw;

double xc = gw.getWidth() / 2; double yc = gw.getHeight() / 2; drawHFractal(gw, xc, yc, 100, 3); return 0;

} would draw an order-3 H-fractal at the center of the graphics window, like this:

Requirments &amp; Hints:

Please fill in the TODO part of drawHFractal function in HFractal.cpp. You can define your own functions in the codes if necessary, but you need to follow the provided code framework.

Problem 2 (Exercise 9.6)

In chess, a knight moves in an L-shaped pattern: two squares in one direction horizontally or vertically, and then one square at right angles to that motion. For example, the white knight in the upper right side of the following diagram can move to any of the eight squares marked with an ×:

The mobility of a knight decreases near the edge of the board, as illustrated by the black knight in the corner, which can reach only the two squares marked with an .

It turns out that a knight can visit all 64 squares on a chessboard without ever moving to the same square twice. A path for the knight that moves through all the squares without repeating a square is called a knights tour. One such tour is shown in the following diagram, in which the numbers in the squares indicate the order in which they were visited:

Write a program that uses backtracking recursion to find a knights tour.

Requirments &amp; Hints:

Please fill in the TODO part of findKnightsTour function in KnightsTour.cpp. You can define your own functions in the codes if necessary, but you need to follow the provided code framework.

Problem 3 (Exercise 11.7)

Rewrite the implementation of the merge sort algorithm from Figure 10-3 (shown as follows) so that it sorts an array rather than a vector.

As in the reimplementation of the selection sort algorithm on page 499 (shown as follows),

void sort(int array[], int n) { for (int lh = 0; lh &lt; n; lh++) { int rh = lh;

for (int i = lh + 1; i &lt; n; i++) {

if (array[i] &lt; array[rh]) rh = i;

} swap(array[lh], array[rh]);

}

} your function should use the prototype

void sort(int array[], int n)

Requirments &amp; Hints:

Please fill in the TODO part of sort function in MergeSort.cpp. You can define your own functions in the codes if necessary, but you need to follow the provided code framework.

Problem 4 (Exercise 13.12)

Implement the EditorBuffer class using the strategy described in the section entitled “Doubly linked lists” (Page 606). Be sure to test your implementation as thoroughly as you can. In particular, make sure that you can move the cursor in both directions across parts of the buffer where you have recently made insertions and deletions. Simple testing results are shown as follows.

In this implementation, the ends of the linked list are joined to form a ring, with the dummy cell at both the beginning and the end. This representation makes it possible to implement the moveCursorToEnd method in constant time, and reduces the number of special cases in the code. The constructor is already given. Methods need to be implemented:

• The destructor that delete all cells;

• Methods move the cursor;

• A insertCharacter method that inserts one character into the buffer on the cursor;

• A deleteCharacter method that deletes one character after the cursor;

• A getText method that returns the content in buffer;

• A getCursor method that returns the index of the cursor.

Implement the EditorBuffer class using this representation (which is, in fact, the design strategy used in many editors today). Make sure that your program continues to have the same computational efficiency as the two-stack implementation in the text and that the buffer space expands dynamically as needed.

Requirments &amp; Hints:

Please fill in the TODO part of the methods in buffer.cpp. You can define your own functions in the codes if necessary, but you need to follow the provided code framework.

Requirements for Assignment

I’ve provided a project named as Assignment4.pro. You should write TODO part in each cpp file according to the problem requirements. The test file is provided under src folder named main.cpp. Please pack your whole project files into a single .zip file, name it using your student ID (e.g. if your student ID is 123456, hereby the file should be named as 123456. zip ), and then submit the .zip file via BB system.

Reminder: For windows users, please switch you input language to English before interacting in Stanford console. Or, you will get no response.
