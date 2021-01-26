# SteemOps
## Steemit: a blockchain-based social media platform using the DPoS consensus protocol
Advancements in distributed ledger technologies are driving the rise of blockchain-based social media platforms such as [*Steemit*](https://steemit.com/), where no single entity can take control of the information and users can receive cryptocurrency as rewards for creating or curating high-quality contents. 

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

## *SteemOps* dataset download
The *SteemOps* dataset is available for downloading at: 

## *SteemOps* dataset paper
Please find detailed instructions of the *SteemOps* dataset in our recently published paper **'SteemOps: Extracting and Analyzing Key Operations in Steemit Blockchain-based Social Media Platform'**, which has been accepted by [**ACM CODASPY'21**](http://www.codaspy.org/2021/index.html) for publishing.

## Related papers
The following papers used the *SteemOps* dataset in their research. You may also find them interesting.
- Li, Chao, and Balaji Palanisamy. "[**Incentivized blockchain-based social media platforms: A case study of steemit**](https://www.researchgate.net/profile/Chao_Li146/publication/334159420_Incentivized_Blockchain-based_Social_Media_Platforms_A_Case_Study_of_Steemit/links/5d25f3ba458515c11c234419/Incentivized-Blockchain-based-Social-Media-Platforms-A-Case-Study-of-Steemit.pdf)." Proceedings of the 10th ACM Conference on Web Science. 2019.
  - This paper presents an empirical analysis of Steemit to understand and evaluate **the actual level of decentralization and the practical effects of cryptocurrency-driven reward system in the emerging social media platforms**. Our study reveals that the actual level of decentralization in Steemit is far lower than the ideal level, indicating that the DPoS consensus protocol may not be a desirable approach for establishing a highly decentralized social media platform. Our analysis of the underlying cryptocurrency transfer network on the blockchain reveals that more than 16% transfers of cryptocurrency in Steemit are sent to curators suspected to be bots and also finds the existence of an underlying supply network for the bots, both suggesting a significant misuse of the current reward system in Steemit.
- Li, Chao, and Balaji Palanisamy. "[**Comparison of decentralization in dpos and pow blockchains**](https://www.researchgate.net/publication/344372774_Comparison_of_Decentralization_in_DPoS_and_PoW_Blockchains)." International Conference on Blockchain. Springer, Cham, 2020.
  - This paper presents **a new comparison study of the level of decentralization in Bitcoin and Steem**, a prominent Delegated-Proof-of-Stake (DPoS) blockchain. Our study particularly focuses on analysing the power that decides the creators of blocks in the blockchain. We analyze the process of stake-weighted election of witnesses in DPoS and measure the actual stake invested by each stakeholder in Steem. We then compute the Shannon entropy of the distribution of computational power among miners in Bitcoin and the distribution of invested stake among stakeholders in Steem. Our analyses reveal that neither Bitcoin nor Steem is dominantly better than the other with respect to decentralization. 
