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
- **value-tansfer operation dataset (VOD)**:
  - **tranfer**: users transfer *STEEM/SBD* to other users;
  - **tansfer_to_vesting**: users transfer *STEEM/SBD* to *VESTS*;
  - **delegate_vesting_shares**: users delegate *VESTS* to other users;
  - **withdraw_vesting**: users transfer *VESTS* to *STEEM*.

## Dataset link

## *SteemOps* dataset paper
Please find detailed instructions of the *SteemOps* dataset in our recently published paper **'SteemOps: Extracting and Analyzing Key Operations in Steemit Blockchain-based Social Media Platform'**, which has been accepted by [**ACM CODASPY'21**](http://www.codaspy.org/2021/index.html) for publishing.

## Related papers
The following papers used the *SteemOps* dataset in their research. You may also find them interesting.
- Li, Chao, and Balaji Palanisamy. "[**Incentivized blockchain-based social media platforms: A case study of steemit**.](https://www.researchgate.net/profile/Chao_Li146/publication/334159420_Incentivized_Blockchain-based_Social_Media_Platforms_A_Case_Study_of_Steemit/links/5d25f3ba458515c11c234419/Incentivized-Blockchain-based-Social-Media-Platforms-A-Case-Study-of-Steemit.pdf)**" Proceedings of the 10th ACM Conference on Web Science. 2019.
- Li, Chao, and Balaji Palanisamy. "Comparison of decentralization in dpos and pow blockchains." International Conference on Blockchain. Springer, Cham, 2020.
