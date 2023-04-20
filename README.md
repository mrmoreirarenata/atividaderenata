# atividaderenata

                  "HeaderLabel": "@@epip_view_logs",
                  "custom": {
                    "type": "Button",
                    "properties": {
                      "aria-label": "@@import_check_history_grid_logs_button",
                      "render": "::item.showLogButton",
                      "properties": {
                        "id": "importCheckhistory-grid-logsbutton"
                      }
                    },
                    "content": [
                      {
                        "type": "Button",
                        "properties": {
                          "className": "fa fa-file-text-o"
                        }
                      }
                    ]
                  },
                  "events": [
                    {
                      "from": "onClick",
                      "dispatch": "openEnhancedCheckHistoryLogsSlider",
                      "params": "::item"
                    }
                  ]
                }
              }
            }
