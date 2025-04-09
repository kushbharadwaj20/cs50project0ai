# degrees.py
# 
# Project: Degrees of Separation (CS50AI)
#
# Description:
# This program identifies the shortest path of connection (degrees of separation) 
# between two actors in a movie database using a graph search algorithm, such as 
# Breadth-First Search (BFS). The script takes command-line inputs to specify the
# source actor and the target actor, and it outputs the connection path or informs 
# if no connection is found.
#
# Usage:
# To run the program, execute it in the terminal with two arguments:
# `python degrees.py source_actor_name target_actor_name`
#
# Example:
# `python degrees.py "Kevin Bacon" "Tom Hanks"`
# The above command finds the shortest path of connection between Kevin Bacon and Tom Hanks.
#
# Files:
# - `large/` and `small/` directories: Contain the CSV files with the movie database 
#   used to build the graph.
# - `util.py`: Includes utility functions for graph traversal and data structures 
#   like queue implementation.
#
# Author: CS50AI Team (Include your name if you're modifying it)
# Date: (Specify the date you are working on this project)
#
# Notes:
# - Ensure to handle errors gracefully, such as invalid actor names or no path between actors.
# - Large datasets may require optimization for performance.
# 
# Academic Integrity:
# Follow CS50's guidelines for academic honesty when using or modifying this code.
