<!DOCTYPE html>
<html>
<head>
    <title>Nested Lists</title>
</head>
<body>

    <table border="2" align="center" cellspacing="0" cellpadding="5" height="200" width="300">
        <tr>
            <th colspan="2" align="center">Student Schedule</th>
            <!-- <td></td> -->
        </tr>
        <tr>

            <th bgcolor="lightgrey" align="center">Time</th>
            <th align="center" bgcolor="lightgrey">Subject</th>
        </tr>
        <tr>
            <td align="center">9:00AM-10:00AM</td>
            <td align="center">Math</td>
        </tr>
        <tr>
            <td align="center">9:00AM-10:00AM</td>
            <td align="center">Science</td>
        </tr>
        <tr>
            <td align="center">9:00AM-10:00AM</td>
            <td align="center">History</td>
        </tr>
        <tr>
            <th colspan="2" align="center" bgcolor="lightgrey">Break Time</th>
            <!-- <td></td> -->
        </tr>
        <tr>
            <td colspan="2" align="center">12:30PM-1:00PM</td>
            <!-- <td></td> -->
        </tr>

    </table>
    
    <br>

    



    <table border="2" align="center" cellspacing="0" cellpadding="5" height="200" width="400">
        <tr>
            <th align="center" colspan="3">Product List</th>
            <!-- <td></td>
            <td></td> -->

        </tr>
        <tr>
             <th align="center" bgcolor="lightgrey">Item</th>
            <th align="center" bgcolor="lightgrey">Details</th>
           <th align="center" bgcolor="lightgrey">Price</th>

        </tr>
        <tr>
             <td>Laptop</td>
            <td>
                <table border="2"cellspacing="0" cellpadding="0" height="50" width="200">
                    <tr>
                       <td align="center"><b>Brand:</b>Dell</td> 
                    </tr>
                    <tr>
                        <td align="center"><b>RAM:</b>8GB</td>
                    </tr>
                </table>
            </td>
            <td>$800</td>

        </tr>
        <tr>
             <td>
                Headphones
             </td>
            <td>
                <table border="2"cellspacing="0" cellpadding="0" height="50" width="200">
                    <tr>
                     <td align="center"><b>Type:</b>Wireless</td>
                    </tr>
                    <tr>
                        <td align="center"><b>Color:</b>Black</td>

                    </tr>
                </table>
            </td>
            <td>$50</td>

        </tr>

    </table>
    <br>
   

    <table border="2" align="center" cellspacing="0" cellpadding="5" height="200" width="400">
        <tr>

            <th align="center" colspan="2">FAQ Section</th>
            <!-- <td></td> -->

        </tr>
        <tr>
            <th bgcolor="lightgrey">Question</th>
            <th bgcolor="lightgrey">Answer</th>
        </tr>
        <tr>
            <td>What is HTML?</td>
            <td align="center">HTML stands for HyperText Markup Language.</td>

        </tr>
        <tr>
               <td>How to center text?</td>
               <td>Use the "align" attribute in a table to center text.</td>
        </tr>
    </table>

   <br>
    
    <table border="2" align="center" cellspacing="0" cellpadding="5" height="200" width="400">
        <tr>
        <th colspan="3" align="center">Pricing Table</th>
        <!-- <td></td>
        <td></td> -->

      </tr>
      <tr>
        <th bgcolor="lightgrey">Basic Plan</th>
        <th bgcolor="lightgrey">Standard Plan</th>
        <th bgcolor="lightgrey">Premium Plan</th>

      </tr>
      <tr>
        <td>
            <table align="center" border="2" cellspacing="0" cellpadding="0">
                <tr>
                    <td align="center" bgcolor="lightgrey">Storage:10GB</td>
                </tr>
                <tr>
                    <td align="center">Support:Email</td>
                </tr>
            </table>
        </td>
        <td>
              <table align="center" border="2" cellspacing="0" cellpadding="0">
                <tr>
                    <td align="center" bgcolor="lightgrey">Storage:50GB</td>
                </tr>
                <tr>
                    <td align=center>Support:Email+Chat</td>
                </tr>
            </table>

        </td>
        <td>

            <table align="center" border="2" cellspacing="0" cellpadding="0">
                <tr>
                    <td align="center" bgcolor="lightgrey">Storage:100GB</td>
                </tr>
                <tr>
                    <td align="center">Support:24/7 Support</td>
                </tr>
            </table>
        </td>

      </tr>
      <tr>
        <td align="center" bgcolor="lightgrey"><b>$10/</b> month</td>
        <td align="center" bgcolor="lightgrey"><b>$25</b>month</td>
        <td align="center" bgcolor="lightgrey"><b>$50</b>month</td>

      </tr>

    </table>

