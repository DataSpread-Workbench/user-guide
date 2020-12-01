---
description: 'http://dataspread.io'
---

# Getting Started

## Intro

DataSpread Workbench is a new application that combines a fully featured spreadsheet user interface with a powerful database backend. It can be used with your existing SQL databases, but adds all the functionality of a spreadsheet including formula evaluation, multiple simultaneous users, formatting, and a lot more! On top of that, you can use it without modifying your original database at all!

#### Key terminology:

* A **DataSpread** is the equivalent of an Excel workbook. It's associated with a SQL database that you provide. It can contain multiple sheets.
* A **Sheet**, ****as the name implies, ****is similar to a sheet in Excel. It can be used like a normal spreadsheet, except it can also be optionally backed by an SQL table, in which case the data for the top left area will come from the SQL table.

## Login/Sign Up

When you first visit [dataspread.io](http://dataspread.io), you'll be greeted with the following screen. Pick a username and password and sign up to create an account.

![](.gitbook/assets/image%20%2810%29.png)

## Create a DataSpread

After signing up, click on the green plus icon in the bottom right corner to create a DataSpread:

![](.gitbook/assets/image%20%2812%29.png)

First, you'll need to add a set of credentials to connect to your database.

![](.gitbook/assets/image%20%2818%29.png)

Then select that set of credentials and click on `Next`. You should see a list of databases that can be accessed using those credentials. Select the one you want to use, and also specify a name for your [DataSpread](./#key-terminology).

![](.gitbook/assets/image%20%284%29.png)

Click on the DataSpread you just created and then add your first sheet by selecting the table you want to associate it with as well as a column from that table that you want to use as the ID. The ID is used to maintain a consistent ordering for the rows \(since SQL tables don't guarantee order by default\).

![](.gitbook/assets/image%20%2813%29.png)

And that's all! You should see something similar to this:

![](.gitbook/assets/image%20%2817%29.png)

