# teamwork-analysis

## Contents

* [Summary](#summary)
* [Contributors](#contributors)
* [MVP Objectives](#mvp-objectives)
* [Functionality](#functionality)
* [Architecture](#architecture)
* [Past Issues](#past-issues)
* [Known Bugs](#known-bugs)
* [References](#references)

## Summary

Our project consists of two main parts. The first part of our project is data visualization and teamwork research. We are using the CS 121 teamwork survey as our basis. From this, we will develop a web interface that shows data from this survey. We will research the best, most helpful graphs to show. To enable us to do this, we will need a database, a method for the user to upload to the database, and a way to construct graphs from this data. The second part of our project consists of researching team dynamics. We are going to research many different teamwork strategies to fine tune the CS 121 survey, as well as estimate what consists of a good team.

## Contributers

* Nathan Justin 
* Sara McAllister
* Maeve Murphy
* Reagan Smith

## MVP objective

For our minimum viable product (MVP), we expect to deliver two main functionalities: a method to import survey data and a basic graphical representation of the data. To import survey data, we plan on allowing the user to enter a json with multiple people’s results from the survey. This data will then be stored in our database. The second part of our MVP is graphical interpretations of the data. For the MVP, we plan on visualizing the overall results of the data so that the user can see the proportions of challenger to communicator to collaborator to contributor for the class. We also plan to have a set of graphs that show a person’s individual scores and a set of graphs that will show the distribution of responses to each question. 

## Functionality

* We will provide an interface where, after submitting their survey, users can see any relevant charts, graphs, and information.
* We will have an analysis of survey results that is useful in helping students find compatible teammates and interesting patterns or characteristics in the data that the instructor can use. The analysis will be backed up by research.
* We will provide algorithms that can interpret the data in multiple ways.

## Architecture

The data processing will be done with Python using numpy. The processor will access the database which will be implemented in SQLite while we discuss data privacy concerns. Ruby will use the Python scripts to display the resulting graphs on a web page a user can access and add data too.
There will be a simple database to hold JSON strings, some Python scripts that access the data to build graphs using numpy, and a Ruby page to display these graphs when asked for. Initially, there will only be one graph that Python needs to construct and Ruby needs to display.

## Past Issues

None.

## Known Bugs

Currently does not work.

## References

### Database Setup

* https://stackoverflow.com/questions/2098131/rails-how-to-list-database-tables-objects-using-the-rails-console
* https://www.justinweiss.com/articles/creating-easy-readable-attributes-with-activerecord-enums/
