TrelloWall
==========
Using the Trello client.js API

Show all cards from different boards that match specific filters. 

Filters:
--------
Those filters are set by url-parameters.  
													
* __board_organization__  
only load cards on boards from a specific organization					

* __card_members_username__  
only load cards with a specific member (by username)						

* __card_labels_name__  
only load cards with a specific label (by name) 								

Sample:
--------
__URL:__ http://freaken.de/trellowall/
													
* all cards from a specific organization  
http://freaken.de/trellowall/?board_organization=mycompany

* all cards with a specific member  
http://freaken.de/trellowall/?card_members_username=sampleuser						

* all cards with a specific label  
http://freaken.de/trellowall/?card_labels_name=samplelabel

* all cards with a specific label and user  
http://freaken.de/trellowall/?card_labels_name=samplelabel&card_members_username=sampleuser	

* all cards with a specific label from a specific organization  
http://freaken.de/trellowall/?card_labels_name=samplelabel&board_organization=mycompany
  
....