<br>


    <table border="2" align="center" cellspacing="0" cellpadding="5" height="200" width="400">

        <tr>
            <th colspan="2">
                Employee Information

            </th>
            <!-- <td>

            </td> -->
        </tr>
        <tr>
             <td align="center">
                Name:<b>John Doe</b>

            </td>
            <td align=center>
                Manager

            </td>

        </tr>
       <tr>
        <td colspan="2">
            <table border="2" cellspacing="0" cellpadding="5"  width="300" align="center">
                <tr>
                   <th align="left" bgcolor="lightgrey">Contact Info</th> 
                </tr>
                <tr>
                   <td align="center"><b>Email:</b>john@example.com</td> 
                </tr>
                <tr>
                   <td align="center" bgcolor="lightgrey"><b>Phone:123-456-7890</b></td> 
                </tr>
            </table>
        </td>
       </tr>
        
        

    </table>
    <hr color="black">
    <br>
    

    <table border="2"  align="center" cellspacing="2" cellpadding="3" height="200" width="400">
        <tr>
            <th colspan="3" bgcolor="skyblue" align="center">Course Overview</th>
            <!-- <td></td>
            <td></td> -->
        </tr>
        <tr>
            <th bgcolor="skyblue" align="center">Module</th>
            <th  bgcolor="skyblue" align="center">Topics Covered
           <th bgcolor="skyblue" align="center">Duration</th>
        </tr>
        <tr>
            <td>Module 1:Introduction</td>
            <td>HTML Basics</td>
            <td>1 Week</td>
        </tr>
        <tr>
            <td>Module 2:Intermediate</td>
            <td>CSS&Styling</td>
            <td>2 Weeks</td>
        </tr>
        <tr>
            <td>Module 3:Advanced</td>
            <td>JavaScript&DOM</td>
            <td>3 Weeks</td>
        </tr>
        <tr>
            <td colspan="3">
                <ul type="disc">
                    <li><font color="yellowblue">HTML:</font>HyperText Markup Language</li>
                    <li><font color="darkpink">CSS:</font>HyperText Markup Language</li>
                     <li><font color="orange">DOM:</font>HyperText Markup Language</li>

                </ul>
            </td>
            <!-- <td></td>
            <td></td> -->
        </tr>

    </table>
    <br>



    <table border="2" cellspacing="2" cellpadding="3" height="200" width="400" align="center">
        <tr>
            <th colspan="3" bgcolor="orange" align="center">Product Comparison</th>
            <!-- <td></td>
            <td></td> -->
        </tr>
        <tr>
            <th bgcolor="orange" align="center">Feature</th>
            <th  bgcolor="orange" align="center">Product A
           <th bgcolor="orange" align="center">Product B</th>
        </tr>
        <tr>
            <td>Price:</td>
            <td>$299</td>
            <td>$399</td>
        </tr>
        <tr>
            <td>Storage</td>
            <td>128GB</td>
            <td>256GB</td>
        </tr>
        <tr>
            <td>Battery Life:</td>
            <td>10 Hours</td>
            <td>15 Hours</td>
        </tr>
        <tr>
            <td colspan="3">
                <ul type="disc">
                    <li><font color="blue">Price:</font>HyperText Markup Language</li>
                    <li><font color="red">Storage:</font>HyperText Markup Language</li>
                     <li><font color="green">Battery Life:</font>HyperText Markup Language</li>

                </ul>
            </td>
            <!-- <td></td>
            <td></td> -->
        </tr>

    </table>
    <br>


    <table border="2" cellspacing="0" cellpadding="3" height="200" width="400" align="center">
        <tr>
            <td colspan="3" align="center" bgcolor="violet">Team Members</td>
            <!-- <td></td> -->
        </tr>
        <tr>
            <td align="center" bgcolor="grey">Name</td>
            <td align="center" bgcolor="grey">Role</td>
        </tr>
        <tr>
            <td align="center">Alice</td>
            <td align="center">Lead Developer</td>
        </tr>
        <tr>
            <td align="center">Bob</td>
            <td align="center">UI/UX Designer</td>
        </tr>
        <tr>
            <td align="center">Charlie</td>
            <td align="center">Project Manager</td>
        </tr>
        <tr>
            <td colspan="2">
                <ul>
                   <li><b>Lead Developer:</b>Responsible for coding and architecture.</li>
                    <li><b>UI/UX Designer:</b>Focuses on user inteface and experience.</li>
                      <li><b>Project Manager:</b>Oversees the project timeline</li>
                </ul>
            </td>
            <!-- <td></td> -->
        </tr>
        <br>


        <table border="2" cellspacing="0" cellpadding="3" height="200" width="400" align="center">
        <tr>
            <td colspan="3" align="center" bgcolor="pink">Travel Itinerary</td>
            <!-- <td></td> -->
        </tr>
        <tr>
            <td align="center" bgcolor="lightgreen">Day</td>
            <td align="center" bgcolor="lightgreen">Destination</td>
            <td align="center" bgcolor="lightgreen">Activity</td>
        </tr>
        <tr>
            <td align="center">Day 1:</td>
            <td align="center" colspan="2">Eiffel Tower Tour</td>
        </tr>
        <tr>
            <td align="center">Day 2:</td>
            <td align="center" colspan="2">Visit the Colosseum</td>
        </tr>
        <tr>
            <td align="center">Day 3:</td>
            <td align="center" colspan="2">Canal Boat Ride</td>
        </tr>
        <tr >
            <td colspan="3">
                <ul>
               <li><b>Lead Developer:</b>Responsible for coding and architecture.</li>
                    <li><b>UI/UX Designer:</b>Focuses on user inteface and experience.</li>
                      <li><b>Project Manager:</b>Oversees the project timeline</li>
                </ul>
            </td>
            <!-- <td></td> -->
        </tr>
        
        </table>
        <br>


        <table border="2" cellspacing="0" cellpadding="3" height="200" width="400" align="center">
        <tr>
            <td colspan="3" align="center" bgcolor="red">Nutrition Facts</td>
            <!-- <td></td> -->
        </tr>
        <tr>
            <td align="center" bgcolor="blue">Nutrient</td>
            <td align="center" bgcolor="blue">Amount</td>
        </tr>
        <tr>
            <td align="center">Calories</td>
            <td align="center">200 kcal</td>
        </tr>
        <tr>
            <td align="center">Total fat</td>
            <td align="center">8g</td>
        </tr>
        <tr>
            <td align="center">Carbohydrates </td>
            <td align="center">25g
        <tr>
        <tr>
            <td align="center">Protien </td>
            <td align="center">5g
        <tr>
            
            <td colspan="2">
                <ul>
                   <li><b>Calories:</b>Energy provided by food.</li>
                    <li><b>Total Fat:</b>Facts and oils content.</li>
                    <li><b>Carbohydates:</b>Sugars and starches.</li>
                     <li><b>Protien:</b>Essentiak for muscle building.</li>
                </ul>
            </td>
            <!-- <td></td> -->
        </tr>
    </table>
    <br>
     <hr color="black">
