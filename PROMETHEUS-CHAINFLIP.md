# Example Chainflip Prometheus Output

```text
# HELP substrate_block_height Block height info of the chain
# TYPE substrate_block_height gauge
substrate_block_height{status="best"} 140434
substrate_block_height{status="finalized"} 140431
substrate_block_height{status="sync_target"} 140434
# HELP substrate_block_verification_and_import_time Time taken to verify and import blocks
# TYPE substrate_block_verification_and_import_time histogram
substrate_block_verification_and_import_time_bucket{le="0.005"} 0
substrate_block_verification_and_import_time_bucket{le="0.01"} 2839
substrate_block_verification_and_import_time_bucket{le="0.025"} 7982
substrate_block_verification_and_import_time_bucket{le="0.05"} 8938
substrate_block_verification_and_import_time_bucket{le="0.1"} 9050
substrate_block_verification_and_import_time_bucket{le="0.25"} 9055
substrate_block_verification_and_import_time_bucket{le="0.5"} 9059
substrate_block_verification_and_import_time_bucket{le="1"} 9061
substrate_block_verification_and_import_time_bucket{le="2.5"} 9061
substrate_block_verification_and_import_time_bucket{le="5"} 9062
substrate_block_verification_and_import_time_bucket{le="10"} 9062
substrate_block_verification_and_import_time_bucket{le="+Inf"} 9062
substrate_block_verification_and_import_time_sum 147.2200280879997
substrate_block_verification_and_import_time_count 9062
# HELP substrate_block_verification_time Time taken to verify blocks
# TYPE substrate_block_verification_time histogram
substrate_block_verification_time_bucket{result="success",le="0.005"} 8846
substrate_block_verification_time_bucket{result="success",le="0.01"} 9011
substrate_block_verification_time_bucket{result="success",le="0.025"} 9055
substrate_block_verification_time_bucket{result="success",le="0.05"} 9061
substrate_block_verification_time_bucket{result="success",le="0.1"} 9061
substrate_block_verification_time_bucket{result="success",le="0.25"} 9061
substrate_block_verification_time_bucket{result="success",le="0.5"} 9061
substrate_block_verification_time_bucket{result="success",le="1"} 9061
substrate_block_verification_time_bucket{result="success",le="2.5"} 9061
substrate_block_verification_time_bucket{result="success",le="5"} 9062
substrate_block_verification_time_bucket{result="success",le="10"} 9062
substrate_block_verification_time_bucket{result="success",le="+Inf"} 9062
substrate_block_verification_time_sum{result="success"} 25.09195755399994
substrate_block_verification_time_count{result="success"} 9062
# HELP substrate_build_info A metric with a constant '1' value labeled by name, version
# TYPE substrate_build_info gauge
substrate_build_info{name="greasy-bee-4929",version="0.1.0-2b496be2-x86_64-linux-gnu"} 1
# HELP substrate_database_cache_bytes RocksDB cache size in bytes
# TYPE substrate_database_cache_bytes gauge
substrate_database_cache_bytes 0
# HELP substrate_finality_grandpa_communication_gossip_validator_messages Number of messages validated by the finality grandpa gossip validator.
# TYPE substrate_finality_grandpa_communication_gossip_validator_messages counter
substrate_finality_grandpa_communication_gossip_validator_messages{action="discard",message="catch_up_request"} 10
substrate_finality_grandpa_communication_gossip_validator_messages{action="discard",message="commit"} 13813
substrate_finality_grandpa_communication_gossip_validator_messages{action="discard",message="neighbor"} 2255863
substrate_finality_grandpa_communication_gossip_validator_messages{action="discard",message="vote"} 617
substrate_finality_grandpa_communication_gossip_validator_messages{action="keep",message="vote"} 1155585
substrate_finality_grandpa_communication_gossip_validator_messages{action="process_and_discard",message="catch_up"} 2
substrate_finality_grandpa_communication_gossip_validator_messages{action="process_and_discard",message="commit"} 9963
# HELP substrate_finality_grandpa_precommits_total Total number of GRANDPA precommits cast locally.
# TYPE substrate_finality_grandpa_precommits_total counter
substrate_finality_grandpa_precommits_total 41852
# HELP substrate_finality_grandpa_prevotes_total Total number of GRANDPA prevotes cast locally.
# TYPE substrate_finality_grandpa_prevotes_total counter
substrate_finality_grandpa_prevotes_total 41853
# HELP substrate_finality_grandpa_round Highest completed GRANDPA round.
# TYPE substrate_finality_grandpa_round gauge
substrate_finality_grandpa_round 20025
# HELP substrate_finality_grandpa_until_imported_waiting_messages_number Number of finality grandpa messages waiting within the until imported queue.
# TYPE substrate_finality_grandpa_until_imported_waiting_messages_number gauge
substrate_finality_grandpa_until_imported_waiting_messages_number 0
# HELP substrate_import_queue_blocks_submitted Number of blocks submitted to the import queue.
# TYPE substrate_import_queue_blocks_submitted counter
substrate_import_queue_blocks_submitted 38550
# HELP substrate_import_queue_justifications_submitted Number of justifications submitted to the import queue.
# TYPE substrate_import_queue_justifications_submitted counter
substrate_import_queue_justifications_submitted 1
# HELP substrate_import_queue_processed_total Blocks processed by import queue
# TYPE substrate_import_queue_processed_total counter
substrate_import_queue_processed_total{result="success"} 21297
# HELP substrate_issued_light_requests Number of light client requests that our node has issued.
# TYPE substrate_issued_light_requests counter
substrate_issued_light_requests 0
# HELP substrate_justification_import_time Time taken to import justifications
# TYPE substrate_justification_import_time histogram
substrate_justification_import_time_bucket{le="0.005"} 0
substrate_justification_import_time_bucket{le="0.01"} 1
substrate_justification_import_time_bucket{le="0.025"} 1
substrate_justification_import_time_bucket{le="0.05"} 1
substrate_justification_import_time_bucket{le="0.1"} 1
substrate_justification_import_time_bucket{le="0.25"} 1
substrate_justification_import_time_bucket{le="0.5"} 1
substrate_justification_import_time_bucket{le="1"} 1
substrate_justification_import_time_bucket{le="2.5"} 1
substrate_justification_import_time_bucket{le="5"} 1
substrate_justification_import_time_bucket{le="10"} 1
substrate_justification_import_time_bucket{le="+Inf"} 1
substrate_justification_import_time_sum 0.006639387
substrate_justification_import_time_count 1
# HELP substrate_network_gossip_expired_messages_total Number of expired messages by the gossip service.
# TYPE substrate_network_gossip_expired_messages_total counter
substrate_network_gossip_expired_messages_total 1282395
# HELP substrate_network_gossip_registered_messages_total Number of registered messages by the gossip service.
# TYPE substrate_network_gossip_registered_messages_total counter
substrate_network_gossip_registered_messages_total 1282503
# HELP substrate_node_roles The roles the node is running as
# TYPE substrate_node_roles gauge
substrate_node_roles 4
# HELP substrate_number_leaves Number of known chain leaves (aka forks)
# TYPE substrate_number_leaves gauge
substrate_number_leaves 1
# HELP substrate_process_start_time_seconds Number of seconds between the UNIX epoch and the moment the process started
# TYPE substrate_process_start_time_seconds gauge
substrate_process_start_time_seconds 1640391531
# HELP substrate_proposer_block_constructed Histogram of time taken to construct new block
# TYPE substrate_proposer_block_constructed histogram
substrate_proposer_block_constructed_bucket{le="0.005"} 223
substrate_proposer_block_constructed_bucket{le="0.01"} 498
substrate_proposer_block_constructed_bucket{le="0.025"} 610
substrate_proposer_block_constructed_bucket{le="0.05"} 636
substrate_proposer_block_constructed_bucket{le="0.1"} 650
substrate_proposer_block_constructed_bucket{le="0.25"} 657
substrate_proposer_block_constructed_bucket{le="0.5"} 657
substrate_proposer_block_constructed_bucket{le="1"} 657
substrate_proposer_block_constructed_bucket{le="2.5"} 657
substrate_proposer_block_constructed_bucket{le="5"} 657
substrate_proposer_block_constructed_bucket{le="10"} 657
substrate_proposer_block_constructed_bucket{le="+Inf"} 657
substrate_proposer_block_constructed_sum 7.177205203999992
substrate_proposer_block_constructed_count 657
# HELP substrate_proposer_number_of_transactions Number of transactions included in block
# TYPE substrate_proposer_number_of_transactions gauge
substrate_proposer_number_of_transactions 1
# HELP substrate_ready_transactions_number Number of transactions in the ready queue
# TYPE substrate_ready_transactions_number gauge
substrate_ready_transactions_number 0
# HELP substrate_rpc_calls_finished Number of processed RPC calls (unique un-batched requests)
# TYPE substrate_rpc_calls_finished counter
substrate_rpc_calls_finished{is_error="false",method="author_submitExtrinsic",protocol="ws"} 56
substrate_rpc_calls_finished{is_error="true",method="author_submitExtrinsic",protocol="ws"} 441
substrate_rpc_calls_finished{is_error="true",method="cf_p2p_subscribeMessages",protocol="ws"} 3
substrate_rpc_calls_finished{is_error="true",method="chain_getBlockHash",protocol="ws"} 3
substrate_rpc_calls_finished{is_error="true",method="chain_getFinalizedHead",protocol="ws"} 3
substrate_rpc_calls_finished{is_error="true",method="chain_getHeader",protocol="ws"} 3
substrate_rpc_calls_finished{is_error="true",method="chain_subscribeFinalizedHeads",protocol="ws"} 3
substrate_rpc_calls_finished{is_error="true",method="p2p_send_message",protocol="ws"} 3686
substrate_rpc_calls_finished{is_error="true",method="p2p_set_peers",protocol="ws"} 3
substrate_rpc_calls_finished{is_error="true",method="state_getMetadata",protocol="ws"} 3
substrate_rpc_calls_finished{is_error="true",method="state_getPairs",protocol="ws"} 3
substrate_rpc_calls_finished{is_error="true",method="state_getRuntimeVersion",protocol="ws"} 3
substrate_rpc_calls_finished{is_error="true",method="state_getStorage",protocol="ws"} 3
substrate_rpc_calls_finished{is_error="true",method="state_queryStorageAt",protocol="ws"} 9737
substrate_rpc_calls_finished{is_error="true",method="system_localPeerId",protocol="ws"} 3
# HELP substrate_rpc_calls_started Number of received RPC calls (unique un-batched requests)
# TYPE substrate_rpc_calls_started counter
substrate_rpc_calls_started{method="author_submitExtrinsic",protocol="ws"} 497
substrate_rpc_calls_started{method="cf_p2p_subscribeMessages",protocol="ws"} 3
substrate_rpc_calls_started{method="chain_getBlockHash",protocol="ws"} 3
substrate_rpc_calls_started{method="chain_getFinalizedHead",protocol="ws"} 3
substrate_rpc_calls_started{method="chain_getHeader",protocol="ws"} 3
substrate_rpc_calls_started{method="chain_subscribeFinalizedHeads",protocol="ws"} 3
substrate_rpc_calls_started{method="p2p_send_message",protocol="ws"} 3686
substrate_rpc_calls_started{method="p2p_set_peers",protocol="ws"} 3
substrate_rpc_calls_started{method="state_getMetadata",protocol="ws"} 3
substrate_rpc_calls_started{method="state_getPairs",protocol="ws"} 3
substrate_rpc_calls_started{method="state_getRuntimeVersion",protocol="ws"} 3
substrate_rpc_calls_started{method="state_getStorage",protocol="ws"} 3
substrate_rpc_calls_started{method="state_queryStorageAt",protocol="ws"} 9737
substrate_rpc_calls_started{method="system_localPeerId",protocol="ws"} 3
# HELP substrate_rpc_calls_time Total time [μs] of processed RPC calls
# TYPE substrate_rpc_calls_time histogram
substrate_rpc_calls_time_bucket{method="author_submitExtrinsic",protocol="ws",le="0.005"} 0
substrate_rpc_calls_time_bucket{method="author_submitExtrinsic",protocol="ws",le="0.01"} 0
substrate_rpc_calls_time_bucket{method="author_submitExtrinsic",protocol="ws",le="0.025"} 0
substrate_rpc_calls_time_bucket{method="author_submitExtrinsic",protocol="ws",le="0.05"} 0
substrate_rpc_calls_time_bucket{method="author_submitExtrinsic",protocol="ws",le="0.1"} 0
substrate_rpc_calls_time_bucket{method="author_submitExtrinsic",protocol="ws",le="0.25"} 0
substrate_rpc_calls_time_bucket{method="author_submitExtrinsic",protocol="ws",le="0.5"} 0
substrate_rpc_calls_time_bucket{method="author_submitExtrinsic",protocol="ws",le="1"} 0
substrate_rpc_calls_time_bucket{method="author_submitExtrinsic",protocol="ws",le="2.5"} 0
substrate_rpc_calls_time_bucket{method="author_submitExtrinsic",protocol="ws",le="5"} 0
substrate_rpc_calls_time_bucket{method="author_submitExtrinsic",protocol="ws",le="10"} 0
substrate_rpc_calls_time_bucket{method="author_submitExtrinsic",protocol="ws",le="+Inf"} 497
substrate_rpc_calls_time_sum{method="author_submitExtrinsic",protocol="ws"} 1576773
substrate_rpc_calls_time_count{method="author_submitExtrinsic",protocol="ws"} 497
substrate_rpc_calls_time_bucket{method="cf_p2p_subscribeMessages",protocol="ws",le="0.005"} 0
substrate_rpc_calls_time_bucket{method="cf_p2p_subscribeMessages",protocol="ws",le="0.01"} 0
substrate_rpc_calls_time_bucket{method="cf_p2p_subscribeMessages",protocol="ws",le="0.025"} 0
substrate_rpc_calls_time_bucket{method="cf_p2p_subscribeMessages",protocol="ws",le="0.05"} 0
substrate_rpc_calls_time_bucket{method="cf_p2p_subscribeMessages",protocol="ws",le="0.1"} 0
substrate_rpc_calls_time_bucket{method="cf_p2p_subscribeMessages",protocol="ws",le="0.25"} 0
substrate_rpc_calls_time_bucket{method="cf_p2p_subscribeMessages",protocol="ws",le="0.5"} 0
substrate_rpc_calls_time_bucket{method="cf_p2p_subscribeMessages",protocol="ws",le="1"} 0
substrate_rpc_calls_time_bucket{method="cf_p2p_subscribeMessages",protocol="ws",le="2.5"} 0
substrate_rpc_calls_time_bucket{method="cf_p2p_subscribeMessages",protocol="ws",le="5"} 0
substrate_rpc_calls_time_bucket{method="cf_p2p_subscribeMessages",protocol="ws",le="10"} 0
substrate_rpc_calls_time_bucket{method="cf_p2p_subscribeMessages",protocol="ws",le="+Inf"} 3
substrate_rpc_calls_time_sum{method="cf_p2p_subscribeMessages",protocol="ws"} 1266
substrate_rpc_calls_time_count{method="cf_p2p_subscribeMessages",protocol="ws"} 3
substrate_rpc_calls_time_bucket{method="chain_getBlockHash",protocol="ws",le="0.005"} 0
substrate_rpc_calls_time_bucket{method="chain_getBlockHash",protocol="ws",le="0.01"} 0
substrate_rpc_calls_time_bucket{method="chain_getBlockHash",protocol="ws",le="0.025"} 0
substrate_rpc_calls_time_bucket{method="chain_getBlockHash",protocol="ws",le="0.05"} 0
substrate_rpc_calls_time_bucket{method="chain_getBlockHash",protocol="ws",le="0.1"} 0
substrate_rpc_calls_time_bucket{method="chain_getBlockHash",protocol="ws",le="0.25"} 0
substrate_rpc_calls_time_bucket{method="chain_getBlockHash",protocol="ws",le="0.5"} 0
substrate_rpc_calls_time_bucket{method="chain_getBlockHash",protocol="ws",le="1"} 0
substrate_rpc_calls_time_bucket{method="chain_getBlockHash",protocol="ws",le="2.5"} 0
substrate_rpc_calls_time_bucket{method="chain_getBlockHash",protocol="ws",le="5"} 0
substrate_rpc_calls_time_bucket{method="chain_getBlockHash",protocol="ws",le="10"} 0
substrate_rpc_calls_time_bucket{method="chain_getBlockHash",protocol="ws",le="+Inf"} 3
substrate_rpc_calls_time_sum{method="chain_getBlockHash",protocol="ws"} 7135
substrate_rpc_calls_time_count{method="chain_getBlockHash",protocol="ws"} 3
substrate_rpc_calls_time_bucket{method="chain_getFinalizedHead",protocol="ws",le="0.005"} 0
substrate_rpc_calls_time_bucket{method="chain_getFinalizedHead",protocol="ws",le="0.01"} 0
substrate_rpc_calls_time_bucket{method="chain_getFinalizedHead",protocol="ws",le="0.025"} 0
substrate_rpc_calls_time_bucket{method="chain_getFinalizedHead",protocol="ws",le="0.05"} 0
substrate_rpc_calls_time_bucket{method="chain_getFinalizedHead",protocol="ws",le="0.1"} 0
substrate_rpc_calls_time_bucket{method="chain_getFinalizedHead",protocol="ws",le="0.25"} 0
substrate_rpc_calls_time_bucket{method="chain_getFinalizedHead",protocol="ws",le="0.5"} 0
substrate_rpc_calls_time_bucket{method="chain_getFinalizedHead",protocol="ws",le="1"} 0
substrate_rpc_calls_time_bucket{method="chain_getFinalizedHead",protocol="ws",le="2.5"} 0
substrate_rpc_calls_time_bucket{method="chain_getFinalizedHead",protocol="ws",le="5"} 0
substrate_rpc_calls_time_bucket{method="chain_getFinalizedHead",protocol="ws",le="10"} 0
substrate_rpc_calls_time_bucket{method="chain_getFinalizedHead",protocol="ws",le="+Inf"} 3
substrate_rpc_calls_time_sum{method="chain_getFinalizedHead",protocol="ws"} 1681
substrate_rpc_calls_time_count{method="chain_getFinalizedHead",protocol="ws"} 3
substrate_rpc_calls_time_bucket{method="chain_getHeader",protocol="ws",le="0.005"} 0
substrate_rpc_calls_time_bucket{method="chain_getHeader",protocol="ws",le="0.01"} 0
substrate_rpc_calls_time_bucket{method="chain_getHeader",protocol="ws",le="0.025"} 0
substrate_rpc_calls_time_bucket{method="chain_getHeader",protocol="ws",le="0.05"} 0
substrate_rpc_calls_time_bucket{method="chain_getHeader",protocol="ws",le="0.1"} 0
substrate_rpc_calls_time_bucket{method="chain_getHeader",protocol="ws",le="0.25"} 0
substrate_rpc_calls_time_bucket{method="chain_getHeader",protocol="ws",le="0.5"} 0
substrate_rpc_calls_time_bucket{method="chain_getHeader",protocol="ws",le="1"} 0
substrate_rpc_calls_time_bucket{method="chain_getHeader",protocol="ws",le="2.5"} 0
substrate_rpc_calls_time_bucket{method="chain_getHeader",protocol="ws",le="5"} 0
substrate_rpc_calls_time_bucket{method="chain_getHeader",protocol="ws",le="10"} 0
substrate_rpc_calls_time_bucket{method="chain_getHeader",protocol="ws",le="+Inf"} 3
substrate_rpc_calls_time_sum{method="chain_getHeader",protocol="ws"} 968
substrate_rpc_calls_time_count{method="chain_getHeader",protocol="ws"} 3
substrate_rpc_calls_time_bucket{method="chain_subscribeFinalizedHeads",protocol="ws",le="0.005"} 0
substrate_rpc_calls_time_bucket{method="chain_subscribeFinalizedHeads",protocol="ws",le="0.01"} 0
substrate_rpc_calls_time_bucket{method="chain_subscribeFinalizedHeads",protocol="ws",le="0.025"} 0
substrate_rpc_calls_time_bucket{method="chain_subscribeFinalizedHeads",protocol="ws",le="0.05"} 0
substrate_rpc_calls_time_bucket{method="chain_subscribeFinalizedHeads",protocol="ws",le="0.1"} 0
substrate_rpc_calls_time_bucket{method="chain_subscribeFinalizedHeads",protocol="ws",le="0.25"} 0
substrate_rpc_calls_time_bucket{method="chain_subscribeFinalizedHeads",protocol="ws",le="0.5"} 0
substrate_rpc_calls_time_bucket{method="chain_subscribeFinalizedHeads",protocol="ws",le="1"} 0
substrate_rpc_calls_time_bucket{method="chain_subscribeFinalizedHeads",protocol="ws",le="2.5"} 0
substrate_rpc_calls_time_bucket{method="chain_subscribeFinalizedHeads",protocol="ws",le="5"} 0
substrate_rpc_calls_time_bucket{method="chain_subscribeFinalizedHeads",protocol="ws",le="10"} 0
substrate_rpc_calls_time_bucket{method="chain_subscribeFinalizedHeads",protocol="ws",le="+Inf"} 3
substrate_rpc_calls_time_sum{method="chain_subscribeFinalizedHeads",protocol="ws"} 6240
substrate_rpc_calls_time_count{method="chain_subscribeFinalizedHeads",protocol="ws"} 3
substrate_rpc_calls_time_bucket{method="p2p_send_message",protocol="ws",le="0.005"} 0
substrate_rpc_calls_time_bucket{method="p2p_send_message",protocol="ws",le="0.01"} 0
substrate_rpc_calls_time_bucket{method="p2p_send_message",protocol="ws",le="0.025"} 0
substrate_rpc_calls_time_bucket{method="p2p_send_message",protocol="ws",le="0.05"} 0
substrate_rpc_calls_time_bucket{method="p2p_send_message",protocol="ws",le="0.1"} 0
substrate_rpc_calls_time_bucket{method="p2p_send_message",protocol="ws",le="0.25"} 0
substrate_rpc_calls_time_bucket{method="p2p_send_message",protocol="ws",le="0.5"} 0
substrate_rpc_calls_time_bucket{method="p2p_send_message",protocol="ws",le="1"} 0
substrate_rpc_calls_time_bucket{method="p2p_send_message",protocol="ws",le="2.5"} 0
substrate_rpc_calls_time_bucket{method="p2p_send_message",protocol="ws",le="5"} 0
substrate_rpc_calls_time_bucket{method="p2p_send_message",protocol="ws",le="10"} 0
substrate_rpc_calls_time_bucket{method="p2p_send_message",protocol="ws",le="+Inf"} 3686
substrate_rpc_calls_time_sum{method="p2p_send_message",protocol="ws"} 577635
substrate_rpc_calls_time_count{method="p2p_send_message",protocol="ws"} 3686
substrate_rpc_calls_time_bucket{method="p2p_set_peers",protocol="ws",le="0.005"} 0
substrate_rpc_calls_time_bucket{method="p2p_set_peers",protocol="ws",le="0.01"} 0
substrate_rpc_calls_time_bucket{method="p2p_set_peers",protocol="ws",le="0.025"} 0
substrate_rpc_calls_time_bucket{method="p2p_set_peers",protocol="ws",le="0.05"} 0
substrate_rpc_calls_time_bucket{method="p2p_set_peers",protocol="ws",le="0.1"} 0
substrate_rpc_calls_time_bucket{method="p2p_set_peers",protocol="ws",le="0.25"} 0
substrate_rpc_calls_time_bucket{method="p2p_set_peers",protocol="ws",le="0.5"} 0
substrate_rpc_calls_time_bucket{method="p2p_set_peers",protocol="ws",le="1"} 0
substrate_rpc_calls_time_bucket{method="p2p_set_peers",protocol="ws",le="2.5"} 0
substrate_rpc_calls_time_bucket{method="p2p_set_peers",protocol="ws",le="5"} 0
substrate_rpc_calls_time_bucket{method="p2p_set_peers",protocol="ws",le="10"} 0
substrate_rpc_calls_time_bucket{method="p2p_set_peers",protocol="ws",le="+Inf"} 3
substrate_rpc_calls_time_sum{method="p2p_set_peers",protocol="ws"} 4476
substrate_rpc_calls_time_count{method="p2p_set_peers",protocol="ws"} 3
substrate_rpc_calls_time_bucket{method="state_getMetadata",protocol="ws",le="0.005"} 0
substrate_rpc_calls_time_bucket{method="state_getMetadata",protocol="ws",le="0.01"} 0
substrate_rpc_calls_time_bucket{method="state_getMetadata",protocol="ws",le="0.025"} 0
substrate_rpc_calls_time_bucket{method="state_getMetadata",protocol="ws",le="0.05"} 0
substrate_rpc_calls_time_bucket{method="state_getMetadata",protocol="ws",le="0.1"} 0
substrate_rpc_calls_time_bucket{method="state_getMetadata",protocol="ws",le="0.25"} 0
substrate_rpc_calls_time_bucket{method="state_getMetadata",protocol="ws",le="0.5"} 0
substrate_rpc_calls_time_bucket{method="state_getMetadata",protocol="ws",le="1"} 0
substrate_rpc_calls_time_bucket{method="state_getMetadata",protocol="ws",le="2.5"} 0
substrate_rpc_calls_time_bucket{method="state_getMetadata",protocol="ws",le="5"} 0
substrate_rpc_calls_time_bucket{method="state_getMetadata",protocol="ws",le="10"} 0
substrate_rpc_calls_time_bucket{method="state_getMetadata",protocol="ws",le="+Inf"} 3
substrate_rpc_calls_time_sum{method="state_getMetadata",protocol="ws"} 11858
substrate_rpc_calls_time_count{method="state_getMetadata",protocol="ws"} 3
substrate_rpc_calls_time_bucket{method="state_getPairs",protocol="ws",le="0.005"} 0
substrate_rpc_calls_time_bucket{method="state_getPairs",protocol="ws",le="0.01"} 0
substrate_rpc_calls_time_bucket{method="state_getPairs",protocol="ws",le="0.025"} 0
substrate_rpc_calls_time_bucket{method="state_getPairs",protocol="ws",le="0.05"} 0
substrate_rpc_calls_time_bucket{method="state_getPairs",protocol="ws",le="0.1"} 0
substrate_rpc_calls_time_bucket{method="state_getPairs",protocol="ws",le="0.25"} 0
substrate_rpc_calls_time_bucket{method="state_getPairs",protocol="ws",le="0.5"} 0
substrate_rpc_calls_time_bucket{method="state_getPairs",protocol="ws",le="1"} 0
substrate_rpc_calls_time_bucket{method="state_getPairs",protocol="ws",le="2.5"} 0
substrate_rpc_calls_time_bucket{method="state_getPairs",protocol="ws",le="5"} 0
substrate_rpc_calls_time_bucket{method="state_getPairs",protocol="ws",le="10"} 0
substrate_rpc_calls_time_bucket{method="state_getPairs",protocol="ws",le="+Inf"} 3
substrate_rpc_calls_time_sum{method="state_getPairs",protocol="ws"} 1565669
substrate_rpc_calls_time_count{method="state_getPairs",protocol="ws"} 3
substrate_rpc_calls_time_bucket{method="state_getRuntimeVersion",protocol="ws",le="0.005"} 0
substrate_rpc_calls_time_bucket{method="state_getRuntimeVersion",protocol="ws",le="0.01"} 0
substrate_rpc_calls_time_bucket{method="state_getRuntimeVersion",protocol="ws",le="0.025"} 0
substrate_rpc_calls_time_bucket{method="state_getRuntimeVersion",protocol="ws",le="0.05"} 0
substrate_rpc_calls_time_bucket{method="state_getRuntimeVersion",protocol="ws",le="0.1"} 0
substrate_rpc_calls_time_bucket{method="state_getRuntimeVersion",protocol="ws",le="0.25"} 0
substrate_rpc_calls_time_bucket{method="state_getRuntimeVersion",protocol="ws",le="0.5"} 0
substrate_rpc_calls_time_bucket{method="state_getRuntimeVersion",protocol="ws",le="1"} 0
substrate_rpc_calls_time_bucket{method="state_getRuntimeVersion",protocol="ws",le="2.5"} 0
substrate_rpc_calls_time_bucket{method="state_getRuntimeVersion",protocol="ws",le="5"} 0
substrate_rpc_calls_time_bucket{method="state_getRuntimeVersion",protocol="ws",le="10"} 0
substrate_rpc_calls_time_bucket{method="state_getRuntimeVersion",protocol="ws",le="+Inf"} 3
substrate_rpc_calls_time_sum{method="state_getRuntimeVersion",protocol="ws"} 2642
substrate_rpc_calls_time_count{method="state_getRuntimeVersion",protocol="ws"} 3
substrate_rpc_calls_time_bucket{method="state_getStorage",protocol="ws",le="0.005"} 0
substrate_rpc_calls_time_bucket{method="state_getStorage",protocol="ws",le="0.01"} 0
substrate_rpc_calls_time_bucket{method="state_getStorage",protocol="ws",le="0.025"} 0
substrate_rpc_calls_time_bucket{method="state_getStorage",protocol="ws",le="0.05"} 0
substrate_rpc_calls_time_bucket{method="state_getStorage",protocol="ws",le="0.1"} 0
substrate_rpc_calls_time_bucket{method="state_getStorage",protocol="ws",le="0.25"} 0
substrate_rpc_calls_time_bucket{method="state_getStorage",protocol="ws",le="0.5"} 0
substrate_rpc_calls_time_bucket{method="state_getStorage",protocol="ws",le="1"} 0
substrate_rpc_calls_time_bucket{method="state_getStorage",protocol="ws",le="2.5"} 0
substrate_rpc_calls_time_bucket{method="state_getStorage",protocol="ws",le="5"} 0
substrate_rpc_calls_time_bucket{method="state_getStorage",protocol="ws",le="10"} 0
substrate_rpc_calls_time_bucket{method="state_getStorage",protocol="ws",le="+Inf"} 3
substrate_rpc_calls_time_sum{method="state_getStorage",protocol="ws"} 4462
substrate_rpc_calls_time_count{method="state_getStorage",protocol="ws"} 3
substrate_rpc_calls_time_bucket{method="state_queryStorageAt",protocol="ws",le="0.005"} 0
substrate_rpc_calls_time_bucket{method="state_queryStorageAt",protocol="ws",le="0.01"} 0
substrate_rpc_calls_time_bucket{method="state_queryStorageAt",protocol="ws",le="0.025"} 0
substrate_rpc_calls_time_bucket{method="state_queryStorageAt",protocol="ws",le="0.05"} 0
substrate_rpc_calls_time_bucket{method="state_queryStorageAt",protocol="ws",le="0.1"} 0
substrate_rpc_calls_time_bucket{method="state_queryStorageAt",protocol="ws",le="0.25"} 0
substrate_rpc_calls_time_bucket{method="state_queryStorageAt",protocol="ws",le="0.5"} 0
substrate_rpc_calls_time_bucket{method="state_queryStorageAt",protocol="ws",le="1"} 0
substrate_rpc_calls_time_bucket{method="state_queryStorageAt",protocol="ws",le="2.5"} 0
substrate_rpc_calls_time_bucket{method="state_queryStorageAt",protocol="ws",le="5"} 0
substrate_rpc_calls_time_bucket{method="state_queryStorageAt",protocol="ws",le="10"} 0
substrate_rpc_calls_time_bucket{method="state_queryStorageAt",protocol="ws",le="+Inf"} 9737
substrate_rpc_calls_time_sum{method="state_queryStorageAt",protocol="ws"} 2564461
substrate_rpc_calls_time_count{method="state_queryStorageAt",protocol="ws"} 9737
substrate_rpc_calls_time_bucket{method="system_localPeerId",protocol="ws",le="0.005"} 0
substrate_rpc_calls_time_bucket{method="system_localPeerId",protocol="ws",le="0.01"} 0
substrate_rpc_calls_time_bucket{method="system_localPeerId",protocol="ws",le="0.025"} 0
substrate_rpc_calls_time_bucket{method="system_localPeerId",protocol="ws",le="0.05"} 0
substrate_rpc_calls_time_bucket{method="system_localPeerId",protocol="ws",le="0.1"} 0
substrate_rpc_calls_time_bucket{method="system_localPeerId",protocol="ws",le="0.25"} 0
substrate_rpc_calls_time_bucket{method="system_localPeerId",protocol="ws",le="0.5"} 0
substrate_rpc_calls_time_bucket{method="system_localPeerId",protocol="ws",le="1"} 0
substrate_rpc_calls_time_bucket{method="system_localPeerId",protocol="ws",le="2.5"} 0
substrate_rpc_calls_time_bucket{method="system_localPeerId",protocol="ws",le="5"} 0
substrate_rpc_calls_time_bucket{method="system_localPeerId",protocol="ws",le="10"} 0
substrate_rpc_calls_time_bucket{method="system_localPeerId",protocol="ws",le="+Inf"} 3
substrate_rpc_calls_time_sum{method="system_localPeerId",protocol="ws"} 2683
substrate_rpc_calls_time_count{method="system_localPeerId",protocol="ws"} 3
# HELP substrate_rpc_requests_finished Number of RPC requests (not calls) processed by the server.
# TYPE substrate_rpc_requests_finished counter
substrate_rpc_requests_finished{protocol="ws"} 13953
# HELP substrate_rpc_requests_started Number of RPC requests (not calls) received by the server.
# TYPE substrate_rpc_requests_started counter
substrate_rpc_requests_started{protocol="ws"} 13953
# HELP substrate_rpc_sessions_closed Number of persistent RPC sessions closed
# TYPE substrate_rpc_sessions_closed counter
substrate_rpc_sessions_closed 4
# HELP substrate_rpc_sessions_opened Number of persistent RPC sessions opened
# TYPE substrate_rpc_sessions_opened counter
substrate_rpc_sessions_opened 6
# HELP substrate_state_cache_bytes State cache size in bytes
# TYPE substrate_state_cache_bytes gauge
substrate_state_cache_bytes 3969081
# HELP substrate_state_db_cache_bytes State DB cache in bytes
# TYPE substrate_state_db_cache_bytes gauge
substrate_state_db_cache_bytes{subtype="non_canonical"} 224
substrate_state_db_cache_bytes{subtype="pinned"} 132
# HELP substrate_sub_libp2p_connections_closed_total Total number of connections closed, by direction and reason
# TYPE substrate_sub_libp2p_connections_closed_total counter
substrate_sub_libp2p_connections_closed_total{direction="in",reason="keep-alive-timeout"} 49758
substrate_sub_libp2p_connections_closed_total{direction="in",reason="ping-timeout"} 31
substrate_sub_libp2p_connections_closed_total{direction="in",reason="transport-error"} 6511
substrate_sub_libp2p_connections_closed_total{direction="out",reason="keep-alive-timeout"} 33340
substrate_sub_libp2p_connections_closed_total{direction="out",reason="ping-timeout"} 28
substrate_sub_libp2p_connections_closed_total{direction="out",reason="transport-error"} 110422
# HELP substrate_sub_libp2p_connections_opened_total Total number of connections opened by direction
# TYPE substrate_sub_libp2p_connections_opened_total counter
substrate_sub_libp2p_connections_opened_total{direction="in"} 56368
substrate_sub_libp2p_connections_opened_total{direction="out"} 143934
# HELP substrate_sub_libp2p_distinct_peers_connections_closed_total Total number of connections closed with distinct peers
# TYPE substrate_sub_libp2p_distinct_peers_connections_closed_total counter
substrate_sub_libp2p_distinct_peers_connections_closed_total 198163
# HELP substrate_sub_libp2p_distinct_peers_connections_opened_total Total number of connections opened with distinct peers
# TYPE substrate_sub_libp2p_distinct_peers_connections_opened_total counter
substrate_sub_libp2p_distinct_peers_connections_opened_total 198374
# HELP substrate_sub_libp2p_incoming_connections_handshake_errors_total Total number of incoming connections that have failed during the initial handshake
# TYPE substrate_sub_libp2p_incoming_connections_handshake_errors_total counter
substrate_sub_libp2p_incoming_connections_handshake_errors_total{reason="invalid-peer-id"} 641
substrate_sub_libp2p_incoming_connections_handshake_errors_total{reason="limit-reached"} 11
substrate_sub_libp2p_incoming_connections_handshake_errors_total{reason="transport-error"} 477
# HELP substrate_sub_libp2p_incoming_connections_total Total number of incoming connections on the listening sockets
# TYPE substrate_sub_libp2p_incoming_connections_total counter
substrate_sub_libp2p_incoming_connections_total 57498
# HELP substrate_sub_libp2p_is_major_syncing Whether the node is performing a major sync or not.
# TYPE substrate_sub_libp2p_is_major_syncing gauge
substrate_sub_libp2p_is_major_syncing 0
# HELP substrate_sub_libp2p_kademlia_random_queries_total Number of random Kademlia queries started
# TYPE substrate_sub_libp2p_kademlia_random_queries_total counter
substrate_sub_libp2p_kademlia_random_queries_total{protocol="sup"} 1012
# HELP substrate_sub_libp2p_kademlia_records_count Number of records in the Kademlia records store
# TYPE substrate_sub_libp2p_kademlia_records_count gauge
substrate_sub_libp2p_kademlia_records_count{protocol="sup"} 3
# HELP substrate_sub_libp2p_kademlia_records_sizes_total Total size of all the records in the Kademlia records store
# TYPE substrate_sub_libp2p_kademlia_records_sizes_total gauge
substrate_sub_libp2p_kademlia_records_sizes_total{protocol="sup"} 483
# HELP substrate_sub_libp2p_kbuckets_num_nodes Number of nodes per kbucket per Kademlia instance
# TYPE substrate_sub_libp2p_kbuckets_num_nodes gauge
substrate_sub_libp2p_kbuckets_num_nodes{lower_ilog2_bucket_bound="242",protocol="sup"} 1
substrate_sub_libp2p_kbuckets_num_nodes{lower_ilog2_bucket_bound="245",protocol="sup"} 1
substrate_sub_libp2p_kbuckets_num_nodes{lower_ilog2_bucket_bound="246",protocol="sup"} 1
substrate_sub_libp2p_kbuckets_num_nodes{lower_ilog2_bucket_bound="247",protocol="sup"} 8
substrate_sub_libp2p_kbuckets_num_nodes{lower_ilog2_bucket_bound="248",protocol="sup"} 12
substrate_sub_libp2p_kbuckets_num_nodes{lower_ilog2_bucket_bound="249",protocol="sup"} 20
substrate_sub_libp2p_kbuckets_num_nodes{lower_ilog2_bucket_bound="250",protocol="sup"} 20
substrate_sub_libp2p_kbuckets_num_nodes{lower_ilog2_bucket_bound="251",protocol="sup"} 20
substrate_sub_libp2p_kbuckets_num_nodes{lower_ilog2_bucket_bound="252",protocol="sup"} 20
substrate_sub_libp2p_kbuckets_num_nodes{lower_ilog2_bucket_bound="253",protocol="sup"} 20
substrate_sub_libp2p_kbuckets_num_nodes{lower_ilog2_bucket_bound="254",protocol="sup"} 20
substrate_sub_libp2p_kbuckets_num_nodes{lower_ilog2_bucket_bound="255",protocol="sup"} 20
# HELP substrate_sub_libp2p_listeners_errors_total Total number of non-fatal errors reported by a listener
# TYPE substrate_sub_libp2p_listeners_errors_total counter
substrate_sub_libp2p_listeners_errors_total 0
# HELP substrate_sub_libp2p_listeners_local_addresses Number of local addresses we're listening on
# TYPE substrate_sub_libp2p_listeners_local_addresses gauge
substrate_sub_libp2p_listeners_local_addresses 2
# HELP substrate_sub_libp2p_network_bytes_total Total bandwidth usage
# TYPE substrate_sub_libp2p_network_bytes_total counter
substrate_sub_libp2p_network_bytes_total{direction="in"} 2735063083
substrate_sub_libp2p_network_bytes_total{direction="out"} 2482706163
# HELP substrate_sub_libp2p_notifications_sizes Sizes of the notifications send to and received from all nodes
# TYPE substrate_sub_libp2p_notifications_sizes histogram
substrate_sub_libp2p_notifications_sizes_bucket{direction="in",protocol="/chainflip-protocol",le="64"} 911
substrate_sub_libp2p_notifications_sizes_bucket{direction="in",protocol="/chainflip-protocol",le="256"} 1766
substrate_sub_libp2p_notifications_sizes_bucket{direction="in",protocol="/chainflip-protocol",le="1024"} 3599
substrate_sub_libp2p_notifications_sizes_bucket{direction="in",protocol="/chainflip-protocol",le="4096"} 3599
substrate_sub_libp2p_notifications_sizes_bucket{direction="in",protocol="/chainflip-protocol",le="16384"} 3683
substrate_sub_libp2p_notifications_sizes_bucket{direction="in",protocol="/chainflip-protocol",le="65536"} 3683
substrate_sub_libp2p_notifications_sizes_bucket{direction="in",protocol="/chainflip-protocol",le="262144"} 3683
substrate_sub_libp2p_notifications_sizes_bucket{direction="in",protocol="/chainflip-protocol",le="1048576"} 3683
substrate_sub_libp2p_notifications_sizes_bucket{direction="in",protocol="/chainflip-protocol",le="+Inf"} 3683
substrate_sub_libp2p_notifications_sizes_sum{direction="in",protocol="/chainflip-protocol"} 2127243
substrate_sub_libp2p_notifications_sizes_count{direction="in",protocol="/chainflip-protocol"} 3683
substrate_sub_libp2p_notifications_sizes_bucket{direction="in",protocol="/paritytech/grandpa/1",le="64"} 2255873
substrate_sub_libp2p_notifications_sizes_bucket{direction="in",protocol="/paritytech/grandpa/1",le="256"} 11531551
substrate_sub_libp2p_notifications_sizes_bucket{direction="in",protocol="/paritytech/grandpa/1",le="1024"} 11531551
substrate_sub_libp2p_notifications_sizes_bucket{direction="in",protocol="/paritytech/grandpa/1",le="4096"} 11627560
substrate_sub_libp2p_notifications_sizes_bucket{direction="in",protocol="/paritytech/grandpa/1",le="16384"} 11627560
substrate_sub_libp2p_notifications_sizes_bucket{direction="in",protocol="/paritytech/grandpa/1",le="65536"} 11627560
substrate_sub_libp2p_notifications_sizes_bucket{direction="in",protocol="/paritytech/grandpa/1",le="262144"} 11627560
substrate_sub_libp2p_notifications_sizes_bucket{direction="in",protocol="/paritytech/grandpa/1",le="1048576"} 11627560
substrate_sub_libp2p_notifications_sizes_bucket{direction="in",protocol="/paritytech/grandpa/1",le="+Inf"} 11627560
substrate_sub_libp2p_notifications_sizes_sum{direction="in",protocol="/paritytech/grandpa/1"} 1586769147
substrate_sub_libp2p_notifications_sizes_count{direction="in",protocol="/paritytech/grandpa/1"} 11627560
substrate_sub_libp2p_notifications_sizes_bucket{direction="in",protocol="/sup/transactions/1",le="64"} 0
substrate_sub_libp2p_notifications_sizes_bucket{direction="in",protocol="/sup/transactions/1",le="256"} 595158
substrate_sub_libp2p_notifications_sizes_bucket{direction="in",protocol="/sup/transactions/1",le="1024"} 605881
substrate_sub_libp2p_notifications_sizes_bucket{direction="in",protocol="/sup/transactions/1",le="4096"} 606065
substrate_sub_libp2p_notifications_sizes_bucket{direction="in",protocol="/sup/transactions/1",le="16384"} 606069
substrate_sub_libp2p_notifications_sizes_bucket{direction="in",protocol="/sup/transactions/1",le="65536"} 606069
substrate_sub_libp2p_notifications_sizes_bucket{direction="in",protocol="/sup/transactions/1",le="262144"} 606069
substrate_sub_libp2p_notifications_sizes_bucket{direction="in",protocol="/sup/transactions/1",le="1048576"} 606069
substrate_sub_libp2p_notifications_sizes_bucket{direction="in",protocol="/sup/transactions/1",le="+Inf"} 606069
substrate_sub_libp2p_notifications_sizes_sum{direction="in",protocol="/sup/transactions/1"} 85225310
substrate_sub_libp2p_notifications_sizes_count{direction="in",protocol="/sup/transactions/1"} 606069
substrate_sub_libp2p_notifications_sizes_bucket{direction="out",protocol="/chainflip-protocol",le="64"} 911
substrate_sub_libp2p_notifications_sizes_bucket{direction="out",protocol="/chainflip-protocol",le="256"} 1766
substrate_sub_libp2p_notifications_sizes_bucket{direction="out",protocol="/chainflip-protocol",le="1024"} 3602
substrate_sub_libp2p_notifications_sizes_bucket{direction="out",protocol="/chainflip-protocol",le="4096"} 3602
substrate_sub_libp2p_notifications_sizes_bucket{direction="out",protocol="/chainflip-protocol",le="16384"} 3686
substrate_sub_libp2p_notifications_sizes_bucket{direction="out",protocol="/chainflip-protocol",le="65536"} 3686
substrate_sub_libp2p_notifications_sizes_bucket{direction="out",protocol="/chainflip-protocol",le="262144"} 3686
substrate_sub_libp2p_notifications_sizes_bucket{direction="out",protocol="/chainflip-protocol",le="1048576"} 3686
substrate_sub_libp2p_notifications_sizes_bucket{direction="out",protocol="/chainflip-protocol",le="+Inf"} 3686
substrate_sub_libp2p_notifications_sizes_sum{direction="out",protocol="/chainflip-protocol"} 2128788
substrate_sub_libp2p_notifications_sizes_count{direction="out",protocol="/chainflip-protocol"} 3686
substrate_sub_libp2p_notifications_sizes_bucket{direction="out",protocol="/paritytech/grandpa/1",le="64"} 2257783
substrate_sub_libp2p_notifications_sizes_bucket{direction="out",protocol="/paritytech/grandpa/1",le="256"} 11385062
substrate_sub_libp2p_notifications_sizes_bucket{direction="out",protocol="/paritytech/grandpa/1",le="1024"} 11385062
substrate_sub_libp2p_notifications_sizes_bucket{direction="out",protocol="/paritytech/grandpa/1",le="4096"} 11475948
substrate_sub_libp2p_notifications_sizes_bucket{direction="out",protocol="/paritytech/grandpa/1",le="16384"} 11475948
substrate_sub_libp2p_notifications_sizes_bucket{direction="out",protocol="/paritytech/grandpa/1",le="65536"} 11475948
substrate_sub_libp2p_notifications_sizes_bucket{direction="out",protocol="/paritytech/grandpa/1",le="262144"} 11475948
substrate_sub_libp2p_notifications_sizes_bucket{direction="out",protocol="/paritytech/grandpa/1",le="1048576"} 11475948
substrate_sub_libp2p_notifications_sizes_bucket{direction="out",protocol="/paritytech/grandpa/1",le="+Inf"} 11475948
substrate_sub_libp2p_notifications_sizes_sum{direction="out",protocol="/paritytech/grandpa/1"} 1556986888
substrate_sub_libp2p_notifications_sizes_count{direction="out",protocol="/paritytech/grandpa/1"} 11475948
substrate_sub_libp2p_notifications_sizes_bucket{direction="out",protocol="/sup/transactions/1",le="64"} 0
substrate_sub_libp2p_notifications_sizes_bucket{direction="out",protocol="/sup/transactions/1",le="256"} 429569
substrate_sub_libp2p_notifications_sizes_bucket{direction="out",protocol="/sup/transactions/1",le="1024"} 439500
substrate_sub_libp2p_notifications_sizes_bucket{direction="out",protocol="/sup/transactions/1",le="4096"} 439643
substrate_sub_libp2p_notifications_sizes_bucket{direction="out",protocol="/sup/transactions/1",le="16384"} 439643
substrate_sub_libp2p_notifications_sizes_bucket{direction="out",protocol="/sup/transactions/1",le="65536"} 439643
substrate_sub_libp2p_notifications_sizes_bucket{direction="out",protocol="/sup/transactions/1",le="262144"} 439643
substrate_sub_libp2p_notifications_sizes_bucket{direction="out",protocol="/sup/transactions/1",le="1048576"} 439643
substrate_sub_libp2p_notifications_sizes_bucket{direction="out",protocol="/sup/transactions/1",le="+Inf"} 439643
substrate_sub_libp2p_notifications_sizes_sum{direction="out",protocol="/sup/transactions/1"} 62149815
substrate_sub_libp2p_notifications_sizes_count{direction="out",protocol="/sup/transactions/1"} 439643
# HELP substrate_sub_libp2p_notifications_streams_closed_total Total number of notification substreams that have been closed
# TYPE substrate_sub_libp2p_notifications_streams_closed_total counter
substrate_sub_libp2p_notifications_streams_closed_total{protocol="/chainflip-protocol"} 8
substrate_sub_libp2p_notifications_streams_closed_total{protocol="/paritytech/grandpa/1"} 13
substrate_sub_libp2p_notifications_streams_closed_total{protocol="/sup/transactions/1"} 13
# HELP substrate_sub_libp2p_notifications_streams_opened_total Total number of notification substreams that have been opened
# TYPE substrate_sub_libp2p_notifications_streams_opened_total counter
substrate_sub_libp2p_notifications_streams_opened_total{protocol="/chainflip-protocol"} 45
substrate_sub_libp2p_notifications_streams_opened_total{protocol="/paritytech/grandpa/1"} 56
substrate_sub_libp2p_notifications_streams_opened_total{protocol="/sup/transactions/1"} 56
# HELP substrate_sub_libp2p_out_events_events_total Number of broadcast network events that have been sent or received across all channels
# TYPE substrate_sub_libp2p_out_events_events_total counter
substrate_sub_libp2p_out_events_events_total{action="received",event_name="notif-\"/chainflip-protocol\"",name="network-chainflip"} 3683
substrate_sub_libp2p_out_events_events_total{action="received",event_name="notif-\"/chainflip-protocol\"",name="network-gossip"} 3683
substrate_sub_libp2p_out_events_events_total{action="received",event_name="notif-\"/chainflip-protocol\"",name="transactions-handler"} 3683
substrate_sub_libp2p_out_events_events_total{action="received",event_name="notif-\"/paritytech/grandpa/1\"",name="network-chainflip"} 11627560
substrate_sub_libp2p_out_events_events_total{action="received",event_name="notif-\"/paritytech/grandpa/1\"",name="network-gossip"} 11627560
substrate_sub_libp2p_out_events_events_total{action="received",event_name="notif-\"/paritytech/grandpa/1\"",name="transactions-handler"} 11627560
substrate_sub_libp2p_out_events_events_total{action="received",event_name="notif-\"/sup/transactions/1\"",name="network-chainflip"} 606069
substrate_sub_libp2p_out_events_events_total{action="received",event_name="notif-\"/sup/transactions/1\"",name="network-gossip"} 606069
substrate_sub_libp2p_out_events_events_total{action="received",event_name="notif-\"/sup/transactions/1\"",name="transactions-handler"} 606069
substrate_sub_libp2p_out_events_events_total{action="received",event_name="notif-closed-\"/chainflip-protocol\"",name="network-chainflip"} 8
substrate_sub_libp2p_out_events_events_total{action="received",event_name="notif-closed-\"/chainflip-protocol\"",name="network-gossip"} 8
substrate_sub_libp2p_out_events_events_total{action="received",event_name="notif-closed-\"/chainflip-protocol\"",name="transactions-handler"} 8
substrate_sub_libp2p_out_events_events_total{action="received",event_name="notif-closed-\"/paritytech/grandpa/1\"",name="network-chainflip"} 13
substrate_sub_libp2p_out_events_events_total{action="received",event_name="notif-closed-\"/paritytech/grandpa/1\"",name="network-gossip"} 13
substrate_sub_libp2p_out_events_events_total{action="received",event_name="notif-closed-\"/paritytech/grandpa/1\"",name="transactions-handler"} 13
substrate_sub_libp2p_out_events_events_total{action="received",event_name="notif-closed-\"/sup/transactions/1\"",name="network-chainflip"} 13
substrate_sub_libp2p_out_events_events_total{action="received",event_name="notif-closed-\"/sup/transactions/1\"",name="network-gossip"} 13
substrate_sub_libp2p_out_events_events_total{action="received",event_name="notif-closed-\"/sup/transactions/1\"",name="transactions-handler"} 13
substrate_sub_libp2p_out_events_events_total{action="received",event_name="notif-open-\"/chainflip-protocol\"",name="network-chainflip"} 45
substrate_sub_libp2p_out_events_events_total{action="received",event_name="notif-open-\"/chainflip-protocol\"",name="network-gossip"} 45
substrate_sub_libp2p_out_events_events_total{action="received",event_name="notif-open-\"/chainflip-protocol\"",name="transactions-handler"} 45
substrate_sub_libp2p_out_events_events_total{action="received",event_name="notif-open-\"/paritytech/grandpa/1\"",name="network-chainflip"} 56
substrate_sub_libp2p_out_events_events_total{action="received",event_name="notif-open-\"/paritytech/grandpa/1\"",name="network-gossip"} 56
substrate_sub_libp2p_out_events_events_total{action="received",event_name="notif-open-\"/paritytech/grandpa/1\"",name="transactions-handler"} 56
substrate_sub_libp2p_out_events_events_total{action="received",event_name="notif-open-\"/sup/transactions/1\"",name="network-chainflip"} 56
substrate_sub_libp2p_out_events_events_total{action="received",event_name="notif-open-\"/sup/transactions/1\"",name="network-gossip"} 56
substrate_sub_libp2p_out_events_events_total{action="received",event_name="notif-open-\"/sup/transactions/1\"",name="transactions-handler"} 56
substrate_sub_libp2p_out_events_events_total{action="received",event_name="sync-connected",name="network-chainflip"} 56
substrate_sub_libp2p_out_events_events_total{action="received",event_name="sync-connected",name="network-gossip"} 56
substrate_sub_libp2p_out_events_events_total{action="received",event_name="sync-connected",name="transactions-handler"} 56
substrate_sub_libp2p_out_events_events_total{action="received",event_name="sync-disconnected",name="network-chainflip"} 13
substrate_sub_libp2p_out_events_events_total{action="received",event_name="sync-disconnected",name="network-gossip"} 13
substrate_sub_libp2p_out_events_events_total{action="received",event_name="sync-disconnected",name="transactions-handler"} 13
substrate_sub_libp2p_out_events_events_total{action="sent",event_name="notif-\"/chainflip-protocol\"",name="network-chainflip"} 3683
substrate_sub_libp2p_out_events_events_total{action="sent",event_name="notif-\"/chainflip-protocol\"",name="network-gossip"} 3683
substrate_sub_libp2p_out_events_events_total{action="sent",event_name="notif-\"/chainflip-protocol\"",name="transactions-handler"} 3683
substrate_sub_libp2p_out_events_events_total{action="sent",event_name="notif-\"/paritytech/grandpa/1\"",name="network-chainflip"} 11627560
substrate_sub_libp2p_out_events_events_total{action="sent",event_name="notif-\"/paritytech/grandpa/1\"",name="network-gossip"} 11627560
substrate_sub_libp2p_out_events_events_total{action="sent",event_name="notif-\"/paritytech/grandpa/1\"",name="transactions-handler"} 11627560
substrate_sub_libp2p_out_events_events_total{action="sent",event_name="notif-\"/sup/transactions/1\"",name="network-chainflip"} 606069
substrate_sub_libp2p_out_events_events_total{action="sent",event_name="notif-\"/sup/transactions/1\"",name="network-gossip"} 606069
substrate_sub_libp2p_out_events_events_total{action="sent",event_name="notif-\"/sup/transactions/1\"",name="transactions-handler"} 606069
substrate_sub_libp2p_out_events_events_total{action="sent",event_name="notif-closed-\"/chainflip-protocol\"",name="network-chainflip"} 8
substrate_sub_libp2p_out_events_events_total{action="sent",event_name="notif-closed-\"/chainflip-protocol\"",name="network-gossip"} 8
substrate_sub_libp2p_out_events_events_total{action="sent",event_name="notif-closed-\"/chainflip-protocol\"",name="transactions-handler"} 8
substrate_sub_libp2p_out_events_events_total{action="sent",event_name="notif-closed-\"/paritytech/grandpa/1\"",name="network-chainflip"} 13
substrate_sub_libp2p_out_events_events_total{action="sent",event_name="notif-closed-\"/paritytech/grandpa/1\"",name="network-gossip"} 13
substrate_sub_libp2p_out_events_events_total{action="sent",event_name="notif-closed-\"/paritytech/grandpa/1\"",name="transactions-handler"} 13
substrate_sub_libp2p_out_events_events_total{action="sent",event_name="notif-closed-\"/sup/transactions/1\"",name="network-chainflip"} 13
substrate_sub_libp2p_out_events_events_total{action="sent",event_name="notif-closed-\"/sup/transactions/1\"",name="network-gossip"} 13
substrate_sub_libp2p_out_events_events_total{action="sent",event_name="notif-closed-\"/sup/transactions/1\"",name="transactions-handler"} 13
substrate_sub_libp2p_out_events_events_total{action="sent",event_name="notif-open-\"/chainflip-protocol\"",name="network-chainflip"} 45
substrate_sub_libp2p_out_events_events_total{action="sent",event_name="notif-open-\"/chainflip-protocol\"",name="network-gossip"} 45
substrate_sub_libp2p_out_events_events_total{action="sent",event_name="notif-open-\"/chainflip-protocol\"",name="transactions-handler"} 45
substrate_sub_libp2p_out_events_events_total{action="sent",event_name="notif-open-\"/paritytech/grandpa/1\"",name="network-chainflip"} 56
substrate_sub_libp2p_out_events_events_total{action="sent",event_name="notif-open-\"/paritytech/grandpa/1\"",name="network-gossip"} 56
substrate_sub_libp2p_out_events_events_total{action="sent",event_name="notif-open-\"/paritytech/grandpa/1\"",name="transactions-handler"} 56
substrate_sub_libp2p_out_events_events_total{action="sent",event_name="notif-open-\"/sup/transactions/1\"",name="network-chainflip"} 56
substrate_sub_libp2p_out_events_events_total{action="sent",event_name="notif-open-\"/sup/transactions/1\"",name="network-gossip"} 56
substrate_sub_libp2p_out_events_events_total{action="sent",event_name="notif-open-\"/sup/transactions/1\"",name="transactions-handler"} 56
substrate_sub_libp2p_out_events_events_total{action="sent",event_name="sync-connected",name="network-chainflip"} 56
substrate_sub_libp2p_out_events_events_total{action="sent",event_name="sync-connected",name="network-gossip"} 56
substrate_sub_libp2p_out_events_events_total{action="sent",event_name="sync-connected",name="transactions-handler"} 56
substrate_sub_libp2p_out_events_events_total{action="sent",event_name="sync-disconnected",name="network-chainflip"} 13
substrate_sub_libp2p_out_events_events_total{action="sent",event_name="sync-disconnected",name="network-gossip"} 13
substrate_sub_libp2p_out_events_events_total{action="sent",event_name="sync-disconnected",name="transactions-handler"} 13
# HELP substrate_sub_libp2p_out_events_notifications_sizes Size of notification events that have been sent or received across all channels
# TYPE substrate_sub_libp2p_out_events_notifications_sizes counter
substrate_sub_libp2p_out_events_notifications_sizes{action="received",name="network-chainflip",protocol="/chainflip-protocol"} 2127243
substrate_sub_libp2p_out_events_notifications_sizes{action="received",name="network-chainflip",protocol="/paritytech/grandpa/1"} 1586769147
substrate_sub_libp2p_out_events_notifications_sizes{action="received",name="network-chainflip",protocol="/sup/transactions/1"} 85225310
substrate_sub_libp2p_out_events_notifications_sizes{action="received",name="network-gossip",protocol="/chainflip-protocol"} 2127243
substrate_sub_libp2p_out_events_notifications_sizes{action="received",name="network-gossip",protocol="/paritytech/grandpa/1"} 1586769147
substrate_sub_libp2p_out_events_notifications_sizes{action="received",name="network-gossip",protocol="/sup/transactions/1"} 85225310
substrate_sub_libp2p_out_events_notifications_sizes{action="received",name="transactions-handler",protocol="/chainflip-protocol"} 2127243
substrate_sub_libp2p_out_events_notifications_sizes{action="received",name="transactions-handler",protocol="/paritytech/grandpa/1"} 1586769147
substrate_sub_libp2p_out_events_notifications_sizes{action="received",name="transactions-handler",protocol="/sup/transactions/1"} 85225310
substrate_sub_libp2p_out_events_notifications_sizes{action="sent",name="network-chainflip",protocol="/chainflip-protocol"} 2127243
substrate_sub_libp2p_out_events_notifications_sizes{action="sent",name="network-chainflip",protocol="/paritytech/grandpa/1"} 1586769147
substrate_sub_libp2p_out_events_notifications_sizes{action="sent",name="network-chainflip",protocol="/sup/transactions/1"} 85225310
substrate_sub_libp2p_out_events_notifications_sizes{action="sent",name="network-gossip",protocol="/chainflip-protocol"} 2127243
substrate_sub_libp2p_out_events_notifications_sizes{action="sent",name="network-gossip",protocol="/paritytech/grandpa/1"} 1586769147
substrate_sub_libp2p_out_events_notifications_sizes{action="sent",name="network-gossip",protocol="/sup/transactions/1"} 85225310
substrate_sub_libp2p_out_events_notifications_sizes{action="sent",name="transactions-handler",protocol="/chainflip-protocol"} 2127243
substrate_sub_libp2p_out_events_notifications_sizes{action="sent",name="transactions-handler",protocol="/paritytech/grandpa/1"} 1586769147
substrate_sub_libp2p_out_events_notifications_sizes{action="sent",name="transactions-handler",protocol="/sup/transactions/1"} 85225310
# HELP substrate_sub_libp2p_out_events_num_channels Number of internal active channels that broadcast network events
# TYPE substrate_sub_libp2p_out_events_num_channels gauge
substrate_sub_libp2p_out_events_num_channels{name="network-chainflip"} 1
substrate_sub_libp2p_out_events_num_channels{name="network-gossip"} 1
substrate_sub_libp2p_out_events_num_channels{name="transactions-handler"} 1
# HELP substrate_sub_libp2p_peers_count Number of connected peers
# TYPE substrate_sub_libp2p_peers_count gauge
substrate_sub_libp2p_peers_count 43
# HELP substrate_sub_libp2p_peerset_num_discovered Number of nodes stored in the peerset manager
# TYPE substrate_sub_libp2p_peerset_num_discovered gauge
substrate_sub_libp2p_peerset_num_discovered 1873
# HELP substrate_sub_libp2p_peerset_num_requested Number of nodes that the peerset manager wants us to be connected to
# TYPE substrate_sub_libp2p_peerset_num_requested gauge
substrate_sub_libp2p_peerset_num_requested 508
# HELP substrate_sub_libp2p_pending_connections Number of connections in the process of being established
# TYPE substrate_sub_libp2p_pending_connections gauge
substrate_sub_libp2p_pending_connections 7
# HELP substrate_sub_libp2p_pending_connections_errors_total Total number of pending connection errors
# TYPE substrate_sub_libp2p_pending_connections_errors_total counter
substrate_sub_libp2p_pending_connections_errors_total{reason="invalid-peer-id"} 5614
substrate_sub_libp2p_pending_connections_errors_total{reason="transport-error"} 73001
# HELP substrate_sub_libp2p_requests_in_success_total For successful incoming requests, time between receiving the request and starting to send the response
# TYPE substrate_sub_libp2p_requests_in_success_total histogram
substrate_sub_libp2p_requests_in_success_total_bucket{protocol="/sup/sync/2",le="0.001"} 31382
substrate_sub_libp2p_requests_in_success_total_bucket{protocol="/sup/sync/2",le="0.002"} 42689
substrate_sub_libp2p_requests_in_success_total_bucket{protocol="/sup/sync/2",le="0.004"} 50437
substrate_sub_libp2p_requests_in_success_total_bucket{protocol="/sup/sync/2",le="0.008"} 54437
substrate_sub_libp2p_requests_in_success_total_bucket{protocol="/sup/sync/2",le="0.016"} 56181
substrate_sub_libp2p_requests_in_success_total_bucket{protocol="/sup/sync/2",le="0.032"} 56629
substrate_sub_libp2p_requests_in_success_total_bucket{protocol="/sup/sync/2",le="0.064"} 56672
substrate_sub_libp2p_requests_in_success_total_bucket{protocol="/sup/sync/2",le="0.128"} 56708
substrate_sub_libp2p_requests_in_success_total_bucket{protocol="/sup/sync/2",le="0.256"} 56708
substrate_sub_libp2p_requests_in_success_total_bucket{protocol="/sup/sync/2",le="0.512"} 56708
substrate_sub_libp2p_requests_in_success_total_bucket{protocol="/sup/sync/2",le="1.024"} 56708
substrate_sub_libp2p_requests_in_success_total_bucket{protocol="/sup/sync/2",le="2.048"} 56708
substrate_sub_libp2p_requests_in_success_total_bucket{protocol="/sup/sync/2",le="4.096"} 56708
substrate_sub_libp2p_requests_in_success_total_bucket{protocol="/sup/sync/2",le="8.192"} 56708
substrate_sub_libp2p_requests_in_success_total_bucket{protocol="/sup/sync/2",le="16.384"} 56708
substrate_sub_libp2p_requests_in_success_total_bucket{protocol="/sup/sync/2",le="32.768"} 56708
substrate_sub_libp2p_requests_in_success_total_bucket{protocol="/sup/sync/2",le="+Inf"} 56708
substrate_sub_libp2p_requests_in_success_total_sum{protocol="/sup/sync/2"} 109.15457946400036
substrate_sub_libp2p_requests_in_success_total_count{protocol="/sup/sync/2"} 56708
# HELP substrate_sub_libp2p_requests_out_failure_total Total number of requests that have failed
# TYPE substrate_sub_libp2p_requests_out_failure_total counter
substrate_sub_libp2p_requests_out_failure_total{protocol="/sup/sync/2",reason="obsolete"} 1
# HELP substrate_sub_libp2p_requests_out_success_total For successful outgoing requests, time between a request's start and finish
# TYPE substrate_sub_libp2p_requests_out_success_total histogram
substrate_sub_libp2p_requests_out_success_total_bucket{protocol="/sup/sync/2",le="0.001"} 26
substrate_sub_libp2p_requests_out_success_total_bucket{protocol="/sup/sync/2",le="0.002"} 568
substrate_sub_libp2p_requests_out_success_total_bucket{protocol="/sup/sync/2",le="0.004"} 669
substrate_sub_libp2p_requests_out_success_total_bucket{protocol="/sup/sync/2",le="0.008"} 700
substrate_sub_libp2p_requests_out_success_total_bucket{protocol="/sup/sync/2",le="0.016"} 743
substrate_sub_libp2p_requests_out_success_total_bucket{protocol="/sup/sync/2",le="0.032"} 1837
substrate_sub_libp2p_requests_out_success_total_bucket{protocol="/sup/sync/2",le="0.064"} 1911
substrate_sub_libp2p_requests_out_success_total_bucket{protocol="/sup/sync/2",le="0.128"} 36473
substrate_sub_libp2p_requests_out_success_total_bucket{protocol="/sup/sync/2",le="0.256"} 38975
substrate_sub_libp2p_requests_out_success_total_bucket{protocol="/sup/sync/2",le="0.512"} 39002
substrate_sub_libp2p_requests_out_success_total_bucket{protocol="/sup/sync/2",le="1.024"} 39004
substrate_sub_libp2p_requests_out_success_total_bucket{protocol="/sup/sync/2",le="2.048"} 39004
substrate_sub_libp2p_requests_out_success_total_bucket{protocol="/sup/sync/2",le="4.096"} 39004
substrate_sub_libp2p_requests_out_success_total_bucket{protocol="/sup/sync/2",le="8.192"} 39004
substrate_sub_libp2p_requests_out_success_total_bucket{protocol="/sup/sync/2",le="16.384"} 39004
substrate_sub_libp2p_requests_out_success_total_bucket{protocol="/sup/sync/2",le="32.768"} 39004
substrate_sub_libp2p_requests_out_success_total_bucket{protocol="/sup/sync/2",le="+Inf"} 39004
substrate_sub_libp2p_requests_out_success_total_sum{protocol="/sup/sync/2"} 4093.897156223979
substrate_sub_libp2p_requests_out_success_total_count{protocol="/sup/sync/2"} 39004
# HELP substrate_sub_txpool_block_transactions_pruned Total number of transactions that was requested to be pruned by block events
# TYPE substrate_sub_txpool_block_transactions_pruned counter
substrate_sub_txpool_block_transactions_pruned 24743
# HELP substrate_sub_txpool_block_transactions_resubmitted Total number of transactions that was requested to be resubmitted by block events
# TYPE substrate_sub_txpool_block_transactions_resubmitted counter
substrate_sub_txpool_block_transactions_resubmitted 0
# HELP substrate_sub_txpool_submitted_transactions Total number of transactions submitted
# TYPE substrate_sub_txpool_submitted_transactions counter
substrate_sub_txpool_submitted_transactions 532171
# HELP substrate_sub_txpool_validations_finished Total number of transactions that finished validation
# TYPE substrate_sub_txpool_validations_finished counter
substrate_sub_txpool_validations_finished 24825
# HELP substrate_sub_txpool_validations_invalid Total number of transactions that were removed from the pool as invalid
# TYPE substrate_sub_txpool_validations_invalid counter
substrate_sub_txpool_validations_invalid 0
# HELP substrate_sub_txpool_validations_scheduled Total number of transactions scheduled for validation
# TYPE substrate_sub_txpool_validations_scheduled counter
substrate_sub_txpool_validations_scheduled 24825
# HELP substrate_sync_extra_justifications Number of extra justifications requests
# TYPE substrate_sync_extra_justifications gauge
substrate_sync_extra_justifications{status="active"} 0
substrate_sync_extra_justifications{status="failed"} 0
substrate_sync_extra_justifications{status="importing"} 0
substrate_sync_extra_justifications{status="pending"} 0
# HELP substrate_sync_fork_targets Number of fork sync targets
# TYPE substrate_sync_fork_targets gauge
substrate_sync_fork_targets 0
# HELP substrate_sync_peers Number of peers we sync with
# TYPE substrate_sync_peers gauge
substrate_sync_peers 43
# HELP substrate_sync_propagated_transactions Number of transactions propagated to at least one peer
# TYPE substrate_sync_propagated_transactions counter
substrate_sync_propagated_transactions 442652
# HELP substrate_sync_queued_blocks Number of blocks in import queue
# TYPE substrate_sync_queued_blocks gauge
substrate_sync_queued_blocks 0
# HELP substrate_tasks_ended_total Total number of tasks for which Future::poll has returned Ready(()) or panicked
# TYPE substrate_tasks_ended_total counter
substrate_tasks_ended_total{reason="finished",task_name="aura"} 0
substrate_tasks_ended_total{reason="finished",task_name="basic-authorship-proposer"} 657
substrate_tasks_ended_total{reason="finished",task_name="basic-block-import-worker"} 0
substrate_tasks_ended_total{reason="finished",task_name="block_request_handler"} 0
substrate_tasks_ended_total{reason="finished",task_name="cf-p2p"} 0
substrate_tasks_ended_total{reason="finished",task_name="grandpa-voter"} 0
substrate_tasks_ended_total{reason="finished",task_name="informant"} 0
substrate_tasks_ended_total{reason="finished",task_name="libp2p-node"} 279834
substrate_tasks_ended_total{reason="finished",task_name="light_client_request_handler"} 0
substrate_tasks_ended_total{reason="finished",task_name="network-transactions-handler"} 0
substrate_tasks_ended_total{reason="finished",task_name="network-worker"} 0
substrate_tasks_ended_total{reason="finished",task_name="offchain-notifications"} 0
substrate_tasks_ended_total{reason="finished",task_name="offchain-on-block"} 9719
substrate_tasks_ended_total{reason="finished",task_name="on-transaction-imported"} 0
substrate_tasks_ended_total{reason="finished",task_name="prometheus-endpoint"} 0
substrate_tasks_ended_total{reason="finished",task_name="state_request_handler"} 0
substrate_tasks_ended_total{reason="finished",task_name="substrate-rpc-subscription"} 4
substrate_tasks_ended_total{reason="finished",task_name="telemetry-periodic-send"} 0
substrate_tasks_ended_total{reason="finished",task_name="transaction-pool-task-0"} 0
substrate_tasks_ended_total{reason="finished",task_name="transaction-pool-task-1"} 0
substrate_tasks_ended_total{reason="finished",task_name="txpool-background"} 0
substrate_tasks_ended_total{reason="finished",task_name="txpool-notifications"} 0
substrate_tasks_ended_total{reason="finished",task_name="warp_sync_request_handler"} 0
# HELP substrate_tasks_polling_duration Duration in seconds of each invocation of Future::poll
# TYPE substrate_tasks_polling_duration histogram
substrate_tasks_polling_duration_bucket{task_name="aura",le="0.001"} 6319
substrate_tasks_polling_duration_bucket{task_name="aura",le="0.004"} 10068
substrate_tasks_polling_duration_bucket{task_name="aura",le="0.016"} 10689
substrate_tasks_polling_duration_bucket{task_name="aura",le="0.064"} 10732
substrate_tasks_polling_duration_bucket{task_name="aura",le="0.256"} 10735
substrate_tasks_polling_duration_bucket{task_name="aura",le="1.024"} 10735
substrate_tasks_polling_duration_bucket{task_name="aura",le="4.096"} 10736
substrate_tasks_polling_duration_bucket{task_name="aura",le="16.384"} 10736
substrate_tasks_polling_duration_bucket{task_name="aura",le="65.536"} 10736
substrate_tasks_polling_duration_bucket{task_name="aura",le="+Inf"} 10736
substrate_tasks_polling_duration_sum{task_name="aura"} 18.083595129999857
substrate_tasks_polling_duration_count{task_name="aura"} 10736
substrate_tasks_polling_duration_bucket{task_name="basic-authorship-proposer",le="0.001"} 0
substrate_tasks_polling_duration_bucket{task_name="basic-authorship-proposer",le="0.004"} 0
substrate_tasks_polling_duration_bucket{task_name="basic-authorship-proposer",le="0.016"} 386
substrate_tasks_polling_duration_bucket{task_name="basic-authorship-proposer",le="0.064"} 637
substrate_tasks_polling_duration_bucket{task_name="basic-authorship-proposer",le="0.256"} 656
substrate_tasks_polling_duration_bucket{task_name="basic-authorship-proposer",le="1.024"} 657
substrate_tasks_polling_duration_bucket{task_name="basic-authorship-proposer",le="4.096"} 657
substrate_tasks_polling_duration_bucket{task_name="basic-authorship-proposer",le="16.384"} 657
substrate_tasks_polling_duration_bucket{task_name="basic-authorship-proposer",le="65.536"} 657
substrate_tasks_polling_duration_bucket{task_name="basic-authorship-proposer",le="+Inf"} 657
substrate_tasks_polling_duration_sum{task_name="basic-authorship-proposer"} 12.646348385000016
substrate_tasks_polling_duration_count{task_name="basic-authorship-proposer"} 657
substrate_tasks_polling_duration_bucket{task_name="basic-block-import-worker",le="0.001"} 54612
substrate_tasks_polling_duration_bucket{task_name="basic-block-import-worker",le="0.004"} 54788
substrate_tasks_polling_duration_bucket{task_name="basic-block-import-worker",le="0.016"} 60932
substrate_tasks_polling_duration_bucket{task_name="basic-block-import-worker",le="0.064"} 63821
substrate_tasks_polling_duration_bucket{task_name="basic-block-import-worker",le="0.256"} 63864
substrate_tasks_polling_duration_bucket{task_name="basic-block-import-worker",le="1.024"} 63870
substrate_tasks_polling_duration_bucket{task_name="basic-block-import-worker",le="4.096"} 63870
substrate_tasks_polling_duration_bucket{task_name="basic-block-import-worker",le="16.384"} 63871
substrate_tasks_polling_duration_bucket{task_name="basic-block-import-worker",le="65.536"} 63871
substrate_tasks_polling_duration_bucket{task_name="basic-block-import-worker",le="+Inf"} 63871
substrate_tasks_polling_duration_sum{task_name="basic-block-import-worker"} 149.69140627099435
substrate_tasks_polling_duration_count{task_name="basic-block-import-worker"} 63871
substrate_tasks_polling_duration_bucket{task_name="block_request_handler",le="0.001"} 50020
substrate_tasks_polling_duration_bucket{task_name="block_request_handler",le="0.004"} 50253
substrate_tasks_polling_duration_bucket{task_name="block_request_handler",le="0.016"} 50289
substrate_tasks_polling_duration_bucket{task_name="block_request_handler",le="0.064"} 50292
substrate_tasks_polling_duration_bucket{task_name="block_request_handler",le="0.256"} 50292
substrate_tasks_polling_duration_bucket{task_name="block_request_handler",le="1.024"} 50292
substrate_tasks_polling_duration_bucket{task_name="block_request_handler",le="4.096"} 50292
substrate_tasks_polling_duration_bucket{task_name="block_request_handler",le="16.384"} 50292
substrate_tasks_polling_duration_bucket{task_name="block_request_handler",le="65.536"} 50292
substrate_tasks_polling_duration_bucket{task_name="block_request_handler",le="+Inf"} 50292
substrate_tasks_polling_duration_sum{task_name="block_request_handler"} 3.885063334000688
substrate_tasks_polling_duration_count{task_name="block_request_handler"} 50292
substrate_tasks_polling_duration_bucket{task_name="cf-p2p",le="0.001"} 10634499
substrate_tasks_polling_duration_bucket{task_name="cf-p2p",le="0.004"} 10637116
substrate_tasks_polling_duration_bucket{task_name="cf-p2p",le="0.016"} 10637630
substrate_tasks_polling_duration_bucket{task_name="cf-p2p",le="0.064"} 10637665
substrate_tasks_polling_duration_bucket{task_name="cf-p2p",le="0.256"} 10637665
substrate_tasks_polling_duration_bucket{task_name="cf-p2p",le="1.024"} 10637665
substrate_tasks_polling_duration_bucket{task_name="cf-p2p",le="4.096"} 10637665
substrate_tasks_polling_duration_bucket{task_name="cf-p2p",le="16.384"} 10637665
substrate_tasks_polling_duration_bucket{task_name="cf-p2p",le="65.536"} 10637665
substrate_tasks_polling_duration_bucket{task_name="cf-p2p",le="+Inf"} 10637665
substrate_tasks_polling_duration_sum{task_name="cf-p2p"} 89.74799776996682
substrate_tasks_polling_duration_count{task_name="cf-p2p"} 10637665
substrate_tasks_polling_duration_bucket{task_name="grandpa-voter",le="0.001"} 15328108
substrate_tasks_polling_duration_bucket{task_name="grandpa-voter",le="0.004"} 15457337
substrate_tasks_polling_duration_bucket{task_name="grandpa-voter",le="0.016"} 15546350
substrate_tasks_polling_duration_bucket{task_name="grandpa-voter",le="0.064"} 15551040
substrate_tasks_polling_duration_bucket{task_name="grandpa-voter",le="0.256"} 15551072
substrate_tasks_polling_duration_bucket{task_name="grandpa-voter",le="1.024"} 15551072
substrate_tasks_polling_duration_bucket{task_name="grandpa-voter",le="4.096"} 15551072
substrate_tasks_polling_duration_bucket{task_name="grandpa-voter",le="16.384"} 15551072
substrate_tasks_polling_duration_bucket{task_name="grandpa-voter",le="65.536"} 15551072
substrate_tasks_polling_duration_bucket{task_name="grandpa-voter",le="+Inf"} 15551072
substrate_tasks_polling_duration_sum{task_name="grandpa-voter"} 1637.3154356714101
substrate_tasks_polling_duration_count{task_name="grandpa-voter"} 15551072
substrate_tasks_polling_duration_bucket{task_name="informant",le="0.001"} 32298
substrate_tasks_polling_duration_bucket{task_name="informant",le="0.004"} 33751
substrate_tasks_polling_duration_bucket{task_name="informant",le="0.016"} 33866
substrate_tasks_polling_duration_bucket{task_name="informant",le="0.064"} 33868
substrate_tasks_polling_duration_bucket{task_name="informant",le="0.256"} 33868
substrate_tasks_polling_duration_bucket{task_name="informant",le="1.024"} 33868
substrate_tasks_polling_duration_bucket{task_name="informant",le="4.096"} 33868
substrate_tasks_polling_duration_bucket{task_name="informant",le="16.384"} 33868
substrate_tasks_polling_duration_bucket{task_name="informant",le="65.536"} 33868
substrate_tasks_polling_duration_bucket{task_name="informant",le="+Inf"} 33868
substrate_tasks_polling_duration_sum{task_name="informant"} 7.272428919999938
substrate_tasks_polling_duration_count{task_name="informant"} 33868
substrate_tasks_polling_duration_bucket{task_name="libp2p-node",le="0.001"} 38392965
substrate_tasks_polling_duration_bucket{task_name="libp2p-node",le="0.004"} 38636746
substrate_tasks_polling_duration_bucket{task_name="libp2p-node",le="0.016"} 38660396
substrate_tasks_polling_duration_bucket{task_name="libp2p-node",le="0.064"} 38661503
substrate_tasks_polling_duration_bucket{task_name="libp2p-node",le="0.256"} 38661507
substrate_tasks_polling_duration_bucket{task_name="libp2p-node",le="1.024"} 38661507
substrate_tasks_polling_duration_bucket{task_name="libp2p-node",le="4.096"} 38661507
substrate_tasks_polling_duration_bucket{task_name="libp2p-node",le="16.384"} 38661507
substrate_tasks_polling_duration_bucket{task_name="libp2p-node",le="65.536"} 38661507
substrate_tasks_polling_duration_bucket{task_name="libp2p-node",le="+Inf"} 38661507
substrate_tasks_polling_duration_sum{task_name="libp2p-node"} 3428.4122337638837
substrate_tasks_polling_duration_count{task_name="libp2p-node"} 38661507
substrate_tasks_polling_duration_bucket{task_name="light_client_request_handler",le="0.001"} 1
substrate_tasks_polling_duration_bucket{task_name="light_client_request_handler",le="0.004"} 1
substrate_tasks_polling_duration_bucket{task_name="light_client_request_handler",le="0.016"} 1
substrate_tasks_polling_duration_bucket{task_name="light_client_request_handler",le="0.064"} 1
substrate_tasks_polling_duration_bucket{task_name="light_client_request_handler",le="0.256"} 1
substrate_tasks_polling_duration_bucket{task_name="light_client_request_handler",le="1.024"} 1
substrate_tasks_polling_duration_bucket{task_name="light_client_request_handler",le="4.096"} 1
substrate_tasks_polling_duration_bucket{task_name="light_client_request_handler",le="16.384"} 1
substrate_tasks_polling_duration_bucket{task_name="light_client_request_handler",le="65.536"} 1
substrate_tasks_polling_duration_bucket{task_name="light_client_request_handler",le="+Inf"} 1
substrate_tasks_polling_duration_sum{task_name="light_client_request_handler"} 0.000350214
substrate_tasks_polling_duration_count{task_name="light_client_request_handler"} 1
substrate_tasks_polling_duration_bucket{task_name="network-transactions-handler",le="0.001"} 8675544
substrate_tasks_polling_duration_bucket{task_name="network-transactions-handler",le="0.004"} 8686208
substrate_tasks_polling_duration_bucket{task_name="network-transactions-handler",le="0.016"} 8688926
substrate_tasks_polling_duration_bucket{task_name="network-transactions-handler",le="0.064"} 8689425
substrate_tasks_polling_duration_bucket{task_name="network-transactions-handler",le="0.256"} 8689437
substrate_tasks_polling_duration_bucket{task_name="network-transactions-handler",le="1.024"} 8689437
substrate_tasks_polling_duration_bucket{task_name="network-transactions-handler",le="4.096"} 8689437
substrate_tasks_polling_duration_bucket{task_name="network-transactions-handler",le="16.384"} 8689437
substrate_tasks_polling_duration_bucket{task_name="network-transactions-handler",le="65.536"} 8689437
substrate_tasks_polling_duration_bucket{task_name="network-transactions-handler",le="+Inf"} 8689437
substrate_tasks_polling_duration_sum{task_name="network-transactions-handler"} 176.3915737739624
substrate_tasks_polling_duration_count{task_name="network-transactions-handler"} 8689437
substrate_tasks_polling_duration_bucket{task_name="network-worker",le="0.001"} 136055156
substrate_tasks_polling_duration_bucket{task_name="network-worker",le="0.004"} 136921795
substrate_tasks_polling_duration_bucket{task_name="network-worker",le="0.016"} 137070848
substrate_tasks_polling_duration_bucket{task_name="network-worker",le="0.064"} 137080730
substrate_tasks_polling_duration_bucket{task_name="network-worker",le="0.256"} 137081147
substrate_tasks_polling_duration_bucket{task_name="network-worker",le="1.024"} 137081171
substrate_tasks_polling_duration_bucket{task_name="network-worker",le="4.096"} 137081171
substrate_tasks_polling_duration_bucket{task_name="network-worker",le="16.384"} 137081171
substrate_tasks_polling_duration_bucket{task_name="network-worker",le="65.536"} 137081171
substrate_tasks_polling_duration_bucket{task_name="network-worker",le="+Inf"} 137081171
substrate_tasks_polling_duration_sum{task_name="network-worker"} 16719.030218779433
substrate_tasks_polling_duration_count{task_name="network-worker"} 137081171
substrate_tasks_polling_duration_bucket{task_name="offchain-notifications",le="0.001"} 6074
substrate_tasks_polling_duration_bucket{task_name="offchain-notifications",le="0.004"} 8902
substrate_tasks_polling_duration_bucket{task_name="offchain-notifications",le="0.016"} 9697
substrate_tasks_polling_duration_bucket{task_name="offchain-notifications",le="0.064"} 9720
substrate_tasks_polling_duration_bucket{task_name="offchain-notifications",le="0.256"} 9720
substrate_tasks_polling_duration_bucket{task_name="offchain-notifications",le="1.024"} 9720
substrate_tasks_polling_duration_bucket{task_name="offchain-notifications",le="4.096"} 9720
substrate_tasks_polling_duration_bucket{task_name="offchain-notifications",le="16.384"} 9720
substrate_tasks_polling_duration_bucket{task_name="offchain-notifications",le="65.536"} 9720
substrate_tasks_polling_duration_bucket{task_name="offchain-notifications",le="+Inf"} 9720
substrate_tasks_polling_duration_sum{task_name="offchain-notifications"} 12.950332894999987
substrate_tasks_polling_duration_count{task_name="offchain-notifications"} 9720
substrate_tasks_polling_duration_bucket{task_name="offchain-on-block",le="0.001"} 17853
substrate_tasks_polling_duration_bucket{task_name="offchain-on-block",le="0.004"} 17878
substrate_tasks_polling_duration_bucket{task_name="offchain-on-block",le="0.016"} 17882
substrate_tasks_polling_duration_bucket{task_name="offchain-on-block",le="0.064"} 17882
substrate_tasks_polling_duration_bucket{task_name="offchain-on-block",le="0.256"} 17882
substrate_tasks_polling_duration_bucket{task_name="offchain-on-block",le="1.024"} 17882
substrate_tasks_polling_duration_bucket{task_name="offchain-on-block",le="4.096"} 17882
substrate_tasks_polling_duration_bucket{task_name="offchain-on-block",le="16.384"} 17882
substrate_tasks_polling_duration_bucket{task_name="offchain-on-block",le="65.536"} 17882
substrate_tasks_polling_duration_bucket{task_name="offchain-on-block",le="+Inf"} 17882
substrate_tasks_polling_duration_sum{task_name="offchain-on-block"} 0.13696290900000105
substrate_tasks_polling_duration_count{task_name="offchain-on-block"} 17882
substrate_tasks_polling_duration_bucket{task_name="on-transaction-imported",le="0.001"} 10086
substrate_tasks_polling_duration_bucket{task_name="on-transaction-imported",le="0.004"} 10095
substrate_tasks_polling_duration_bucket{task_name="on-transaction-imported",le="0.016"} 10099
substrate_tasks_polling_duration_bucket{task_name="on-transaction-imported",le="0.064"} 10099
substrate_tasks_polling_duration_bucket{task_name="on-transaction-imported",le="0.256"} 10099
substrate_tasks_polling_duration_bucket{task_name="on-transaction-imported",le="1.024"} 10099
substrate_tasks_polling_duration_bucket{task_name="on-transaction-imported",le="4.096"} 10099
substrate_tasks_polling_duration_bucket{task_name="on-transaction-imported",le="16.384"} 10099
substrate_tasks_polling_duration_bucket{task_name="on-transaction-imported",le="65.536"} 10099
substrate_tasks_polling_duration_bucket{task_name="on-transaction-imported",le="+Inf"} 10099
substrate_tasks_polling_duration_sum{task_name="on-transaction-imported"} 0.1111977590000004
substrate_tasks_polling_duration_count{task_name="on-transaction-imported"} 10099
substrate_tasks_polling_duration_bucket{task_name="prometheus-endpoint",le="0.001"} 1
substrate_tasks_polling_duration_bucket{task_name="prometheus-endpoint",le="0.004"} 2
substrate_tasks_polling_duration_bucket{task_name="prometheus-endpoint",le="0.016"} 3
substrate_tasks_polling_duration_bucket{task_name="prometheus-endpoint",le="0.064"} 3
substrate_tasks_polling_duration_bucket{task_name="prometheus-endpoint",le="0.256"} 3
substrate_tasks_polling_duration_bucket{task_name="prometheus-endpoint",le="1.024"} 3
substrate_tasks_polling_duration_bucket{task_name="prometheus-endpoint",le="4.096"} 3
substrate_tasks_polling_duration_bucket{task_name="prometheus-endpoint",le="16.384"} 3
substrate_tasks_polling_duration_bucket{task_name="prometheus-endpoint",le="65.536"} 3
substrate_tasks_polling_duration_bucket{task_name="prometheus-endpoint",le="+Inf"} 3
substrate_tasks_polling_duration_sum{task_name="prometheus-endpoint"} 0.01128393
substrate_tasks_polling_duration_count{task_name="prometheus-endpoint"} 3
substrate_tasks_polling_duration_bucket{task_name="state_request_handler",le="0.001"} 1
substrate_tasks_polling_duration_bucket{task_name="state_request_handler",le="0.004"} 1
substrate_tasks_polling_duration_bucket{task_name="state_request_handler",le="0.016"} 1
substrate_tasks_polling_duration_bucket{task_name="state_request_handler",le="0.064"} 1
substrate_tasks_polling_duration_bucket{task_name="state_request_handler",le="0.256"} 1
substrate_tasks_polling_duration_bucket{task_name="state_request_handler",le="1.024"} 1
substrate_tasks_polling_duration_bucket{task_name="state_request_handler",le="4.096"} 1
substrate_tasks_polling_duration_bucket{task_name="state_request_handler",le="16.384"} 1
substrate_tasks_polling_duration_bucket{task_name="state_request_handler",le="65.536"} 1
substrate_tasks_polling_duration_bucket{task_name="state_request_handler",le="+Inf"} 1
substrate_tasks_polling_duration_sum{task_name="state_request_handler"} 0.00000069
substrate_tasks_polling_duration_count{task_name="state_request_handler"} 1
substrate_tasks_polling_duration_bucket{task_name="substrate-rpc-subscription",le="0.001"} 10836
substrate_tasks_polling_duration_bucket{task_name="substrate-rpc-subscription",le="0.004"} 12717
substrate_tasks_polling_duration_bucket{task_name="substrate-rpc-subscription",le="0.016"} 13060
substrate_tasks_polling_duration_bucket{task_name="substrate-rpc-subscription",le="0.064"} 13069
substrate_tasks_polling_duration_bucket{task_name="substrate-rpc-subscription",le="0.256"} 13069
substrate_tasks_polling_duration_bucket{task_name="substrate-rpc-subscription",le="1.024"} 13069
substrate_tasks_polling_duration_bucket{task_name="substrate-rpc-subscription",le="4.096"} 13069
substrate_tasks_polling_duration_bucket{task_name="substrate-rpc-subscription",le="16.384"} 13069
substrate_tasks_polling_duration_bucket{task_name="substrate-rpc-subscription",le="65.536"} 13069
substrate_tasks_polling_duration_bucket{task_name="substrate-rpc-subscription",le="+Inf"} 13069
substrate_tasks_polling_duration_sum{task_name="substrate-rpc-subscription"} 7.125443627000005
substrate_tasks_polling_duration_count{task_name="substrate-rpc-subscription"} 13069
substrate_tasks_polling_duration_bucket{task_name="telemetry-periodic-send",le="0.001"} 24124
substrate_tasks_polling_duration_bucket{task_name="telemetry-periodic-send",le="0.004"} 24140
substrate_tasks_polling_duration_bucket{task_name="telemetry-periodic-send",le="0.016"} 24142
substrate_tasks_polling_duration_bucket{task_name="telemetry-periodic-send",le="0.064"} 24142
substrate_tasks_polling_duration_bucket{task_name="telemetry-periodic-send",le="0.256"} 24142
substrate_tasks_polling_duration_bucket{task_name="telemetry-periodic-send",le="1.024"} 24142
substrate_tasks_polling_duration_bucket{task_name="telemetry-periodic-send",le="4.096"} 24142
substrate_tasks_polling_duration_bucket{task_name="telemetry-periodic-send",le="16.384"} 24142
substrate_tasks_polling_duration_bucket{task_name="telemetry-periodic-send",le="65.536"} 24142
substrate_tasks_polling_duration_bucket{task_name="telemetry-periodic-send",le="+Inf"} 24142
substrate_tasks_polling_duration_sum{task_name="telemetry-periodic-send"} 0.4852967929999993
substrate_tasks_polling_duration_count{task_name="telemetry-periodic-send"} 24142
substrate_tasks_polling_duration_bucket{task_name="transaction-pool-task-0",le="0.001"} 12299
substrate_tasks_polling_duration_bucket{task_name="transaction-pool-task-0",le="0.004"} 21312
substrate_tasks_polling_duration_bucket{task_name="transaction-pool-task-0",le="0.016"} 22529
substrate_tasks_polling_duration_bucket{task_name="transaction-pool-task-0",le="0.064"} 22653
substrate_tasks_polling_duration_bucket{task_name="transaction-pool-task-0",le="0.256"} 22658
substrate_tasks_polling_duration_bucket{task_name="transaction-pool-task-0",le="1.024"} 22658
substrate_tasks_polling_duration_bucket{task_name="transaction-pool-task-0",le="4.096"} 22658
substrate_tasks_polling_duration_bucket{task_name="transaction-pool-task-0",le="16.384"} 22658
substrate_tasks_polling_duration_bucket{task_name="transaction-pool-task-0",le="65.536"} 22658
substrate_tasks_polling_duration_bucket{task_name="transaction-pool-task-0",le="+Inf"} 22658
substrate_tasks_polling_duration_sum{task_name="transaction-pool-task-0"} 28.57376808899992
substrate_tasks_polling_duration_count{task_name="transaction-pool-task-0"} 22658
substrate_tasks_polling_duration_bucket{task_name="transaction-pool-task-1",le="0.001"} 12312
substrate_tasks_polling_duration_bucket{task_name="transaction-pool-task-1",le="0.004"} 21325
substrate_tasks_polling_duration_bucket{task_name="transaction-pool-task-1",le="0.016"} 22501
substrate_tasks_polling_duration_bucket{task_name="transaction-pool-task-1",le="0.064"} 22634
substrate_tasks_polling_duration_bucket{task_name="transaction-pool-task-1",le="0.256"} 22642
substrate_tasks_polling_duration_bucket{task_name="transaction-pool-task-1",le="1.024"} 22642
substrate_tasks_polling_duration_bucket{task_name="transaction-pool-task-1",le="4.096"} 22642
substrate_tasks_polling_duration_bucket{task_name="transaction-pool-task-1",le="16.384"} 22642
substrate_tasks_polling_duration_bucket{task_name="transaction-pool-task-1",le="65.536"} 22642
substrate_tasks_polling_duration_bucket{task_name="transaction-pool-task-1",le="+Inf"} 22642
substrate_tasks_polling_duration_sum{task_name="transaction-pool-task-1"} 28.660711724999913
substrate_tasks_polling_duration_count{task_name="transaction-pool-task-1"} 22642
substrate_tasks_polling_duration_bucket{task_name="txpool-background",le="0.001"} 311089
substrate_tasks_polling_duration_bucket{task_name="txpool-background",le="0.004"} 311444
substrate_tasks_polling_duration_bucket{task_name="txpool-background",le="0.016"} 311506
substrate_tasks_polling_duration_bucket{task_name="txpool-background",le="0.064"} 311511
substrate_tasks_polling_duration_bucket{task_name="txpool-background",le="0.256"} 311511
substrate_tasks_polling_duration_bucket{task_name="txpool-background",le="1.024"} 311511
substrate_tasks_polling_duration_bucket{task_name="txpool-background",le="4.096"} 311511
substrate_tasks_polling_duration_bucket{task_name="txpool-background",le="16.384"} 311511
substrate_tasks_polling_duration_bucket{task_name="txpool-background",le="65.536"} 311511
substrate_tasks_polling_duration_bucket{task_name="txpool-background",le="+Inf"} 311511
substrate_tasks_polling_duration_sum{task_name="txpool-background"} 10.447626437000368
substrate_tasks_polling_duration_count{task_name="txpool-background"} 311511
substrate_tasks_polling_duration_bucket{task_name="txpool-notifications",le="0.001"} 34874
substrate_tasks_polling_duration_bucket{task_name="txpool-notifications",le="0.004"} 35451
substrate_tasks_polling_duration_bucket{task_name="txpool-notifications",le="0.016"} 35509
substrate_tasks_polling_duration_bucket{task_name="txpool-notifications",le="0.064"} 35515
substrate_tasks_polling_duration_bucket{task_name="txpool-notifications",le="0.256"} 35515
substrate_tasks_polling_duration_bucket{task_name="txpool-notifications",le="1.024"} 35515
substrate_tasks_polling_duration_bucket{task_name="txpool-notifications",le="4.096"} 35515
substrate_tasks_polling_duration_bucket{task_name="txpool-notifications",le="16.384"} 35515
substrate_tasks_polling_duration_bucket{task_name="txpool-notifications",le="65.536"} 35515
substrate_tasks_polling_duration_bucket{task_name="txpool-notifications",le="+Inf"} 35515
substrate_tasks_polling_duration_sum{task_name="txpool-notifications"} 3.183183340000002
substrate_tasks_polling_duration_count{task_name="txpool-notifications"} 35515
substrate_tasks_polling_duration_bucket{task_name="warp_sync_request_handler",le="0.001"} 1
substrate_tasks_polling_duration_bucket{task_name="warp_sync_request_handler",le="0.004"} 1
substrate_tasks_polling_duration_bucket{task_name="warp_sync_request_handler",le="0.016"} 1
substrate_tasks_polling_duration_bucket{task_name="warp_sync_request_handler",le="0.064"} 1
substrate_tasks_polling_duration_bucket{task_name="warp_sync_request_handler",le="0.256"} 1
substrate_tasks_polling_duration_bucket{task_name="warp_sync_request_handler",le="1.024"} 1
substrate_tasks_polling_duration_bucket{task_name="warp_sync_request_handler",le="4.096"} 1
substrate_tasks_polling_duration_bucket{task_name="warp_sync_request_handler",le="16.384"} 1
substrate_tasks_polling_duration_bucket{task_name="warp_sync_request_handler",le="65.536"} 1
substrate_tasks_polling_duration_bucket{task_name="warp_sync_request_handler",le="+Inf"} 1
substrate_tasks_polling_duration_sum{task_name="warp_sync_request_handler"} 0.000481056
substrate_tasks_polling_duration_count{task_name="warp_sync_request_handler"} 1
# HELP substrate_tasks_polling_started_total Total number of times we started invoking Future::poll
# TYPE substrate_tasks_polling_started_total counter
substrate_tasks_polling_started_total{task_name="aura"} 10736
substrate_tasks_polling_started_total{task_name="basic-authorship-proposer"} 657
substrate_tasks_polling_started_total{task_name="basic-block-import-worker"} 63871
substrate_tasks_polling_started_total{task_name="block_request_handler"} 50292
substrate_tasks_polling_started_total{task_name="cf-p2p"} 10637665
substrate_tasks_polling_started_total{task_name="grandpa-voter"} 15551072
substrate_tasks_polling_started_total{task_name="informant"} 33868
substrate_tasks_polling_started_total{task_name="libp2p-node"} 38661507
substrate_tasks_polling_started_total{task_name="light_client_request_handler"} 1
substrate_tasks_polling_started_total{task_name="network-transactions-handler"} 8689437
substrate_tasks_polling_started_total{task_name="network-worker"} 137081174
substrate_tasks_polling_started_total{task_name="offchain-notifications"} 9720
substrate_tasks_polling_started_total{task_name="offchain-on-block"} 17882
substrate_tasks_polling_started_total{task_name="on-transaction-imported"} 10099
substrate_tasks_polling_started_total{task_name="prometheus-endpoint"} 3
substrate_tasks_polling_started_total{task_name="state_request_handler"} 1
substrate_tasks_polling_started_total{task_name="substrate-rpc-subscription"} 13069
substrate_tasks_polling_started_total{task_name="telemetry-periodic-send"} 24142
substrate_tasks_polling_started_total{task_name="transaction-pool-task-0"} 22658
substrate_tasks_polling_started_total{task_name="transaction-pool-task-1"} 22642
substrate_tasks_polling_started_total{task_name="txpool-background"} 311511
substrate_tasks_polling_started_total{task_name="txpool-notifications"} 35515
substrate_tasks_polling_started_total{task_name="warp_sync_request_handler"} 1
# HELP substrate_tasks_spawned_total Total number of tasks that have been spawned on the Service
# TYPE substrate_tasks_spawned_total counter
substrate_tasks_spawned_total{task_name="aura"} 1
substrate_tasks_spawned_total{task_name="basic-authorship-proposer"} 657
substrate_tasks_spawned_total{task_name="basic-block-import-worker"} 1
substrate_tasks_spawned_total{task_name="block_request_handler"} 1
substrate_tasks_spawned_total{task_name="cf-p2p"} 1
substrate_tasks_spawned_total{task_name="grandpa-voter"} 1
substrate_tasks_spawned_total{task_name="informant"} 1
substrate_tasks_spawned_total{task_name="libp2p-node"} 280053
substrate_tasks_spawned_total{task_name="light_client_request_handler"} 1
substrate_tasks_spawned_total{task_name="network-transactions-handler"} 1
substrate_tasks_spawned_total{task_name="network-worker"} 1
substrate_tasks_spawned_total{task_name="offchain-notifications"} 1
substrate_tasks_spawned_total{task_name="offchain-on-block"} 9719
substrate_tasks_spawned_total{task_name="on-transaction-imported"} 1
substrate_tasks_spawned_total{task_name="prometheus-endpoint"} 1
substrate_tasks_spawned_total{task_name="state_request_handler"} 1
substrate_tasks_spawned_total{task_name="substrate-rpc-subscription"} 6
substrate_tasks_spawned_total{task_name="telemetry-periodic-send"} 1
substrate_tasks_spawned_total{task_name="transaction-pool-task-0"} 1
substrate_tasks_spawned_total{task_name="transaction-pool-task-1"} 1
substrate_tasks_spawned_total{task_name="txpool-background"} 1
substrate_tasks_spawned_total{task_name="txpool-notifications"} 1
substrate_tasks_spawned_total{task_name="warp_sync_request_handler"} 1
# HELP substrate_tokio_threads_alive Number of threads alive right now
# TYPE substrate_tokio_threads_alive gauge
substrate_tokio_threads_alive 9
# HELP substrate_tokio_threads_total Total number of threads created
# TYPE substrate_tokio_threads_total counter
substrate_tokio_threads_total 666
# HELP substrate_unbounded_channel_len Items in each mpsc::unbounded instance
# TYPE substrate_unbounded_channel_len counter
substrate_unbounded_channel_len{action="dropped",entity="mpsc_import_notification_stream"} 21
substrate_unbounded_channel_len{action="received",entity="mpsc_background_tasks"} 290454
substrate_unbounded_channel_len{action="received",entity="mpsc_buffered_link"} 21298
substrate_unbounded_channel_len{action="received",entity="mpsc_finality_notification_stream"} 29154
substrate_unbounded_channel_len{action="received",entity="mpsc_grandpa_gossip_validator"} 3435853
substrate_unbounded_channel_len{action="received",entity="mpsc_grandpa_neighbor_packet_worker"} 52561
substrate_unbounded_channel_len{action="received",entity="mpsc_import_notification_stream"} 60638
substrate_unbounded_channel_len{action="received",entity="mpsc_import_queue_worker_blocks"} 21297
substrate_unbounded_channel_len{action="received",entity="mpsc_import_queue_worker_justification"} 1
substrate_unbounded_channel_len{action="received",entity="mpsc_network_worker"} 142519
substrate_unbounded_channel_len{action="received",entity="mpsc_peerset_messages"} 14432558
substrate_unbounded_channel_len{action="received",entity="mpsc_revalidation_queue"} 9719
substrate_unbounded_channel_len{action="received",entity="mpsc_system_rpc"} 3
substrate_unbounded_channel_len{action="send",entity="mpsc_buffered_link"} 21298
substrate_unbounded_channel_len{action="send",entity="mpsc_finality_notification_stream"} 29154
substrate_unbounded_channel_len{action="send",entity="mpsc_grandpa_gossip_validator"} 3435853
substrate_unbounded_channel_len{action="send",entity="mpsc_grandpa_neighbor_packet_worker"} 52561
substrate_unbounded_channel_len{action="send",entity="mpsc_import_notification_stream"} 60638
substrate_unbounded_channel_len{action="send",entity="mpsc_import_queue_worker_blocks"} 21297
substrate_unbounded_channel_len{action="send",entity="mpsc_import_queue_worker_justification"} 1
substrate_unbounded_channel_len{action="send",entity="mpsc_network_worker"} 142519
substrate_unbounded_channel_len{action="send",entity="mpsc_peerset_messages"} 14432558
substrate_unbounded_channel_len{action="send",entity="mpsc_revalidation_queue"} 9719
substrate_unbounded_channel_len{action="send",entity="mpsc_system_rpc"} 3
```
