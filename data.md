**Baseline**

|                                    | Accuracy | Score  |
| ---------------------------------- | -------- | ------ |
| **Bag of Words (Batch size = 32)** | 0.6791   | 2.3010 |

### Recurrent Models

**Max Features = 500, Max Length = 50**

|                                                | Accuracy | Score  |
| ---------------------------------------------- | -------- | ------ |
| **GRU (Batch size = 32)**                      | 0.7545   | 0.7570 |
| **GRU (Batch size = 32, Dropout = 0.2)**       | 0.7594   | 0.6843 |
| **LSTM (Batch size = 32)**                     | 0.7596   | 0.6081 |
| **LSTM (Batch size = 32, Dropout = 0.2)**      | 0.7592   | 0.5905 |
| **SimpleRNN (Batch size = 32)**                | 0.6862   | 0.5875 |
| **SimpleRNN (Batch size = 32, Dropout = 0.2)** | 0.6546   | 0.6095 |

**Max Features = 20,000, Max Length = 80**

|                                                | Accuracy | Score  |
| ---------------------------------------------- | -------- | ------ |
| **GRU (Batch size = 32)**                      | 0.8071   | 1.5070 |
| **GRU (Batch size = 32, Dropout = 0.2)**       | 0.8142   | 1.2643 |
| **LSTM (Batch size = 32)**                     | 0.8115   | 1.0614 |
| **LSTM (Batch size = 32, Dropout = 0.2)**      | 0.8059   | 1.0915 |
| **SimpleRNN (Batch size = 32)**                | 0.734    | 0.6682 |
| **SimpleRNN (Batch size = 32, Dropout = 0.2)** | 0.6522   | 0.6218 |

