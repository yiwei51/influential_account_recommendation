# influential_account_recommendation

Dataset for recommending influential accounts on social media

We only provide the test data in this repository due to the large file size.
The full dataset will be released using Google drive.

----------------------

Brand dataset


Nodes information file format: node id, node name  (split by space)

- nodes_id_name.txt

  File for nodes in the brand dataset.


Edges list file format: node id, node id, weight (split by space)

- brand_user.edgelist

  File for the edges between brands and users.
  
- test_brand_user.edgelist

  File for the edges between brands and test users.
  
- user_tag.edgelist

  File for the edges between users and tags.
  
- tag_tag.edgelist

  File for the edges between tags and tags.


----------------------

Influencer dataset

Nodes information file format: node id, node name  (split by space)

- nodes_id_name.txt

  File for nodes in the influencer dataset.


Edges list file format: node id, node id, weight (split by space)

- influence_user.edgelist

  File for the edges between influences and users.

- test_influencer_user.edgelist

  File for the edges between influences and test users.

- user_tag.edgelist

  File for the edges between users and tags.

- tag_tag.edgelist

  File for the edges between tags and tags.



