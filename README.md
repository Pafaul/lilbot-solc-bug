# lilbot-solc-bug
Files for ton solidity compiler bug report

sol files:\
lilbot_bug.sol - original contract that causes segmentation fault \
lilbot.1.sol - segmentation fault \
lilbot.2.sol - solc works normal \
lilbot.3.sol - segmentation fault 

diff files:\
diff_1_2 -> diff lilbot.1.sol lilbot.2.sol \
diff_2_3 -> diff lilbot.2.sol lilbot.3.sol \
diff_1_3 -> diff lilbot.1.sol lilbot.3.sol
