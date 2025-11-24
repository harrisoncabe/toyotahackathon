# toyotahackathon

## Inspiration
Splits in racing tell the driver, team, and audience what is happening during those standout laps, I wanted to make an analysis tool that chooses what the driver did correct from different points around the track so that someone can see what they and their car are capable of.

## What it does
This analysis takes a driver's telemetry data over a session to determine the fastest possible lap achievable by that driver and car to show condition-differing improvement points. This can be compared to the overall 

## How we built it
Learned how to extrapolate data from telemetry using the FastF1 package in python and got a good idea for how to partition the track, find the best lines, and account for missing telemetry data

## Challenges we ran into
There were some gaps in the telemetry data at points, which I made up for by choosing data from the next fastest lap that does have data there. It was very difficult to properly merge the chosen fastest lines because there was variance between the lines taken to make the fastest splits. 

## Accomplishments that we're proud of
I am proud of making this universal to the different drivers at Barber. I was able to make an adaptive fill option so that this program works for all the drivers where data is missing at different places. This makes it so that the full predicted lap is cohesive and it shows a real change in comparison to other lines that is an actionable insight. 

## What we learned
I learned a lot, I was a full beginner going into this project. I am going to continue to improve this but I am proud of the work I have done to figure out how to extrapolate telemetry data into smooth lines. Another important skill that I learned is how to backtest functions and data to see why I am getting unexpected outcomes.

## What's next for Theoretical Fastest Lap per Conditions Analysis
I am going to continue to improve this to make an easy setting options at the top where more track's coordinates are loaded then it will work for all tracks!
