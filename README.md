<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
<body>

<h1>Smart Waiter</h1>

<p>This hardware project introduces an innovative <b>Smart Trolley</b> designed to transform food service in restaurants. Unlike traditional methods, this Smart Trolley autonomously delivers food from the kitchen directly to the customer's table. Below is a detailed description of its operation:</p>

<h2>System Operation</h2>

<ul>
  <li><strong>Delivery Path:</strong> The Smart Trolley is equipped with navigation capabilities that enable it to travel from the kitchen door to the designated customer table. The trolley follows a predefined route or adapts its path in real-time based on the restaurant's layout and obstacles.</li>
  
  <li><strong>Food Loading:</strong> In the kitchen, the manager loads the prepared food items into the trolley’s designated compartments. These compartments are secured with locks to prevent tampering and ensure the food remains safe and at the appropriate temperature during transit.</li>
  
  <li><strong>Table Information:</strong> The manager inputs detailed information about the table into the system, including the table number, its location within the restaurant, and the customer’s bill. Each table is assigned a unique pin-code that helps the trolley identify its destination accurately.</li>
  
  <li><strong>Journey:</strong> After receiving the table information, the trolley starts its journey towards the specified table. The journey is carefully managed to navigate through the restaurant, avoiding obstacles and ensuring the safe delivery of the food.</li>
  
  <li><strong>Verification:</strong> Upon reaching the customer’s table, the trolley prompts for a password to verify the delivery. The customer or restaurant staff enter the pin-code associated with the table. If the correct pin-code is entered, the compartment door opens, allowing the food to be served directly to the customer.</li>
</ul>

<hr />

<h2>Requirements</h2>
<div class="tech-stack">
  <h3>Hardware Components:</h3>
  <ul>
    <li><strong>Arduino:</strong> The microcontroller used for managing the trolley’s operations and processing inputs from sensors.</li>
    <li><strong>DC Motor:</strong> Powers the trolley's movement, enabling it to travel between the kitchen and the table.</li>
    <li><strong>Buzzer:</strong> Alerts the user or staff to notify them of specific actions or errors.</li>
    <li><strong>LM35 Temperature Sensor:</strong> Monitors the temperature inside the trolley to ensure food safety.</li>
    <li><strong>Servo Motor:</strong> Controls the opening and closing of the trolley’s compartments.</li>
    <li><strong>IR Sensor:</strong> Assists with navigation and obstacle detection to avoid collisions.</li>
    <li><strong>Proteus V8 (Simulation Software):</strong> Used to simulate and test the trolley's functionality in a virtual environment before physical implementation.</li>
    <li><strong>Arduino Mega 2560:</strong> Provides additional input/output pins and processing power for handling complex tasks.</li>
  </ul>
</div>

<p>This description pertains to the software simulation of the Smart-Waiter project completed on Proteus. The actual implementation integrates these hardware components to achieve a fully functional Smart Trolley for efficient food delivery in restaurants.</p>

</body>
</html>
