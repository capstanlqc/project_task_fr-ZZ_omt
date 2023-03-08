# OmegaT exercises

## Getting started

1. Download project package [xxx](XXX). @For the time being available at https://github.com/capstanlqc/project_task_fr-ZZ_omt
2. Unpack that project.

## Section 01: Navigation @WIP

- Ctrl+U
- Enter / Ctrl+Enter
- Double click
- Ctrl+J

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

If you want more practice, go to segment #29 ("Subject:"), which is also repeated

## Section 04: Tags

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

---


