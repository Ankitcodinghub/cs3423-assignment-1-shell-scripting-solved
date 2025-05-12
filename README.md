# cs3423-assignment-1-shell-scripting-solved
**TO GET THIS SOLUTION VISIT:** [CS3423 Assignment 1-Shell Scripting Solved](https://www.ankitcodinghub.com/product/cs3423-assignment-1-shell-scripting-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;91183&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS3423 Assignment 1-Shell Scripting Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
<div class="page" title="Page 1">
<div class="section">
<div class="layoutArea">
<div class="column">
Assignment 1: Shell Scripting

For this assignment, you will use bash create a simple inventory system. The system will store basic information about items and allow the user to create, read, update, delete, and total these items.

This assignment requires only the utilities used so far in the lecture notes. Further, you may not use sed, awk, find, grep, Python, perl, any programming language, scripting language, or other tools not otherwise permitted. The only external tool you may utilize is bc, which can be used to perform floating-point arithmetic.

Storing Item Information

Item information will be stored in text files (ending with the extension .item).

<ol>
<li>Files will be stored in a directory named data, located within the same directory as your shell
script.
</li>
<li>Each file will be named based on its unique item number, an integer (henceforth referred to
as item_num) with exactly four digits, followed by the extension .item.
</li>
<li>An item file consists of exactly three lines, in the following format:
• item_name (string with no whitespace) simple_name (string)

• unit_price (floating point number) cur_qty (unsigned integer) max_qty (unsigned

integer)

• item_desc (string)
</li>
<li>The following are the example contents of an item file named 3293.item:</li>
</ol>
Script Execution

When the script is run, the following should occur.

1. Upon running your script, the user should be presented with the following menu:

<pre>     Enter one of the following actions or press CTRL-D to exit.
       C - create a new inventory item
       R - read an existing inventory item
       U - update an existing inventory item
</pre>
<pre>       D - delete an existing inventory item
       T - calculate total value of an inventory item
</pre>
</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
btl_water Bottled Water (24/pk)

15.99 23 50

Poland Springs natural spring drinking water

</div>
</div>
</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="section">
<div class="layoutArea">
<div class="column">
2. The user then enters a corresponding one-character selection (either upper or lowercase entries should be permissible), leading to one of the following actions:

• C: create a new inventory record (thus, also creating its associated data file)

<ol>
<li>(a) &nbsp;From the terminal, read the following fields, one at a time, each separated on its own
line:

i. Item number: (four digit unsigned integer)

Example input: 3293

ii. Item name: (string containing no whitespace)

Example input: btl_water iii. Simple name: (string)

Example input: Bottled Water (24/pk) iv. Unit price: (floating point number)

Example input: 15.99

v. Current quantity: (unsigned integer)

Example input: 23

vi. Maximum quantity: (unsigned integer)

Example input: 50 vii. Description: (string)

Example input: Poland Springs natural spring drinking water
</li>
<li>(b) &nbsp;Using the values entered by the user, create a new file in the data subdirectory
(which may or may not pre-exist) based on the file naming instructions above.
</li>
<li>(c) &nbsp;Update data/queries.log by adding the following line:

[date] CREATED: item_num – item_name – cur_qty / max_qty where:

<ol>
<li>date is the formatted output from the shell’s ‘date “+[%Y-%M-%d %H:%m:%S]”‘ command,</li>
<li>item_num represents the item’s internal identification number (e.g. 3293),</li>
<li>item_name represents the item’s internal identification string (e.g. btl_water),
and
</li>
<li>cur_qty represents the item’s initial quantity as of its entry into this inventory
system (e.g. 20).
</li>
<li>max_qty represents the item’s maximum allowable inventory quantity (e.g. 50).</li>
</ol>
</li>
<li>(d) &nbsp;If the item number already exists, abandon the “Create” operation and print the following example error message, then continue with the script.

For example: ERROR: item 3293 already exists</li>
</ol>
• R: read and display an existing item’s inventory information

</div>
</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="section">
<div class="layoutArea">
<div class="column">
<ol>
<li>(a) &nbsp;Prompt the user for an inventory item’s number:
<pre>   Enter an item number:
</pre>
</li>
<li>(b) &nbsp;Search for the specified inventory item using the item number provided.</li>
<li>(c) &nbsp;Print the item’s inventory information in the following format:</li>
</ol>
</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>Item Number:
Item Name:
Simple Name:
Unit Price:
Quantity:
Description:
</pre>
</div>
<div class="column">
item_num

item_name simple_name unit_price

cur_qty / max_qty item_desc

</div>
</div>
<div class="layoutArea">
<div class="column">
(d) If the item is not found, print the following example error and continue with the script.

ERROR: item 3293 not found • U: update an existing inventory record

<ol>
<li>(a) &nbsp;Prompt the user for the following fields one at a time: i. Item number (four digit unsigned integer)
ii. Item name (string containing no whitespace) iii. Simple name (string)

iv. Unit price (floating point number)

v. Current quantity (unsigned integer) vi. Maximum quantity (unsigned integer)

vii. Description (string)
</li>
<li>(b) &nbsp;Using the values entered by the user, search for the specified item in the data
subdirectory using the given item number.
</li>
<li>(c) &nbsp;Update each of the corresponding fields based on the user’s input. If the user input is blank for a particular field (except for the item number), keep the existing value currently utilized within the file.</li>
<li>(d) &nbsp;Update data/queries.log by adding the following line:

[date] UPDATED: item_num – item_name – cur_qty / max_qty where:

<ol>
<li>date is the formatted output from the shell’s ‘date “+[%Y-%M-%d %H:%m:%S]”‘ command,</li>
<li>item_num represents the item’s internal identification number (e.g. 8299),</li>
<li>item_name represents the item’s internal identification string (e.g. btl_water),
and
</li>
<li>cur_qty represents the item’s currently-stocked quantity (e.g. 12).</li>
</ol>
</li>
</ol>
</div>
</div>
<div class="layoutArea"></div>
</div>
</div>
<div class="page" title="Page 4">
<div class="section">
<div class="layoutArea">
<div class="column">
v. max_qty represents the item’s maximum allowable inventory quantity (e.g. 85).

(e) If the item number does not already exist, abandon the “Update” operation and print the following example error message, then continue with the script.

For example: ERROR: item 8299 not found

• D: delete an existing item’s inventory record

<ol>
<li>(a) &nbsp;Prompt the user for an item number:
<pre>          Enter an item number:
</pre>
</li>
<li>(b) &nbsp;Delete the specified item’s file from the data directory.</li>
<li>(c) &nbsp;Update data/queries.log by adding the following line:
[date] DELETED: item_num – item_name – simple_name – cur_qty where:

<ol>
<li>date is the formatted output from the shell’s ‘date “+[%Y-%M-%d %H:%m:%S]”‘
command,
</li>
<li>item_num represents the item’s internal identification number (e.g. 8299),</li>
<li>item_name represents the item’s internal identification string (e.g. btl_water), and</li>
<li>simple_name represents the item’s short-form description (e.g. Bottled Water (24/pk)).</li>
<li>cur_qty represents the item’s currently-stocked quantity (e.g. 12).</li>
</ol>
</li>
<li>(d) &nbsp;If the item number does not already exist, abandon the “Delete” operation and print the following example error message, then continue with the script.

For example: ERROR: item 8299 not found</li>
</ol>
• T: calculate total value of current inventory items

<ol>
<li>(a) &nbsp;Prompt the user for an item number:
<pre>          Enter an item number:
</pre>
</li>
<li>(b) &nbsp;Calculate the total value currently in inventory for this specific item (e.g. unit price × current quantity).</li>
<li>(c) &nbsp;Print the following message with the item’s number, simple name, and total value:
item_num – simple_name – $(unit_price×cur_qty) total
</li>
<li>(d) &nbsp;If the given item number does not exist, abandon the “Total” operation and print the following example error message, then continue with the script.

For example: ERROR: item 8299 not found</li>
</ol>
• If an invalid character is entered at the main menu, print the following error message and continue with the script:

<pre>           ERROR: invalid option
</pre>
3. After an action is completed, display the menu again. This should go on indefinitely until CTRL-D or the end of a file is reached.

</div>
</div>
<div class="layoutArea">
<div class="column">
Assignment 1: Shell Scripting Page 4 of 5

</div>
</div>
</div>
</div>
<div class="page" title="Page 5">
<div class="section">
<div class="layoutArea">
<div class="column">
Assignment Data

An initial data set can be found in /usr/local/courses/ssilvestro/cs3423/Spring20/assign1. Copy this to your own assignment’s directory when you are prepared to begin initial testing. You should not, under any circumstances, rely solely on this data as the only data set with which to test the functionality of your script.

Script Files

Your program should consist of six bash files:

• assign1.bash – the main file which is to be initially invoked

• create.bash – logic for the create option

• read.bash – logic for the read option

• update.bash – logic for the update option

• delete.bash – logic for the delete option

• total.bash – logic for the calculating total value in inventory of a given item

Verifying Your Program

Your program must at least function correctly with the input provided in a1Input.txt. It is extremely important to note that this is NOT the only input your script will be tested with. Thus, think carefully of corner cases and work diligently to test your scripts with large scale input and debug them accordingly, if necessary.

<ol>
<li>Verify that your assignment folder has a data directory with the initial data set.</li>
<li>Execute your script and redirect a1Input.txt into it. You should not be copying or typing
the contents of a1Input.txt into your terminal. File redirection must work. For example, the following must work: ./assign1.bash &lt; a1Input.txt
</li>
<li>Verify that both the printed output and data files are as expected.</li>
</ol>
</div>
</div>
</div>
</div>
