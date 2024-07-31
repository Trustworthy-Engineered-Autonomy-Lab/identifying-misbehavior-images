# Test1
  - ## quick_test_encoder_assign_test1.ipynb
    Working with original data and experimenting with different normal:misbehavior ratio (800:200) for 40 epochs

# Test 2
  - ## quick_test_encoder_assign_test2.ipynb
    Working with original data - normal:misbehavior ratio (990:10)
    Tried adding new layers to the autoencoders
    Focusing on detecting normal images


# Test 3
  - ## quick_test_encoder_assign_test3.ipynb
    Working with original data
    Added an augmentation loss by randomly sampling 100 images, calculating their reconstruction loss, and adding it to the overall loss

    ### Scenario 2:
    Added extra convolutional and pooling layers
    Also added dropout layers after each pooling layer
    The training loop shuffles the data and processes it in smaller batches (shuffling and using different batches in each epoch)
    Also added an augmentation loss by randomly sampling 100 images from the normal data, calculating their reconstruction loss, and adding it to the overall loss.
    The ratio of normal to misbehavior images (950:50)

    ### Scenario 3:
    Added extra convolutional and pooling layers
    Also added dropout layers after each pooling layer
    The training loop shuffles the data and processes it in smaller batches (shuffling and using different batches in each epoch)
    Also added an augmentation loss by randomly sampling 100 images from the normal data, calculating their reconstruction loss, and adding it to the overall loss.
    The ratio of normal to misbehavior images (900:100)
    Batch size: 32
    Number of epochs: 20
