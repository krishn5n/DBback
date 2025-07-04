<h1 align="center">Dbback</h1>
<p align='Center'>
 CLI Tool for clean and easy way of managing databases
</p>
<br></br>
The goal of this project is to ensure we can revert the problems made by an intern at a DB level like  <code>Truncate table</code>.
<br></br>
The tech stack is using <b>python</b> as a programming language and using <b>Click</b> as a framework while using rich library for styling table for clean views
<br></br>
For ease there are mainly 3 commands being add, delete and list for all groups in the Tool which are explained below
<h2>Groups</h2>
<h3>1. Connection</h3>
The First group for estabilishing connections to the DB for esnsuring we can track the tables. This is the first step to later track and maintain the tables. Details required are
    <ol type='1'> 
        <li>Project Name for ID
        <li> DB type currently MySQL
        <li> Host and Port for Connections
        <li> Username and Password
        <li> DB Name
    </ol>
    The commands possible are
    <ol>
        <li> add
        <li> delete
        <li> list
    </ol>

<h3>2. Table</h3>
For adding tables to the connections that we have established already. Here we simply establish a table for storing snapshots and is a necessary step as well.The commands possible are
    <ol>
        <li> add
        <li> delete
        <li> list
    </ol>

<h3>3. Snapshot</h3>
Finally having created a connection and listed tables, we can take snapshots and store them for later use.
    <ol>
        <li> add
        <li> list
        <li> restore
    </ol>
    A unique ID is given to each snapshot during its <i>addition</i> and can be visible when <i>listed</i> , this ID is used to restore and taken as an input.

<h2>Additional Informations</h2>
A folder is created in local C drive for storing the metadata for each user and also the snapshots taken. In further versions , we can remove the local usage and go for a cloud based approach.

<h2>Scope for Improvement</h2>
Following can be implemented in further versions
<ol>
    <li> More Database Options
    <li> Ability to use snapshots remotely
    <li> Cloud based storage of Snapshots
</ol>