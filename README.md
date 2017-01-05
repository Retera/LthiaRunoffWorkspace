# LthiaRunoffWorkspace

We created too many places to store the LTHIA maintenance and backend code, so I created a new one to try to solve the problem. This time, instead of copy pasting between places, I'm going to hold the code in source control for a while, and it will be apparent to other people what I did.

The reason we went back to this Java code today is some of the numbers in our new, unreleased and upgraded LTHIA model were not correct. The curve numbers 98, 99, and 100 had vastly different value from other curve numbers. It suggests one of the two must have been computed incorrectly.

So, I'm bringing LTHIA code into this workspace to check it, run it, and find if it truly is a formula error responsible for the problem.
