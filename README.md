# MDetect-Swift
MDetect library written in swift

# How to use
if MDetect.isUnicode() {
  //device can render myanmar unicode properly.
} else {
  //he's using zawgyi
}

# Why MDetect
To display burmese text where you can't embed font. For example, MapKit.
To decide user's input. (This method is more reliable than using regex)
