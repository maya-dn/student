---
layout: post
title: About
permalink: /about/
comments: true
---

## Where I'm From!

<!-- This grid_container class is used by CSS styling and the id is used by JavaScript connection -->
<div class="grid-container" id="grid_container">
    <!-- content will be added here by JavaScript -->
</div>

<script>
    // 1. Make a connection to the HTML container defined in the HTML div
    var container = document.getElementById("grid_container"); // This container connects to the HTML div

    // 2. Define a JavaScript object for our http source and our data rows for the Living in the World grid
    var http_source = "https://upload.wikimedia.org/wikipedia/commons/";
    var living_in_the_world = [
        {"flag": "0/01/Flag_of_California.svg", "description": "California - for the rest of my life hopefully"},
    ];

    // 3a. Consider how to update style count for size of container
    // The grid-template-columns has been defined as dynamic with auto-fill and minmax

    // 3b. Build grid items inside of our container for each row of data
    for (const location of living_in_the_world) {
        // Create a "div" with "class grid-item" for each row
        var gridItem = document.createElement("div");
        gridItem.className = "grid-item";  // This class name connects the gridItem to the CSS style elements
        // Add "img" HTML tag for the flag
        var img = document.createElement("img");
        img.src = http_source + location.flag; // concatenate the source and flag
        img.alt = location.flag + " Flag"; // add alt text for accessibility

        // Add "p" HTML tag for the description
        var description = document.createElement("p");
        description.textContent = location.description; // extract the description

        // Add "p" HTML tag for the greeting
        var greeting = document.createElement("p");
        greeting.textContent = location.greeting;  // extract the greeting

        // Append img and p HTML tags to the grid item DIV
        gridItem.appendChild(img);
        gridItem.appendChild(description);
        gridItem.appendChild(greeting);

        // Append the grid item DIV to the container DIV
        container.appendChild(gridItem);
    }
</script>

### Journey through Life

My life

- Elementary school until second grade in New Jersey
- Moved to California, San Diego, before the start of 3rd grade and have been here since

### Culture, Family, and Fun

My family includes my mom and dad, and my two youner brothers, age 13 and 9. My parents were both born in the Soviet Union and lived there for 20 years before moving to the middle east for another 20 years and finally settling in the United States.

### My City

I love visiting La Jolla cove and seeing the sea lions!

<img src="https://fox5sandiego.com/wp-content/uploads/sites/15/2023/04/AdobeStock_284439394.jpeg?w=2560&h=1440&crop=1" alt="My favorite place"> 

<h4 id="-evaluation-matrix">📊 Evaluation Matrix</h4>

<table>
  <thead>
    <tr>
      <th>Skill</th>
      <th>Mastered (N)</th>
      <th>Self Rank (1-5)</th>
      <th>Peer Rank (1-5)</th>
      <th>Teacher Rank (1-5)</th>
      <th>Average</th>
      <th>Notes/Evidence</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><strong>🎯 Core Behaviors</strong></td>
      <td> </td>
      <td> </td>
      <td> </td>
      <td> </td>
      <td> </td>
      <td> </td>
    </tr>
    <tr>
      <td>Attendance</td>
      <td>[ ]</td>
      <td>5</td>
      <td>0</td>
      <td>0</td>
      <td>0.0</td>
      <td> </td>
    </tr>
    <tr>
      <td>Work Habits</td>
      <td>[ ]</td>
      <td>4</td>
      <td>0</td>
      <td>0</td>
      <td>0.0</td>
      <td> </td>
    </tr>
    <tr>
      <td>Behavior</td>
      <td>[ ]</td>
      <td>5</td>
      <td>0</td>
      <td>0</td>
      <td>0.0</td>
      <td> </td>
    </tr>
    <tr>
      <td>Timeliness</td>
      <td>[ ]</td>
      <td>5</td>
      <td>0</td>
      <td>0</td>
      <td>0.0</td>
      <td> </td>
    </tr>
    <tr>
      <td><strong>💻 Technical Skills</strong></td>
      <td> </td>
      <td> </td>
      <td> </td>
      <td> </td>
      <td> </td>
      <td> </td>
    </tr>
    <tr>
      <td>Tech/Cyber Sense</td>
      <td>[ ]</td>
      <td>1</td>
      <td>0</td>
      <td>0</td>
      <td>0.0</td>
      <td> </td>
    </tr>
    <tr>
      <td>Tech/Cyber Talk</td>
      <td>[ ]</td>
      <td>1</td>
      <td>0</td>
      <td>0</td>
      <td>0.0</td>
      <td> </td>
    </tr>
    <tr>
      <td>Tech Growth</td>
      <td>[ ]</td>
      <td>1</td>
      <td>0</td>
      <td>0</td>
      <td>0.0</td>
      <td> </td>
    </tr>
    <tr>
      <td><strong>🤝 Collaboration</strong></td>
      <td> </td>
      <td> </td>
      <td> </td>
      <td> </td>
      <td> </td>
      <td> </td>
    </tr>
    <tr>
      <td>Advocacy</td>
      <td>[ ]</td>
      <td>4</td>
      <td>0</td>
      <td>0</td>
      <td>0.0</td>
      <td> </td>
    </tr>
    <tr>
      <td>Communication &amp; Collab</td>
      <td>[ ]</td>
      <td>5</td>
      <td>0</td>
      <td>0</td>
      <td>0.0</td>
      <td> </td>
    </tr>
    <tr>
      <td><strong>🎨 Professional Skills</strong></td>
      <td> </td>
      <td> </td>
      <td> </td>
      <td> </td>
      <td> </td>
      <td> </td>
    </tr>
    <tr>
      <td>Integrity</td>
      <td>[ ]</td>
      <td>4</td>
      <td>0</td>
      <td>0</td>
      <td>0.0</td>
      <td> </td>
    </tr>
    <tr>
      <td>Organization</td>
      <td>[ ]</td>
      <td>5</td>
      <td>0</td>
      <td>0</td>
      <td>0.0</td>
      <td> </td>
    </tr>
    <tr>
      <td><strong>📈 TOTALS</strong></td>
      <td> </td>
      <td><strong>40</strong></td>
      <td><strong>0</strong></td>
      <td><strong>0</strong></td>
      <td><strong>0.0</strong></td>
      <td> </td>
    </tr>
    <tr>
      <td><strong>🎯 AVERAGE SCORE</strong></td>
      <td> </td>
      <td><strong>3.64</strong></td>
      <td><strong>0.0</strong></td>
      <td><strong>0.0</strong></td>
      <td><strong>0.0</strong></td>
      <td> </td>
    </tr>
  </tbody>
</table>

[def]: ic_of_family.jp
