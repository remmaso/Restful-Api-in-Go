# Restful-Api-in-Go
This is a sample restful api in go

# Task

Design API endpoints.
Create a folder for your code.
Create the data.
Write a handler to return all items.
Write a handler to add a new item.
Write a handler to return a specific item.

# Prerequisites
An installation of Go 1.16 or later. For installation instructions, see Installing Go.
A tool to edit your code. Any text editor you have will work fine.
A command terminal. Go works well using any terminal on Linux and Mac, and on PowerShell or cmd in Windows.
The curl tool. On Linux and Mac, this should already be installed. On Windows, it’s included on Windows 10 Insider build 17063 and later. For earlier Windows versions, you might need to install it. For more, see Tar and Curl Come to 

Design API endpoints
You’ll build an API that provides access to a store selling vintage recordings on vinyl. So you’ll need to provide endpoints through which a client can get and add albums for users.

When developing an API, you typically begin by designing the endpoints. Your API’s users will have more success if the endpoints are easy to understand.

Here are the endpoints you’ll create in this tutorial.

/albums

GET – Get a list of all albums, returned as JSON.
POST – Add a new album from request data sent as JSON.

