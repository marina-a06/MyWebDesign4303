# Mom Command Center Reflection

## Decisions
Building my “Mom Command Center” page was a much more involved process than I expected. It wasn’t just about making a page look organized, it was about deciding how information should actually flow in a way that would be useful in real life. Throughout the project, I had to constantly balance design, functionality, and simplicity.

One of the most important decisions I made was how to structure the page layout. Early on, I tried to fit everything into one large container with multiple sections stacked vertically, but it quickly felt cluttered and hard to navigate. I decided to break the page into clear sections like the sidebar, calendar area, and activity tracker. This made the interface easier to understand and helped me think more like a user instead of just a developer. I also chose to use a consistent “card” style for key components so the design would feel unified rather than scattered.

Another major decision was how to handle data storage for the activities and events. Instead of keeping everything temporary in the DOM, I used `localStorage` so the information would persist after refreshing the page. This was important because the whole idea of a “command center” is that it should actually feel functional and reusable, not just a static layout. I also decided to store events by date, which required restructuring how I was originally thinking about the calendar logic.

## What Worked
What worked really well was the iterative approach I took with the calendar and tracker integration. At first, I built them separately, but over time I slowly connected them so that selecting a date actually updates the activity view. That moment when everything started syncing correctly felt like a breakthrough.

I’m also really satisfied with how the visual hierarchy turned out, things like the sidebar buttons and headings clearly guide the user’s attention without overwhelming them. The layout feels more intentional now, and the sections are easier to scan quickly.

## What I Would Do Differently
If I had to start over, I would definitely plan my CSS structure more carefully from the beginning. I ran into several issues with overlapping styles, especially with repeated classes like `.container`, which caused unexpected layout behavior.

I also would have created a clearer wireframe before coding. I spent a lot of time adjusting spacing and layout after the fact, which could have been reduced with better upfront planning. In addition, I would modularize my JavaScript earlier instead of letting it grow into one large script file, because debugging became more difficult as features increased.

## What I Learned
What I learned from this project goes beyond just coding. I learned that building for the web is a process of constant refinement, not a one-time build. Small design decisions, like spacing, naming conventions, and layout structure, end up having a huge impact later.

I also learned that I tend to underestimate how interconnected different parts of a project are. Changing the calendar logic affected the tracker, and styling changes affected usability in ways I didn’t always anticipate.

On a personal level, I learned that I work best when I build in small, testable pieces rather than trying to finish entire features at once. I also became more comfortable troubleshooting issues in JavaScript and CSS instead of immediately restarting or rewriting everything.

Overall, this project taught me that good web design is not just about making something work, it’s about making it feel intuitive, stable, and intentional.