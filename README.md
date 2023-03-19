# quadruped-controller

## Context

This project is the result of discussions a group of people had that are working on [Mini Pupper] (https://www.mangdang.net)

## Objectives

Produce software that will drive a quadruped robot.

There are already many libraries available, many of them as open source. A valid product of this project might be to pick a particular library or to combine several existing libraries.

But writing everything from scratch just as a learning exercise is also an option.

## Assumptions

We assume the quadruped we want to work on has 12 doF and exposes an API that takes 12 values to set the position of the 12 motors. We also assume that the API allows to query the robots capabilities but we do not specify any particular sensor that the robot must have.

We further assume that we will provide an API to a higher level controller that takes as input a speed expressed as a 3D vector. Other API calls are optional.

## Rules of Engagements

This effort should work with any 12 dof quadruped and is not limited to Mini Pupper. If you want to participate create a folder with your Github user name and put any document you want to share in this folder. Then create a pull request and I will merge your content and make you a collaborator.

You are free to use any format you want within your directory. It will be helpful if you chose a file format that others can open as well. Text files is preferred, pdf should be good as well, all other formats are subject to your good judgement.

It also helps to provide documents in a language that others can understand. Using English is a good bet but if you are more at easy to express yourself in any other language please do so. We will see how much automated translation will help.

## Phases

We should break down the project in several phases, the phases are subject to changes as we see fit. To start with I suggest:

- Idea gathering
- Reseaach what is availble 
- Prototyping, implemention and testing
