**Example 1: 创建雪碧图模板**



Input: 

```
tccli mps CreateImageSpriteTemplate --cli-unfold-argument  \
    --Name 雪碧图模板1 \
    --Width 54 \
    --Height 96 \
    --SampleType Percent \
    --SampleInterval 10 \
    --RowCount 5 \
    --ColumnCount 10
```

Output: 
```
{
    "Response": {
        "Definition": 1008,
        "RequestId": "12ae8d8e-dce3-4151-9d4b-5594145287e1"
    }
}
```

