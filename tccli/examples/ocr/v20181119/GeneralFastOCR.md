**Example 1: 通用印刷体识别（高速版）示例代码**



Input: 

```
tccli ocr GeneralFastOCR --cli-unfold-argument  \
    --ImageUrl https://xx/a.jpg
```

Output: 
```
{
    "Response": {
        "TextDetections": [
            {
                "DetectedText": "Confetteria",
                "Confidence": 99,
                "ItemPolygon": {
                    "X": 473,
                    "Y": 273,
                    "Width": 112,
                    "Height": 22
                },
                "Polygon": [
                    {
                        "X": 450,
                        "Y": 211
                    },
                    {
                        "X": 560,
                        "Y": 223
                    },
                    {
                        "X": 558,
                        "Y": 244
                    },
                    {
                        "X": 448,
                        "Y": 232
                    }
                ],
                "AdvancedInfo": "{\"Parag\":{\"ParagNo\":1}}"
            },
            {
                "DetectedText": "Raffaello",
                "Confidence": 99,
                "ItemPolygon": {
                    "X": 396,
                    "Y": 304,
                    "Width": 282,
                    "Height": 68
                },
                "Polygon": [
                    {
                        "X": 370,
                        "Y": 233
                    },
                    {
                        "X": 649,
                        "Y": 265
                    },
                    {
                        "X": 642,
                        "Y": 331
                    },
                    {
                        "X": 362,
                        "Y": 299
                    }
                ],
                "AdvancedInfo": "{\"Parag\":{\"ParagNo\":2}}"
            },
            {
                "DetectedText": "费列罗臻点坊",
                "Confidence": 99,
                "ItemPolygon": {
                    "X": 437,
                    "Y": 385,
                    "Width": 188,
                    "Height": 32
                },
                "Polygon": [
                    {
                        "X": 402,
                        "Y": 318
                    },
                    {
                        "X": 587,
                        "Y": 339
                    },
                    {
                        "X": 584,
                        "Y": 370
                    },
                    {
                        "X": 398,
                        "Y": 349
                    }
                ],
                "AdvancedInfo": "{\"Parag\":{\"ParagNo\":3}}"
            },
            {
                "DetectedText": "拉斐尔脆雪柔",
                "Confidence": 99,
                "ItemPolygon": {
                    "X": 427,
                    "Y": 435,
                    "Width": 207,
                    "Height": 34
                },
                "Polygon": [
                    {
                        "X": 386,
                        "Y": 366
                    },
                    {
                        "X": 591,
                        "Y": 390
                    },
                    {
                        "X": 587,
                        "Y": 423
                    },
                    {
                        "X": 382,
                        "Y": 399
                    }
                ],
                "AdvancedInfo": "{\"Parag\":{\"ParagNo\":3}}"
            }
        ],
        "Language": "zh",
        "Angel": 6.5,
        "RequestId": "6809d421-875a-47f6-915f-fee749982f80"
    }
}
```

