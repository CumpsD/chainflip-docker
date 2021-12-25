# Example Geth Prometheus Output

```text
# TYPE chain_account_commits_count counter
chain_account_commits_count 0

# TYPE chain_account_commits summary
chain_account_commits {quantile="0.5"} 0
chain_account_commits {quantile="0.75"} 0
chain_account_commits {quantile="0.95"} 0
chain_account_commits {quantile="0.99"} 0
chain_account_commits {quantile="0.999"} 0
chain_account_commits {quantile="0.9999"} 0

# TYPE chain_account_hashes_count counter
chain_account_hashes_count 0

# TYPE chain_account_hashes summary
chain_account_hashes {quantile="0.5"} 0
chain_account_hashes {quantile="0.75"} 0
chain_account_hashes {quantile="0.95"} 0
chain_account_hashes {quantile="0.99"} 0
chain_account_hashes {quantile="0.999"} 0
chain_account_hashes {quantile="0.9999"} 0

# TYPE chain_account_reads_count counter
chain_account_reads_count 0

# TYPE chain_account_reads summary
chain_account_reads {quantile="0.5"} 0
chain_account_reads {quantile="0.75"} 0
chain_account_reads {quantile="0.95"} 0
chain_account_reads {quantile="0.99"} 0
chain_account_reads {quantile="0.999"} 0
chain_account_reads {quantile="0.9999"} 0

# TYPE chain_account_updates_count counter
chain_account_updates_count 0

# TYPE chain_account_updates summary
chain_account_updates {quantile="0.5"} 0
chain_account_updates {quantile="0.75"} 0
chain_account_updates {quantile="0.95"} 0
chain_account_updates {quantile="0.99"} 0
chain_account_updates {quantile="0.999"} 0
chain_account_updates {quantile="0.9999"} 0

# TYPE chain_execution_count counter
chain_execution_count 0

# TYPE chain_execution summary
chain_execution {quantile="0.5"} 0
chain_execution {quantile="0.75"} 0
chain_execution {quantile="0.95"} 0
chain_execution {quantile="0.99"} 0
chain_execution {quantile="0.999"} 0
chain_execution {quantile="0.9999"} 0

# TYPE chain_head_block gauge
chain_head_block 0

# TYPE chain_head_header gauge
chain_head_header 22656

# TYPE chain_head_receipt gauge
chain_head_receipt 21612

# TYPE chain_inserts_count counter
chain_inserts_count 0

# TYPE chain_inserts summary
chain_inserts {quantile="0.5"} 0
chain_inserts {quantile="0.75"} 0
chain_inserts {quantile="0.95"} 0
chain_inserts {quantile="0.99"} 0
chain_inserts {quantile="0.999"} 0
chain_inserts {quantile="0.9999"} 0

# TYPE chain_prefetch_executes_count counter
chain_prefetch_executes_count 0

# TYPE chain_prefetch_executes summary
chain_prefetch_executes {quantile="0.5"} 0
chain_prefetch_executes {quantile="0.75"} 0
chain_prefetch_executes {quantile="0.95"} 0
chain_prefetch_executes {quantile="0.99"} 0
chain_prefetch_executes {quantile="0.999"} 0
chain_prefetch_executes {quantile="0.9999"} 0

# TYPE chain_prefetch_interrupts gauge
chain_prefetch_interrupts 0

# TYPE chain_reorg_add gauge
chain_reorg_add 0

# TYPE chain_reorg_drop gauge
chain_reorg_drop 0

# TYPE chain_reorg_executes gauge
chain_reorg_executes 0

# TYPE chain_reorg_invalidTx gauge
chain_reorg_invalidTx 0

# TYPE chain_snapshot_account_reads_count counter
chain_snapshot_account_reads_count 0

# TYPE chain_snapshot_account_reads summary
chain_snapshot_account_reads {quantile="0.5"} 0
chain_snapshot_account_reads {quantile="0.75"} 0
chain_snapshot_account_reads {quantile="0.95"} 0
chain_snapshot_account_reads {quantile="0.99"} 0
chain_snapshot_account_reads {quantile="0.999"} 0
chain_snapshot_account_reads {quantile="0.9999"} 0

# TYPE chain_snapshot_commits_count counter
chain_snapshot_commits_count 0

# TYPE chain_snapshot_commits summary
chain_snapshot_commits {quantile="0.5"} 0
chain_snapshot_commits {quantile="0.75"} 0
chain_snapshot_commits {quantile="0.95"} 0
chain_snapshot_commits {quantile="0.99"} 0
chain_snapshot_commits {quantile="0.999"} 0
chain_snapshot_commits {quantile="0.9999"} 0

# TYPE chain_snapshot_storage_reads_count counter
chain_snapshot_storage_reads_count 0

# TYPE chain_snapshot_storage_reads summary
chain_snapshot_storage_reads {quantile="0.5"} 0
chain_snapshot_storage_reads {quantile="0.75"} 0
chain_snapshot_storage_reads {quantile="0.95"} 0
chain_snapshot_storage_reads {quantile="0.99"} 0
chain_snapshot_storage_reads {quantile="0.999"} 0
chain_snapshot_storage_reads {quantile="0.9999"} 0

# TYPE chain_storage_commits_count counter
chain_storage_commits_count 0

# TYPE chain_storage_commits summary
chain_storage_commits {quantile="0.5"} 0
chain_storage_commits {quantile="0.75"} 0
chain_storage_commits {quantile="0.95"} 0
chain_storage_commits {quantile="0.99"} 0
chain_storage_commits {quantile="0.999"} 0
chain_storage_commits {quantile="0.9999"} 0

# TYPE chain_storage_hashes_count counter
chain_storage_hashes_count 0

# TYPE chain_storage_hashes summary
chain_storage_hashes {quantile="0.5"} 0
chain_storage_hashes {quantile="0.75"} 0
chain_storage_hashes {quantile="0.95"} 0
chain_storage_hashes {quantile="0.99"} 0
chain_storage_hashes {quantile="0.999"} 0
chain_storage_hashes {quantile="0.9999"} 0

# TYPE chain_storage_reads_count counter
chain_storage_reads_count 0

# TYPE chain_storage_reads summary
chain_storage_reads {quantile="0.5"} 0
chain_storage_reads {quantile="0.75"} 0
chain_storage_reads {quantile="0.95"} 0
chain_storage_reads {quantile="0.99"} 0
chain_storage_reads {quantile="0.999"} 0
chain_storage_reads {quantile="0.9999"} 0

# TYPE chain_storage_updates_count counter
chain_storage_updates_count 0

# TYPE chain_storage_updates summary
chain_storage_updates {quantile="0.5"} 0
chain_storage_updates {quantile="0.75"} 0
chain_storage_updates {quantile="0.95"} 0
chain_storage_updates {quantile="0.99"} 0
chain_storage_updates {quantile="0.999"} 0
chain_storage_updates {quantile="0.9999"} 0

# TYPE chain_validation_count counter
chain_validation_count 0

# TYPE chain_validation summary
chain_validation {quantile="0.5"} 0
chain_validation {quantile="0.75"} 0
chain_validation {quantile="0.95"} 0
chain_validation {quantile="0.99"} 0
chain_validation {quantile="0.999"} 0
chain_validation {quantile="0.9999"} 0

# TYPE chain_write_count counter
chain_write_count 0

# TYPE chain_write summary
chain_write {quantile="0.5"} 0
chain_write {quantile="0.75"} 0
chain_write {quantile="0.95"} 0
chain_write {quantile="0.99"} 0
chain_write {quantile="0.999"} 0
chain_write {quantile="0.9999"} 0

# TYPE db_preimage_hits gauge
db_preimage_hits 257

# TYPE db_preimage_total gauge
db_preimage_total 257

# TYPE eth_db_chaindata_ancient_read gauge
eth_db_chaindata_ancient_read 0

# TYPE eth_db_chaindata_ancient_size gauge
eth_db_chaindata_ancient_size 8096144

# TYPE eth_db_chaindata_ancient_write gauge
eth_db_chaindata_ancient_write 5571761

# TYPE eth_db_chaindata_compact_input gauge
eth_db_chaindata_compact_input 0

# TYPE eth_db_chaindata_compact_level0 gauge
eth_db_chaindata_compact_level0 0

# TYPE eth_db_chaindata_compact_memory gauge
eth_db_chaindata_compact_memory 0

# TYPE eth_db_chaindata_compact_nonlevel0 gauge
eth_db_chaindata_compact_nonlevel0 0

# TYPE eth_db_chaindata_compact_output gauge
eth_db_chaindata_compact_output 0

# TYPE eth_db_chaindata_compact_seek gauge
eth_db_chaindata_compact_seek 0

# TYPE eth_db_chaindata_compact_time gauge
eth_db_chaindata_compact_time 0

# TYPE eth_db_chaindata_compact_writedelay_counter gauge
eth_db_chaindata_compact_writedelay_counter 0

# TYPE eth_db_chaindata_compact_writedelay_duration gauge
eth_db_chaindata_compact_writedelay_duration 0

# TYPE eth_db_chaindata_disk_read gauge
eth_db_chaindata_disk_read 0

# TYPE eth_db_chaindata_disk_size gauge
eth_db_chaindata_disk_size 0

# TYPE eth_db_chaindata_disk_write gauge
eth_db_chaindata_disk_write 15951931

# TYPE eth_downloader_bodies_drop gauge
eth_downloader_bodies_drop 0

# TYPE eth_downloader_bodies_in gauge
eth_downloader_bodies_in 31

# TYPE eth_downloader_bodies_req_count counter
eth_downloader_bodies_req_count 18

# TYPE eth_downloader_bodies_req summary
eth_downloader_bodies_req {quantile="0.5"} 2.0835765e+08
eth_downloader_bodies_req {quantile="0.75"} 5.519965e+08
eth_downloader_bodies_req {quantile="0.95"} 1.2397028e+09
eth_downloader_bodies_req {quantile="0.99"} 1.2397028e+09
eth_downloader_bodies_req {quantile="0.999"} 1.2397028e+09
eth_downloader_bodies_req {quantile="0.9999"} 1.2397028e+09

# TYPE eth_downloader_bodies_timeout gauge
eth_downloader_bodies_timeout 0

# TYPE eth_downloader_headers_drop gauge
eth_downloader_headers_drop 0

# TYPE eth_downloader_headers_in gauge
eth_downloader_headers_in 16101

# TYPE eth_downloader_headers_req_count counter
eth_downloader_headers_req_count 120

# TYPE eth_downloader_headers_req summary
eth_downloader_headers_req {quantile="0.5"} 1.100577e+08
eth_downloader_headers_req {quantile="0.75"} 2.0047215e+08
eth_downloader_headers_req {quantile="0.95"} 8.110462299999992e+08
eth_downloader_headers_req {quantile="0.99"} 1.180713811999998e+09
eth_downloader_headers_req {quantile="0.999"} 1.2293084e+09
eth_downloader_headers_req {quantile="0.9999"} 1.2293084e+09

# TYPE eth_downloader_headers_timeout gauge
eth_downloader_headers_timeout 0

# TYPE eth_downloader_receipts_drop gauge
eth_downloader_receipts_drop 0

# TYPE eth_downloader_receipts_in gauge
eth_downloader_receipts_in 31

# TYPE eth_downloader_receipts_req_count counter
eth_downloader_receipts_req_count 18

# TYPE eth_downloader_receipts_req summary
eth_downloader_receipts_req {quantile="0.5"} 2.0882745e+08
eth_downloader_receipts_req {quantile="0.75"} 5.55911025e+08
eth_downloader_receipts_req {quantile="0.95"} 1.2409877e+09
eth_downloader_receipts_req {quantile="0.99"} 1.2409877e+09
eth_downloader_receipts_req {quantile="0.999"} 1.2409877e+09
eth_downloader_receipts_req {quantile="0.9999"} 1.2409877e+09

# TYPE eth_downloader_receipts_timeout gauge
eth_downloader_receipts_timeout 0

# TYPE eth_downloader_states_drop gauge
eth_downloader_states_drop 0

# TYPE eth_downloader_states_in gauge
eth_downloader_states_in 0

# TYPE eth_downloader_throttle gauge
eth_downloader_throttle 0

# TYPE eth_fetcher_block_announces_dos gauge
eth_fetcher_block_announces_dos 0

# TYPE eth_fetcher_block_announces_drop gauge
eth_fetcher_block_announces_drop 1

# TYPE eth_fetcher_block_announces_in gauge
eth_fetcher_block_announces_in 1

# TYPE eth_fetcher_block_announces_out_count counter
eth_fetcher_block_announces_out_count 0

# TYPE eth_fetcher_block_announces_out summary
eth_fetcher_block_announces_out {quantile="0.5"} 0
eth_fetcher_block_announces_out {quantile="0.75"} 0
eth_fetcher_block_announces_out {quantile="0.95"} 0
eth_fetcher_block_announces_out {quantile="0.99"} 0
eth_fetcher_block_announces_out {quantile="0.999"} 0
eth_fetcher_block_announces_out {quantile="0.9999"} 0

# TYPE eth_fetcher_block_bodies gauge
eth_fetcher_block_bodies 0

# TYPE eth_fetcher_block_broadcasts_dos gauge
eth_fetcher_block_broadcasts_dos 0

# TYPE eth_fetcher_block_broadcasts_drop gauge
eth_fetcher_block_broadcasts_drop 0

# TYPE eth_fetcher_block_broadcasts_in gauge
eth_fetcher_block_broadcasts_in 0

# TYPE eth_fetcher_block_broadcasts_out_count counter
eth_fetcher_block_broadcasts_out_count 0

# TYPE eth_fetcher_block_broadcasts_out summary
eth_fetcher_block_broadcasts_out {quantile="0.5"} 0
eth_fetcher_block_broadcasts_out {quantile="0.75"} 0
eth_fetcher_block_broadcasts_out {quantile="0.95"} 0
eth_fetcher_block_broadcasts_out {quantile="0.99"} 0
eth_fetcher_block_broadcasts_out {quantile="0.999"} 0
eth_fetcher_block_broadcasts_out {quantile="0.9999"} 0

# TYPE eth_fetcher_block_filter_bodies_in gauge
eth_fetcher_block_filter_bodies_in 31

# TYPE eth_fetcher_block_filter_bodies_out gauge
eth_fetcher_block_filter_bodies_out 31

# TYPE eth_fetcher_block_filter_headers_in gauge
eth_fetcher_block_filter_headers_in 23

# TYPE eth_fetcher_block_filter_headers_out gauge
eth_fetcher_block_filter_headers_out 23

# TYPE eth_fetcher_block_headers gauge
eth_fetcher_block_headers 0

# TYPE eth_fetcher_transaction_announces_dos gauge
eth_fetcher_transaction_announces_dos 0

# TYPE eth_fetcher_transaction_announces_in gauge
eth_fetcher_transaction_announces_in 0

# TYPE eth_fetcher_transaction_announces_known gauge
eth_fetcher_transaction_announces_known 0

# TYPE eth_fetcher_transaction_announces_underpriced gauge
eth_fetcher_transaction_announces_underpriced 0

# TYPE eth_fetcher_transaction_broadcasts_in gauge
eth_fetcher_transaction_broadcasts_in 0

# TYPE eth_fetcher_transaction_broadcasts_known gauge
eth_fetcher_transaction_broadcasts_known 0

# TYPE eth_fetcher_transaction_broadcasts_otherreject gauge
eth_fetcher_transaction_broadcasts_otherreject 0

# TYPE eth_fetcher_transaction_broadcasts_underpriced gauge
eth_fetcher_transaction_broadcasts_underpriced 0

# TYPE eth_fetcher_transaction_fetching_hashes gauge
eth_fetcher_transaction_fetching_hashes 0

# TYPE eth_fetcher_transaction_fetching_peers gauge
eth_fetcher_transaction_fetching_peers 0

# TYPE eth_fetcher_transaction_queueing_hashes gauge
eth_fetcher_transaction_queueing_hashes 0

# TYPE eth_fetcher_transaction_queueing_peers gauge
eth_fetcher_transaction_queueing_peers 0

# TYPE eth_fetcher_transaction_replies_in gauge
eth_fetcher_transaction_replies_in 0

# TYPE eth_fetcher_transaction_replies_known gauge
eth_fetcher_transaction_replies_known 0

# TYPE eth_fetcher_transaction_replies_otherreject gauge
eth_fetcher_transaction_replies_otherreject 0

# TYPE eth_fetcher_transaction_replies_underpriced gauge
eth_fetcher_transaction_replies_underpriced 0

# TYPE eth_fetcher_transaction_request_done gauge
eth_fetcher_transaction_request_done 0

# TYPE eth_fetcher_transaction_request_fail gauge
eth_fetcher_transaction_request_fail 0

# TYPE eth_fetcher_transaction_request_out gauge
eth_fetcher_transaction_request_out 0

# TYPE eth_fetcher_transaction_request_timeout gauge
eth_fetcher_transaction_request_timeout 0

# TYPE eth_fetcher_transaction_waiting_hashes gauge
eth_fetcher_transaction_waiting_hashes 0

# TYPE eth_fetcher_transaction_waiting_peers gauge
eth_fetcher_transaction_waiting_peers 0

# TYPE les_client_req_rtt_count counter
les_client_req_rtt_count 0

# TYPE les_client_req_rtt summary
les_client_req_rtt {quantile="0.5"} 0
les_client_req_rtt {quantile="0.75"} 0
les_client_req_rtt {quantile="0.95"} 0
les_client_req_rtt {quantile="0.99"} 0
les_client_req_rtt {quantile="0.999"} 0
les_client_req_rtt {quantile="0.9999"} 0

# TYPE les_client_req_sendDelay_count counter
les_client_req_sendDelay_count 0

# TYPE les_client_req_sendDelay summary
les_client_req_sendDelay {quantile="0.5"} 0
les_client_req_sendDelay {quantile="0.75"} 0
les_client_req_sendDelay {quantile="0.95"} 0
les_client_req_sendDelay {quantile="0.99"} 0
les_client_req_sendDelay {quantile="0.999"} 0
les_client_req_sendDelay {quantile="0.9999"} 0

# TYPE les_client_serverPool_connected gauge
les_client_serverPool_connected 0

# TYPE les_client_serverPool_dialed gauge
les_client_serverPool_dialed 0

# TYPE les_client_serverPool_selectable gauge
les_client_serverPool_selectable 0

# TYPE les_client_serverPool_sessionValue gauge
les_client_serverPool_sessionValue 0

# TYPE les_client_serverPool_timeout gauge
les_client_serverPool_timeout 0

# TYPE les_client_serverPool_totalValue gauge
les_client_serverPool_totalValue 0

# TYPE les_connection_duration_count counter
les_connection_duration_count 0

# TYPE les_connection_duration summary
les_connection_duration {quantile="0.5"} 0
les_connection_duration {quantile="0.75"} 0
les_connection_duration {quantile="0.95"} 0
les_connection_duration {quantile="0.99"} 0
les_connection_duration {quantile="0.999"} 0
les_connection_duration {quantile="0.9999"} 0

# TYPE les_connection_server gauge
les_connection_server 0

# TYPE les_misc_in_packets_body gauge
les_misc_in_packets_body 0

# TYPE les_misc_in_packets_code gauge
les_misc_in_packets_code 0

# TYPE les_misc_in_packets_header gauge
les_misc_in_packets_header 0

# TYPE les_misc_in_packets_helperTrie gauge
les_misc_in_packets_helperTrie 0

# TYPE les_misc_in_packets_proof gauge
les_misc_in_packets_proof 0

# TYPE les_misc_in_packets_receipt gauge
les_misc_in_packets_receipt 0

# TYPE les_misc_in_packets_total gauge
les_misc_in_packets_total 0

# TYPE les_misc_in_packets_txStatus gauge
les_misc_in_packets_txStatus 0

# TYPE les_misc_in_packets_txs gauge
les_misc_in_packets_txs 0

# TYPE les_misc_in_traffic_body gauge
les_misc_in_traffic_body 0

# TYPE les_misc_in_traffic_code gauge
les_misc_in_traffic_code 0

# TYPE les_misc_in_traffic_header gauge
les_misc_in_traffic_header 0

# TYPE les_misc_in_traffic_helperTrie gauge
les_misc_in_traffic_helperTrie 0

# TYPE les_misc_in_traffic_proof gauge
les_misc_in_traffic_proof 0

# TYPE les_misc_in_traffic_receipt gauge
les_misc_in_traffic_receipt 0

# TYPE les_misc_in_traffic_total gauge
les_misc_in_traffic_total 0

# TYPE les_misc_in_traffic_txStatus gauge
les_misc_in_traffic_txStatus 0

# TYPE les_misc_in_traffic_txs gauge
les_misc_in_traffic_txs 0

# TYPE les_misc_out_packets_body gauge
les_misc_out_packets_body 0

# TYPE les_misc_out_packets_code gauge
les_misc_out_packets_code 0

# TYPE les_misc_out_packets_header gauge
les_misc_out_packets_header 0

# TYPE les_misc_out_packets_helperTrie gauge
les_misc_out_packets_helperTrie 0

# TYPE les_misc_out_packets_proof gauge
les_misc_out_packets_proof 0

# TYPE les_misc_out_packets_receipt gauge
les_misc_out_packets_receipt 0

# TYPE les_misc_out_packets_total gauge
les_misc_out_packets_total 0

# TYPE les_misc_out_packets_txStatus gauge
les_misc_out_packets_txStatus 0

# TYPE les_misc_out_packets_txs gauge
les_misc_out_packets_txs 0

# TYPE les_misc_out_traffic_body gauge
les_misc_out_traffic_body 0

# TYPE les_misc_out_traffic_code gauge
les_misc_out_traffic_code 0

# TYPE les_misc_out_traffic_header gauge
les_misc_out_traffic_header 0

# TYPE les_misc_out_traffic_helperTrie gauge
les_misc_out_traffic_helperTrie 0

# TYPE les_misc_out_traffic_proof gauge
les_misc_out_traffic_proof 0

# TYPE les_misc_out_traffic_receipt gauge
les_misc_out_traffic_receipt 0

# TYPE les_misc_out_traffic_total gauge
les_misc_out_traffic_total 0

# TYPE les_misc_out_traffic_txStatus gauge
les_misc_out_traffic_txStatus 0

# TYPE les_misc_out_traffic_txs gauge
les_misc_out_traffic_txs 0

# TYPE les_misc_serve_body_count counter
les_misc_serve_body_count 0

# TYPE les_misc_serve_body summary
les_misc_serve_body {quantile="0.5"} 0
les_misc_serve_body {quantile="0.75"} 0
les_misc_serve_body {quantile="0.95"} 0
les_misc_serve_body {quantile="0.99"} 0
les_misc_serve_body {quantile="0.999"} 0
les_misc_serve_body {quantile="0.9999"} 0

# TYPE les_misc_serve_code_count counter
les_misc_serve_code_count 0

# TYPE les_misc_serve_code summary
les_misc_serve_code {quantile="0.5"} 0
les_misc_serve_code {quantile="0.75"} 0
les_misc_serve_code {quantile="0.95"} 0
les_misc_serve_code {quantile="0.99"} 0
les_misc_serve_code {quantile="0.999"} 0
les_misc_serve_code {quantile="0.9999"} 0

# TYPE les_misc_serve_header_count counter
les_misc_serve_header_count 0

# TYPE les_misc_serve_header summary
les_misc_serve_header {quantile="0.5"} 0
les_misc_serve_header {quantile="0.75"} 0
les_misc_serve_header {quantile="0.95"} 0
les_misc_serve_header {quantile="0.99"} 0
les_misc_serve_header {quantile="0.999"} 0
les_misc_serve_header {quantile="0.9999"} 0

# TYPE les_misc_serve_helperTrie_count counter
les_misc_serve_helperTrie_count 0

# TYPE les_misc_serve_helperTrie summary
les_misc_serve_helperTrie {quantile="0.5"} 0
les_misc_serve_helperTrie {quantile="0.75"} 0
les_misc_serve_helperTrie {quantile="0.95"} 0
les_misc_serve_helperTrie {quantile="0.99"} 0
les_misc_serve_helperTrie {quantile="0.999"} 0
les_misc_serve_helperTrie {quantile="0.9999"} 0

# TYPE les_misc_serve_proof_count counter
les_misc_serve_proof_count 0

# TYPE les_misc_serve_proof summary
les_misc_serve_proof {quantile="0.5"} 0
les_misc_serve_proof {quantile="0.75"} 0
les_misc_serve_proof {quantile="0.95"} 0
les_misc_serve_proof {quantile="0.99"} 0
les_misc_serve_proof {quantile="0.999"} 0
les_misc_serve_proof {quantile="0.9999"} 0

# TYPE les_misc_serve_receipt_count counter
les_misc_serve_receipt_count 0

# TYPE les_misc_serve_receipt summary
les_misc_serve_receipt {quantile="0.5"} 0
les_misc_serve_receipt {quantile="0.75"} 0
les_misc_serve_receipt {quantile="0.95"} 0
les_misc_serve_receipt {quantile="0.99"} 0
les_misc_serve_receipt {quantile="0.999"} 0
les_misc_serve_receipt {quantile="0.9999"} 0

# TYPE les_misc_serve_txStatus_count counter
les_misc_serve_txStatus_count 0

# TYPE les_misc_serve_txStatus summary
les_misc_serve_txStatus {quantile="0.5"} 0
les_misc_serve_txStatus {quantile="0.75"} 0
les_misc_serve_txStatus {quantile="0.95"} 0
les_misc_serve_txStatus {quantile="0.99"} 0
les_misc_serve_txStatus {quantile="0.999"} 0
les_misc_serve_txStatus {quantile="0.9999"} 0

# TYPE les_misc_serve_txs_count counter
les_misc_serve_txs_count 0

# TYPE les_misc_serve_txs summary
les_misc_serve_txs {quantile="0.5"} 0
les_misc_serve_txs {quantile="0.75"} 0
les_misc_serve_txs {quantile="0.95"} 0
les_misc_serve_txs {quantile="0.99"} 0
les_misc_serve_txs {quantile="0.999"} 0
les_misc_serve_txs {quantile="0.9999"} 0

# TYPE les_server_blockProcessingTime_count counter
les_server_blockProcessingTime_count 0

# TYPE les_server_blockProcessingTime summary
les_server_blockProcessingTime {quantile="0.5"} 0
les_server_blockProcessingTime {quantile="0.75"} 0
les_server_blockProcessingTime {quantile="0.95"} 0
les_server_blockProcessingTime {quantile="0.99"} 0
les_server_blockProcessingTime {quantile="0.999"} 0
les_server_blockProcessingTime {quantile="0.9999"} 0

# TYPE les_server_clientEvent_error gauge
les_server_clientEvent_error 0

# TYPE les_server_clientEvent_freeze gauge
les_server_clientEvent_freeze 0

# TYPE les_server_globalFactor gauge
les_server_globalFactor 0

# TYPE les_server_recentRequestEstimated gauge
les_server_recentRequestEstimated 0

# TYPE les_server_recentRequestServed gauge
les_server_recentRequestServed 0

# TYPE les_server_req_avgEstimatedTime gauge
les_server_req_avgEstimatedTime 0

# TYPE les_server_req_avgServedTime gauge
les_server_req_avgServedTime 0

# TYPE les_server_req_estimatedTime_count counter
les_server_req_estimatedTime_count 0

# TYPE les_server_req_estimatedTime summary
les_server_req_estimatedTime {quantile="0.5"} 0
les_server_req_estimatedTime {quantile="0.75"} 0
les_server_req_estimatedTime {quantile="0.95"} 0
les_server_req_estimatedTime {quantile="0.99"} 0
les_server_req_estimatedTime {quantile="0.999"} 0
les_server_req_estimatedTime {quantile="0.9999"} 0

# TYPE les_server_req_relative_count counter
les_server_req_relative_count 0

# TYPE les_server_req_relative summary
les_server_req_relative {quantile="0.5"} 0
les_server_req_relative {quantile="0.75"} 0
les_server_req_relative {quantile="0.95"} 0
les_server_req_relative {quantile="0.99"} 0
les_server_req_relative {quantile="0.999"} 0
les_server_req_relative {quantile="0.9999"} 0

# TYPE les_server_req_relative_body_count counter
les_server_req_relative_body_count 0

# TYPE les_server_req_relative_body summary
les_server_req_relative_body {quantile="0.5"} 0
les_server_req_relative_body {quantile="0.75"} 0
les_server_req_relative_body {quantile="0.95"} 0
les_server_req_relative_body {quantile="0.99"} 0
les_server_req_relative_body {quantile="0.999"} 0
les_server_req_relative_body {quantile="0.9999"} 0

# TYPE les_server_req_relative_code_count counter
les_server_req_relative_code_count 0

# TYPE les_server_req_relative_code summary
les_server_req_relative_code {quantile="0.5"} 0
les_server_req_relative_code {quantile="0.75"} 0
les_server_req_relative_code {quantile="0.95"} 0
les_server_req_relative_code {quantile="0.99"} 0
les_server_req_relative_code {quantile="0.999"} 0
les_server_req_relative_code {quantile="0.9999"} 0

# TYPE les_server_req_relative_header_count counter
les_server_req_relative_header_count 0

# TYPE les_server_req_relative_header summary
les_server_req_relative_header {quantile="0.5"} 0
les_server_req_relative_header {quantile="0.75"} 0
les_server_req_relative_header {quantile="0.95"} 0
les_server_req_relative_header {quantile="0.99"} 0
les_server_req_relative_header {quantile="0.999"} 0
les_server_req_relative_header {quantile="0.9999"} 0

# TYPE les_server_req_relative_helperTrie_count counter
les_server_req_relative_helperTrie_count 0

# TYPE les_server_req_relative_helperTrie summary
les_server_req_relative_helperTrie {quantile="0.5"} 0
les_server_req_relative_helperTrie {quantile="0.75"} 0
les_server_req_relative_helperTrie {quantile="0.95"} 0
les_server_req_relative_helperTrie {quantile="0.99"} 0
les_server_req_relative_helperTrie {quantile="0.999"} 0
les_server_req_relative_helperTrie {quantile="0.9999"} 0

# TYPE les_server_req_relative_proof_count counter
les_server_req_relative_proof_count 0

# TYPE les_server_req_relative_proof summary
les_server_req_relative_proof {quantile="0.5"} 0
les_server_req_relative_proof {quantile="0.75"} 0
les_server_req_relative_proof {quantile="0.95"} 0
les_server_req_relative_proof {quantile="0.99"} 0
les_server_req_relative_proof {quantile="0.999"} 0
les_server_req_relative_proof {quantile="0.9999"} 0

# TYPE les_server_req_relative_receipt_count counter
les_server_req_relative_receipt_count 0

# TYPE les_server_req_relative_receipt summary
les_server_req_relative_receipt {quantile="0.5"} 0
les_server_req_relative_receipt {quantile="0.75"} 0
les_server_req_relative_receipt {quantile="0.95"} 0
les_server_req_relative_receipt {quantile="0.99"} 0
les_server_req_relative_receipt {quantile="0.999"} 0
les_server_req_relative_receipt {quantile="0.9999"} 0

# TYPE les_server_req_relative_txStatus_count counter
les_server_req_relative_txStatus_count 0

# TYPE les_server_req_relative_txStatus summary
les_server_req_relative_txStatus {quantile="0.5"} 0
les_server_req_relative_txStatus {quantile="0.75"} 0
les_server_req_relative_txStatus {quantile="0.95"} 0
les_server_req_relative_txStatus {quantile="0.99"} 0
les_server_req_relative_txStatus {quantile="0.999"} 0
les_server_req_relative_txStatus {quantile="0.9999"} 0

# TYPE les_server_req_relative_txs_count counter
les_server_req_relative_txs_count 0

# TYPE les_server_req_relative_txs summary
les_server_req_relative_txs {quantile="0.5"} 0
les_server_req_relative_txs {quantile="0.75"} 0
les_server_req_relative_txs {quantile="0.95"} 0
les_server_req_relative_txs {quantile="0.99"} 0
les_server_req_relative_txs {quantile="0.999"} 0
les_server_req_relative_txs {quantile="0.9999"} 0

# TYPE les_server_req_servedTime_count counter
les_server_req_servedTime_count 0

# TYPE les_server_req_servedTime summary
les_server_req_servedTime {quantile="0.5"} 0
les_server_req_servedTime {quantile="0.75"} 0
les_server_req_servedTime {quantile="0.95"} 0
les_server_req_servedTime {quantile="0.99"} 0
les_server_req_servedTime {quantile="0.999"} 0
les_server_req_servedTime {quantile="0.9999"} 0

# TYPE les_server_servingQueue_queued gauge
les_server_servingQueue_queued 0

# TYPE les_server_servingQueue_served gauge
les_server_servingQueue_served 0

# TYPE les_server_totalCapacity gauge
les_server_totalCapacity 0

# TYPE les_server_totalRecharge gauge
les_server_totalRecharge 0

# TYPE p2p_dials gauge
p2p_dials 65

# TYPE p2p_egress gauge
p2p_egress 96555

# TYPE p2p_egress_eth_66_0x00 gauge
p2p_egress_eth_66_0x00 414

# TYPE p2p_egress_eth_66_0x00_packets gauge
p2p_egress_eth_66_0x00_packets 6

# TYPE p2p_egress_eth_66_0x03 gauge
p2p_egress_eth_66_0x03 2255

# TYPE p2p_egress_eth_66_0x03_packets gauge
p2p_egress_eth_66_0x03_packets 113

# TYPE p2p_egress_eth_66_0x04 gauge
p2p_egress_eth_66_0x04 26

# TYPE p2p_egress_eth_66_0x04_packets gauge
p2p_egress_eth_66_0x04_packets 2

# TYPE p2p_egress_eth_66_0x05 gauge
p2p_egress_eth_66_0x05 1532

# TYPE p2p_egress_eth_66_0x05_packets gauge
p2p_egress_eth_66_0x05_packets 11

# TYPE p2p_egress_eth_66_0x0f gauge
p2p_egress_eth_66_0x0f 1532

# TYPE p2p_egress_eth_66_0x0f_packets gauge
p2p_egress_eth_66_0x0f_packets 11

# TYPE p2p_egress_snap_1_0x00 gauge
p2p_egress_snap_1_0x00 328

# TYPE p2p_egress_snap_1_0x00_packets gauge
p2p_egress_snap_1_0x00_packets 5

# TYPE p2p_egress_snap_1_0x02 gauge
p2p_egress_snap_1_0x02 31719

# TYPE p2p_egress_snap_1_0x02_packets gauge
p2p_egress_snap_1_0x02_packets 4

# TYPE p2p_egress_snap_1_0x04 gauge
p2p_egress_snap_1_0x04 4610

# TYPE p2p_egress_snap_1_0x04_packets gauge
p2p_egress_snap_1_0x04_packets 4

# TYPE p2p_handle_eth_66_0x01_count counter
p2p_handle_eth_66_0x01_count 2

# TYPE p2p_handle_eth_66_0x01 summary
p2p_handle_eth_66_0x01 {quantile="0.5"} 298.5
p2p_handle_eth_66_0x01 {quantile="0.75"} 454
p2p_handle_eth_66_0x01 {quantile="0.95"} 454
p2p_handle_eth_66_0x01 {quantile="0.99"} 454
p2p_handle_eth_66_0x01 {quantile="0.999"} 454
p2p_handle_eth_66_0x01 {quantile="0.9999"} 454

# TYPE p2p_handle_eth_66_0x02_count counter
p2p_handle_eth_66_0x02_count 14

# TYPE p2p_handle_eth_66_0x02 summary
p2p_handle_eth_66_0x02 {quantile="0.5"} 3
p2p_handle_eth_66_0x02 {quantile="0.75"} 4.5
p2p_handle_eth_66_0x02 {quantile="0.95"} 13
p2p_handle_eth_66_0x02 {quantile="0.99"} 13
p2p_handle_eth_66_0x02 {quantile="0.999"} 13
p2p_handle_eth_66_0x02 {quantile="0.9999"} 13

# TYPE p2p_handle_eth_66_0x03_count counter
p2p_handle_eth_66_0x03_count 3

# TYPE p2p_handle_eth_66_0x03 summary
p2p_handle_eth_66_0x03 {quantile="0.5"} 99
p2p_handle_eth_66_0x03 {quantile="0.75"} 485
p2p_handle_eth_66_0x03 {quantile="0.95"} 485
p2p_handle_eth_66_0x03 {quantile="0.99"} 485
p2p_handle_eth_66_0x03 {quantile="0.999"} 485
p2p_handle_eth_66_0x03 {quantile="0.9999"} 485

# TYPE p2p_handle_eth_66_0x04_count counter
p2p_handle_eth_66_0x04_count 147

# TYPE p2p_handle_eth_66_0x04 summary
p2p_handle_eth_66_0x04 {quantile="0.5"} 403
p2p_handle_eth_66_0x04 {quantile="0.75"} 543
p2p_handle_eth_66_0x04 {quantile="0.95"} 730
p2p_handle_eth_66_0x04 {quantile="0.99"} 1216.680000000002
p2p_handle_eth_66_0x04 {quantile="0.999"} 1317
p2p_handle_eth_66_0x04 {quantile="0.9999"} 1317

# TYPE p2p_handle_eth_66_0x06_count counter
p2p_handle_eth_66_0x06_count 18

# TYPE p2p_handle_eth_66_0x06 summary
p2p_handle_eth_66_0x06 {quantile="0.5"} 97.5
p2p_handle_eth_66_0x06 {quantile="0.75"} 172.25
p2p_handle_eth_66_0x06 {quantile="0.95"} 257
p2p_handle_eth_66_0x06 {quantile="0.99"} 257
p2p_handle_eth_66_0x06 {quantile="0.999"} 257
p2p_handle_eth_66_0x06 {quantile="0.9999"} 257

# TYPE p2p_handle_eth_66_0x07_count counter
p2p_handle_eth_66_0x07_count 1

# TYPE p2p_handle_eth_66_0x07 summary
p2p_handle_eth_66_0x07 {quantile="0.5"} 833
p2p_handle_eth_66_0x07 {quantile="0.75"} 833
p2p_handle_eth_66_0x07 {quantile="0.95"} 833
p2p_handle_eth_66_0x07 {quantile="0.99"} 833
p2p_handle_eth_66_0x07 {quantile="0.999"} 833
p2p_handle_eth_66_0x07 {quantile="0.9999"} 833

# TYPE p2p_handle_eth_66_0x08_count counter
p2p_handle_eth_66_0x08_count 92

# TYPE p2p_handle_eth_66_0x08 summary
p2p_handle_eth_66_0x08 {quantile="0.5"} 3
p2p_handle_eth_66_0x08 {quantile="0.75"} 4
p2p_handle_eth_66_0x08 {quantile="0.95"} 19.399999999999977
p2p_handle_eth_66_0x08 {quantile="0.99"} 230
p2p_handle_eth_66_0x08 {quantile="0.999"} 230
p2p_handle_eth_66_0x08 {quantile="0.9999"} 230

# TYPE p2p_handle_eth_66_0x10_count counter
p2p_handle_eth_66_0x10_count 18

# TYPE p2p_handle_eth_66_0x10 summary
p2p_handle_eth_66_0x10 {quantile="0.5"} 39
p2p_handle_eth_66_0x10 {quantile="0.75"} 65.25
p2p_handle_eth_66_0x10 {quantile="0.95"} 369
p2p_handle_eth_66_0x10 {quantile="0.99"} 369
p2p_handle_eth_66_0x10 {quantile="0.999"} 369
p2p_handle_eth_66_0x10 {quantile="0.9999"} 369

# TYPE p2p_handle_snap_1_0x01_count counter
p2p_handle_snap_1_0x01_count 9

# TYPE p2p_handle_snap_1_0x01 summary
p2p_handle_snap_1_0x01 {quantile="0.5"} 42866
p2p_handle_snap_1_0x01 {quantile="0.75"} 44687
p2p_handle_snap_1_0x01 {quantile="0.95"} 47994
p2p_handle_snap_1_0x01 {quantile="0.99"} 47994
p2p_handle_snap_1_0x01 {quantile="0.999"} 47994
p2p_handle_snap_1_0x01 {quantile="0.9999"} 47994

# TYPE p2p_handle_snap_1_0x03_count counter
p2p_handle_snap_1_0x03_count 7

# TYPE p2p_handle_snap_1_0x03 summary
p2p_handle_snap_1_0x03 {quantile="0.5"} 19059
p2p_handle_snap_1_0x03 {quantile="0.75"} 30902
p2p_handle_snap_1_0x03 {quantile="0.95"} 37464
p2p_handle_snap_1_0x03 {quantile="0.99"} 37464
p2p_handle_snap_1_0x03 {quantile="0.999"} 37464
p2p_handle_snap_1_0x03 {quantile="0.9999"} 37464

# TYPE p2p_handle_snap_1_0x05_count counter
p2p_handle_snap_1_0x05_count 7

# TYPE p2p_handle_snap_1_0x05 summary
p2p_handle_snap_1_0x05 {quantile="0.5"} 3278
p2p_handle_snap_1_0x05 {quantile="0.75"} 7222
p2p_handle_snap_1_0x05 {quantile="0.95"} 34855
p2p_handle_snap_1_0x05 {quantile="0.99"} 34855
p2p_handle_snap_1_0x05 {quantile="0.999"} 34855
p2p_handle_snap_1_0x05 {quantile="0.9999"} 34855

# TYPE p2p_ingress gauge
p2p_ingress 4520041

# TYPE p2p_ingress_eth_66_0x00 gauge
p2p_ingress_eth_66_0x00 257

# TYPE p2p_ingress_eth_66_0x00_packets gauge
p2p_ingress_eth_66_0x00_packets 3

# TYPE p2p_ingress_eth_66_0x01 gauge
p2p_ingress_eth_66_0x01 41

# TYPE p2p_ingress_eth_66_0x01_packets gauge
p2p_ingress_eth_66_0x01_packets 1

# TYPE p2p_ingress_eth_66_0x02 gauge
p2p_ingress_eth_66_0x02 4628

# TYPE p2p_ingress_eth_66_0x02_packets gauge
p2p_ingress_eth_66_0x02_packets 7

# TYPE p2p_ingress_eth_66_0x03 gauge
p2p_ingress_eth_66_0x03 40

# TYPE p2p_ingress_eth_66_0x03_packets gauge
p2p_ingress_eth_66_0x03_packets 2

# TYPE p2p_ingress_eth_66_0x04 gauge
p2p_ingress_eth_66_0x04 2187081

# TYPE p2p_ingress_eth_66_0x04_packets gauge
p2p_ingress_eth_66_0x04_packets 111

# TYPE p2p_ingress_eth_66_0x06 gauge
p2p_ingress_eth_66_0x06 7640

# TYPE p2p_ingress_eth_66_0x06_packets gauge
p2p_ingress_eth_66_0x06_packets 9

# TYPE p2p_ingress_eth_66_0x07 gauge
p2p_ingress_eth_66_0x07 0

# TYPE p2p_ingress_eth_66_0x07_packets gauge
p2p_ingress_eth_66_0x07_packets 0

# TYPE p2p_ingress_eth_66_0x08 gauge
p2p_ingress_eth_66_0x08 272692

# TYPE p2p_ingress_eth_66_0x08_packets gauge
p2p_ingress_eth_66_0x08_packets 56

# TYPE p2p_ingress_eth_66_0x10 gauge
p2p_ingress_eth_66_0x10 2138

# TYPE p2p_ingress_eth_66_0x10_packets gauge
p2p_ingress_eth_66_0x10_packets 9

# TYPE p2p_ingress_snap_1_0x01 gauge
p2p_ingress_snap_1_0x01 1465320

# TYPE p2p_ingress_snap_1_0x01_packets gauge
p2p_ingress_snap_1_0x01_packets 4

# TYPE p2p_ingress_snap_1_0x03 gauge
p2p_ingress_snap_1_0x03 341733

# TYPE p2p_ingress_snap_1_0x03_packets gauge
p2p_ingress_snap_1_0x03_packets 3

# TYPE p2p_ingress_snap_1_0x05 gauge
p2p_ingress_snap_1_0x05 105138

# TYPE p2p_ingress_snap_1_0x05_packets gauge
p2p_ingress_snap_1_0x05_packets 3

# TYPE p2p_peers gauge
p2p_peers 4

# TYPE p2p_serves gauge
p2p_serves 0

# TYPE p2p_tracked_eth_66_0x03 gauge
p2p_tracked_eth_66_0x03 4

# TYPE p2p_tracked_eth_66_0x05 gauge
p2p_tracked_eth_66_0x05 2

# TYPE p2p_tracked_eth_66_0x0f gauge
p2p_tracked_eth_66_0x0f 2

# TYPE p2p_tracked_snap_1_0x00 gauge
p2p_tracked_snap_1_0x00 2

# TYPE p2p_tracked_snap_1_0x02 gauge
p2p_tracked_snap_1_0x02 2

# TYPE p2p_tracked_snap_1_0x04 gauge
p2p_tracked_snap_1_0x04 2

# TYPE p2p_wait_eth_66_0x03_count counter
p2p_wait_eth_66_0x03_count 147

# TYPE p2p_wait_eth_66_0x03 summary
p2p_wait_eth_66_0x03 {quantile="0.5"} 107796
p2p_wait_eth_66_0x03 {quantile="0.75"} 191563
p2p_wait_eth_66_0x03 {quantile="0.95"} 783985.5999999995
p2p_wait_eth_66_0x03 {quantile="0.99"} 1.1292890400000021e+06
p2p_wait_eth_66_0x03 {quantile="0.999"} 1.229238e+06
p2p_wait_eth_66_0x03 {quantile="0.9999"} 1.229238e+06

# TYPE p2p_wait_eth_66_0x05_count counter
p2p_wait_eth_66_0x05_count 18

# TYPE p2p_wait_eth_66_0x05 summary
p2p_wait_eth_66_0x05 {quantile="0.5"} 208175
p2p_wait_eth_66_0x05 {quantile="0.75"} 551849.25
p2p_wait_eth_66_0x05 {quantile="0.95"} 1.239539e+06
p2p_wait_eth_66_0x05 {quantile="0.99"} 1.239539e+06
p2p_wait_eth_66_0x05 {quantile="0.999"} 1.239539e+06
p2p_wait_eth_66_0x05 {quantile="0.9999"} 1.239539e+06

# TYPE p2p_wait_eth_66_0x0f_count counter
p2p_wait_eth_66_0x0f_count 18

# TYPE p2p_wait_eth_66_0x0f summary
p2p_wait_eth_66_0x0f {quantile="0.5"} 208743.5
p2p_wait_eth_66_0x0f {quantile="0.75"} 555739.5
p2p_wait_eth_66_0x0f {quantile="0.95"} 1.24089e+06
p2p_wait_eth_66_0x0f {quantile="0.99"} 1.24089e+06
p2p_wait_eth_66_0x0f {quantile="0.999"} 1.24089e+06
p2p_wait_eth_66_0x0f {quantile="0.9999"} 1.24089e+06

# TYPE p2p_wait_snap_1_0x00_count counter
p2p_wait_snap_1_0x00_count 9

# TYPE p2p_wait_snap_1_0x00 summary
p2p_wait_snap_1_0x00 {quantile="0.5"} 1.012818e+06
p2p_wait_snap_1_0x00 {quantile="0.75"} 1.2368575e+06
p2p_wait_snap_1_0x00 {quantile="0.95"} 1.404601e+06
p2p_wait_snap_1_0x00 {quantile="0.99"} 1.404601e+06
p2p_wait_snap_1_0x00 {quantile="0.999"} 1.404601e+06
p2p_wait_snap_1_0x00 {quantile="0.9999"} 1.404601e+06

# TYPE p2p_wait_snap_1_0x02_count counter
p2p_wait_snap_1_0x02_count 8

# TYPE p2p_wait_snap_1_0x02 summary
p2p_wait_snap_1_0x02 {quantile="0.5"} 1.072343e+06
p2p_wait_snap_1_0x02 {quantile="0.75"} 1.302457e+06
p2p_wait_snap_1_0x02 {quantile="0.95"} 1.522983e+06
p2p_wait_snap_1_0x02 {quantile="0.99"} 1.522983e+06
p2p_wait_snap_1_0x02 {quantile="0.999"} 1.522983e+06
p2p_wait_snap_1_0x02 {quantile="0.9999"} 1.522983e+06

# TYPE p2p_wait_snap_1_0x04_count counter
p2p_wait_snap_1_0x04_count 7

# TYPE p2p_wait_snap_1_0x04 summary
p2p_wait_snap_1_0x04 {quantile="0.5"} 908302
p2p_wait_snap_1_0x04 {quantile="0.75"} 1.403041e+06
p2p_wait_snap_1_0x04 {quantile="0.95"} 1.532121e+06
p2p_wait_snap_1_0x04 {quantile="0.99"} 1.532121e+06
p2p_wait_snap_1_0x04 {quantile="0.999"} 1.532121e+06
p2p_wait_snap_1_0x04 {quantile="0.9999"} 1.532121e+06

# TYPE rpc_duration_all_count counter
rpc_duration_all_count 0

# TYPE rpc_duration_all summary
rpc_duration_all {quantile="0.5"} 0
rpc_duration_all {quantile="0.75"} 0
rpc_duration_all {quantile="0.95"} 0
rpc_duration_all {quantile="0.99"} 0
rpc_duration_all {quantile="0.999"} 0
rpc_duration_all {quantile="0.9999"} 0

# TYPE rpc_failure gauge
rpc_failure 0

# TYPE rpc_requests gauge
rpc_requests 0

# TYPE rpc_success gauge
rpc_success 0

# TYPE state_commit_account gauge
state_commit_account 0

# TYPE state_commit_storage gauge
state_commit_storage 0

# TYPE state_delete_account gauge
state_delete_account 0

# TYPE state_delete_storage gauge
state_delete_storage 0

# TYPE state_snapshot_bloom_account_falsehit gauge
state_snapshot_bloom_account_falsehit 0

# TYPE state_snapshot_bloom_account_miss gauge
state_snapshot_bloom_account_miss 0

# TYPE state_snapshot_bloom_account_truehit gauge
state_snapshot_bloom_account_truehit 0

# TYPE state_snapshot_bloom_error gauge
state_snapshot_bloom_error 0

# TYPE state_snapshot_bloom_storage_falsehit gauge
state_snapshot_bloom_storage_falsehit 0

# TYPE state_snapshot_bloom_storage_miss gauge
state_snapshot_bloom_storage_miss 0

# TYPE state_snapshot_bloom_storage_truehit gauge
state_snapshot_bloom_storage_truehit 0

# TYPE state_snapshot_clean_account_hit gauge
state_snapshot_clean_account_hit 0

# TYPE state_snapshot_clean_account_inex gauge
state_snapshot_clean_account_inex 0

# TYPE state_snapshot_clean_account_miss gauge
state_snapshot_clean_account_miss 0

# TYPE state_snapshot_clean_account_read gauge
state_snapshot_clean_account_read 0

# TYPE state_snapshot_clean_account_write gauge
state_snapshot_clean_account_write 0

# TYPE state_snapshot_clean_storage_hit gauge
state_snapshot_clean_storage_hit 0

# TYPE state_snapshot_clean_storage_inex gauge
state_snapshot_clean_storage_inex 0

# TYPE state_snapshot_clean_storage_miss gauge
state_snapshot_clean_storage_miss 0

# TYPE state_snapshot_clean_storage_read gauge
state_snapshot_clean_storage_read 0

# TYPE state_snapshot_clean_storage_write gauge
state_snapshot_clean_storage_write 0

# TYPE state_snapshot_dirty_account_hit gauge
state_snapshot_dirty_account_hit 0

# TYPE state_snapshot_dirty_account_hit_depth_count counter
state_snapshot_dirty_account_hit_depth_count 0

# TYPE state_snapshot_dirty_account_hit_depth summary
state_snapshot_dirty_account_hit_depth {quantile="0.5"} 0
state_snapshot_dirty_account_hit_depth {quantile="0.75"} 0
state_snapshot_dirty_account_hit_depth {quantile="0.95"} 0
state_snapshot_dirty_account_hit_depth {quantile="0.99"} 0
state_snapshot_dirty_account_hit_depth {quantile="0.999"} 0
state_snapshot_dirty_account_hit_depth {quantile="0.9999"} 0

# TYPE state_snapshot_dirty_account_inex gauge
state_snapshot_dirty_account_inex 0

# TYPE state_snapshot_dirty_account_miss gauge
state_snapshot_dirty_account_miss 0

# TYPE state_snapshot_dirty_account_read gauge
state_snapshot_dirty_account_read 0

# TYPE state_snapshot_dirty_account_write gauge
state_snapshot_dirty_account_write 0

# TYPE state_snapshot_dirty_storage_hit gauge
state_snapshot_dirty_storage_hit 0

# TYPE state_snapshot_dirty_storage_hit_depth_count counter
state_snapshot_dirty_storage_hit_depth_count 0

# TYPE state_snapshot_dirty_storage_hit_depth summary
state_snapshot_dirty_storage_hit_depth {quantile="0.5"} 0
state_snapshot_dirty_storage_hit_depth {quantile="0.75"} 0
state_snapshot_dirty_storage_hit_depth {quantile="0.95"} 0
state_snapshot_dirty_storage_hit_depth {quantile="0.99"} 0
state_snapshot_dirty_storage_hit_depth {quantile="0.999"} 0
state_snapshot_dirty_storage_hit_depth {quantile="0.9999"} 0

# TYPE state_snapshot_dirty_storage_inex gauge
state_snapshot_dirty_storage_inex 0

# TYPE state_snapshot_dirty_storage_miss gauge
state_snapshot_dirty_storage_miss 0

# TYPE state_snapshot_dirty_storage_read gauge
state_snapshot_dirty_storage_read 0

# TYPE state_snapshot_dirty_storage_write gauge
state_snapshot_dirty_storage_write 0

# TYPE state_snapshot_flush_account_item gauge
state_snapshot_flush_account_item 0

# TYPE state_snapshot_flush_account_size gauge
state_snapshot_flush_account_size 0

# TYPE state_snapshot_flush_storage_item gauge
state_snapshot_flush_storage_item 0

# TYPE state_snapshot_flush_storage_size gauge
state_snapshot_flush_storage_size 0

# TYPE state_snapshot_generation_account_generated gauge
state_snapshot_generation_account_generated 257

# TYPE state_snapshot_generation_account_missall gauge
state_snapshot_generation_account_missall 1

# TYPE state_snapshot_generation_account_recovered gauge
state_snapshot_generation_account_recovered 0

# TYPE state_snapshot_generation_account_wiped gauge
state_snapshot_generation_account_wiped 0

# TYPE state_snapshot_generation_duration_account_prove gauge
state_snapshot_generation_duration_account_prove 433400

# TYPE state_snapshot_generation_duration_account_snapread gauge
state_snapshot_generation_duration_account_snapread 92100

# TYPE state_snapshot_generation_duration_account_trieread gauge
state_snapshot_generation_duration_account_trieread 5923200

# TYPE state_snapshot_generation_duration_account_write gauge
state_snapshot_generation_duration_account_write 4435700

# TYPE state_snapshot_generation_duration_storage_prove gauge
state_snapshot_generation_duration_storage_prove 0

# TYPE state_snapshot_generation_duration_storage_snapread gauge
state_snapshot_generation_duration_storage_snapread 0

# TYPE state_snapshot_generation_duration_storage_trieread gauge
state_snapshot_generation_duration_storage_trieread 0

# TYPE state_snapshot_generation_duration_storage_write gauge
state_snapshot_generation_duration_storage_write 0

# TYPE state_snapshot_generation_proof_failure gauge
state_snapshot_generation_proof_failure 1

# TYPE state_snapshot_generation_proof_success gauge
state_snapshot_generation_proof_success 0

# TYPE state_snapshot_generation_storage_generated gauge
state_snapshot_generation_storage_generated 0

# TYPE state_snapshot_generation_storage_missall gauge
state_snapshot_generation_storage_missall 0

# TYPE state_snapshot_generation_storage_recovered gauge
state_snapshot_generation_storage_recovered 0

# TYPE state_snapshot_generation_storage_wiped gauge
state_snapshot_generation_storage_wiped 0

# TYPE state_update_account gauge
state_update_account 0

# TYPE state_update_storage gauge
state_update_storage 0

# TYPE system_cpu_goroutines gauge
system_cpu_goroutines 127

# TYPE system_cpu_procload gauge
system_cpu_procload 71

# TYPE system_cpu_sysload gauge
system_cpu_sysload 83

# TYPE system_cpu_syswait gauge
system_cpu_syswait 0

# TYPE system_cpu_threads gauge
system_cpu_threads 16

# TYPE system_disk_readbytes gauge
system_disk_readbytes 10917615

# TYPE system_disk_readcount gauge
system_disk_readcount 4293

# TYPE system_disk_readdata gauge
system_disk_readdata 7374320

# TYPE system_disk_writebytes gauge
system_disk_writebytes 35081399

# TYPE system_disk_writecount gauge
system_disk_writecount 2639

# TYPE system_disk_writedata gauge
system_disk_writedata 21505892

# TYPE system_memory_allocs gauge
system_memory_allocs 2846859

# TYPE system_memory_frees gauge
system_memory_frees 2100241

# TYPE system_memory_held gauge
system_memory_held 373661696

# TYPE system_memory_pauses gauge
system_memory_pauses 1226900

# TYPE system_memory_used gauge
system_memory_used 223251288

# TYPE trie_bloom_add gauge
trie_bloom_add 0

# TYPE trie_bloom_error gauge
trie_bloom_error 0

# TYPE trie_bloom_fault gauge
trie_bloom_fault 2

# TYPE trie_bloom_load gauge
trie_bloom_load 0

# TYPE trie_bloom_miss gauge
trie_bloom_miss 0

# TYPE trie_bloom_test gauge
trie_bloom_test 0

# TYPE trie_memcache_clean_hit gauge
trie_memcache_clean_hit 3

# TYPE trie_memcache_clean_miss gauge
trie_memcache_clean_miss 355

# TYPE trie_memcache_clean_read gauge
trie_memcache_clean_read 1596

# TYPE trie_memcache_clean_write gauge
trie_memcache_clean_write 40549

# TYPE trie_memcache_commit_nodes gauge
trie_memcache_commit_nodes 355

# TYPE trie_memcache_commit_size gauge
trie_memcache_commit_size 51639

# TYPE trie_memcache_commit_time_count counter
trie_memcache_commit_time_count 1

# TYPE trie_memcache_commit_time summary
trie_memcache_commit_time {quantile="0.50"} 4821000
trie_memcache_commit_time {quantile="0.95"} 4821000
trie_memcache_commit_time {quantile="0.99"} 4821000

# TYPE trie_memcache_dirty_hit gauge
trie_memcache_dirty_hit 0

# TYPE trie_memcache_dirty_miss gauge
trie_memcache_dirty_miss 355

# TYPE trie_memcache_dirty_read gauge
trie_memcache_dirty_read 0

# TYPE trie_memcache_dirty_write gauge
trie_memcache_dirty_write 40279

# TYPE trie_memcache_flush_nodes gauge
trie_memcache_flush_nodes 0

# TYPE trie_memcache_flush_size gauge
trie_memcache_flush_size 0

# TYPE trie_memcache_gc_nodes gauge
trie_memcache_gc_nodes 0

# TYPE trie_memcache_gc_size gauge
trie_memcache_gc_size 0

# TYPE trie_prefetch_miner_account_dup gauge
trie_prefetch_miner_account_dup 0

# TYPE trie_prefetch_miner_account_load gauge
trie_prefetch_miner_account_load 0

# TYPE trie_prefetch_miner_account_skip gauge
trie_prefetch_miner_account_skip 0

# TYPE trie_prefetch_miner_account_waste gauge
trie_prefetch_miner_account_waste 0

# TYPE trie_prefetch_miner_deliverymiss gauge
trie_prefetch_miner_deliverymiss 1

# TYPE trie_prefetch_miner_storage_dup gauge
trie_prefetch_miner_storage_dup 0

# TYPE trie_prefetch_miner_storage_load gauge
trie_prefetch_miner_storage_load 0

# TYPE trie_prefetch_miner_storage_skip gauge
trie_prefetch_miner_storage_skip 0

# TYPE trie_prefetch_miner_storage_waste gauge
trie_prefetch_miner_storage_waste 0

# TYPE txpool_dropbetweenreorg_count counter
txpool_dropbetweenreorg_count 0

# TYPE txpool_dropbetweenreorg summary
txpool_dropbetweenreorg {quantile="0.5"} 0
txpool_dropbetweenreorg {quantile="0.75"} 0
txpool_dropbetweenreorg {quantile="0.95"} 0
txpool_dropbetweenreorg {quantile="0.99"} 0
txpool_dropbetweenreorg {quantile="0.999"} 0
txpool_dropbetweenreorg {quantile="0.9999"} 0

# TYPE txpool_invalid gauge
txpool_invalid 0

# TYPE txpool_known gauge
txpool_known 0

# TYPE txpool_local gauge
txpool_local 0

# TYPE txpool_overflowed gauge
txpool_overflowed 0

# TYPE txpool_pending gauge
txpool_pending 0

# TYPE txpool_pending_discard gauge
txpool_pending_discard 0

# TYPE txpool_pending_nofunds gauge
txpool_pending_nofunds 0

# TYPE txpool_pending_ratelimit gauge
txpool_pending_ratelimit 0

# TYPE txpool_pending_replace gauge
txpool_pending_replace 0

# TYPE txpool_queued gauge
txpool_queued 0

# TYPE txpool_queued_discard gauge
txpool_queued_discard 0

# TYPE txpool_queued_eviction gauge
txpool_queued_eviction 0

# TYPE txpool_queued_nofunds gauge
txpool_queued_nofunds 0

# TYPE txpool_queued_ratelimit gauge
txpool_queued_ratelimit 0

# TYPE txpool_queued_replace gauge
txpool_queued_replace 0

# TYPE txpool_reheap_count counter
txpool_reheap_count 0

# TYPE txpool_reheap summary
txpool_reheap {quantile="0.5"} 0
txpool_reheap {quantile="0.75"} 0
txpool_reheap {quantile="0.95"} 0
txpool_reheap {quantile="0.99"} 0
txpool_reheap {quantile="0.999"} 0
txpool_reheap {quantile="0.9999"} 0

# TYPE txpool_reorgtime_count counter
txpool_reorgtime_count 0

# TYPE txpool_reorgtime summary
txpool_reorgtime {quantile="0.5"} 0
txpool_reorgtime {quantile="0.75"} 0
txpool_reorgtime {quantile="0.95"} 0
txpool_reorgtime {quantile="0.99"} 0
txpool_reorgtime {quantile="0.999"} 0
txpool_reorgtime {quantile="0.9999"} 0

# TYPE txpool_slots gauge
txpool_slots 0

# TYPE txpool_throttle gauge
txpool_throttle 0

# TYPE txpool_underpriced gauge
txpool_underpriced 0

# TYPE txpool_valid gauge
txpool_valid 0

# TYPE vflux_server_active_capacity gauge
vflux_server_active_capacity 0

# TYPE vflux_server_active_count gauge
vflux_server_active_count 0

# TYPE vflux_server_capQueryNonZero gauge
vflux_server_capQueryNonZero 0

# TYPE vflux_server_capQueryZero gauge
vflux_server_capQueryZero 0

# TYPE vflux_server_clientEvent_activated gauge
vflux_server_clientEvent_activated 0

# TYPE vflux_server_clientEvent_connected gauge
vflux_server_clientEvent_connected 0

# TYPE vflux_server_clientEvent_deactivated gauge
vflux_server_clientEvent_deactivated 0

# TYPE vflux_server_clientEvent_disconnected gauge
vflux_server_clientEvent_disconnected 0

# TYPE vflux_server_inactive_count gauge
vflux_server_inactive_count 0
```
