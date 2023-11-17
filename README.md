---aws cloudwatch get-metric-data \
  --region <your-region> \
  --metric-data-queries \
    '[
      {
        "id": "m1",
        "metricStat": {
          "metric": {
            "namespace": "AWS/Billing",
            "metricName": "EstimatedCharges",
            "dimensions": [
              {
                "name": "Currency",
                "value": "USD"
              }
            ]
          },
          "period": 86400,
          "stat": "Maximum"
        },
        "returnData": true
      }
    ]'


gvkrhub/gvkrhub is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profilen click the Preview link to take a look at your changes.
--->

