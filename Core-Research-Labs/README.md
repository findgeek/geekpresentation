# Outline Logging system & The challenges in distributed system. 

## Slide 1 (Briefly Summarise)

This slide should provide enough brief summary for the audiences 
- What was the story
- Feel free to interrupt me during the presentation
- All slides & materials needed will be uploaded at SpeakerDeck & GitHub

## Slide 2 (Using the storyteller accent)

Once upon a time when we only had simple architecture like this .. So the logging will only be 

But nowadays it is not easy like that when we have something like this 

The question is how will we deal with those challenges ? 

## Slide 3 

Easy like people usually mention (ELK - EFK)

You think that ENOUGH ? NO ! So what were the next challenges ? 

## Slide 4 

Observability for your logging pipeline 
- How many events were ingested successfully into your backend 
- How many events your pipeline can handle in a second 
- Don't forget that Developer is the actual person who plays the key role in this architecture.
How to involve their responsibility here ? 

## Slide 5 

That's exactly what we lost in the past few months at my current company. 

## Slide 6 

So overview how much of the log traffic we have so far 
With the simple architecture like (Slide 3)

## Slide 7

Improvement 1 
- FluentD connectivity 
(BackPressure)

## Slide 8 

Improvement 2 
- FluentD output 
(GELF multiple workers)

## Slide 9 

Improvement 3 
- Decoupling fluentD function
(ConfigMap)

## Slide 10 

Infrastructure as a Code for the full logging pipeline

## Slide 11 

Throttling & Data type constraints

## Slide 12

SLO for the logging pipeline

## Overview 

Mention about some methodology & thoughts

Q & Al

## Slide 13 

Presenter information
- Email
- Twitter
- GitHub
