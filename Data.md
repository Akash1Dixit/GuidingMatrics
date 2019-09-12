{
   "title": "Sample Chart #2",
   "id": "166273ade1950dee9f29112b826a8b7c",
   "workspace": {
      "dimensions": {
         "w": 1079
      },
      "datasources": [
         "2fb200fa299a77827c008c379f281f88",
         "2c26c9df9cb41805b6be8f2d8f2962a5",
         "8fba003daa6ad83d43794e699aafd050",
         "0ae47c6b24b8caf5dbbbde556dcdf017",
         "33678d3a0881d72c1f24b3251bd133e0",
         "2d0870fd0afd4f1797f27bbd0c6e2813",
         "9e4819f5cf6f93e9d8e7209822f51fe9",
         "4cefabbf1f80120a38969d8e4ab3fe18"
      ]
   },
   "showToolbar": false,
   "appliedMigrations": {
      "post_dst": true,
      "separate_root_dsts": true,
      "result_rows2": true
   },
   "components": [
      {
         "type": "panel_grid",
         "id": "02bfffc9-21",
         "displayName": "Layout Grid",
         "components": [
            {
               "type": "panel_grid",
               "id": "3bdebfd6",
               "displayName": "Layout Grid 5 Copy",
               "layoutConfig": {
                  "x": 0,
                  "y": 0
               },
               "components": [
                  {
                     "type": "panel_grid",
                     "id": "42981273",
                     "displayName": "Layout Grid 6 Copy 2",
                     "layoutConfig": {
                        "y": 0,
                        "x": 0
                     },
                     "components": [
                        {
                           "type": "label",
                           "id": "edcb06bd",
                           "displayName": "Label Copy 3",
                           "layoutConfig": {
                              "y": 0,
                              "x": 0
                           },
                           "size": "medium",
                           "fmt": "txt",
                           "fmtArgs": {
                              "autoFmt": {
                                 "fmtArgs": {},
                                 "defaultAggregate": "COUNT",
                                 "fmt": "txt"
                              },
                              "resultMetadata": {
                                 "ignoreDateFormat": false,
                                 "isAggregated": false,
                                 "formulaIsDataPointer": false,
                                 "suggestedName": "Unnamed 1",
                                 "resultCount": 1
                              }
                           },
                           "dstContext": {
                              "id": "dstedcb06bd",
                              "kid": "166273ade1950dee9f29112b826a8b7c"
                           },
                           "formulas": [
                              {
                                 "txt": "\"Croatia Current Year\"",
                                 "ver": 2
                              }
                           ],
                           "data": [
                              [
                                 "Croatia Current Year"
                              ]
                           ],
                           "autoFmt": true,
                           "align": "c",
                           "font_colour": "cx-color_blue_5",
                           "wrap": true
                        },
                        {
                           "type": "label",
                           "id": "1fb8e0c4",
                           "displayName": "Label 2 Copy",
                           "layoutConfig": {
                              "y": 1,
                              "x": 0
                           },
                           "size": "xx-small",
                           "fmt": "txt",
                           "fmtArgs": {
                              "autoFmt": {
                                 "fmtArgs": {},
                                 "defaultAggregate": "COUNT",
                                 "fmt": "txt"
                              },
                              "resultMetadata": {
                                 "ignoreDateFormat": false,
                                 "isAggregated": false,
                                 "formulaIsDataPointer": false,
                                 "suggestedName": "Unnamed 1",
                                 "resultCount": 1
                              }
                           },
                           "dstContext": {
                              "id": "dst1fb8e0c4",
                              "kid": "166273ade1950dee9f29112b826a8b7c"
                           },
                           "components": [
                              {
                                 "type": "data_slot",
                                 "role": "data",
                                 "id": "39b8ecf9",
                                 "displayName": "CY Income",
                                 "fmt": "txt",
                                 "fmtArgs": {
                                    "autoFmt": {
                                       "fmtArgs": {},
                                       "defaultAggregate": "COUNT",
                                       "fmt": "txt"
                                    },
                                    "resultMetadata": {
                                       "ignoreDateFormat": false,
                                       "isAggregated": false,
                                       "formulaIsDataPointer": false,
                                       "suggestedName": "Unnamed 1",
                                       "resultCount": 1
                                    }
                                 },
                                 "dstContext": {
                                    "id": "dst39b8ecf9",
                                    "kid": "166273ade1950dee9f29112b826a8b7c"
                                 },
                                 "isDstRoot": true,
                                 "formulas": [
                                    {
                                       "txt": "SUM(SLICE(9e4819f5cf6f93e9d8e7209822f51fe9@B:B;))",
                                       "ver": 2
                                    }
                                 ],
                                 "data": [
                                    [
                                       186314261.65999997
                                    ]
                                 ],
                                 "autoFmt": true,
                                 "name": "CY Income"
                              },
                              {
                                 "type": "data_slot",
                                 "role": "data",
                                 "id": "9257e1d0",
                                 "displayName": "CY Expense",
                                 "fmt": "txt",
                                 "fmtArgs": {
                                    "autoFmt": {
                                       "fmtArgs": {},
                                       "defaultAggregate": "COUNT",
                                       "fmt": "txt"
                                    },
                                    "resultMetadata": {
                                       "ignoreDateFormat": false,
                                       "isAggregated": false,
                                       "expiryScheme": [
                                          {
                                             "expiryType": "EOD",
                                             "expiryTimezoneId": null
                                          }
                                       ],
                                       "formulaIsDataPointer": false,
                                       "suggestedName": "Unnamed 1",
                                       "resultCount": 1
                                    }
                                 },
                                 "dstContext": {
                                    "id": "dst9257e1d0",
                                    "kid": "166273ade1950dee9f29112b826a8b7c"
                                 },
                                 "isDstRoot": true,
                                 "formulas": [
                                    {
                                       "txt": "(SUM(&'afdd612f-5')+SUM(SLICE(0ae47c6b24b8caf5dbbbde556dcdf017@A:A;)))",
                                       "ver": 2
                                    }
                                 ],
                                 "data": [
                                    [
                                       174166752.93199998
                                    ]
                                 ],
                                 "autoFmt": true,
                                 "name": "CY Expense"
                              }
                           ],
                           "formulas": [
                              {
                                 "txt": "if(&'3772d47f'>&'6fc6a393',\"Profit\",\"Loss\")",
                                 "ver": 2
                              }
                           ],
                           "data": [
                              [
                                 "Loss"
                              ]
                           ],
                           "autoFmt": true,
                           "align": "c",
                           "font_colour": "cx-color_orange_4",
                           "wrap": true
                        },
                        {
                           "type": "simple_value",
                           "id": "f06e0f20",
                           "displayName": "Gross Margin",
                           "layoutConfig": {
                              "y": 2,
                              "x": 0
                           },
                           "renamed": true,
                           "dstContext": {
                              "id": "dstf06e0f20"
                           },
                           "components": [
                              {
                                 "type": "label",
                                 "role": "primary",
                                 "id": "74ee624f",
                                 "displayName": "Primary Value",
                                 "size": "large",
                                 "fmt": "pct",
                                 "fmtArgs": {
                                    "precision": "2",
                                    "resultMetadata": {
                                       "ignoreDateFormat": false,
                                       "isAggregated": false,
                                       "formulaIsDataPointer": false,
                                       "suggestedName": "Unnamed 1",
                                       "resultCount": 1
                                    }
                                 },
                                 "dstContext": {
                                    "id": "dst74ee624f",
                                    "kid": "166273ade1950dee9f29112b826a8b7c"
                                 },
                                 "formulas": [
                                    {
                                       "txt": "(&'39b8ecf9'-SUM(SLICE(33678d3a0881d72c1f24b3251bd133e0@B:B;))-SUM(SLICE(2d0870fd0afd4f1797f27bbd0c6e2813@B:B;))-SUM(SLICE(2fb200fa299a77827c008c379f281f88@B:B;))+SUM(SLICE(2c26c9df9cb41805b6be8f2d8f2962a5@B:B;)))/(&'39b8ecf9'-SUM(SLICE(33678d3a0881d72c1f24b3251bd133e0@B:B;))+SUM(SLICE(2c26c9df9cb41805b6be8f2d8f2962a5@B:B;)))",
                                       "ver": 2
                                    }
                                 ],
                                 "data": [
                                    [
                                       0.27738386100786266
                                    ]
                                 ],
                                 "autoFmt": false,
                                 "align": "c",
                                 "font_colour": "#56a5e2"
                              },
                              {
                                 "type": "label",
                                 "role": "secondary",
                                 "id": "d1159b91",
                                 "displayName": "Secondary Value",
                                 "size": "medium",
                                 "fmt": "txt",
                                 "fmtArgs": {
                                    "resultMetadata": {
                                       "ignoreDateFormat": false,
                                       "isAggregated": false,
                                       "formulaIsDataPointer": false,
                                       "suggestedName": "Unnamed 1",
                                       "resultCount": 1
                                    },
                                    "autoFmt": {
                                       "fmtArgs": {},
                                       "defaultAggregate": "COUNT",
                                       "fmt": "txt"
                                    }
                                 },
                                 "dstContext": {
                                    "id": "dstd1159b91",
                                    "kid": "166273ade1950dee9f29112b826a8b7c"
                                 },
                                 "formulas": [
                                    {
                                       "txt": "\"GROSS MARGIN CROATIA\"",
                                       "ver": 2
                                    }
                                 ],
                                 "data": [
                                    [
                                       "GROSS MARGIN CROATIA"
                                    ]
                                 ],
                                 "autoFmt": true,
                                 "align": "c",
                                 "font_colour": "cx-color_000"
                              }
                           ]
                        },
                        {
                           "type": "separator",
                           "id": "f7dce1b5",
                           "displayName": "Separator",
                           "layoutConfig": {
                              "y": 2,
                              "x": 1
                           },
                           "orientation": "v",
                           "line_style": "Dash"
                        },
                        {
                           "type": "simple_value",
                           "id": "0ad17d26",
                           "displayName": "Net Profit",
                           "layoutConfig": {
                              "y": 2,
                              "x": 2
                           },
                           "renamed": true,
                           "dstContext": {
                              "id": "dst0ad17d26"
                           },
                           "components": [
                              {
                                 "type": "label",
                                 "role": "primary",
                                 "id": "f29f8ea2",
                                 "displayName": "Primary Value",
                                 "size": "large",
                                 "fmt": "pct",
                                 "fmtArgs": {
                                    "precision": "2",
                                    "suffix": "",
                                    "resultMetadata": {
                                       "ignoreDateFormat": false,
                                       "isAggregated": false,
                                       "formulaIsDataPointer": false,
                                       "suggestedName": "Unnamed 1",
                                       "expiryScheme": [
                                          {
                                             "expiryType": "EOD",
                                             "expiryTimezoneId": null
                                          }
                                       ],
                                       "resultCount": 1
                                    }
                                 },
                                 "dstContext": {
                                    "id": "dstf29f8ea2",
                                    "kid": "166273ade1950dee9f29112b826a8b7c"
                                 },
                                 "formulas": [
                                    {
                                       "txt": "(&'e395afda')/(&'39b8ecf9'-SUM(SLICE(33678d3a0881d72c1f24b3251bd133e0@B:B;))+SUM(SLICE(2c26c9df9cb41805b6be8f2d8f2962a5@B:B;)))",
                                       "ver": 2
                                    }
                                 ],
                                 "data": [
                                    [
                                       0.27616857874827766
                                    ]
                                 ],
                                 "autoFmt": false,
                                 "align": "c",
                                 "font_colour": "#56a5e2"
                              },
                              {
                                 "type": "label",
                                 "role": "secondary",
                                 "id": "bbec861a",
                                 "displayName": "Secondary Value",
                                 "size": "medium",
                                 "fmt": "txt",
                                 "fmtArgs": {
                                    "resultMetadata": {
                                       "ignoreDateFormat": false,
                                       "isAggregated": false,
                                       "formulaIsDataPointer": false,
                                       "suggestedName": "Unnamed 1",
                                       "resultCount": 1
                                    },
                                    "autoFmt": {
                                       "fmtArgs": {},
                                       "defaultAggregate": "COUNT",
                                       "fmt": "txt"
                                    }
                                 },
                                 "dstContext": {
                                    "id": "dstbbec861a",
                                    "kid": "166273ade1950dee9f29112b826a8b7c"
                                 },
                                 "formulas": [
                                    {
                                       "txt": "\"NET PROFIT CROATIA\"",
                                       "ver": 2
                                    }
                                 ],
                                 "data": [
                                    [
                                       "NET PROFIT CROATIA"
                                    ]
                                 ],
                                 "autoFmt": true,
                                 "align": "c",
                                 "font_colour": "cx-color_000"
                              }
                           ]
                        },
                        {
                           "type": "separator",
                           "id": "93a5a61b",
                           "displayName": "Separator 10",
                           "layoutConfig": {
                              "y": 4,
                              "x": 0
                           },
                           "line_style": "ShortDot"
                        },
                        {
                           "type": "simple_value",
                           "id": "1685410f",
                           "displayName": "Gross Margin Amount",
                           "layoutConfig": {
                              "y": 6,
                              "x": 0
                           },
                           "renamed": true,
                           "dstContext": {
                              "id": "dst1685410f"
                           },
                           "components": [
                              {
                                 "type": "label",
                                 "role": "primary",
                                 "id": "61b28216",
                                 "displayName": "Primary Value",
                                 "size": "medium",
                                 "fmt": "num",
                                 "fmtArgs": {
                                    "suffix": " KM",
                                    "resultMetadata": {
                                       "ignoreDateFormat": false,
                                       "isAggregated": false,
                                       "formulaIsDataPointer": false,
                                       "suggestedName": "Unnamed 1",
                                       "resultCount": 1
                                    }
                                 },
                                 "dstContext": {
                                    "id": "dst61b28216",
                                    "kid": "166273ade1950dee9f29112b826a8b7c"
                                 },
                                 "formulas": [
                                    {
                                       "txt": "(&'39b8ecf9'-SUM(SLICE(33678d3a0881d72c1f24b3251bd133e0@B:B;))-SUM(SLICE(2d0870fd0afd4f1797f27bbd0c6e2813@B:B;))-SUM(SLICE(2fb200fa299a77827c008c379f281f88@B:B;))+SUM(SLICE(2c26c9df9cb41805b6be8f2d8f2962a5@B:B;)))",
                                       "ver": 2
                                    }
                                 ],
                                 "data": [
                                    [
                                       66743505.42
                                    ]
                                 ],
                                 "autoFmt": false,
                                 "align": "c",
                                 "font_colour": "cx-color_blue_5"
                              },
                              {
                                 "type": "label",
                                 "role": "secondary",
                                 "id": "21bf1198",
                                 "displayName": "Secondary Value",
                                 "size": "xx-small",
                                 "fmt": "txt",
                                 "fmtArgs": {
                                    "resultMetadata": {
                                       "ignoreDateFormat": false,
                                       "isAggregated": false,
                                       "formulaIsDataPointer": false,
                                       "suggestedName": "Unnamed 1",
                                       "resultCount": 1
                                    },
                                    "autoFmt": {
                                       "fmtArgs": {},
                                       "defaultAggregate": "COUNT",
                                       "fmt": "txt"
                                    }
                                 },
                                 "dstContext": {
                                    "id": "dst21bf1198",
                                    "kid": "166273ade1950dee9f29112b826a8b7c"
                                 },
                                 "formulas": [
                                    {
                                       "txt": "\"Gross Margin Amount\"",
                                       "ver": 2
                                    }
                                 ],
                                 "data": [
                                    [
                                       "Gross Margin Amount"
                                    ]
                                 ],
                                 "autoFmt": true,
                                 "align": "c",
                                 "font_colour": "cx-color_000"
                              }
                           ]
                        },
                        {
                           "type": "separator",
                           "id": "74f1c282",
                           "displayName": "Separator 2",
                           "layoutConfig": {
                              "y": 6,
                              "x": 1
                           },
                           "orientation": "v",
                           "line_style": "Dash"
                        },
                        {
                           "type": "simple_value",
                           "id": "1cbdb111",
                           "displayName": "Net Profit Amount",
                           "layoutConfig": {
                              "y": 6,
                              "x": 2
                           },
                           "renamed": true,
                           "dstContext": {
                              "id": "dst1cbdb111"
                           },
                           "components": [
                              {
                                 "type": "label",
                                 "role": "primary",
                                 "id": "e395afda",
                                 "displayName": "NP Amount",
                                 "renamed": true,
                                 "size": "medium",
                                 "fmt": "num",
                                 "fmtArgs": {
                                    "suffix": " KM",
                                    "resultMetadata": {
                                       "ignoreDateFormat": false,
                                       "isAggregated": false,
                                       "formulaIsDataPointer": false,
                                       "suggestedName": "Unnamed 1",
                                       "expiryScheme": [
                                          {
                                             "expiryType": "EOD",
                                             "expiryTimezoneId": null
                                          }
                                       ],
                                       "resultCount": 1
                                    }
                                 },
                                 "dstContext": {
                                    "id": "dste395afda",
                                    "kid": "166273ade1950dee9f29112b826a8b7c"
                                 },
                                 "formulas": [
                                    {
                                       "txt": "(&'39b8ecf9'-SUM(SLICE(33678d3a0881d72c1f24b3251bd133e0@B:B;))-SUM(SLICE(2d0870fd0afd4f1797f27bbd0c6e2813@B:B;))-SUM(SLICE(2fb200fa299a77827c008c379f281f88@B:B;))+SUM(SLICE(2c26c9df9cb41805b6be8f2d8f2962a5@B:B;))-SUM(&'5f9b182e-30')-SUM(&'69744d13-2'))",
                                       "ver": 2
                                    }
                                 ],
                                 "data": [
                                    [
                                       66451086.82800001
                                    ]
                                 ],
                                 "autoFmt": false,
                                 "align": "c",
                                 "font_colour": "cx-color_blue_5"
                              },
                              {
                                 "type": "label",
                                 "role": "secondary",
                                 "id": "03e8ac91",
                                 "displayName": "Secondary Value",
                                 "size": "xx-small",
                                 "fmt": "txt",
                                 "fmtArgs": {
                                    "resultMetadata": {
                                       "ignoreDateFormat": false,
                                       "isAggregated": false,
                                       "formulaIsDataPointer": false,
                                       "suggestedName": "Unnamed 1",
                                       "resultCount": 1
                                    },
                                    "autoFmt": {
                                       "fmtArgs": {},
                                       "defaultAggregate": "COUNT",
                                       "fmt": "txt"
                                    }
                                 },
                                 "dstContext": {
                                    "id": "dst03e8ac91",
                                    "kid": "166273ade1950dee9f29112b826a8b7c"
                                 },
                                 "formulas": [
                                    {
                                       "txt": "\"Net Profit Amount\"",
                                       "ver": 2
                                    }
                                 ],
                                 "data": [
                                    [
                                       "Net Profit Amount"
                                    ]
                                 ],
                                 "autoFmt": true,
                                 "align": "c",
                                 "font_colour": "cx-color_000"
                              }
                           ]
                        }
                     ],
                     "rows": 7,
                     "cols": 3,
                     "widths": [
                        {
                           "w": "5%",
                           "x": 1
                        }
                     ],
                     "cellData": [
                        {
                           "y": 0,
                           "x": 1
                        },
                        {
                           "w": 3,
                           "y": 0,
                           "x": 0
                        },
                        {
                           "w": 3,
                           "y": 1,
                           "x": 0
                        },
                        {
                           "w": 3,
                           "y": 4,
                           "x": 0
                        }
                     ]
                  },
                  {
                     "type": "separator",
                     "id": "192e9dc9",
                     "displayName": "Separator 9 Copy",
                     "layoutConfig": {
                        "y": 0,
                        "x": 1
                     },
                     "orientation": "v",
                     "line_style": "Dash"
                  },
                  {
                     "type": "panel_grid",
                     "id": "53a3fe48",
                     "displayName": "Layout Grid 6 Copy 3",
                     "layoutConfig": {
                        "y": 0,
                        "x": 2
                     },
                     "components": [
                        {
                           "type": "label",
                           "id": "1d36f4b2",
                           "displayName": "BIH Prev Year",
                           "layoutConfig": {
                              "y": 0,
                              "x": 0
                           },
                           "renamed": true,
                           "size": "medium",
                           "fmt": "txt",
                           "fmtArgs": {
                              "autoFmt": {
                                 "fmtArgs": {},
                                 "defaultAggregate": "COUNT",
                                 "fmt": "txt"
                              },
                              "resultMetadata": {
                                 "ignoreDateFormat": false,
                                 "isAggregated": false,
                                 "formulaIsDataPointer": false,
                                 "suggestedName": "Unnamed 1",
                                 "resultCount": 1
                              }
                           },
                           "dstContext": {
                              "id": "dst1d36f4b2",
                              "kid": "166273ade1950dee9f29112b826a8b7c"
                           },
                           "formulas": [
                              {
                                 "txt": "\"Croatia Prev Year\"",
                                 "ver": 2
                              }
                           ],
                           "data": [
                              [
                                 "Croatia Prev Year"
                              ]
                           ],
                           "autoFmt": true,
                           "align": "c",
                           "font_colour": "cx-color_blue_5",
                           "wrap": true
                        },
                        {
                           "type": "label",
                           "id": "22fde0e0",
                           "displayName": "Label 2",
                           "layoutConfig": {
                              "y": 1,
                              "x": 0
                           },
                           "size": "xx-small",
                           "fmt": "txt",
                           "fmtArgs": {
                              "autoFmt": {
                                 "fmtArgs": {},
                                 "defaultAggregate": "COUNT",
                                 "fmt": "txt"
                              },
                              "resultMetadata": {
                                 "ignoreDateFormat": false,
                                 "isAggregated": false,
                                 "formulaIsDataPointer": false,
                                 "suggestedName": "Unnamed 1",
                                 "resultCount": 1
                              }
                           },
                           "dstContext": {
                              "id": "dst22fde0e0",
                              "kid": "166273ade1950dee9f29112b826a8b7c"
                           },
                           "formulas": [
                              {
                                 "txt": "if(&'3772d47f'>&'6fc6a393',\"Profit\",\"Loss\")",
                                 "ver": 2
                              }
                           ],
                           "data": [
                              [
                                 "Loss"
                              ]
                           ],
                           "autoFmt": true,
                           "align": "c",
                           "font_colour": "cx-color_orange_4",
                           "wrap": true
                        },
                        {
                           "type": "simple_value",
                           "id": "9eafe313",
                           "displayName": "Gross Margin PY",
                           "layoutConfig": {
                              "y": 2,
                              "x": 0
                           },
                           "renamed": true,
                           "dstContext": {
                              "id": "dst9eafe313"
                           },
                           "components": [
                              {
                                 "type": "label",
                                 "role": "primary",
                                 "id": "5dc3a322",
                                 "displayName": "Primary Value",
                                 "size": "large",
                                 "fmt": "pct",
                                 "fmtArgs": {
                                    "precision": "2",
                                    "resultMetadata": {
                                       "ignoreDateFormat": false,
                                       "isAggregated": false,
                                       "formulaIsDataPointer": false,
                                       "suggestedName": "Unnamed 1",
                                       "resultCount": 1
                                    }
                                 },
                                 "dstContext": {
                                    "id": "dst5dc3a322",
                                    "kid": "166273ade1950dee9f29112b826a8b7c"
                                 },
                                 "formulas": [
                                    {
                                       "txt": "(&'3772d47f'-SUM(SLICE(4cefabbf1f80120a38969d8e4ab3fe18@Violeta Croatia,7:7;,2,-1))-SUM(SLICE(4cefabbf1f80120a38969d8e4ab3fe18@Violeta Croatia,5:5;,2,-1))+SUM(SLICE(4cefabbf1f80120a38969d8e4ab3fe18@Violeta Croatia,10:10;,2,-1)))/(&'3772d47f'-SUM(SLICE(4cefabbf1f80120a38969d8e4ab3fe18@Violeta Croatia,7:7;,2,-1))+SUM(SLICE(4cefabbf1f80120a38969d8e4ab3fe18@Violeta Croatia,10:10;,2,-1)))",
                                       "ver": 2
                                    }
                                 ],
                                 "data": [
                                    [
                                       0.26652971170773443
                                    ]
                                 ],
                                 "autoFmt": false,
                                 "align": "c",
                                 "font_colour": "#56a5e2"
                              },
                              {
                                 "type": "label",
                                 "role": "secondary",
                                 "id": "c07a7108",
                                 "displayName": "Secondary Value",
                                 "size": "medium",
                                 "fmt": "txt",
                                 "fmtArgs": {
                                    "resultMetadata": {
                                       "ignoreDateFormat": false,
                                       "isAggregated": false,
                                       "formulaIsDataPointer": false,
                                       "suggestedName": "Unnamed 1",
                                       "resultCount": 1
                                    },
                                    "autoFmt": {
                                       "fmtArgs": {},
                                       "defaultAggregate": "COUNT",
                                       "fmt": "txt"
                                    }
                                 },
                                 "dstContext": {
                                    "id": "dstc07a7108",
                                    "kid": "166273ade1950dee9f29112b826a8b7c"
                                 },
                                 "formulas": [
                                    {
                                       "txt": "\"GROSS MARGIN BIH\"",
                                       "ver": 2
                                    }
                                 ],
                                 "data": [
                                    [
                                       "GROSS MARGIN BIH"
                                    ]
                                 ],
                                 "autoFmt": true,
                                 "align": "c",
                                 "font_colour": "cx-color_000"
                              }
                           ]
                        },
                        {
                           "type": "separator",
                           "id": "d409bff3",
                           "displayName": "Separator 3",
                           "layoutConfig": {
                              "y": 2,
                              "x": 1
                           },
                           "orientation": "v",
                           "line_style": "Dash"
                        },
                        {
                           "type": "simple_value",
                           "id": "dcdae2d3",
                           "displayName": "Profit Percentage LY",
                           "layoutConfig": {
                              "y": 2,
                              "x": 2
                           },
                           "renamed": true,
                           "dstContext": {
                              "id": "dstdcdae2d3"
                           },
                           "components": [
                              {
                                 "type": "label",
                                 "role": "primary",
                                 "id": "a62b3c6c",
                                 "displayName": "Profit Percent Croatia LY",
                                 "renamed": true,
                                 "size": "medium",
                                 "fmt": "pct",
                                 "fmtArgs": {
                                    "precision": "2",
                                    "resultMetadata": {
                                       "ignoreDateFormat": false,
                                       "isAggregated": false,
                                       "formulaIsDataPointer": false,
                                       "suggestedName": "Unnamed 1",
                                       "resultCount": 1
                                    }
                                 },
                                 "dstContext": {
                                    "id": "dsta62b3c6c",
                                    "kid": "166273ade1950dee9f29112b826a8b7c"
                                 },
                                 "conditions": [
                                    {
                                       "predicates": [
                                          {
                                             "left": {
                                                "cx": "3772d47f"
                                             },
                                             "type": "gteq",
                                             "right": {
                                                "cx": "6fc6a393"
                                             }
                                          }
                                       ],
                                       "reactions": [
                                          {
                                             "value": "cx-theme_green_3",
                                             "isScalar": true,
                                             "type": "color"
                                          }
                                       ]
                                    },
                                    {
                                       "predicates": [
                                          {
                                             "left": {
                                                "cx": "3772d47f"
                                             },
                                             "type": "lt",
                                             "right": {
                                                "cx": "6fc6a393"
                                             }
                                          }
                                       ],
                                       "reactions": [
                                          {
                                             "value": "cx-theme_red_4",
                                             "isScalar": true,
                                             "type": "color"
                                          }
                                       ]
                                    }
                                 ],
                                 "formulas": [
                                    {
                                       "txt": "(1-&'6fc6a393'/(&'3772d47f'-SUM(SLICE(4cefabbf1f80120a38969d8e4ab3fe18@Violeta Croatia,7:7;,2,-1))+SUM(SLICE(4cefabbf1f80120a38969d8e4ab3fe18@Violeta Croatia,10:10;,2,-1))))",
                                       "ver": 2
                                    }
                                 ],
                                 "data": [
                                    [
                                       0.00375473690522099
                                    ]
                                 ],
                                 "autoFmt": false,
                                 "align": "c"
                              },
                              {
                                 "type": "label",
                                 "role": "secondary",
                                 "id": "168ca239",
                                 "displayName": "Secondary Value",
                                 "size": "xx-small",
                                 "fmt": "txt",
                                 "fmtArgs": {
                                    "autoFmt": {
                                       "fmtArgs": {},
                                       "defaultAggregate": "COUNT",
                                       "fmt": "txt"
                                    },
                                    "resultMetadata": {
                                       "ignoreDateFormat": false,
                                       "isAggregated": false,
                                       "formulaIsDataPointer": false,
                                       "suggestedName": "Unnamed 1",
                                       "resultCount": 1
                                    }
                                 },
                                 "dstContext": {
                                    "id": "dst168ca239",
                                    "kid": "166273ade1950dee9f29112b826a8b7c"
                                 },
                                 "formulas": [
                                    {
                                       "txt": "if(&'3772d47f'>&'6fc6a393',\"Profit Percent\",\"Loss Percent\")",
                                       "ver": 2
                                    }
                                 ],
                                 "data": [
                                    [
                                       "Loss Percent"
                                    ]
                                 ],
                                 "autoFmt": true,
                                 "align": "c",
                                 "font_colour": "cx-color_yellow_green_5"
                              }
                           ]
                        },
                        {
                           "type": "separator",
                           "id": "7e17b668",
                           "displayName": "Separator 10 Copy",
                           "layoutConfig": {
                              "y": 4,
                              "x": 0
                           },
                           "line_style": "ShortDot"
                        },
                        {
                           "type": "simple_value",
                           "id": "b290a427",
                           "displayName": "Gross Margin Amount Copy",
                           "layoutConfig": {
                              "y": 6,
                              "x": 0
                           },
                           "renamed": true,
                           "dstContext": {
                              "id": "dstb290a427"
                           },
                           "components": [
                              {
                                 "type": "label",
                                 "role": "primary",
                                 "id": "1109d1c3",
                                 "displayName": "Primary Value",
                                 "size": "medium",
                                 "fmt": "num",
                                 "fmtArgs": {
                                    "suffix": " KM",
                                    "resultMetadata": {
                                       "ignoreDateFormat": false,
                                       "isAggregated": false,
                                       "formulaIsDataPointer": false,
                                       "suggestedName": "Unnamed 1",
                                       "resultCount": 1
                                    }
                                 },
                                 "dstContext": {
                                    "id": "dst1109d1c3",
                                    "kid": "166273ade1950dee9f29112b826a8b7c"
                                 },
                                 "formulas": [
                                    {
                                       "txt": "(&'3772d47f'-SUM(SLICE(4cefabbf1f80120a38969d8e4ab3fe18@Violeta Croatia,7:7;,2,-1))-SUM(SLICE(4cefabbf1f80120a38969d8e4ab3fe18@Violeta Croatia,5:5;,2,-1))+SUM(SLICE(4cefabbf1f80120a38969d8e4ab3fe18@Violeta Croatia,10:10;,2,-1)))",
                                       "ver": 2
                                    }
                                 ],
                                 "data": [
                                    [
                                       80996297.00999999
                                    ]
                                 ],
                                 "autoFmt": false,
                                 "align": "c",
                                 "font_colour": "cx-color_blue_5"
                              },
                              {
                                 "type": "label",
                                 "role": "secondary",
                                 "id": "352b05d5",
                                 "displayName": "Secondary Value",
                                 "size": "xx-small",
                                 "fmt": "txt",
                                 "fmtArgs": {
                                    "resultMetadata": {
                                       "ignoreDateFormat": false,
                                       "isAggregated": false,
                                       "formulaIsDataPointer": false,
                                       "suggestedName": "Unnamed 1",
                                       "resultCount": 1
                                    },
                                    "autoFmt": {
                                       "fmtArgs": {},
                                       "defaultAggregate": "COUNT",
                                       "fmt": "txt"
                                    }
                                 },
                                 "dstContext": {
                                    "id": "dst352b05d5",
                                    "kid": "166273ade1950dee9f29112b826a8b7c"
                                 },
                                 "formulas": [
                                    {
                                       "txt": "\"Gross Margin Amount\"",
                                       "ver": 2
                                    }
                                 ],
                                 "data": [
                                    [
                                       "Gross Margin Amount"
                                    ]
                                 ],
                                 "autoFmt": true,
                                 "align": "c",
                                 "font_colour": "cx-color_000"
                              }
                           ]
                        },
                        {
                           "type": "separator",
                           "id": "e51b3071",
                           "displayName": "Separator 4",
                           "layoutConfig": {
                              "y": 6,
                              "x": 1
                           },
                           "orientation": "v",
                           "line_style": "Dash"
                        },
                        {
                           "type": "simple_value",
                           "id": "9ec28c44",
                           "displayName": "Profit Amount LY",
                           "layoutConfig": {
                              "y": 6,
                              "x": 2
                           },
                           "renamed": true,
                           "dstContext": {
                              "id": "dst9ec28c44"
                           },
                           "components": [
                              {
                                 "type": "label",
                                 "role": "primary",
                                 "id": "f90204ec",
                                 "displayName": "Profit Amount LY Primary Value",
                                 "renamed": true,
                                 "size": "medium",
                                 "fmt": "num",
                                 "fmtArgs": {
                                    "suffix": " KM",
                                    "resultMetadata": {
                                       "ignoreDateFormat": false,
                                       "isAggregated": false,
                                       "formulaIsDataPointer": false,
                                       "suggestedName": "Unnamed 1",
                                       "resultCount": 1
                                    }
                                 },
                                 "dstContext": {
                                    "id": "dstf90204ec",
                                    "kid": "166273ade1950dee9f29112b826a8b7c"
                                 },
                                 "conditions": [
                                    {
                                       "predicates": [
                                          {
                                             "left": {
                                                "cx": "3772d47f"
                                             },
                                             "type": "lteq",
                                             "right": {
                                                "cx": "6fc6a393"
                                             }
                                          }
                                       ],
                                       "reactions": [
                                          {
                                             "value": "cx-theme_red_4",
                                             "isScalar": true,
                                             "type": "color"
                                          },
                                          {
                                             "value": "ind-triangle-down-red",
                                             "isScalar": true,
                                             "type": "icon",
                                             "pos": "right"
                                          }
                                       ]
                                    },
                                    {
                                       "predicates": [
                                          {
                                             "left": {
                                                "cx": "3772d47f"
                                             },
                                             "type": "gt",
                                             "right": {
                                                "cx": "6fc6a393"
                                             }
                                          }
                                       ],
                                       "reactions": [
                                          {
                                             "value": "cx-theme_green_3",
                                             "isScalar": true,
                                             "type": "color"
                                          },
                                          {
                                             "value": "ind-triangle-up-green",
                                             "isScalar": true,
                                             "type": "icon",
                                             "pos": "right"
                                          }
                                       ]
                                    }
                                 ],
                                 "components": [
                                    {
                                       "type": "data_slot",
                                       "role": "data",
                                       "id": "3772d47f",
                                       "displayName": "Income LY",
                                       "fmt": "txt",
                                       "fmtArgs": {
                                          "autoFmt": {
                                             "fmtArgs": {},
                                             "defaultAggregate": "COUNT",
                                             "fmt": "txt"
                                          },
                                          "resultMetadata": {
                                             "ignoreDateFormat": false,
                                             "isAggregated": false,
                                             "formulaIsDataPointer": false,
                                             "suggestedName": "Unnamed 1",
                                             "resultCount": 1
                                          }
                                       },
                                       "dstContext": {
                                          "id": "dst3772d47f",
                                          "kid": "166273ade1950dee9f29112b826a8b7c"
                                       },
                                       "isDstRoot": true,
                                       "formulas": [
                                          {
                                             "txt": "SUM(SLICE(4cefabbf1f80120a38969d8e4ab3fe18@Violeta Croatia,3:3;,2,-1))",
                                             "ver": 2
                                          }
                                       ],
                                       "data": [
                                          [
                                             298469996.51
                                          ]
                                       ],
                                       "autoFmt": true,
                                       "name": "Income LY"
                                    },
                                    {
                                       "type": "data_slot",
                                       "role": "data",
                                       "id": "6fc6a393",
                                       "displayName": "Expense LY",
                                       "fmt": "txt",
                                       "fmtArgs": {
                                          "autoFmt": {
                                             "fmtArgs": {},
                                             "defaultAggregate": "COUNT",
                                             "fmt": "txt"
                                          },
                                          "resultMetadata": {
                                             "ignoreDateFormat": false,
                                             "isAggregated": false,
                                             "formulaIsDataPointer": false,
                                             "suggestedName": "Unnamed 1",
                                             "resultCount": 1
                                          }
                                       },
                                       "dstContext": {
                                          "id": "dst6fc6a393",
                                          "kid": "166273ade1950dee9f29112b826a8b7c"
                                       },
                                       "isDstRoot": true,
                                       "formulas": [
                                          {
                                             "txt": "SUM(SLICE(4cefabbf1f80120a38969d8e4ab3fe18@Violeta Croatia,8:8;,2,-1))",
                                             "ver": 2
                                          }
                                       ],
                                       "data": [
                                          [
                                             302751151.85999995
                                          ]
                                       ],
                                       "autoFmt": true,
                                       "name": "Expense LY"
                                    }
                                 ],
                                 "formulas": [
                                    {
                                       "txt": "(&'3772d47f'-SUM(SLICE(4cefabbf1f80120a38969d8e4ab3fe18@Violeta Croatia,7:7;,2,-1))-SUM(SLICE(4cefabbf1f80120a38969d8e4ab3fe18@Violeta Croatia,5:5;,2,-1))+SUM(SLICE(4cefabbf1f80120a38969d8e4ab3fe18@Violeta Croatia,10:10;,2,-1))-SUM(SLICE(4cefabbf1f80120a38969d8e4ab3fe18@Violeta Croatia,6:6;,2,-1)))",
                                       "ver": 2
                                    }
                                 ],
                                 "data": [
                                    [
                                       1141035.2099999934
                                    ]
                                 ],
                                 "autoFmt": false,
                                 "align": "c"
                              },
                              {
                                 "type": "label",
                                 "role": "secondary",
                                 "id": "78ec647d",
                                 "displayName": "Secondary Value",
                                 "size": "xx-small",
                                 "fmt": "txt",
                                 "fmtArgs": {
                                    "autoFmt": {
                                       "fmtArgs": {},
                                       "defaultAggregate": "COUNT",
                                       "fmt": "txt"
                                    },
                                    "resultMetadata": {
                                       "ignoreDateFormat": false,
                                       "isAggregated": false,
                                       "formulaIsDataPointer": false,
                                       "suggestedName": "Unnamed 1",
                                       "resultCount": 1
                                    }
                                 },
                                 "dstContext": {
                                    "id": "dst78ec647d",
                                    "kid": "166273ade1950dee9f29112b826a8b7c"
                                 },
                                 "formulas": [
                                    {
                                       "txt": "if(&'3772d47f'>&'6fc6a393',\"Profit Amount\",\"Loss Amount\")",
                                       "ver": 2
                                    }
                                 ],
                                 "data": [
                                    [
                                       "Loss Amount"
                                    ]
                                 ],
                                 "autoFmt": true,
                                 "align": "c",
                                 "font_colour": "cx-color_yellow_green_5"
                              }
                           ]
                        }
                     ],
                     "rows": 7,
                     "cols": 3,
                     "widths": [
                        {
                           "w": "5%",
                           "x": 1
                        }
                     ],
                     "cellData": [
                        {
                           "y": 0,
                           "x": 1
                        },
                        {
                           "w": 3,
                           "y": 0,
                           "x": 0
                        },
                        {
                           "w": 3,
                           "y": 1,
                           "x": 0
                        },
                        {
                           "alignment": 1,
                           "y": 2,
                           "x": 2
                        },
                        {
                           "w": 3,
                           "y": 4,
                           "x": 0
                        }
                     ]
                  }
               ],
               "rows": 1,
               "cols": 3,
               "widths": [
                  {
                     "w": "5%",
                     "x": 1
                  }
               ],
               "cellData": [
                  {
                     "y": 0,
                     "x": 1
                  }
               ]
            }
         ],
         "rows": 1,
         "cols": 1
      },
      {
         "type": "table",
         "id": "c05ca424-1",
         "displayName": "Table",
         "dstContext": {
            "id": "dstc05ca4241",
            "kid": "166273ade1950dee9f29112b826a8b7c"
         },
         "components": [
            {
               "type": "table_col",
               "role": "tcol",
               "id": "69744d13-2",
               "displayName": "Unlocked_OtherCost",
               "namerenamed": true,
               "vis": false,
               "size": "xx-small",
               "fmt": "num",
               "fmtArgs": {
                  "resultMetadata": {
                     "ignoreDateFormat": false,
                     "isAggregated": false,
                     "expiryScheme": [
                        {
                           "expiryType": "EOD",
                           "expiryTimezoneId": null
                        }
                     ],
                     "formulaIsDataPointer": false,
                     "suggestedName": "Unnamed 1",
                     "resultCount": 1
                  },
                  "autoFmt": {
                     "fmtArgs": {
                        "precision": "4"
                     },
                     "defaultAggregate": "SUM",
                     "fmt": "num"
                  },
                  "precision": "0"
               },
               "components": [],
               "formulas": [
                  {
                     "txt": "ARRAY((SUM(&'5f9b182e-30')/COUNT(&'5f9b182e-30')),((SUM(&'5f9b182e-30')/COUNT(&'5f9b182e-30'))/COUNT_DAYS(DATE_STARTOF(TODAY(),\"3\"),DATE_ENDOF(TODAY(),\"3\")))*COUNT_DAYS(DATE_STARTOF(TODAY(),\"3\"),TODAY()))",
                     "ver": 2
                  }
               ],
               "data": [
                  [
                     34811.73714285714,
                     13924.694857142858
                  ]
               ],
               "autoFmt": true,
               "name": "Unlocked_OtherCost",
               "index": 0,
               "colHidden": "hidden",
               "customHeader": false
            },
            {
               "type": "table_col",
               "role": "tcol",
               "id": "afdd612f-5",
               "displayName": "Unlocked_TotalCost",
               "namerenamed": true,
               "vis": false,
               "size": "xx-small",
               "fmt": "num",
               "fmtArgs": {
                  "resultMetadata": {
                     "ignoreDateFormat": false,
                     "isAggregated": false,
                     "expiryScheme": [
                        {
                           "expiryType": "EOD",
                           "expiryTimezoneId": null
                        }
                     ],
                     "formulaIsDataPointer": false,
                     "suggestedName": "Unnamed 1",
                     "resultCount": 1
                  },
                  "autoFmt": {
                     "fmtArgs": {
                        "precision": "4"
                     },
                     "defaultAggregate": "SUM",
                     "fmt": "num"
                  },
                  "precision": "0"
               },
               "components": [],
               "formulas": [
                  {
                     "txt": "SUM(SLICE(2fb200fa299a77827c008c379f281f88@B:B;),&'69744d13-2')",
                     "ver": 2
                  }
               ],
               "data": [
                  [
                     8008386.647142857,
                     21944177.124857143
                  ]
               ],
               "autoFmt": true,
               "name": "Unlocked_TotalCost",
               "index": 1,
               "colHidden": "hidden",
               "customHeader": false
            },
            {
               "type": "data_slot",
               "role": "data",
               "id": "f4de7c3d-14",
               "displayName": "locked_month",
               "fmt": "txt",
               "fmtArgs": {
                  "resultMetadata": {
                     "ignoreDateFormat": false,
                     "isAggregated": false,
                     "expiryScheme": [
                        {
                           "expiryType": "EOD",
                           "expiryTimezoneId": null
                        }
                     ],
                     "formulaIsDataPointer": false,
                     "suggestedName": "Unnamed 1",
                     "resultCount": 1
                  },
                  "autoFmt": {
                     "fmtArgs": {},
                     "defaultAggregate": "COUNT",
                     "fmt": "txt"
                  }
               },
               "dstContext": {
                  "id": "dstf4de7c3d14",
                  "kid": "166273ade1950dee9f29112b826a8b7c"
               },
               "isDstRoot": true,
               "formulas": [
                  {
                     "txt": "DATE_CONVERT(GROUP(DATEVALUE(DATERANGE(DATE_STARTOF(TODAY(),\"1\"),DATE_STARTOF(TODAY(),\"3\",-2)),\"MM\")),\"MM\",\"MMM\")",
                     "ver": 2
                  }
               ],
               "data": [
                  [
                     "Jan",
                     "Feb",
                     "Mar",
                     "Apr",
                     "May",
                     "Jun",
                     "Jul"
                  ]
               ],
               "autoFmt": true,
               "name": "locked_month"
            },
            {
               "type": "data_slot",
               "role": "data",
               "id": "bdebe3b9-15",
               "displayName": "total_cost",
               "fmt": "num",
               "fmtArgs": {
                  "resultMetadata": {
                     "ignoreDateFormat": false,
                     "isAggregated": false,
                     "expiryScheme": [
                        {
                           "expiryType": "EOD",
                           "expiryTimezoneId": null
                        }
                     ],
                     "formulaIsDataPointer": false,
                     "suggestedName": "Unnamed 1",
                     "resultCount": 1
                  },
                  "autoFmt": {
                     "fmtArgs": {
                        "precision": "4"
                     },
                     "defaultAggregate": "SUM",
                     "fmt": "num"
                  }
               },
               "dstContext": {
                  "id": "dstbdebe3b915",
                  "kid": "166273ade1950dee9f29112b826a8b7c"
               },
               "isDstRoot": true,
               "formulas": [
                  {
                     "txt": "LOOKUP(UPPER(&'f4de7c3d-14'),UPPER(DATE_CONVERT(ARRAY(SLICE(0ae47c6b24b8caf5dbbbde556dcdf017@B:B;)),\"M\",\"MMM\")),ARRAY(SLICE(0ae47c6b24b8caf5dbbbde556dcdf017@A:A;)))",
                     "ver": 2
                  }
               ],
               "data": [
                  [
                     "22986677.74000000000000000000",
                     "18281676.94000000000000000000",
                     "19913451.00000000000000000000",
                     "21778728.03000000000000000000",
                     "21712098.52000000000000000000",
                     "17126810.82000000000000000000",
                     "22414746.11000000000000000000"
                  ]
               ],
               "autoFmt": true,
               "name": "total_cost"
            },
            {
               "type": "data_slot",
               "role": "data",
               "id": "5f9b182e-30",
               "displayName": "other_cost",
               "fmt": "num",
               "fmtArgs": {
                  "resultMetadata": {
                     "ignoreDateFormat": false,
                     "isAggregated": false,
                     "expiryScheme": [
                        {
                           "expiryType": "EOD",
                           "expiryTimezoneId": null
                        }
                     ],
                     "formulaIsDataPointer": false,
                     "suggestedName": "Unnamed 1",
                     "resultCount": 1
                  },
                  "autoFmt": {
                     "fmtArgs": {
                        "precision": "2"
                     },
                     "defaultAggregate": "SUM",
                     "fmt": "num"
                  }
               },
               "dstContext": {
                  "id": "dst5f9b182e30",
                  "kid": "166273ade1950dee9f29112b826a8b7c"
               },
               "isDstRoot": true,
               "formulas": [
                  {
                     "txt": "ROUND((&'bdebe3b9-15'-&'0d6f581e-31'),2)",
                     "ver": 2
                  }
               ],
               "data": [
                  [
                     25710.83,
                     110948.17,
                     -39732.3,
                     22183.52,
                     51663.51,
                     6745.68,
                     66162.75
                  ]
               ],
               "autoFmt": true,
               "name": "other_cost"
            },
            {
               "type": "data_slot",
               "role": "data",
               "id": "0d6f581e-31",
               "displayName": "pv_cost",
               "fmt": "num",
               "fmtArgs": {
                  "resultMetadata": {
                     "ignoreDateFormat": false,
                     "isAggregated": false,
                     "expiryScheme": [
                        {
                           "expiryType": "EOD",
                           "expiryTimezoneId": null
                        }
                     ],
                     "formulaIsDataPointer": false,
                     "suggestedName": "Unnamed 1",
                     "resultCount": 1
                  },
                  "autoFmt": {
                     "fmtArgs": {
                        "precision": "4"
                     },
                     "defaultAggregate": "SUM",
                     "fmt": "num"
                  }
               },
               "dstContext": {
                  "id": "dst0d6f581e31",
                  "kid": "166273ade1950dee9f29112b826a8b7c"
               },
               "isDstRoot": true,
               "formulas": [
                  {
                     "txt": "LOOKUP(UPPER(&'f4de7c3d-14'),UPPER(DATE_CONVERT(ARRAY(SLICE(2d0870fd0afd4f1797f27bbd0c6e2813@A:A;)),\"M\",\"MMM\")),ARRAY(SLICE(2d0870fd0afd4f1797f27bbd0c6e2813@B:B;)))",
                     "ver": 2
                  }
               ],
               "data": [
                  [
                     "22960966.91000000000000000000",
                     "18170728.77000000000000000000",
                     "19953183.30000000000000000000",
                     "21756544.51000000000000000000",
                     "21660435.01000000000000000000",
                     "17120065.14000000000000000000",
                     "22348583.36000000000000000000"
                  ]
               ],
               "autoFmt": true,
               "name": "pv_cost"
            }
         ]
      }
   ]
}
