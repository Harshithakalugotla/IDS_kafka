<<<<<<< HEAD
# Intrusion-Detection-System-using-Kafka
=======
---
license: gpl-3.0
tags:
- Network Security
---
# NSL-KDD



> The data set is a data set that converts the arff File provided by the [link](https://www.unb.ca/cic/datasets/nsl.html) into CSV and results.
>
> The data set is personally stored by converting data to float64.
>
> If you want to obtain additional original files, they are organized in the [Original Directory](./Original) in the repo.



## Labels

The label of the data set is as follows.

|#|Column|Non-Null|Count|Dtype|
|---|---|---|---|---|
|0|duration|151165|non-null|int64|
|1|protocol_type|151165|non-null|object|
|2|service|151165|non-null|object|
|3|flag|151165|non-null|object|
|4|src_bytes|151165|non-null|int64|
|5|dst_bytes|151165|non-null|int64|
|6|land|151165|non-null|int64|
|7|wrong_fragment|151165|non-null|int64|
|8|urgent|151165|non-null|int64|
|9|hot|151165|non-null|int64|
|10|num_failed_logins|151165|non-null|int64|
|11|logged_in|151165|non-null|int64|
|12|num_compromised|151165|non-null|int64|
|13|root_shell|151165|non-null|int64|
|14|su_attempted|151165|non-null|int64|
|15|num_root|151165|non-null|int64|
|16|num_file_creations|151165|non-null|int64|
|17|num_shells|151165|non-null|int64|
|18|num_access_files|151165|non-null|int64|
|19|num_outbound_cmds|151165|non-null|int64|
|20|is_host_login|151165|non-null|int64|
|21|is_guest_login|151165|non-null|int64|
|22|count|151165|non-null|int64|
|23|srv_count|151165|non-null|int64|
|24|serror_rate|151165|non-null|float64|
|25|srv_serror_rate|151165|non-null|float64|
|26|rerror_rate|151165|non-null|float64|
|27|srv_rerror_rate|151165|non-null|float64|
|28|same_srv_rate|151165|non-null|float64|
|29|diff_srv_rate|151165|non-null|float64|
|30|srv_diff_host_rate|151165|non-null|float64|
|31|dst_host_count|151165|non-null|int64|
|32|dst_host_srv_count|151165|non-null|int64|
|33|dst_host_same_srv_rate|151165|non-null|float64|
|34|dst_host_diff_srv_rate|151165|non-null|float64|
|35|dst_host_same_src_port_rate|151165|non-null|float64|
|36|dst_host_srv_diff_host_rate|151165|non-null|float64|
|37|dst_host_serror_rate|151165|non-null|float64|
|38|dst_host_srv_serror_rate|151165|non-null|float64|
|39|dst_host_rerror_rate|151165|non-null|float64|
|40|dst_host_srv_rerror_rate|151165|non-null|float64|
|41|class|151165|non-null|float64|
>>>>>>> 11b041e (Initial commit - IDS project with LOF + XGBoost)
