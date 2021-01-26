# SteemOps
## Steemit
Advancements in distributed ledger technologies are driving the rise of blockchain-based social media platforms such as [*Steemit*](https://steemit.com/), where users interact with each other in similar ways as conventional social networks. 

## SteemOps: a well-processed ready-to-use dataset for Steemit
We collect over 38 million blocks generated in *Steemit* during a 45 month time period from 2016/03 to 2019/11 and extract ten key types of operations performed by the users.
The results generate *SteemOps*, a new dataset that organizes over 900 million operations from *Steemit* into three sub-datasets:

- **social-network operation dataset (SOD)**: 
  - **comment**: users create posts, reply to posts or replies;
  - **vote**: users vote for posts;
  - **custom_json**: users follow other users, repost a blog.

- **witness-election operation dataset (WOD)**:
  - **witness_update**: users join the witness pool to be elected, witnesses in pool update their information;
  - **witness_vote**: users vote for witnesses by themselves;
  - **witness_proxy**: users cast votes to the same witnesses voted by another user by setting that user as their election proxy.

- **value-tansfer operation dataset (VOD)**: transfer, transfer_to_vesting, delegate_vesting_shares, withdraw_vesting.
  - **comment**: users transfer *STEEM/SBD* to other users;
  - **vote**: users transfer *STEEM/SBD* to *VESTS*;
  - **vote**: users delegate *VESTS* to other users;
  - **custom_json**: users transfer *VESTS* to *STEEM*.

## Dataset link

## Dataset paper
Please find detailed instructions of the *SteemOps* dataset in our recently published paper **'SteemOps: Extracting and Analyzing Key Operations in Steemit Blockchain-based Social Media Platform'**, which has been accepted by [**ACM CODASPY'21**](http://www.codaspy.org/2021/index.html) for publishing.

## Related papers
