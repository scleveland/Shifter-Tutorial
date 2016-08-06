# Docker tutorial

SC 16

## Prerequisites

This is hands-on tutorial.  Participants should bring a laptop and pre-install software in advance to make
the best use of time during the tutorial.  Participants should [install Docker](https://docs.docker.com/) locally on their laptop.  Alternatively, participants can have remote access to a system that has docker installed and allows them to run docker commands.  In addition,
users should install an ssh client for their operating system so they can access the HPC resources we will
use for the Shifter portion of the tutorials.  We will attempt to have some alternative options for users
who have issues installing Docker.

## Agenda

- 8:30: [Welcome and Intro to Docker](00-docker.md)
- 9:00: [First hands-on](01-hands-on.md)
  - [Pulling and running an existing image](01-hands-on.md#pulling-and-running-an-existing-image)
  - [Making changes and committing them](01-hands-on.md#making-changes-and-committing-them)
  - [Creating and building a Dockerfile](01-hands-on.md#creating-and-building-a-dockerfile)
  - [Pushing a Dockerfile to dockerhub](01-hands-on.md#pushing-a-dockerfile-to-dockerhub)
- 9:30: Break (check time on this)
  - Distribute NERSC logins - Please obtain a NERSC login from tutorial staff
- 10:00: [Intro to Shifter and how it is different](02-shifter.md)
- 10:30: [Second hands-on - Shifter](03-hands-on.md)
  - [Logging in to NERSC](03-hands-on.md#logging-in-to-nersc)
  - [Pulling an image](03-hands-on.md#pulling-an-image)
  - [Running an image interactively](03-hands-on.md#running-an-image-interactively)
  - [Submitting a Shifter batch job](03-hands-on.md#submitting-a-shifter-batch-job)
  - [Running a parallel Python MPI job](03-hands-on.md#running-a-parallel-python-mpi-job)
- 11:15: [Uses Cases in the Real World and Best Practices](04-use-cases.md)
  - [Reproducibility](04-use-cases.md#reproducibility)
  - [LHC, Astronomy](04-use-cases.md#lhc-astronomy)
- 11:30: [Final Hands-on](05-hands-on.md)
  - [Controlling layers and making builds faster](05-hands-on.d#controlling-layers-and-making-builds-faster)
  - [What goes in the image and what should stay out](05-hands-on.md#what-goes-in-the-image-and-what-should-stay-out)
  - [Bring us your problem](05-hands-on.md#bring-us-your-problem)
