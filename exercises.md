# OmegaT exercises

## Getting started

1. Download project package [xxx](XXX). @For the time being available at https://github.com/capstanlqc/project_task_fr-ZZ_omt
2. Unpack that project.

> Tip: to go to a specific segment, you can press Ctrl+J and enter the segment number.

## Section 01: Navigation @WIP
<!--
- Ctrl+U
- Enter / Ctrl+Enter
- Double click
- Ctrl+J

-->

<!---Check segment numbers!!-->

1. Go to segment number 31 using the Ctrl+J shortcut.
2. Jump to the next untranslated segment using the Ctrl+U shortcut
>You should arrive on segment 38
3. Press Enter to move the next segment
>You should be on segment 39
4. Double click on the last segment you see
>It should read "After delivery, the translator took a well-deserved rest!"
5. Use the Ctrl+J shortcut to go to segment number 1

## Section 02: Repetitions

### Exercise 02.1

1. Go to segment #2 ("Good"). 
2. Notice how the segment marker says that this segment is repeated three more times: `<segment 0002 +3 more ¶>`. @quiz: how many reps?
3. Look at the Segment Properties pane. It says "Is duplicate: FIRST"
4. Right click on the segment. See how all the instances are listed with their segment number. 
5. Select segment #5 to go to segment #5.
6. Look at the Segment Properties pane for segment #5. It says "Is duplicate: NEXT"
7. Right click on segment #5 to see instances listed again, go back to segment #2 again.
    > @quiz: something about FIRST and NEXT

### Exercise 02.2

1. Translate segment #2: "Good". Suggested translation: "BonNE" 
    > info: (-NE: feminine suffix, because "Good" here refers to "economic situation", which is feminine in French).
2. Press Enter after translating segment #2 to go to segment #3.
3. Notice how the translation is auto-propagated to segment #5.
4. Translate segment #3: "Bad". Suggested translation: "MauvaisE"
    > info: (-E: feminine suffix, because "Bad" here refers to "economic situation", which is feminine in French).
5. Press Enter after translating segment #3 to confirm the translation of segment #3 and go to the next segment.

### Exercise 02.3

1. Go to segment #5 in the project. You can see that it is pretranslated with an auto-propagated translation.
2. Modify the translation in segment #5 and press Ctrl+S to register the transalion. Notice how the translation of segment #2 also changes.
    > You can also save in Project > Save.
3. Undo your changes (e.g. you may press Ctrl+Z)

## Section 03: Alternative repetitions

In the previous section you have seen that translations of repeated segments auto-propagate when you create. Edits you make to the translation of a repeated segment will also auto-propagate to all intances of that repeated segment.

That is convenient in many cases, but not always. To prevent auto-propagation, you must create an alternative translation.

### Exercise 03.1

Go to segment #5 in the project. You can see that it is pretranslated with an auto-propagated translation.

    Good" and "Bad" in this context refer to "level of English" which is masculine in French.

You want to modify the translation in segments #5 and #6 to make it masculine, so that it agrees with "level" in French. 

Follow these simple three steps:

1. Go to Edit > Create Alternative Translation
    > Also available if you right-click the segment
2. Modify the translation to make it masculine
    > Just remove the last character if you don't know French
3. Press Ctrl+S to register the translation

Did you follow the steps above? If you did, now notice

* how your alternative translation appears in the Mutiple Translations pane, followed the !filename and the segment ID.
* how the Segment Properties pane says now "Is alternative: TRUE"
* how the translation of segment #2 hasn't changed

Press Enter to move to segment #6 and do the same steps as above.

info: If you want more practice, go to segment #29 ("Subject:"), which is also repeated a few times. The first occurrence refers to an email subject line, whereas the other occurrences refer to the topic or field of books in a library classification system, so each of those requires a different translation, i.e. "Objet" vs "Sujet".



## Section 04: Tags

### Exercise 04.1: insert tags

1. Go to segment #9 (“There are no &lt;g1&gt;right&lt;/g1&gt; answers.”) <!-- segment should be untranslated -->
2. Notice the tags in the segment.
    > @quiz: what do you think these are? How to we handle them: should we ignore them or reproduce them in the translation?
