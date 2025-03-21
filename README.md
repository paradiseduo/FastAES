# FastAES
移动端高性能AES加密

# iOS
AES 128，CBC，iPhone 13 mini
| 加密长度（字符数） | CryptoSwift | CCCryptorCreateWithMode | FastAES |
| :-----: | :----: | :----: | :----: |
| 1KB | 2.32ms | 0.045ms | 0.028ms |
| 10KB | 16.41ms | 0.21ms | 0.13ms |
| 100KB | 157.7ms | 3.14ms | 0.5ms |
| 1MB | 1837.3ms | 3.66ms | 2.24ms |

# Android
AES 128，CBC，Readmi Note8
| 加密长度（字符数） | Java | Native | FastAES |
| :-----: | :----: | :----: | :----: |
| 1KB | 0.46ms | 1.03ms | 0.11ms |
| 10KB | 0.78ms | 8.92ms | 0.35ms |
| 100KB | 3.04ms | 87.84ms | 2.36ms |
| 1MB | 23.51ms | 874.97ms | 24.96ms |

AES 128，CBC，Redmi K80 Pro
| 加密长度（字符数） | Java | Native | FastAES |
| :-----: | :----: | :----: | :----: |
| 1KB | 0.13ms | 0.29ms | 0.04ms |
| 10KB | 0.15ms | 1.93ms | 0.15ms |
| 100KB | 0.38ms | 23.02ms | 0.56ms |
| 1MB | 2.70ms | 780.39ms | 4.31ms |