<table border="1" width="600" align="center" cellspacing="0" cellpadding="2">
    <tr>
        <th colspan="2" bgcolor="pink">To Do List</th>
    </tr>
    <tr>
        <td colspan="2">
            <ul>
                <li>Buy Groceries</li>
                <li>Finish Homework</li>
                <li>Call the Doctor</li>
                <li>Clean the House</li>
            </ul>
        </td>
    </tr>
</table>

<br>

<table border="1" width="600" align="center" cellspacing="0" cellpadding="2">
    <tr>
        <th colspan="2" bgcolor="yellow">Course Schedule</th>
    </tr>
    <tr>
        <th>Day</th>
        <th>Subjects</th>
    </tr>
    <tr>
        <td>Monday</td>
        <td>
            <ul>
                <li>Math</li>
                <li>English</li>
            </ul>
        </td>
    </tr>
    <tr>
        <td>Tuesday</td>
        <td>
            <ul>
                <li>Science</li>
                <li>History</li>
            </ul>
        </td>
    </tr>
</table>

<br>

<table border="1" width="600" align="center" cellspacing="0" cellpadding="2">
    <tr>
        <th colspan="2" bgcolor="blue">Travel Packing List</th>
    </tr>
    <tr>
        <th>Clothing</th>
        <th>Essentials</th>
    </tr>
    <tr>
        <td>
            <ul>
                <li>T-Shirts</li>
                <li>Jeans</li>
                <li>Jacket</li>
            </ul>
        </td>
        <td>
            <ul>
                <li>Passport</li>
                <li>Toothbrush</li>
                <li>Chargers</li>
            </ul>
        </td>
    </tr>
</table>

<br>

