



1 test project ?

This mode is not for creating the test... this mode is for when your test is ok and you want to start it remotly.

List tests as tree view and you can run the test you want or all or a group.


let's start with 1 test

Main questions:

- how to securely transfer this test into the server ?
=> one file == through mqtt but does not work with python requirement (need docker image ? => need internet)

- how to adapt remote IP to local IP ? 
=> env variables ok




user provide a test repo well formated with a dockerfile
the interface clone this repo
build the docker image
list tests for the user
allow the user to run a test or get the status

