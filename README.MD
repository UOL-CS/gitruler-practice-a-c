<!--
Marked Style: Github
-->

# GitRuler Practice A-C

This repository provides you with practice of the skills that you have learned in exercises A to C. The topics that are tested in this exercise are:

1. Committing new and existing files
2. Create commits that contains only specific files
3. Ignoring files
4. Finding the status of files in the working directory.

## Introduction

This exercise involves a car salesman who has a several cars that he is selling. Each car has a file in the `files/cars`. The name of the file is the make of car followed by the registration number.

## Instructions

1. After cloning the repository change into the directory on a [command line](https://www.techopedia.com/definition/3337/command-line-interface-cli).
2. Run gitruler to initialise the exercise.

## Tidying up the car files

Currently all of the files are in a single folder. Also some files have been created or changed but not committed. Our first job is to commit the changes, then to tidy up the files.

1. Commit the changes to existing files with the message "Update car details for bank holiday sale".
2. Commit the new files with the message "Add new cars for bank holiday sale"

Our salesman want a separate folder for luxury cars. 

1. Create a folder inside `files/cars` called `luxury`.
2. Move all `Mercedes` and `Ferrari` files to the luxury folder and commit this change with the message "Move luxury cars to own folder"

## Stop selling Italian cars

Our salesman decides he no longer wants to sell Italian cars. He wants to remove the files for existing ones, and set up git to ignore all future Italian cars.

1. Remove from git all `Fiat` and `Ferrari`.
2. Tell git to ignore all `Fiat` and `Ferrari` cars.

## Submitting the results

Once the exercise is complete, push this repository to the remote. If there are multiple branches for an exercise, make sure that you push them all. 

To ensure that you have you correctly pushed everything that you need to, you could clone the remote repository into a separate folder and re-run gitruler.
