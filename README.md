# Lab-1
**Lab 1 AI Assistance - Map and Trim Question**
**Overview**
This assignment requires creating a list of strings with extra spaces and using the map function to trim the spaces from each string.

**My Approach**
I created the initial list with the given names containing spaces at the start and end.

To remove these extra spaces, I used the List.map function combined with the String.Trim() method, which removes whitespace from the start and end of each string.

Since Trim is an instance method of the string type, I applied it to each element in the list via a lambda function (fun name -> name.Trim()).

I printed the resulting list with trimmed strings to verify the output.

**Notes on Assistance**
I encountered some issues with correctly applying the Trim method in F# because it is an instance method and requires calling it on each string, not as a standalone function.

To resolve this and to ensure proper F# syntax, I sought help from an AI language model (ChatGPT).

The AI helped me understand the correct usage of String.Trim() within the List.map function and how to write the lambda function appropriately.

I carefully reviewed and tested the AI-assisted code to ensure it worked correctly and that I fully understood it.

**Conclusion**
I know using AI isn’t always ideal, but at that moment, I needed the help to move forward with some parts of the code. The AI guided me through the syntax and logic, and I made sure to fully understand and verify everything before submitting. This topic will take a while to grasp for a while because I don't fully understand how Maps work as of yet.
