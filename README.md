#Social Network Code For CS350

##Prerequisites
An Internet Connection

#MichaelLogin File Structure

###User

##Description

The User class is the data management for individual users well as friend and post management.
It is important to note that no password was required in the specifications thus a password was
was deemed as fluf and not added to the project.
  
*Public Variables
  *id
      *holds user Id as an int.
  *name
      *string holding the registered name under the id

*Public Functions
  *getPosts
      *call to get all posts that are contained under a user ID
      
  *getFriends
      *call to get all friends are stored under a user ID
      
  *setFriends
      *used to add or delete a friend from the users Friends List by ID 
      (both the friend and the users ID's are requierd
      
  *getName
    *gets the name stored under a Users Id
    
  *setName
    *used to make the name that is stored under the users ID
  *getID
    *Gets the int used as the wanted ID
    
  *addPost
    *used to make the title and text in a post
    (importent to note that this varaible is overloaded to be able to post to friends Post list under
    diffrent users ID that is not the owner of the list being posted to)
  *addPost
    *used to make the title and text in a post to another users post list


##Post

###Description

The Post class manages data for all posts indivually.

*Public Variables
  *getText
      *returns String Text
      *Used to hold the body of the Post stored under the title and author
  *SetText
  *getAuthorId
      *returns Int authorId
      *used to hold the Id of the author of the post
      *used in posting to ones own posts and posting to other peoples posts lists.
  *setAuthorId
      
*Public Functions
  *Post
    *holds the authorId, Title and Text of Posts

##Server

###Description
*Public Variables

##PassHash

###Description


*Private Variables

*Public Functions

##social_network

###Description

The main program with all of the calls, separated into it's own class for ease of use.

*Public Variables

*Public Functions


#social_network_test File Structure

##social_network_test

###Description

The testing class for the social_network.cs file.

For each function in the social_network class, there is a corresponding test_function that asserts that it return either true, or not null for functions that return a non-boolean value.
