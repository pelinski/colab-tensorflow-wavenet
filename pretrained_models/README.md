# Pretrained models

Here you can find some pretrained models over interesting datasets:

## Eric Satie's 2 hours music

I used the album [Music For Airports](https://www.youtube.com/watch?v=vNwYtllyt3Q) and a [1 hour extended version of An Ending (Ascent)](https://www.youtube.com/watch?v=alo3KFRfLvE).

To generate 16000 (1 second, 16kHz) samples from this pre-trained model:

``` python ../generate.py --wav_out_path=brian_eno_generated.wav --samples=16000 brian-eno-2-hours-123122-steps/model.ckpt-123122 ```

## Rhodes keyboard

I used a 1 hour youtube video of [Ikumi Ogasawara’s remarkable interpretation of well-known Pop songs](https://www.youtube.com/watch?v=EFLmGlQLavE) in her Rhodes keyboard

``` python ../generate.py --wav_out_path=rhodes_generated.wav --samples=16000  ```

