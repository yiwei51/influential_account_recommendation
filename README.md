# influential_account_recommendation

Dataset for recommending influential accounts on social media

Yiwei Zhang, Xueting Wang, Toshihiko Yamasaki. Which account will you follow? Recommending influential accounts on social media. Multimed Tools Appl (2023). https://doi.org/10.1007/s11042-023-14538-3

We only provide the test data in this repository due to the large file size.
The full dataset will be released using Google drive. Please contact the following address: jinyuzyw@gmail.com

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



