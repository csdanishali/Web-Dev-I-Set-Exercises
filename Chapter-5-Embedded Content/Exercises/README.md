# Chapter 5 Exercises

Each chapter includes one mandatory and one bonus exercise. The mandatory exercise is indicated with a :ballot_box_with_check: and must be completed as part of the Set Exercises assessment. The bonus exercise is optional but completing it opens up the possibility of achieving a grade in the higher mark boundaries.

For each exercise you should create a new folder with the name of the exercise and save it to this exercises folder in your local repository. Once you have completed your solution you should make sure you commit and push your work to GitHub. You can commit and push as many changes to your solutions as you wish; only those pushed before the deadlines will be marked.

## Assessment Exercises

### Embed Video :ballot_box_with_check:

Embed a locally hosted video of your choice into a html document. The video must:

* Loop;
* Display a relevant poster image;
* Be centred on the page horizontally and vertically.

<hr>

### Alan Partridge Soundboard (Bonus - Optional)

A local comedy radio show needs you to develop an audio soundboard for them. The soundboard will display a grid of Alan Partridge samples. When a sample is clicked the associated audio file will play. The audio samples for this exercise are located in Exercises/Audio Sampler. Your sampler must:

* Include all of the samples in the Audio Sampler directory;
* Display all samples on a single non-scrolling page;
* Make use of correct semantic markup;
* Display the correct sample name;
* Change the colour of the background, and text, when the user hovers over a sample;
* Include index.html, style.css and index.js files;
* Include creative styling for your background, sample buttons, fonts and hover effects;

Use the below example as a reference:

![image](Audio%20Sampler/Soundboard.png)

#### Further Extension Problems

The radio show loved the sampler you made for them before, but they'd like to give a more advanced system a go. In a new directory, build on top of your previous sampler and include the following new ideas:

* The show would like to include a text to speech feature. This feature allows presenters to type any text they like into a `<textarea>` element and have it converted to audio which then plays immediately. This new feature should be displayed in a seperate column next to the audio samples (see image below for reference);

* The show would like to include more audio samples. However, they only want sampler to display nine samples at a time. Create a system whereby the team can use "left" and "right" arrows to scroll through an extended bank of samples. The team is open to your creative ideas as to what audio is included on these new pages. When the first page is displayed, the "left arrow" should be hidden, and when the last page is displayed the "right" arrow should be hidden (prevents users from scrolling to blank sample pages or encountering errors);

* The team would like the length of the sample in seconds to be dynamically displayed underneath the sample title.

Use the below example as a reference:

![image](Audio%20Sampler/Soundboard_Advanced.png)