3. Translate segment #9. Suggested translation: "Il n’y a pas de bonne réponse."
4. Select the corresponding translation of “right” in the translation (i.e. “bonne”).
5. Press Ctrl+Space. Notice how this opens the auto-completer.
6. Press Crtl+Space several times to cycle through all the sections. Stop when you reach the “Missing tags”.
7. Select the first option (i.e. `<g1>|</g1>`) and press Enter.
8. Notice how the tags are inserted around the selected text in the translation.


### Exercise 04.2: see what tags stand for

<!-- translation: Le traducteur a dû prêter attention au formatage tel que le gras, l'italique, le soulignement</g3>. -->
1. Go to segment #39: “The translator had to pay attention to formatting such as <g1>bold</g1>, <g2>italics</g2>, <g3>underline</g3>.”
2. Hover over the tags with your mouse to see the HTML code the tags stand for.
    > tip: `<strong>`, `<em>`, `<span class="underline">` etc.


### Exercise 04.3: insert standalone tag

@todo

### Exercise 04.4: insert more tags

1. Still in segment #39, notice how most tags are missing in the translation.
2. Select the translation of “bold” (tip: “le gras”).
3. Press Ctrl+Space to open the "Missing tags" section in the auto-completer
4. The first line (i.e. `<g1></g1>`) is selected by default. Press Enter to insert that tag pair.
4. Notice how the tags have been inserted around the selected text (i.e. `<g1>le gras</g1>`)
5. Do the same for the translation of “italics” (tip: “l’italique”). 
5. Do the same for the translation of “underline” (tip: “le soulignement”). 

> @quiz: insert 

### Exercise 04.5: relocate tag

<!-- more for editors! -->

In this exercise, you'll practice how to move a tag.

1. Go to segment #30 (“<g1>Don’t Open This Email</g1>”) <!-- translation: N<g1>'ouvrez pas cet </g1>e-mail -->
    > @quiz: what do you notice?
2. Notice how the position of the first tag (tag `<g1>`) is incorrect. You will fix that.
    > @quiz: it should be at the beginning of the segment / end / in the middle
3. Double click on the tag `<g1>` to select it.
4. Now drag and drop it to the correct position.
    > tip: the paired tags should also include "N"  
    > hidden tip: shows the expected result (the solution)

> Tip for RTL languages.. @todo please use the helpdesk if you find a complicated situation

Well done!

### Exercise 04.6: relocate tag

<!-- more for editors! -->

In this exercise, you'll practice another way to move a tag to its correct position.

1. Still in segment #30 (“<g1>Don’t Open This Email</g1>”) <!-- translation is now: <g1>N'ouvrez pas cet </g1>e-mail -->
2. Notice the the position of the second tag (`</g1>`) is also incorrect.
3. Double click on the tag `<g1>` to select it.
4. Press +del+ on your keyboard to delete the tag.
5. Place the cursor (e.g. just click) where you want the tag to appear instead
6. Use the auto-completer to insert the tag
    > tip: ctrl+space

> hidden tip: shows the expected result (the solution)


## Section 05. Matches < MS: WIP
## Section 06. Autotext
## Section 07. Search: AM

Using the search function, try to find the following segments in the project:

1. There is one occurence where "Rather unsatisfied" was not translated consistenly, can you find it?
2. Find the segment with "How" in a note.
3. Try to find the translation of "translator" in the translation memories.
4. Find "Subject", but only if it has a translation.

## Section 08. QA checks: AM

1. There are two segments with tag errors, can you find them?
2. On which segment is there a glossary error?


## Section 09. Download git project + commit target files + helpdesk

<!--Check URL?!-->

1. Copy this URL to your clipboard (select it and press Ctrl+C): https://github.com/capstanlqc-pisa/PISA_2025_fr-ZZ_Verification_OMT.git
2. Open OmegaT, click on the Project menu, select "Download Team Project".
3. Click inside the Repository URL field and press Ctrl+V to paste the URL you have copied.
4. Click inside the New Local Project Folder field.
>OmegaT will propose a default path for you, if that path is not suitable you can edit it to have the project created in your preferred location

>**Note**
>We advise you to use an easy path to remember, such as a folder in your Documents folder

5. Press OK, the project will be loaded after a few seconds.

---