<table border="1" width="600" align="center" cellspacing="0" cellpadding="2">
    <tr>
        <th colspan="2" bgcolor="violet">Monthly Budget</th>
    </tr>
    <tr>
        <th>Income</th>
        <th>Expenses</th>
    </tr>
    <tr>
        <td>
            <ul>
                <li>Salary</li>
                <li>Freelance Work</li>
            </ul>
        </td>
        <td>
            <ul>
                <li>Rent</li>
                <li>Groceries</li>
                <li>Utilities</li>
            </ul>
        </td>
    </tr>
</table>

<br>

<table border="1" width="600" align="center" cellspacing="0" cellpadding="2">
    <tr>
        <th colspan="2" bgcolor="red">Team Members & Roles</th>
    </tr>
    <tr>
        <td>
            <table border="1" width="100%">
                <tr>
                    <th>Development Team</th>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>Alice</li>
                            <li>Bob - Tester</li>
                        </ul>
                    </td>
                </tr>
            </table>
        </td>

        <td>
            <table border="1" width="100%">
                <tr>
                    <th>Design Team</th>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>Sarah - Designer</li>
                            <li>John - UI/UX</li>
                        </ul>
                    </td>
                </tr>
            </table>
        </td>
    </tr>
</table>
<br>
 <hr color="black">




<table border="1" width="600" align="center" cellspacing="0" cellpadding="0" align="left">
    <tr>

        <!-- Task 1 -->
        <td>
           <table border="1" width="600" align="center" cellspacing="0" cellpadding="2">
                <tr>
                    <th colspan="2">Task 1: Project Overview</th>
                </tr>
                <tr>
                    <th>Project Phase</th>
                    <th>Key Steps</th>
                </tr>
                <tr>
                    <td>
                        <ol>
                            <li>Planning</li>
                            <li>Development</li>
                            <li>Testing</li>
                        </ol>
                    </td>
                    <td>
                        <ol>
                            <li>Define Goals</li>
                            <li>Build Features</li>
                            <li>Conduct Testing</li>
                        </ol>
                    </td>
                </tr>
            </table>
        </td>
        <br>
        <!-- Task 2 -->
        
            <table border="1" width="600" align="center" cellspacing="0" cellpadding="2" align="center">
                <tr>
                    <th colspan="2">Task 2: Daily Schedule</th>
                </tr>
                <tr>
                    <th>Time</th>
                    <th>Activity</th>
                </tr>
                <tr>
                    <td>
                        <ol>
                            <li>8:00 AM</li>
                            <li>10:00 AM</li>
                            <li>1:00 PM</li>
                        </ol>
                    </td>
                    <td>
                        <ol>
                            <li>Check Emails</li>
                            <li>Team Meeting</li>
                            <li>Work on Tasks</li>
                        </ol>
                    </td>
                </tr>
            </table>
        </td>
        <br>

        <!-- Task 3 -->
        <td>
            <table border="1" width="600" align="center" cellspacing="0" cellpadding="2" align="center">
                <tr>
                    <th>Task 3: Shopping List with Categories</th>
                </tr>
                <tr>
                    <td>
                        <b>Shopping Categories</b>

                        <ul>
                            <li>Fruits
                                <ol>
                                    <li>Apples</li>
                                    <li>Bananas</li>
                                </ol>
                            </li>

                            <li>Snacks
                                <ol>
                                    <li>Chips</li>
                                    <li>Cookies</li>
                                </ol>
                            </li>
                        </ul>
                    </td>
                </tr>
            </table>
        </td>

    </tr>
</table>

<br><br>

<table border="1" width="600" align="center" cellspacing="0" cellpadding="2">
    <tr>

        <!-- Task 4 -->
        <td>
            <table border="1" width="100%">
                <tr>
                    <th colspan="2">Task 4: Employee Details</th>
                </tr>
                <tr>
                    <th>Attribute</th>
                    <th>Information</th>
                </tr>
                <tr>
                    <td>Name</td>
                    <td>John Smith</td>
                </tr>
                <tr>
                    <td>Skills</td>
                    <td>
                        <ol>
                            <li>HTML</li>
                            <li>CSS</li>
                            <li>JavaScript</li>
                        </ol>
                    </td>
                </tr>
            </table>
        </td>

        <br>

        <!-- Task 5 -->
        <td>
           <table border="1" width="600" align="center" cellspacing="0" cellpadding="2">
                <tr>
                    <th>Task 5: Tech Term Definitions</th>
                </tr>

                <tr>
                    <td>
                        <b>HTML:</b>
                        <p>Hypertext Markup Language</p>

                        <b>CSS:</b>
                        <p>Cascading Style Sheets</p>
                    </td>
                </tr>
            </table>
        </td>

    </tr>
