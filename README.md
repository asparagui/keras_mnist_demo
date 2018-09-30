iOS 12 talk (2018)
===========================

  - Talk:  https://www.youtube.com/watch?v=jki130apVhI
  - Slides:  http://static.brettkoonce.com/presentations/slug_cnn_2018.pdf


iOS 11 + keras demo (2017)
===========================

  - Talk:  https://academy.realm.io/posts/brett-koonce-cnns-swift-metal-swift-language-user-group-2017/
  - Slides:  http://static.brettkoonce.com/presentations/cnn.pdf

This is a simple demo to:

a) build and train a two layer neural network using keras/tensorflow
b) save the neural network model using coremltools for use with xcode
c) load said model in xcode and load/use to classify two input digits

Things learned:
1) Need to use virtualenv with coremltools to avoid threading issue with python
2) Uses keras 1.2.2, so had to backport code to use older numpy imports 
3) Xcode beta wierdness: need to build model, move to completely different directory, then add/import (need to see the "add this file to following targets" dialogue) to ensure that Xcode will auto-generate the swift model file.

