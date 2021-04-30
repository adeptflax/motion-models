# Motion Models



[![Foo](https://licensebuttons.net/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, adeptflax has waived all copyright and related or neighboring rights to motion models. This work is published from: United States.


## First Order Model (512x512 pixels)

It was trained using this script and more info can be found there: https://github.com/AliaksandrSiarohin/first-order-model

Model, config, and examples can be downloaded here: https://www.mediafire.com/folder/e6ikqpr3eegxf/first-order-model

This model was trained on rtx 3090 for 5 days on vast.ai. 2 gpus didn't seem to speed up the process very much, it only had around 50% - 60% gpu usage. I used mp4 files for the training data, png format was too big. The model is on the 95th epoch. The training script crashed for some unknown reason right before completion but it mostly seems to work just fine. I changed the sigma to 1.5 as described [here](https://github.com/AliaksandrSiarohin/first-order-model/issues/20#issuecomment-600784060).

## Motion Cosegmentation (512x512 pixels)

It seems a First Order Model can be use with https://github.com/AliaksandrSiarohin/motion-cosegmentation. I'll post details later.
