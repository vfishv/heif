ISO BMFF Byte Stream Format

识别HEIF文件
检测设备是否支持硬解码 HEVC



https://nokiatech.github.io/heif/

http://standards.iso.org/ittf/PubliclyAvailableStandards/c066067_ISO_IEC_23008-12_2017.zip

https://zh.wikipedia.org/wiki/%E9%AB%98%E6%95%88%E7%8E%87%E5%9B%BE%E5%83%8F%E6%96%87%E4%BB%B6%E6%A0%BC%E5%BC%8F


图像项（Image Items）：存储单个图像、图像属性或缩略图。
图像派生（Image Derivations）: 派生图像是在运行时基于旋转、网格和叠加等描述生成的。这些图像取决于存储在HEIF文件中的其他图像。派生图像的存储空间很小。
图像序列（Image Sequences）：存储多个时间相关或时间预测的图像（如突发式照片拍摄或电影图形动画）其属性和缩略图。 可以使用不同的预测选项来利用图像之间的时间和空间相似性。 因此，即使将数十张图像存储在同一个HEIF文件中，文件大小也可以大幅降低。
辅助图像项（Auxiliary Image Items）: 存储补充另一图像项目的图像数据。 一个alpha平面或深度图是这种图像的例子。 这些数据并非如此显示，而是以各种形式用于补充另一图像项目。
图像元数据（Image Metadata）：存储同一个HEIF文件中存储图像的EXIF、XMP等元数据。


