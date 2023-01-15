# Clinical-Chemistry-Analyzer

Nodered Flow for get data from Clinical Analyzer and pusblish to kafka

1. Using Nodered
2. Push Data to Kafka

<br/>
Nodered Flow

![image](https://user-images.githubusercontent.com/18347199/212526068-b333ba36-f77f-43e1-ad09-e449e9f8fde6.png)


<br/>

Output

```json

{
  "messageVersion": "1.1",
  "equipmentId": "00000008",
  "equipmentDatetime": "2022-06-10T12:28:00.050Z",
  "header": {
    "recordType": "H",
    "processingId": "U",
    "sender": {
      "systemName": "XS-800i",
      "serialNumber": "62111"
    }
  },
  "patient": {
    "recordType": "P",
    "patientId": "22061010147",
    "order": {
      "recordType": "O",
      "sequenceNumber": "287",
      "specimenId": "22061010147",
      "instrumentSpecimen": {
        "carrierId": "",
        "position": "00",
        "sampleIdAttr": "0"
      },
      "universalTestId": [
        {
          "value": "",
          "code": "",
          "dilution": "",
          "dilutionStatus": "1"
        }
      ],
      "orderDatetime": "202206101932",
      "actionCode": "0",
      "spesimenDescriptor": "",
      "reportType": "0",
      "result": [
        {
          "recordType": "R",
          "universalTestId": {
            "code": "Positive_Diff"
          },
          "dataValue": "",
          "resultAbnormalFlag": "0"
        },
        {
          "recordType": "R",
          "universalTestId": {
            "code": "Positive_Morph"
          },
          "dataValue": "",
          "resultAbnormalFlag": "0"
        },
        {
          "recordType": "R",
          "universalTestId": {
            "code": "Positive_Count"
          },
          "dataValue": "",
          "resultAbnormalFlag": "0"
        },
        {
          "recordType": "R",
          "universalTestId": {
            "code": "Error_Func"
          },
          "dataValue": "",
          "resultAbnormalFlag": "0"
        },
        {
          "recordType": "R",
          "universalTestId": {
            "code": "Error_Result"
          },
          "dataValue": "",
          "resultAbnormalFlag": "0"
        },
        {
          "recordType": "R",
          "sequenceNumber": "",
          "universalTestId": {
            "code": "WBC"
          },
          "dataValue": "090300",
          "units": "",
          "resultAbnormalFlag": "N",
          "resultStatus": ""
        },
        {
          "recordType": "R",
          "sequenceNumber": "",
          "universalTestId": {
            "code": "RBC"
          },
          "dataValue": "54600",
          "units": "",
          "resultAbnormalFlag": "N",
          "resultStatus": ""
        },
        {
          "recordType": "R",
          "sequenceNumber": "",
          "universalTestId": {
            "code": "HGB"
          },
          "dataValue": "16100",
          "units": "",
          "resultAbnormalFlag": "",
          "resultStatus": ""
        },
        {
          "recordType": "R",
          "sequenceNumber": "",
          "universalTestId": {
            "code": "HCT"
          },
          "dataValue": "47600",
          "units": "",
          "resultAbnormalFlag": "",
          "resultStatus": ""
        },
        {
          "recordType": "R",
          "sequenceNumber": "",
          "universalTestId": {
            "code": "MVC"
          },
          "dataValue": "87200",
          "units": "",
          "resultAbnormalFlag": "",
          "resultStatus": ""
        },
        {
          "recordType": "R",
          "sequenceNumber": "",
          "universalTestId": {
            "code": "MCH"
          },
          "dataValue": "29500",
          "units": "",
          "resultAbnormalFlag": "",
          "resultStatus": ""
        },
        {
          "recordType": "R",
          "sequenceNumber": "",
          "universalTestId": {
            "code": "MCHC"
          },
          "dataValue": "33800",
          "units": "",
          "resultAbnormalFlag": "",
          "resultStatus": ""
        },
        {
          "recordType": "R",
          "sequenceNumber": "",
          "universalTestId": {
            "code": "PLT"
          },
          "dataValue": "35000",
          "units": "",
          "resultAbnormalFlag": "N",
          "resultStatus": ""
        },
        {
          "recordType": "R",
          "sequenceNumber": "",
          "universalTestId": {
            "code": "LYMPH%"
          },
          "dataValue": "38600",
          "units": "",
          "resultAbnormalFlag": "",
          "resultStatus": ""
        },
        {
          "recordType": "R",
          "sequenceNumber": "",
          "universalTestId": {
            "code": "MONO%"
          },
          "dataValue": "07600",
          "units": "",
          "resultAbnormalFlag": "",
          "resultStatus": ""
        },
        {
          "recordType": "R",
          "sequenceNumber": "",
          "universalTestId": {
            "code": "NEUT%"
          },
          "dataValue": "47600",
          "units": "",
          "resultAbnormalFlag": "",
          "resultStatus": ""
        },
        {
          "recordType": "R",
          "sequenceNumber": "",
          "universalTestId": {
            "code": "EO%"
          },
          "dataValue": "05800",
          "units": "",
          "resultAbnormalFlag": "",
          "resultStatus": ""
        },
        {
          "recordType": "R",
          "sequenceNumber": "",
          "universalTestId": {
            "code": "BASO%"
          },
          "dataValue": "00400",
          "units": "",
          "resultAbnormalFlag": "",
          "resultStatus": ""
        },
        {
          "recordType": "R",
          "sequenceNumber": "",
          "universalTestId": {
            "code": "LYMPH#"
          },
          "dataValue": "034900",
          "units": "",
          "resultAbnormalFlag": "",
          "resultStatus": ""
        },
        {
          "recordType": "R",
          "sequenceNumber": "",
          "universalTestId": {
            "code": "MONO#"
          },
          "dataValue": "006900",
          "units": "",
          "resultAbnormalFlag": "",
          "resultStatus": ""
        },
        {
          "recordType": "R",
          "sequenceNumber": "",
          "universalTestId": {
            "code": "NEUT#"
          },
          "dataValue": "042900",
          "units": "",
          "resultAbnormalFlag": "",
          "resultStatus": ""
        },
        {
          "recordType": "R",
          "sequenceNumber": "",
          "universalTestId": {
            "code": "EO#"
          },
          "dataValue": "005210",
          "units": "",
          "resultAbnormalFlag": "",
          "resultStatus": ""
        },
        {
          "recordType": "R",
          "sequenceNumber": "",
          "universalTestId": {
            "code": "BASO#"
          },
          "dataValue": "000400",
          "units": "",
          "resultAbnormalFlag": "",
          "resultStatus": ""
        },
        {
          "recordType": "R",
          "sequenceNumber": "",
          "universalTestId": {
            "code": "RDW-CV"
          },
          "dataValue": "13600",
          "units": "",
          "resultAbnormalFlag": "",
          "resultStatus": ""
        },
        {
          "recordType": "R",
          "sequenceNumber": "",
          "universalTestId": {
            "code": "RDW-SD"
          },
          "dataValue": "42400",
          "units": "",
          "resultAbnormalFlag": "",
          "resultStatus": ""
        },
        {
          "recordType": "R",
          "sequenceNumber": "",
          "universalTestId": {
            "code": "PDW"
          },
          "dataValue": "10700",
          "units": "",
          "resultAbnormalFlag": "",
          "resultStatus": ""
        },
        {
          "recordType": "R",
          "sequenceNumber": "",
          "universalTestId": {
            "code": "MVP"
          },
          "dataValue": "09900",
          "units": "",
          "resultAbnormalFlag": "",
          "resultStatus": ""
        },
        {
          "recordType": "R",
          "sequenceNumber": "",
          "universalTestId": {
            "code": "P-LCR"
          },
          "dataValue": "23800",
          "units": "",
          "resultAbnormalFlag": "",
          "resultStatus": ""
        },
        {
          "recordType": "R",
          "sequenceNumber": "",
          "universalTestId": {
            "code": "PCT"
          },
          "dataValue": "03500",
          "units": "",
          "resultAbnormalFlag": "",
          "resultStatus": ""
        }
      ]
    }
  }
}

```


