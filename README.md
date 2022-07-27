# Ops-Challenge

## Objectives
* Write a script that prints the login history of users on this computer.
"lastlog"
 ![image](https://user-images.githubusercontent.com/16893161/181377881-bcd88065-985f-4f3b-a49a-3fab41d937b4.png)

*  "last"


![image](https://user-images.githubusercontent.com/16893161/181378884-4d315241-de4b-43a3-be02-6ff4ae541d14.png)




function history {
	echo "$(last)"
}



#!/bin/bash

# Script: Ops 201 Class 03 Ops Challenge Solution
# Author: sujan thapa magar
# Date of latest revision: 27 July 2022
# Purpose: Show login history
function history {
	echo "$(last)"
}

#this calls history
history
