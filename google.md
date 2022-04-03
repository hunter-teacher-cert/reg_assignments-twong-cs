# Googling Away
* Create or use an existing programming task in a programming language of a class you are teaching (or would like to teach).
  - The task should involve multiple steps, ~5.
* Run a few internet searches that a student might run when presented with your task.
* In a markdown file:
  - Describe the task
  - For each search you ran provide three links from the results
    - Provide a critique on the result. Things to consider:
      - Was it useful?
      - Was it too simple/complex?
      - Was it unecessarily compicated?
      - Did it include copypastable code?
      - Did you learn from it/could a student learn from it?

## Programming Task
A programming assignment I do with my students is a number guessing game in Snap. Students write a function that takes an input number as the upper bound. 1 will always be the lower bound. A secret number is randomly chosen between 1 and the upper bound. The user has to guess what the secret number is. If the guess is greater than the secret number, the sprite will tell the user their guess is too high. Similarly, if the guess is lesser than the secret number, the sprite will tell teh user their guess is too low. The program will stop running when the user guesses the secret number.

## Online Research Results
1. YouTube Video by Michael Ida: https://www.youtube.com/watch?v=W3rhIGLjSKU <br>
The first search result I found is a YouTube video that walks through coding a similar program. While the narration of the video is useful, it is not the exact same assignment. The video's function does not have a parameter for the upper bound and has a feature of counting the number of guesses the user needs. The function also contains no iteration inside - instead, this function is for a singular guess and is run many times, until the user correctly guesses the secret number. This is a different way to solve the same problem so there is merit to examining a different approach to the same problem.

2.  YouTube Video by mrGcoding: https://www.youtube.com/watch?v=8df6nmWYIWA <br>
In my search, I found a different YouTube video. This one is more detailed and aligned more closely to the actual solutions. Mr. G's videos are well-known among teachers and students - it's no secret that they're out there. I've never discouraged students from looking up these videos because he does a great job explaining each step and the purpose of each line of code. The video shows the initial half of the development of the entire code, so it's a partial solution. If students want this help to get started, I would not be opposed to it. However, I would strongly prefer if students tried to think it through with each other and themselves first. Allowing students to watch video tutorials instead of working with each other can be detrimental to the classroom culture.

3. Blog Post by William Wang: http://williamwangcs.blogspot.com/2018/08/snap-u2l1-numberguessing.html <br>
The solution presented in this blog post is the most similar to the actual solution. This one shows students how to provide the user with the too high or too low feedback but it still doesn't show students how to create an input variable and use it as the upper bound. This resource is the least useful as there is little explanation and just shows students the final result instead of explaining the lines of code while live coding. This is the resource I least want students to use because, while it is the most useful, it gives away too much with too little explanation.