</table>

<br><br>
 <hr color="black">
<!-- Company Department Overview -->

<table border="1" width="600" align="center" cellspacing="0" cellpadding="2">
    <tr>
        <th colspan="3">Company Department Overview</th>
    </tr>

    <tr>
        <th>Department</th>
        <th>Team Members</th>
        <th>Details</th>
    </tr>

    <tr>
        <td>Development</td>

        <td>
            <ol>
                <li>John</li>
                <li>Maria</li>
                <li>Alex</li>
            </ol>
        </td>

        <td>
            <ul>
                <li>Focus: Web Application Development</li>
                <li>Tools: HTML, CSS, JavaScript, Django</li>
            </ul>
        </td>
    </tr>

    <tr>
        <td>Design</td>

        <td>
            <ul>
                <li>Sophie</li>
                <li>David</li>
            </ul>
        </td>

        <td>
            <table border="1" width="600" align="center" cellspacing="0" cellpadding="2">
                <tr>
                    <th>Task</th>
                    <th>Status</th>
                </tr>

                <tr>
                    <td>UI Mockups</td>
                    <td>Completed</td>
                </tr>

                <tr>
                    <td>UX Testing</td>
                    <td>In Progress</td>
                </tr>
            </table>
        </td>
    </tr>

    <tr>
        <td>Marketing</td>

        <td>
            <ul>
                <li>Emma</li>
                <li>Chris</li>
            </ul>
        </td>

        <td>
            <ul>
                <li>Campaigns
                    <ul>
                        <li>Social Media</li>
                        <li>Email Outreach</li>
                    </ul>
                </li>

                <li>Goal
                    <ul>
                        <li>Increase Brand Visibility</li>
                    </ul>
                </li>
            </ul>
        </td>
    </tr>

</table>
<br>



<table border="2" align="center" cellspacing="2" cellpadding="2" height="500" width="750">
        <tr>
            <th  bgcolor="lightgrey"colspan="4">Project MileStone Tracker</th>
            <!-- <td></td>
            <td></td>
            <td></td> -->
        </tr>
        <tr>

        </tr>
        <tr><th align="center" rowspan="1" bgcolor="lightgrey">Phase</th>
            <th align="center" bgcolor="lightgrey">Task</th>
            <th align="center" bgcolor="lightgrey">Team Members</th>
            <th align="center" bgcolor="lightgrey">Status</th>
        </tr>
        <tr>
            <th rowspan="2">Phase 1</th>
            <td>Research&Planning</td>
            <td>Alice,Bob</td>
            <td>Completed</td>
        </tr>
        <tr>
            <!-- <td></td> -->
            <td>inital design</td>
            <td>Charlie</td>
            <td>In Progress</td>
        </tr>
        <tr>
            <th>Phase 2</th>
            <td>
                <table border="2" height="100" width="350" cellspacing="0" cellpadding="2">
                    <tr>
                        <th colspan="4" bgcolor="lightgrey">Development Tools</th>
                        <!-- <td></td>
                        <td></td> -->
                    </tr>
                    <tr>
                        <td>-Frontend Coding</td>
                        <td>Maria</td>
                       
                    </tr>
                    <tr>
                        <td>-Backend Integration</td>
                        <td>Alex</td>
                        
                    </tr>
                </table>
                
            </td>
            <td align="center" colspan="2">Ongoing</td>
            <!-- <td></td> -->
        </tr>
        <tr>
            <th>Phase 3</th>
            <td>Testing & QA</td>
            <td>
                
                 <table border="2" height]="100" width="250" cellspacing="0" cellpadding="0">
                    <tr>
                        <th colspan="3">Testing team,IT Support</th>
                        <!-- <td></td>
                        <td></td> -->
                    </tr>
                    <tr>
                        <td colspan="2">
                            <ul type="disc">
                            <li>Bug Fixing</li>
                             <li>Final Testing</li>
                        </ul>
                    </td>
                        
                       
                    </tr>
                    
                </table>


            </td>
            <td>Pending Scheduled</td>
        </tr>
        <tr>
            <td  align="center"colspan="4" bgcolor="lightgrey">
                Launch & Review
            </td>
            <!-- <td></td>
            <td></td>
            <td></td>
        </tr> -->
        <tr>
        <td colspan="3" align="center">
            Entire Team
        </td>
        
        
        <td>Upcomimg</td>
    </table>











</body>
</html>
