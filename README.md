
Math Helper for DeltaMath
An unofficial helper panel for DeltaMath. It reads the question on your screen, works it out with steps, checks the answer, and can fill it in when you click. It never submits for you.

Not affiliated with or endorsed by DeltaMath.

Install
Open a question on DeltaMath.
Open the console: Option-Command-C in Safari. Turn on the Develop menu first in Safari's settings.
Paste this line and press Return:
fetch('https://cdn.jsdelivr.net/gh/Coolman266776/Deltamath-helper-1.60@main/math-helper.js').then(r=>{if(!r.ok)throw new Error(r.status);return r.text()}).then(t=>{(0,eval)(t)}).catch(e=>alert('Math Helper could not load: '+e.message))

What it covers
Algebra 1: equations, inequalities, factoring, quadratics, lines, systems, functions, tables, graphs, mapping diagrams, percents
Geometry: triangles, circles, area and volume, right-triangle trig, transformations, and angles and sides from marked diagrams
Algebra 2: complex numbers, polynomials, logs and exponentials, radicals, rational expressions, sequences, trig functions
Statistics: mean, median, quartiles, regression, two-way tables, probability, bar graphs, histograms, dot plots
If it can't be sure, it says so and shows no answer instead of guessing.

Using it
Control	What it does
Fill Answer (⌥F)	Types the answer into the box, or sets the dropdown. It asks before replacing anything
Check (⌥K)	Tells you if what you typed is right, without showing the answer
Hide	Blurs the answer so you can try first
Steps	Shows the worked solution
Copy (⌥C)	Copies the answer
Dark	Switches DeltaMath to a dark look, and remembers your choice
?	Shortcuts and tools
⌥S solves and ⌥M shrinks the panel. Nothing is sent anywhere: it runs in your browser and only reads the page you have open.

What works so far
Most of this has only been tested on a local copy of DeltaMath's layout, so expect some questions to be read wrongly. Always check an answer before you submit it.

Feature	Status
Reading math questions, filling answer boxes, mapping diagrams and dropdowns	Seen working on real DeltaMath
Geometry, statistics, Algebra 2, tables, bar graphs, geometry diagrams, dark look	Tested on the local copy only
Plot on the graph	Not confirmed. The dots did not move in its first real test. It has been changed since, but not retried there, so be ready to place them yourself
RELIABILITY.md has the full breakdown and test results.

Use it fairly
This is meant for checking your work and learning from the steps. Using it on graded work may break your school's rules or DeltaMath's terms, and that choice is yours.

Development
src/ has the source. There's nothing to install on a Mac beyond Python 3.


No license has been chosen yet, so all rights are reserved by default.

