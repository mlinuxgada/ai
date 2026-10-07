# General

Some non IT ppl frequently ask us, the conputer science engineers - arent you afraid that AI gonna steal your jobs.
Which led me to 2 major thoughts:
 - most of the ppl dont get the real job of a software engineer
 - atm we're not even doint AI
 
About the second one, I wanted to write in a general way my "core" concepts about AI

For the purpose of the doc, lets define some basic concepts:
 - code jump - event, when AI behaves /for some reason, OR randomly/ outside the current code implementation
 - CORE code - the code, done by humans, eg software engineers
 - ADDITIONS - the additional code, based on the assessments, done by AI itself

Here are some basic thoughts.

# Rules

### AI must never ever touch CORE code.


# Concepts

### AI must be able to make mistakes

what does it mean ?! It means that the AI needs to be able at random moment to "jump" outside its current code behavioral
implementational frames.

In short, lets say that we have some code segment, where currently have a logic implementation, with caseA and caseB.
AI needs to be able to "jump" outside, eg to do caseC, even its not currently implemented/defined into the code itself.

## AI must be able to assess the result

When such random event, where we have AI behaves outside ot its code frame, AI must be able to assess the result.
Whether its good or bad. Right or wrong.

## AI must be able to do additions to its current codebase, based on the above assessments

When such "jump" appears, AI must be able to update its codebase, depending on the assessment. Theres no need to wait, eg waste time, waiting for the event to happen again.

Again, based on rules above, AI must never ever be able to touch/alter CORE code. Ever!

## AI must be able to doubt the ADDITIONS code from such additions

Even when AI performed assessment, from concept 2, in time, AI will gain additional knowledge. Which means, assessment made in the past may not be relevand/correct now.

Always doubt, at random intervals. 

But doubt the ADDITIONS code.
NEVER allow AI to doubt the CORE code.
