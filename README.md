# xHack
## Note: 
This version is not what was built during the hackathon - it is my forked version to be deployed to a web server. I am using Renderer for the backend and Vercel for the frontend. You can see the live version [here](ic-hack26-sigma.vercel.app). Please note that the backend is being hosted for free on Renderer, so the app will stop working briefly if the memory limit is exceeded - which happens regularly considering it is loading 4 substantial models - and patience is required for the first request to the server while it 'spins up'.

## About xHack

As a group of avid football fans, we're all interested in finding out in how we can improve, and how likely we are to score! However, sometimes the best option isn't always the most obvious, and we wanted to uncover the truth behind that.

We wanted to create a tool that would be able to help not just hobbyists like us but also coaches and small teams without the massive budgets of higher-league football teams.
What it does

We have built a website that allows a user to place all 22 players on the football pitch, select which player to control, and from there they are presented with a list of the most optimal actions they can take, to maximise the probability of scoring a goal in that same play!

## Running xHack

Using Python>=3.11 you can install all compatible needed dependencies.

The backend with Flask can be run on `run.py`.

You can run the frontend with `npm run dev` in `frontend/haggin`.
