# X-SUNIT (Extraterrestrial Survival Unit)

## Problem Description

The world as we know it has fallen into an apocalyptic scenario. An alien invasion is abducting humans and swaping them for evil clones that are really similar to the original person.

You, as a X-SUNIT member (and the last survivor who knows how to code), was designated to develop a system to share resources between non-abducted humans.

## Requirements

You will develop a ***REST API*** (yes, we care about architecture design even in the midst of an alien apocalypse!), which will store information about the survivors, as well as the resources they own.

In order to accomplish this, the API must fulfill the following use cases:

- **Add survivors to the database**

  A survivor must have a *name*, *age*, *gender* and *last location (latitude, longitude)*.

- **Update survivor location**

  A survivor must have the ability to update their last location, storing the new latitude/longitude pair in the base (no need to track locations, just replacing the previous one is enough).

- **Flag survivor as abducted**

  In a chaotic situation like that, it's inevitable that a survivor may get abducted. When this happens, we need to flag the survivor as abducted.

  **A survivor is marked as abducted when at least three other survivors report their abduction.**

- **Reports**

  The API must offer the following reports:

    1. Percentage of abducted survivors.
    2. Percentage of non-abducted survivors.
    3. List of all survivors names, by alphabetic order, marking all abducted survivor.

---------------------------------------

## Notes

1. Please use *Ruby on Rails* to implement the solution (everything you need is in the Reference section below).
2. Use may use any database you want (including Sqlite).
3. No authentication is needed - it's an alien apocalypse, no one will try to hack a system while running from a horde of alien (they don't know REST, they still use SOAP);
4. We still care about proper programming and architecture techniques, you must showcase that you're worthy of surving the alien apocalypse through the sheer strength of your skills;
5. Don't forget to make at least a minimal documentation of the API endpoints and how to use them;
6. From the problem description above you can either do a very bare bones solution or add optional features that are not described. Use your time wisely; the abolute optimal solution might take too long to be effective in the apocalypse, so you must come up with the best possible solution that will hold up within the least ammount of time and still be able to showcase your skills in order to prove your worth.

## How can I submit it?

Create a git repository with your solution and texts and give us the path to access it. It can be a public GitHub repository or something else if you prefer. If for some reason you didn't have enough time to complete all the requirements, add a brief description of how would you handle the missing features.

## What is under evaluation?

1. Does the solution satisfy the requirements and it works correctly?
2. How did you designed your solution? Is it organized?
3. Is your code easy to understand?

We don't expect that everything will be perfect, but we value a lot if you can identify where you're lacking and where you can improve. Thank you very much for accepting our challenge!

---------------------------------------

## References

...

## Credits

- This was adapted from the Codeminer42 recruitment challenge.
- X-COM: Enemy Unknown

**Your efforts will have considerable influence on this planet's future. We urge you to keep that in mind as you proceed. Good luck, Commander**
