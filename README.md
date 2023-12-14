# EOSIO-Voting-Data

This repository includes the voting data of EOSIO from the first 135,000,000 blocks. The file ``EOS_voting_data_135000000_blocks.rar`` contains 4 kinds of data. 

- ``block.csv`` records the block producer of each block. 
- ``reg_bp_x.csv`` stores the records of calling the ``regproducer`` and ``unregprod`` interfaces. 
- ``user_net_x.csv`` stores the records of account creation. 
- ``voting_action_x.csv`` stores the records of calling the ``delegatebw`` ,``undelegatebw``, ``voteproducer`` interfaces. 



Our analysis results are presented in the paper ``From Decentralization to Oligopoly: A Data-driven Analysis of Decentralization Evolution and Voting Behaviors on EOSIO``
