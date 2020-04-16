convolutional neural networks with swift (2020)
===========================
  - Book: https://convolutionalneuralnetworkswithswift.com/

convolutional neural networks with swift (and python) (2019)
===========================
  - Transcript: https://brettkoonce.com/talks/convolutional-neural-networkswith-swift-and-python/

iOS 12 talk (2018)
===========================

  - Transcript:  https://brettkoonce.com/talks/convolutional-neural-networks-swift-ios12/
  - Overview:  https://medium.com/quark-works/an-overview-of-convolutional-neural-networks-swift-and-ios-12-8ce96f223c29
  - Talk:  https://www.youtube.com/watch?v=jki130apVhI
  - Slides:  http://static.brettkoonce.com/presentations/slug_cnn_2018.pdf


iOS 11 + keras demo (2017)
===========================

  - Transcript:  https://brettkoonce.com/talks/convolutional-neural-networks-swift-ios11/
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

