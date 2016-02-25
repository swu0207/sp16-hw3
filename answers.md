1. What is the difference between new and create for a model?
  New simply makes the page to create the new resource but you don't save anything with you make a request to 'new'.
  Create is the endpoint to create the resource; it is where the resource gets sent to and inserted into the database.

2. What command combined with new will emulate the same behavior as create?
  The .save command will be like create because .save puts the resource into the database.

3. What is the column that exists on every table but we did NOT define?
  The 'id' column is always on every table.

4. What single line of ruby code can insert a cat with the name "hat" in the database?
  Cat.create name: "hat"

5. What was the most confusing part over the last few weeks?
  I think the most confusing was mainly trying to remember what commands did what and trying to get used to the process of creating a controller, making a home page and putting information on it (hw2 content).

6. How did you like this homework in comparison with the others?
  I liked the previous homework assignment more (hw2) because while it was difficult, it really helped me get a more interactive experience with using rails. This one a lot of information was already provided and there was a guide, which is great but I feel like it won't make me try as hard to finish the assignment.
