# Pet Store

*AAB Project Code 8ae9ef7e*

## Introduction

The Pet Store is a classic Object Oriented exercise, intended to show the importance of the 4 principles of OOP: Abstraction, Encapsulation, Inheritance, and Polymorphism.

## Instructions

Business requirements can take the form of required functionality, technical requirements, and are always subject to change based on the needs of the business.

When working through requirements, try to get one to work at a time. Don't try to get everything to work in one go. Instead, get one requirement completed, commit your code to GitHub, then start on the second. There are several reasons we recommend this:

1. A running application that does some of the requirements is better than a non-running application that might do all of them.
1. Source control is our friend! Constant commits and pushes will keep you from losing your code!
1. Sometimes a new requirement will force a major change to the code. If it doesn't work out, it's easy to roll back to a previous commit that did work!
1. Visibility! If you are committing code, mentors and others are able to view your code and provide help and suggestions. If it only exists on your computer, we can't see it!

## Requirements

> Note: None of the data for this app needs to be persisted. It can all exist entirely in memory, and be deleted when the application closes.

1. A `PetStore.exe` file the can be run on a Windows machine
1. A menu that allows users to:
    - View all available pets
    - Search pets by type/breed
    - Add a pet
1. View all available pets
    - Show all pets available for adoption
    - Prints them in alphabetical order
    - Shows the following data
        - Name
        - Animal Type (Cat, Dog, Bird)
        - Breed (German Shepherd, Bulldog, Maine Coon, Scottish Fold)
        - Age
    - Allows user to:
        - Select a pet for more details
        - Go back to main menu
1. Search pets by type/breed
    - Takes an input from the user
    - Displays all the pets that contain the input in either their type or breed
    - Display and options the same as view all
1. Add a pet
    - Takes the following input from the user about the pet:
       - Name
       - Type
       - Breed
       - Age
       - Description
    - Adds the pet to the list of available pets
1. Pet details
    - Shows the details about this pet. Details include:
        - Name
        - Type
        - Breed
        - Age
        - Description 
    - Allows user to:
        - Ask pet to speak
            - Pet should speak, then return to menu
        - Adopt the pet
            - Removes the pet from the list of available pets
        - Go back to main menu
1. Pet Speaking:
    - Dog: "Woof Woof!"
    - Cat: "Meow!"
    - Bird: "Chirp Chirp"

## Stretch Goals

1. Allow users to log in
1. Different breeds can speak differently
    - Dogs:
        - German Shepherd: "Vow-vow"
        - Great Dane: "Boof"
    - Cats:
        - Maine Coon: "Purr!"
    - Birds:
        - Parrot: "Hello! Hello!"
        - Owl: "Hoot Hoot!"
