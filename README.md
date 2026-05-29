<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <title>Mia Sommavilla-5R</title>
    </head>
<body>

<h2>Geografische Fakten</h2>
<p>Traumstadt:Paris</p>
<p>Einwohnerzahl:2,05 Millionen</p>
<body style="background-color: lightblue;">
<h2>Top 3 Sehenswürdigkeiten</h2>
<ol>
      <li>Eiffelturm</li>
      <li>Louvre</li>
      <li>Kathedrale Notre-Dame de Paris</li>
    </ol>
    <h2>Kulinarische Spezialitäten</h2>
    <ul id="liste-essen"></ul>

<script>
const essen = [
  "Croissant",
  "Baguette",
  "Crêpes",
  "Frankreich"
];

const liste = document.getElementById("liste-essen");

essen.forEach(h => {
  let li = document.createElement("li");
  li.textContent = h;
  liste.appendChild(li);
});
</script>
<h2>Visueller Eindruck</h2>
