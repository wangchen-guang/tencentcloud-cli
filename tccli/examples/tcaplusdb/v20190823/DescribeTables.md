**Example 1: 查询表列表**

查询表列表

Input: 

```
tccli tcaplusdb DescribeTables --cli-unfold-argument  \
    --ClusterId 5674209986
```

Output: 
```
{
    "Response": {
        "RequestId": "68821f04-f15b-46e6-b4ce-669341e6c848",
        "TableInfos": [
            {
                "ApiAccessId": "10",
                "ClusterName": "gz测试App",
                "ClusterId": "5674209986",
                "CreatedTime": "2019-08-29 22:03:27",
                "Error": null,
                "IdlFiles": [
                    {
                        "FileContent": null,
                        "FileExtType": "proto",
                        "FileId": 551,
                        "FileName": "tb_example",
                        "FileSize": 266,
                        "FileType": "PROTO"
                    }
                ],
                "IndexStruct": null,
                "KeyStruct": null,
                "ListElementNum": 1,
                "TableGroupId": "101",
                "Memo": "pb测试表1",
                "ReservedReadQps": 80,
                "ReservedVolume": 1,
                "ReservedWriteQps": 26,
                "ShardingKeySet": "key",
                "Status": "RUNNING",
                "TableIdlType": "PROTO",
                "TableInstanceId": "tcaplus-1f224454",
                "TableName": "tb_example",
                "TableSize": 48566336,
                "TableType": "GENERIC",
                "UpdatedTime": "",
                "ValueStruct": null,
                "SortFieldNum": null,
                "SortRule": null,
                "TableGroupName": "test_zone_1"
            }
        ],
        "TotalCount": 1
    }
}
```

